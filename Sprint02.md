
## Sprint 02
* Data: 02/06/19
* Local: Online/Grad05
* Intervalo: 27/05/2019 - 02/06/2019
## Participantes
  * Flávio Nevez
  * Gabriel Fontannari
  * Lucas Pires
  * Múcio Jaziel
  * Vitor Cardim Menezes. 
## Objetivos
* Pesquisar artigos cientificos que embasem a problemática, bem como reproduzir a implementação das duas aplicações e também o EFK nas mesmas, com um ou mais responsáveis pela tarefa, porém executada por todos do time

## Planejamento da Sprint 02
| Ação | Responsável(eis) | Detalhes |
|----------|----------|----------| 
| Pesquisas em artigos científicos para embasamento teórico da problemática | Time | |
| Reproduzir a implementação das duas aplicações que serão usadas como cobaia | Gabriel | |
| Implementar EFK (Fluentd, ElasticSearch, Kibana) nas aplicações citadas acima | Gabriel e Lucas | 
| Discussão dos microsserviços para a aplicação Sock Shop e Robot Shop | Time | |
| Definição dos microsserviços de Logs | Time | |
# Realizadas na Sprint 02
| Ação | Responsável(eis) | Detalhes |
|----------|----------|----------|
| Estudo do material levantado sobre Microsserviços de Logs | Vitor e Múcio | |
| Definição das ferramentas a serem usada no projeto | Time | Finalizar todas escolhas, expondo-as|
| Discussão sobre como implementar o microsserviço de Logs na aplicação Sock Shop| Lucas e Múcio | |
| Implementação inicial do microsserviço de Log | Vitor e Gabriel |  |
| Início da Documentação (Relatório Técnico) | Flávio e Múcio | Fazer parte introdutória e documentar todo o feito na Sprint
## Em andamento 
| Ação | Responsável(eis) | Detalhes |
|----------|----------|----------|
| Definição dos recursos a serem usados no projeto | Time | Em Análise |
| Definição das métricas de avaliação usando GQM | Lucas e Múcio | Em Progresso |Finalizar todas escolhas, expondo-as |
| Levantamento de Escopo do Projeto | Vitor e Gabriel | |
## Planejamento para Status Report 03
| Ação | Responsável(eis) | Detalhes
|----------|----------|----------|
| Analisar logs obtidos dessa implementação, elicitando os tratamentos que serão necessários para melhor utilização desses dados | Vitor e Múcio |
| Desenvolver microsserviço que aplique os devidos tratamentos ao Log | Vitor e Múcio |  |
| Garantir que seja agnóstico e plug and play  | Vitor | |
## Ferramentas
| Nome | Decisão | Detalhes
|----------|----------|----------|
| Kubernets | Imposição do Professor | Será utilizado, nem que caia o mundo |
| Docker    | Time | Uso de containers
| Fluentd   | Time | Coletor de dados para unificação de Logs
| Kibana    | Time | Visualizador de dados
| Log       | Time | Para monitoramento
| Python (Pandas)| Vitor   | Ajuda a tratar os dados
| ElasticSearch | Certeza | Usaremos nas buscas|
| Testes | Em Análise | A ser definido |

## Lições Aprendidas
* Verificamos que estávamos preocupados e focados no que iríamos usar relacionado à abordagem tecnológica; Repensando isso, entendemos que seria preciso focar em qual objetivo e problema deveríamos resolver;
* Aprendemos que precisamos partir de um problema real para o desenvolvimento do projeto 
* Organizar o GQM previamente para que o mesmo oriente não somente as métricas de qualidade, mas todo o desenvolvimento do projeto.
* Necessidade de divisão de trabalho de uma forma mais eficiente, com pessoas responsáveis pela tarefa, mas todos a fazem ( o responsável estuda a problemática e todos a implementam, assegurando o alinhamento de todo o time com todos os tópicos do projeto).
* Pequeno problema limitação de Hardware, lentidão extrema apenas com uma das aplicações possíveis rodando.

