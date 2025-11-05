Surgiu uma ofensa partindo do SOC, de falhas de autenticação em um usuário oriundo da agencia porém com o código fora do padrão. O código usado era de uma usuária do setor administrativo, porém logando de uma agência. Após investigação, na mesma máquina da agência em questão houveram mais falhas de login, e as autenticações se originavam de um SWITCH.

Parque de rede do (cliente)
- Contam com 4 vlans /2x;
- As vLans /2x pertencem as agências e são divididas em 4 seguimentos de rede, uma para os ATMs outra para as câmeras e etc...
 
Foi observado que não era normal a autenticação partindo de um switch. Após a análise do pessoal de Telecom, foi identificado um ativo suspeitos onde não deveria ter login de usuários.
 
Percebeu-se então, o uso de uma campanha de Microtik para ataques. Olhando para os logs no SIEM, começou a ser observado o uso de diversos usuários estranhos (padrões não conhecidos) no ambiente interno do banco.
 
No dia seguinte, quando um técnico se deslocou até a agência afetada, observou-se que no equipamento de solicitação de senhas de atendimento da agência, uma pequena carcaça foi encaixada na tomada de energia, contendo uma adaptação com um microtik e um transmissor 5G.
 
Visto que o equipamento de emissão de senhas tinha apenas o contato elétrico de energia e um cabo de rede que o ligava ao sistema de rede interna da agência. O atacante conseguiu acesso a rede, assim, foi identificado diversas tentativas de autenticação com o usuário de nomenclatura "Os" em Active Directorys (uma regra foi desenvolvida no SIEM e capturou novos comportamentos semelhantes).
Ao ter acesso na rede, foi constatado a tentativa de exploração de vulnerabilidades em ativos do CITRIX e Notes, além da tentativa de SQLi, que fora bloqueada pelo IPS. Como a comunicação saía da agência e passava pela central do banco, o IPS utilizado  realizou a detecção e bloqueou as tentativas.
 
Se caso o SQLi fosse realizado com sucesso, o atacante teria tido acesso total a  todos os usuários do banco.
 
Foram observadas diversas tentativas de movimentação lateral barradas pela segmentação de vLans utilizadas. Assim foi desenvolvido regras de firewall para isolar as agências de todo o sistema interno do banco.
 
Houveram tentativas de scans, RDP e SSH partindo das agências afetadas, Três Corações e São Roque.
 
Quando o aparelho Microtik é conectado à rede de internet da agência, é observado uma nova rede ZTE dentro dos logs do ClearPass.
 
O cliente estava com o equipamento de Microtik utilizado no ataque em mãos...

Algumas regras emergenciais foram desenvolvidas durante o ataque dos dias 12,13,14 de Junho.

Regras desenvolvidas no SIEM com alta criticidade:

**Aparentes padrões:**
 
Uso das mesmas ferramentas, com Microtik;
Aparentemente a ideia inicial seria utilizar Ransonware na rede interna.
Ataques realizados nas agências de Três Corações e MG e  São roque em SP. (Estados comumente conhecidos por serem controlados pelo PCC).
 
**Modus Operandi:**
 
Entram na agência, permanecem um tempo esperando a agência esvaziar, em questão de 30s plugam o dispositivo nos totens de emissão de senha para atendimento;
Clonam MAC address de equipamentos (MAC Spoofing);
Em outros momentos, também aliciam funcionários do banco, com ameaças sobre a família e a vida da pessoa.
