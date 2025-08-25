# Introdução
O presente projeto tem como objetivo o desenvolvimento de uma plataforma de E-commerce escalável voltada para o modelo B2B (Business to Business). O sistema busca atender empresas parceiras na aquisição de itens eletrônicos, como memória RAM, placas de vídeo, teclados, mouses e headsets, todos de uma única marca, garantindo padronização e controle da qualidade.
O contexto de criação deste projeto parte da necessidade crescente de empresas adquirirem insumos de tecnologia de forma rápida, confiável e automatizada, diante da evolução do mercado digital e da competitividade no setor de eletrônicos.
Dessa forma, este trabalho tem como objetivo desenvolver um sistema robusto e escalável, que permita atender múltiplas demandas de clientes corporativos, oferecendo facilidade na gestão de pedidos, controle de estoque e escalabilidade em servidores distribuídos.

## Problema
Atualmente, muitas empresas encontram dificuldades na aquisição de equipamentos eletrônicos em larga escala devido à escassez de plataformas de e-commerce voltadas especificamente para esse segmento. A maioria dos sistemas existentes é direcionada ao consumidor final ou que não contempla as necessidades particulares das empresas no processo de compra corporativa. Esse cenário gera alguns problemas como a ausência de padronização nos produtos, dificuldades na negociação em volume e processos pouco adaptados às demandas de empresas que necessitam de agilidade, previsibilidade e controle de estoque.
Portanto, o principal problema identificado é a inexistência de uma solução de e-commerce dedicada ao segmento B2B de eletrônicos, que seja capaz de oferecer escalabilidade e personalização para atender o mercado corporativo.


## Objetivos

### Objetivo Geral:
Desenvolver uma plataforma de e-commerce escalável, voltada para o modelo B2B, para a comercialização de itens eletrônicos de uma única marca, com suporte a múltiplos servidores e gerenciamento de estoque distribuído.

### Objetivos Específicos:
    1. Implementar um sistema de controle de estoque em tempo real, sincronizado em servidores distribuídos.
    2. Oferecer relatórios gerenciais detalhados sobre pedidos, clientes e movimentação de estoque.
    3. Garantir escalabilidade e alta disponibilidade por meio de arquitetura distribuída.
    4. Desenvolver uma interface amigável e responsiva, acessível em múltiplos dispositivos.
 
