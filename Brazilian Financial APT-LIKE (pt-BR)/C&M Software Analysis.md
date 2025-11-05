**Caso C&M Software**


O que hoje é considerado o maior assalto cibernético da história do Brasil teve início de forma
silenciosa, nas primeiras horas da madrugada de uma segunda-feira, 30 de junho de 2025. Longe
dos holofotes, um grupo de cibercriminosos colocava em prática a fase final de um ataque
meticulosamente planejado contra a espinha dorsal de uma parcela crítica do sistema
financeiro nacional.

Segundo relatos da imprensa, o primeiro sinal de que algo estava terrivelmente errado surgiu por
volta das 4h da manhã. Um executivo da BMPMoney Plus – uma fintech especializada em bankingas-
a-service (BaaS) – recebeu uma ligação de um funcionário do CorpX Bank. O motivo era uma
transferência via PIX de R$ 18 milhões, originada da conta da BMP e direcionada ao banco, uma
operação atípica e não autorizada que imediatamente acendeu o alerta. Ao verificar a situação, o
executivo da BMP percebeu que não se tratava de um evento isolado, mas de uma série de
movimentações fraudulentas que estavam drenando os recursos da conta reserva da empresa,
mantida diretamente no BancoCentral. Às 5h, a C&MSoftware foi oficialmente acionada.

As características do ataque, aliadas ao depoimento do primeiro suspeito identificado pela polícia,
indicam que o crime foi realizado por um grupo criminoso brasileiro, formado por, pelo menos, 5
pessoas. O golpe foi planejado por vários meses, pelo menos desde antes de março de 2025, e o
grupo possui grande conhecimento técnico e processual sobre o funcionamento do sistema
financeiro brasileiro, incluindo do sistema de pagamentos (SPB) e sistema Pix (Sistema de
Pagamentos Instantâneo).

Segundo investigações da Polícia Civil de São Paulo, os criminosos conseguiram acesso ao
ambiente da C&M Software ao aliciar um funcionário da empresa, J.N.R, que atuava como
desenvolvedor júnior. Ele confessou ter sido aliciado por outras pessoas e as ajudou a invadir o
sistema. Em maio deste ano J.N.R realizou comandos nos servidores da C&M, seguindo orientação
dos criminosos, que lhes permitiu o acesso remoto aos sistemas da empresa. J.N.R recebeu dois
pagamentos, o 1° para iniciar o acesso dos criminosos na rede da C&M, no valor de R$5.000,00 (5
mil reais) e um segundo por continuar inserindo os comandos, onde os mesmos vinham em
instruções no Notion, o pagamento era realizado gradativamente, com o dinheiro enviado através
de ummotoboy.

<img width="811" height="427" alt="image" src="https://github.com/user-attachments/assets/9bf360ca-54a5-4327-9930-fa34eea95a48" />

Em nota oficial, publicadaemseu site, a C&MSoftware destacou que os elementos apurados pelas
autoridades e pelas investigações independentes contratadas indicam que o episódio teve início
com o compartilhamento indevido de credenciais por parte de um colaborador, induzido por
terceiros por meio de técnicas de engenharia social. O colaborador foi abordado fora do ambiente
da empresa por um terceiro que se apresentou como “ligado a hackers” e lhe prometeu benefício
financeiro. O acesso começou com suas credenciais pessoais, mas há indícios de que foram
utilizadas credenciais adicionais ou mecanismos de autenticação auxiliares, o que estáem análise
técnica.

A empresa declara que não houve invasão externa ou violação técnica da infraestrutura da C&M e
que eles não identificaramqualquer falha técnica ou vulnerabilidade nos seus sistemas.
Uma vez obtido acesso inicial ao ambiente da C&M Software, os invasores teriam realizado um
mapeamento da infraestrutura e do funcionamento do sistema de transferências, identificando
como as transações Pix eram estruturadas e onde estavam armazenados os artefatos críticos de
autenticação.

Neste momento, os atacantes possivelmente mapearam as instituições financeiras clientes da
C&M e que possuíam credenciais armazenadas com a mesma, possivelmente usando
enumeração. Acreditamos que, nessa fase, os atacantes identificaram as instituições financeiras
emque era possível ter acesso às suas contas reservas.
Há fortes indícios de que a maioria das transações foram direcionadas inicialmente a contas
correntes em instituições de pagamento de menor porte, que geralmente possuemcontroles mais
brandos de onboarding e verificação (KYC), facilitando a abertura e manipulação de contas em
nome de laranjas. A transferência via Pix deu agilidade na evasão dos recursos.
As contas de destino foram usadas como ponte para o objetivo final do grupo criminoso: esconder
o dinheiro desviado emcriptomoedas.

Após a exfiltração dos recursos para contas laranjas, os valores foram rapidamente dispersos em
pequenas transações e supostamente tambémconvertidos em criptoativos, dificultando o rastreio
e bloqueio dos valores desviados. Segundo notícias, parte dessas transações foram identificadas
como suspeitas e bloqueadas emalgumas exchanges.
Segundo reportagem do portal Cointelegraph, O CEO da SmartPay e Truther, Rocelo Lopes,
informou ter detectado movimento atípico em ambas plataformas às 00:18 do dia 30 de junho, e
automaticamente elevou os filtros de validação nas compras de USDT e Bitcoin. Segundo ele,
foram retidos grandes somas de dinheiro e, na mesma hora, foi feito o processo de devolução para
as instituições envolvidas. Os operadores da SmartPay identificaram um Pix no valor de R$ 6
milhões a partir da BMP, que chamou a atenção. Os funcionários, então, perceberam uma
quantidade bem acima do normal de movimentações de novas contas e muitos pedidos de
transferênciasemum intervalo curto, de cerca de duas horas.

Segundo matéria publicada no portal Bleeping Computer, os criminosos responsáveis pelo desvio
de dinheiro do sistema financeiro brasileiro conseguiram converter entre US$ 30 a 40 milhões
(entre, aproximadamente, R$ 160 milhões e R$ 220 milhões) do dinheiro roubado para
criptomoedas como BTC, ETH e USDT, através de diversas corretoras emercados de balcão (OTC)
