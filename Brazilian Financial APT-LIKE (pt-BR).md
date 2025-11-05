
**Key Decisions:** Determinar o entendimento de como os ataques ao Sistema Financeiro Brasileiro se desenvolveu e
como proteger o ambiente interno, alinhado com o conhecimento e TTP's dos novos tipos de ataques.

**Decision-Enabling** Data Points: Contexto e relevância da ameaça para a organização; Comportamento do adversário e
objetivos potenciais; Enriquecimento de informações de Intelligence com o auxílio na tomada de decisão.



📘 **Executive Summary**

Os ataques ao sistema financeiro brasileiro iniciados em julho de 2025marcaram uma nova etapa na evolução das ameaças cibernéticas contra o setor. O incidente revelou um nível inédito de
coordenação entre grupos criminosos e atores técnicos capazes de explorar fragilidades na cadeia
de suprimentos financeira, comprometendo provedores de tecnologia críticos para a operação de
diversas instituições. A ofensiva demonstrou alto grau de planejamento e conhecimento interno
das estruturas do sistema de pagamentos, permitindo o desvio de valores expressivos e a
movimentação rápida dos recursos pormeio de transações digitais e conversões emcriptoativos.

Mais preocupante que o impacto financeiro direto foi a demonstração de como vulnerabilidades
em terceiros podem ser exploradas em larga escala para atingir múltiplas instituições
simultaneamente, vulnerabilidades essas que nem sempre são a nível de Software, mas sim, a
nível humano.

Desde então, observou-se um efeito cascata, com tentativas e incidentes confirmados afetando
fintechs e bancos menores, especialmente aqueles com menor maturidade em governança de
segurança e alta dependência de fornecedores externos. Esses eventos expuseram lacunas
estruturais no modelo de supervisão, evidenciando a necessidade urgente de mecanismos mais
robustos de monitoramento contínuo, compartilhamento de inteligência e avaliação de risco de
terceiros.

O panorama atual indica uma transformação no perfil do cibercrime financeiro no Brasil — de
ataques oportunistas para operações complexas, planejadas e sustentadas por redes de
cooperação entre fraudadores, técnicos e insiders. A resposta do setor precisará evoluir na mesma
velocidade, priorizando integração de defesas, fortalecimento de parcerias estratégicas e uma
cultura de segurança que transcenda os limites institucionais.

📘 **Analysis Summary**

A série de incidentes iniciada em julho de 2025 representa uma das campanhas mais complexas já
observadas contra o sistema financeiro brasileiro, caracterizada pela exploração coordenada da
cadeia de suprimentos e pela evolução tática dos atacantes após o primeiro comprometimento
bem-sucedido. A fase inicial, centrada no ataque a um provedor de tecnologia com acesso
privilegiado a infraestruturas críticas do Sistema de Pagamentos Brasileiro (SPB), abriu caminho
para a disseminação lateral do impacto a dezenas de instituições dependentes de suas
integrações, incluindo fintechs e bancos digitais de pequeno emédio porte.

A análise técnica dos eventos revela o uso de técnicas típicas de Advanced Persistent Threats
(APT), adaptadas a um contexto de fraude financeira. Os atacantes demonstraram domínio sobre
fluxos de autenticação e comunicação entre APIs bancárias, empregando módulos customizados
para interceptar e manipular transações legítimas. O vetor inicial provavelmente envolveu
credenciais administrativas comprometidas — obtidas por meio de engenharia social, phishing
direcionado ou cooptação de insiders — que possibilitaram o acesso a ambientes internos de
desenvolvimento e homologação. Uma vez inseridos, os invasores exploraram a ausência de
segmentação adequada e o uso de tokens de serviço sem expiração para escalar privilégios e
realizar movimentações financeiras simulando operações válidas.

Após o ataque inicial, observou-se a replicação da metodologia em outras fintechs e instituições
menores, com variações que indicam a reutilização de toolkits e scripts desenvolvidos na primeira
fase. Em muitos casos, os agentes de ameaça exploraram a dependência dessas empresas de
provedores de software e APIs terceirizadas, utilizando o mesmo padrão de acesso indireto via
integrações comprometidas. Houve ainda relatos de uso de Remote Monitoring andManagement
(RMM) legítimos, como AnyDesk e RustDesk, para persistência e movimentação lateral,
mascarando a atividade maliciosa como manutenção técnica rotineira.

Indicadores coletados em fontes abertas e no relatório técnico publicado posteriormente por
empresas de segurança nacionais, apontamque a campanha foi altamente modular. Os atacantes
desenvolveram rotinas automáticas de dispersão de valores via PIX, associadas a redes de contas
laranja e intermediários de criptoativos, dificultando a rastreabilidade. Em paralelo, logs de
autenticação e telemetria de endpoints indicam o uso de técnicas de ofuscação e living-off-theland,
com abuso de ferramentas nativas do Windows (como PowerShell e WMI) para execução de
comandos semgerar alertas imediatos emsoluções de EDR.

O padrão operacional observado sugere uma convergência entre grupos tradicionais de fraude
bancária e atores tecnicamente sofisticados com experiência em intrusão corporativa. Essa
combinação permitiu que os ataques fossem executados com precisão e discrição, sustentandose
por longos períodos antes da detecção. O modelo de ameaça adotado demonstra uma clara
transição do cibercrime financeiro brasileiro para estruturas semi-organizadas, com distribuição de
papéis, infraestrutura de suporte compartilhada e capacidade de replicação em novos alvos em
poucos dias. A continuidade dos ataques após julho indica que o comprometimento inicial serviu
de prova de conceito, incentivando outras células criminosas a explorar vulnerabilidades
semelhantes em fintechs e bancos menores.

Este movimento reforça a necessidade de
fortalecimento de controles de acesso privilegiado, revisão de integrações API, auditoria de
dependências externas e implementação de threat hunting focado em cadeias de suprimentos —
hoje, o principal vetor de risco sistêmico no setor financeiro nacional.

<img width="803" height="462" alt="image" src="https://github.com/user-attachments/assets/17b89c45-17b7-465f-b26d-ca1939a7d571" />

