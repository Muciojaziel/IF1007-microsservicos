## Sprint 03
* Data: 09/06/19
* Local: Presencial/SalaA011
* Intervalo: 03/06/2019 - 09/06/2019
## Participantes
  * Flávio Nevez
  * Gabriel Fontannari
  * Lucas Pires
  * Múcio Jaziel
  * Vitor Cardim Menezes. 
## Objetivos
* Planejamento do projeto
## Planejamento da Sprint 03
| Ação | Responsável(eis) | Detalhes |
|----------|----------|----------| 
| Estudo do material enviado pelo professor (Vinicius Cardoso Garcia), bem como outros que serviram como base para a mudança acerca dos microsserviços de logs | Vitor, Múcio, Gabriel | |
| Reavaliação da ideia anterior, e nova sugestão para a implementação dos microsserviços Monitoring_ms | Lucas e Vitor| |
| Discussão das novas ferramentas/abordagens tecnologicas a serem usadas no projeto | Vitor e Lucas ||
| Replicação da infraestrutura em docker do Monitoring_ms |Múcio, Vitor, Lucas, Gabriel ||
| Expor todas novas escolhas | Time ||
| Refatoração da Documentação (Relatório Técnico)|  Flávio e Múcio ||
| Fazer parte introdutória, documentar, e relatar lições aprendidas e dificuldades encontradas na Sprint | Múcio ||
# Realizadas na Sprint 03
| Ação | Responsável(eis) | Detalhes |
|----------|----------|----------|
| Ação | Responsável(eis) | Detalhes |
|----------|----------|----------| 
| Estudo do material enviado pelo professor (Vinicius Cardoso Garcia), bem como outros que serviram como base (...) | Vitor, Múcio, Gabriel | data: 04/06 |
| Reavaliação da ideia anterior, e nova sugestão para a implementação dos microsserviços Monitoring_ms | Lucas e Vitor| data: 05/06 |
| Discussão das novas ferramentas/abordagens tecnologicas a serem usadas no projeto | Vitor e Lucas |data: 06/06 |
| Replicação da infraestrutura em docker do Monitoring_ms |Múcio, Vitor, Lucas, Gabriel | Quarta e Quinta-feira (05 e 06/06)|
| Expor todas novas escolhas | Time | data: até inicio/meio da sprint04|
| Refatoração da Documentação (Relatório Técnico)|  Flávio e Múcio | data: até inicio/meio da sprint04|
| Fazer parte introdutória, documentar, e relatar lições aprendidas e dificuldades encontradas na Sprint | Múcio | data:09/06|

## Em andamento 
| Ação | Responsável(eis) | Detalhes |
|----------|----------|----------|
| Verificação de alguns erros encontrados ao implementar o Monitoring_ms |Gabriel e Múcio||
| Status Report - equipe e professor | Gabriel e Múcio | data: 10/06 |

## Planejamento para Status Report 04
| Ação | Responsável(eis) | Detalhes
|----------|----------|----------|
| Analisar a infraestutura criada do microsserviço Monitoring_ms, elicitando o funcionamento e solidificar as abordagens escolhidas pelo time | Vitor e  Lucas||
| Elicitar, caso haja possíveis mudanças nas abordagens tecnologicas embasando o motivo da nova mudança escolhida |Vitor e Lucas||
| Implementar a nova estrutura/abordagem do Monitoring_ms | Múcio e Gabriel||
| Analisar e comparar as duas infraestruturas implementadas | Vitor e Múcio||
| Realizar o comparativo | Vitor, Lucas e Flávio ||
## Ferramentas
| Nome | Decisão | Detalhes
|----------|----------|----------|
| Kubernets | Imposição do Professor | Será utilizado, nem que caia o mundo |
| mariaDB | Em Análise | Estamos escolhendo melhor local |
| Elastic | Certeza | Usaremos nas buscas|
| Zull | certeza | framework Netflix |
| Grafana | certeza | gerador de gráficos e dashboard é utilizado como frontEnd do Monitoring_ms |
| Definição de novas ferramentas para aumentar o escopo de uso  | A ser feito | Será abordado em reunião presencial|

## Lições Aprendidas
* Relacionadas à questões conceituais do docker:
Para usar uma máquina linux, é só instalar a engine do docker. Pelo que entendemos, o docker fica somente provisionando containers, e esses rodam sobre um único docker. Já se quisermos, termos vários Hosts cada um, com um docker, a gente usa o docker-machine, assim é como se a gente tivesse um docker como base, criamos um host que dentro dele vai ter outro docker.
Dessa forma, pra gerenciar cada um desses hosts [ a exemplo do cluster que temos vários hosts] usamos o docker-machine. Nesse caso, usamos como se fosse uma simulação de máquinas reais juntando-as há um cluster de máquinas quando usamos o docker machine, pra isso, e pelo que entendi, ele usa o driver do virtualBox pra instanciar como se fosse docker VM's, e dentro dessas Docker vm's elas já vem dockerizadas [termo usado para esse tipo de procedimento]. por assim dizer,
Isso demonstra também que, quando usamos o comando *docker-machine ssh nomedaInstancia*, acessamos e podemos rodar dentro da mesma, um comando a exemplo: docker ps, ou ls ou até o docker swarm init etc...
