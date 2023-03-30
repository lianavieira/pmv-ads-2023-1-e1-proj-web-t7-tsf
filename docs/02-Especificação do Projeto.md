# Especificações do Projeto

<span style="color:red">Pré-requisitos: <a href="1-Documentação de Contexto.md"> Documentação de Contexto</a></span>

Definição do problema e ideia de solução a partir da perspectiva do usuário. É composta pela definição do  diagrama de personas, histórias de usuários, requisitos funcionais e não funcionais além das restrições do projeto.

Apresente uma visão geral do que será abordado nesta parte do documento, enumerando as técnicas e/ou ferramentas utilizadas para realizar a especificações do projeto

## Personas

1- Fabiana de Fátima dos Santos Pereira tem 33 anos, é analista financeira em uma empresa do ramo esportivo. Durante sua expedições sente dificuldade em acomodações com muitas pessoas, didifucldade em se adaptar com temperaturas muito baixas e sente muitas saudades da família, mas adora andar a toa para conhecer cidades, passear pelos parques.  Esta em busca de conhecer novas pessoas, culturas e novos lugares.

2- Jullio Ravazoli tem 36 anos é executivo de vendas em uma empresa de serviços tecrceirizados. Tem como hobbie viajar e fotografar, busca conhecer nocas culturas e outros idiomas visando crescimento pessoal.  Sente dificuldade na adaptação às novas culturas, distanciamento familiar e em se adaptar à climas diferentes do habitual.

3- Elisa Budreckas Vieira tem 34 anos, é sceretária da diretoria de uma empresa do ramo de fornecimento de energia elétrica. Ama cozinhar e ler livros, tem facilidade com decoração de interiores e como maior sua companhia o marido. Busca conhecer o mundo para aprender sobre diversas culturas culinárias.  Sempre tem dificuldade em lidar com a saudade da família e em muitas de suas viagens alega perceber muita discriminação cultural.  

4- Maria Cristina Bizotti tem 28 anos, é psicóloga e atua na abordagem da TCC - Terapia Cognitivo Comportamental.  Já realizou muito trabalhos voluntários, gosta muito de ler e aprecia a arte voltada para pinturas.  Busca promover qualidade de vida, bem-estar psicológico e emocional para as pessoas, sua maior alegria é ver os resultados que a terapia proporciona na vida dos pacientes.  Sua frustração é saber que muitas pessoas acham que terapia é para pessoas "loucas" e que depressão e ansiedade é frescura. 


## Histórias de Usuários

Com base na análise das personas forma identificadas as seguintes histórias de usuários:

|EU COMO... `PERSONA`| QUERO/PRECISO ... `FUNCIONALIDADE` |PARA ... `MOTIVO/VALOR`                 |
|--------------------|------------------------------------|----------------------------------------|
|Fabiana             | encontrar ajuda para lidar         | Para poder aproveitar melhor as viagens|
                       com distanciamento familiar        
|Jullio              | conhecer relatos de pessoas que    | para que eu consiga lidar melhor com   |       
                        enfretaram as mesmas dificuldades   minhas frustrações    
|Elisa               | ajuda profissional                 | para lidar com a discriminação cultural|
|Maria               | Divulgar meus serviços             | para que mais pessoas encontrem        |
                                                            resultados através de terapias



## Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto.

### Requisitos Funcionais

|ID    | Descrição do Requisito  | Prioridade |
|------|------------------------------------------------------|------|
|RF-001| O site deve apresentar na página inicial cards com   | ALTA | 
         os psicólogos disponíveis, área de login,
         cards com relatos de imigrantes
|RF-002| Para a página de psicólogos, deve haver um           | ALTA |
         formulário requerendo informações previamente 
         discutidas como email, CRP, telefone, abordagem
|RF-003| O site deve apresentar na tela de cadastro para      | ALTA |
         opção paciente, a o formulário para cadastrar formas 
         de contato
|RF-004| Todos os botões devem ser clicáveis                  | MÉDIA |
|RF-005| Na página principal, devemos deixar claro o          | MÉDIA |
         propósito do site já que envolve assuntos sensíveis 
|RF-006| O site deve apresentar na página de relatos, cards   | MÉDIA |
         com identificação anônima ou não, opção de relatar  
|RF-007| O site deve apresentar na página de relatos, cards   | MÉDIA |
          com identificação anônima ou não, e com relatos 
          de pessoas que relataram
 RF-008| O site deve funcionar em mobile e desktop            | BAIXA |
         




### Requisitos não Funcionais

|ID     | Descrição do Requisito  |Prioridade |
|-------|-------------------------------------------------------------------|-------|
|RNF-001| O site deve apresentar na tela de cadastro de psicólogo,          | MÉDIA | 
          a escolha do plano que ele quer assinar
|RNF-002| Interface de usuário                                              | MÉDIA | 
|RNF-003| O sistema deve ser fácil de usar e entender                       | MÉDIA | 
|RNF-004| O sistema deve rodar em diferentes plataformas com alterações     | MÉDIA | 
           mínimas 
|RNF-005| Chat Online para suporte                                          | BAIXA | 
           mínimas 


## Restrições

O projeto está restrito pelos itens apresentados na tabela a seguir.

|ID| Restrição                                                                     |
|--|-------------------------------------------------------------------------------|
|01| O projeto deverá ser entregue até o final do semestre                         |
|02| O aplicativo deve se restringir às tecnologias básicas da Web Frontend        |
|03| A equipe não pode subcontratar o desenvolvimento do trabalho                  |
|04| O grupo deverá utilizar o repositório específico do curso ADS                 |



Enumere as restrições à sua solução. Lembre-se de que as restrições geralmente limitam a solução candidata.

> **Links Úteis**:
> - [O que são Requisitos Funcionais e Requisitos Não Funcionais?](https://codificar.com.br/requisitos-funcionais-nao-funcionais/)
> - [O que são requisitos funcionais e requisitos não funcionais?](https://analisederequisitos.com.br/requisitos-funcionais-e-requisitos-nao-funcionais-o-que-sao/)