> **Links Úteis**:
> - [Objetivo geral e objetivo específico: como fazer e quais verbos utilizar](https://blog.mettzer.com/diferenca-entre-objetivo-geral-e-objetivo-especifico/)

## Justificativa

O mercado de tecnologia cresce em ritmo acelerado, aumentando a necessidade de soluções digitais que suportem alto desempenho, confiabilidade e escalabilidade. O comércio eletrônico, especialmente no modelo B2B, demanda plataformas robustas que consigam atender empresas compradoras com grandes volumes de pedidos sem comprometer a qualidade do serviço.
A escolha desse tema justifica-se pela relevância do setor de eletrônicos e pela carência de soluções escaláveis que integrem de maneira eficaz a gestão de estoque e pedidos distribuídos. Além disso, a escalabilidade da aplicação permitirá que a plataforma acompanhe o crescimento do negócio, evitando gargalos tecnológicos comuns em soluções pouco preparadas.
O projeto também será uma oportunidade de aprofundar o estudo em arquitetura distribuída, banco de dados escaláveis e tecnologias de e-commerce, que são áreas de alta demanda no mercado atual de TI.

## Público-Alvo

Descreva quem serão as pessoas que usarão a sua aplicação indicando os diferentes perfis. O objetivo aqui não é definir quem serão os clientes ou quais serão os papéis dos usuários na aplicação. A ideia é, dentro do possível, conhecer um pouco mais sobre o perfil dos usuários: conhecimentos prévios, relação com a tecnologia, relações
hierárquicas, etc.

Adicione informações sobre o público-alvo por meio de uma descrição textual, diagramas de personas e mapa de stakeholders.

> **Links Úteis**:
> - [Público-alvo](https://blog.hotmart.com/pt-br/publico-alvo/)
> - [Como definir o público alvo](https://exame.com/pme/5-dicas-essenciais-para-definir-o-publico-alvo-do-seu-negocio/)
> - [Público-alvo: o que é, tipos, como definir seu público e exemplos](https://klickpages.com.br/blog/publico-alvo-o-que-e/)
> - [Qual a diferença entre público-alvo e persona?](https://rockcontent.com/blog/diferenca-publico-alvo-e-persona/)

# Especificações do Projeto

## Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto. Para determinar a prioridade de requisitos, aplicar uma técnica de priorização de requisitos e detalhar como a técnica foi aplicada.

### Requisitos Funcionais

|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|----|
|RF-001| Permitir que o usuário corporativo cadastre pedidos de compra | ALTA | 
|RF-002| Sincronizar o estoque em tempo real entre múltiplos servidores   | ALTA |
|RF-003| Emitir relatórios gerenciais de pedidos e movimentação de estoque  | MÉDIA |
|RF-004| Gerar faturas e notas fiscais de forma automática   | ALTA |
|RF-005| Oferecer histórico de compras para cada cliente   | MÉDIA |

### Requisitos não Funcionais

|ID     | Descrição do Requisito  |Prioridade |
|-------|-------------------------|----|
|RNF-001| O sistema deve ser responsivo para rodar em um dispositivos móvel | MÉDIA | 
|RNF-002| Deve processar requisições do usuário em no máximo 3s |  BAIXA | 

Com base nas Histórias de Usuário, enumere os requisitos da sua solução. Classifique esses requisitos em dois grupos:

- [Requisitos Funcionais
 (RF)](https://pt.wikipedia.org/wiki/Requisito_funcional):
 correspondem a uma funcionalidade que deve estar presente na
  plataforma (ex: cadastro de usuário).
- [Requisitos Não Funcionais
  (RNF)](https://pt.wikipedia.org/wiki/Requisito_n%C3%A3o_funcional):
  correspondem a uma característica técnica, seja de usabilidade,
  desempenho, confiabilidade, segurança ou outro (ex: suporte a
  dispositivos iOS e Android).
Lembre-se que cada requisito deve corresponder à uma e somente uma
característica alvo da sua solução. Além disso, certifique-se de que
todos os aspectos capturados nas Histórias de Usuário foram cobertos.

## Restrições

O projeto está restrito pelos itens apresentados na tabela a seguir.

|ID| Restrição                                             |
|--|-------------------------------------------------------|
|01| O projeto deverá ser entregue até o final do semestre |
|02| Não pode ser desenvolvido um módulo de backend        |

Enumere as restrições à sua solução. Lembre-se de que as restrições geralmente limitam a solução candidata.

> **Links Úteis**:
> - [O que são Requisitos Funcionais e Requisitos Não Funcionais?](https://codificar.com.br/requisitos-funcionais-nao-funcionais/)
> - [O que são requisitos funcionais e requisitos não funcionais?](https://analisederequisitos.com.br/requisitos-funcionais-e-requisitos-nao-funcionais-o-que-sao/)

# Catálogo de Serviços

Descreva aqui todos os serviços que serão disponibilizados pelo seu projeto, detalhando suas características e funcionalidades.

# Arquitetura da Solução

Definição de como o software é estruturado em termos dos componentes que fazem parte da solução e do ambiente de hospedagem da aplicação.

![arq](https://github.com/user-attachments/assets/b9402e05-8445-47c3-9d47-f11696e38a3d)


## Tecnologias Utilizadas

Descreva aqui qual(is) tecnologias você vai usar para resolver o seu problema, ou seja, implementar a sua solução. Liste todas as tecnologias envolvidas, linguagens a serem utilizadas, serviços web, frameworks, bibliotecas, IDEs de desenvolvimento, e ferramentas.

Apresente também uma figura explicando como as tecnologias estão relacionadas ou como uma interação do usuário com o sistema vai ser conduzida, por onde ela passa até retornar uma resposta ao usuário.

## Hospedagem

Explique como a hospedagem e o lançamento da plataforma foi feita.

# Planejamento

##  Quadro de tarefas

> Apresente a divisão de tarefas entre os membros do grupo e o acompanhamento da execução, conforme o exemplo abaixo.

### Semana 1

Atualizado em: 21/04/2024

| Responsável   | Tarefa/Requisito | Iniciado em    | Prazo      | Status | Terminado em    |
| :----         |    :----         |      :----:    | :----:     | :----: | :----:          |
| AlunaX        | Introdução | 01/02/2024     | 07/02/2024 | ✔️    | 05/02/2024      |
| AlunaZ        | Objetivos    | 03/02/2024     | 10/02/2024 | 📝    |                 |
| AlunoY        | Histórias de usuário  | 01/01/2024     | 07/01/2005 | ⌛     |                 |
| AlunoK        | Personas 1  |    01/01/2024        | 12/02/2005 | ❌    |       |

#### Semana 2

Atualizado em: 21/04/2024

| Responsável   | Tarefa/Requisito | Iniciado em    | Prazo      | Status | Terminado em    |
| :----         |    :----         |      :----:    | :----:     | :----: | :----:          |
| AlunaX        | Página inicial   | 01/02/2024     | 07/03/2024 | ✔️    | 05/02/2024      |
| AlunaZ        | CSS unificado    | 03/02/2024     | 10/03/2024 | 📝    |                 |
| AlunoY        | Página de login  | 01/02/2024     | 07/03/2024 | ⌛     |                 |
| AlunoK        | Script de login  |  01/01/2024    | 12/03/2024 | ❌    |       |

Legenda:
- ✔️: terminado
- 📝: em execução
- ⌛: atrasado
- ❌: não iniciado
