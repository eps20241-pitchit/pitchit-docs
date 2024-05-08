# <center> **Priorização**

#### **Histórico de Versão**

|    Data    | Versão |      Descrição       |     Autor(es)     |
| :--------: | :----: | :------------------: | :---------------: |
| 07/05/2024 |  0.1   | Criação do documento | Douglas Farias  |
| 08/05/2024 |  0.2   | Priorização dos épicos | Douglas, Lucas, Iago, Pedro  |


<div align="justify">

## **1. Introdução**
A priorização é uma etapa crucial na produção de um software, pois ajuda a minimizar o risco de falhas no desenvolvimento da aplicação. Isso ocorre porque, por meio de um sistema de prioridades, é possível avaliar todos os requisitos e organizar as tarefas de acordo com a importância, quase como uma ordem de implementação.

Ao realizar essa priorização, é importante levar em conta vários fatores, como os diferentes tipos de tecnologias utilizadas, os objetivos desejados, o contexto específico do projeto, entre outros. Existem várias técnicas para auxiliar na priorização de requisitos, e a escolha deve recair sobre a que melhor se adapta ao projeto.

<br/>

## **2. Planning Poker**
Planning Poker é uma técnica colaborativa utilizada na gestão de projetos de software para estimar o esforço necessário para completar tarefas ou histórias de usuário. É uma abordagem eficaz para a estimativa de prazos, custos e complexidade de desenvolvimento de um projeto.

O uso dessa técnica envolveu a participação de toda a equipe, onde cada participante pode votar usando as cartas com os valores 0, 1, 2, 3, 5, 8 e 13. Essas cartas representam a quantidade de esforço ou complexidade que cada integrante atribui ao épico específico.

## **3. Objetivo**

O presente documento tem como objetivo a demostração do resultado da aplicação da técnica de priorização de requisitos _Planning Poker_, que foi aplicada no resultado da elicitação de requisitos do Pitch It, usando as diretrizes desta técnica como guia para classificação de quais deveriam ser priorizados ou não, e qual o grau de sua importância para o sucesso da aplicação.  

<br/>

## **4. Priorização dos Épicos**
- EP01: Controle de Acesso **(Pontuação: 3)**
  - F08: Controle de acesso
    - US01: Eu, como um usuário, desejo criar uma conta, para que possa acessar as funcionalidade do Pitch It.
    - US02: Eu, como um usuário, desejo alterar minhas informações pessoais, para que possa manter meu perfil atualizado.
    - US03: Eu, como um usuário, desejo alterar minha senha de acesso, para que possa garantir a segurança da minha conta.

- EP02: Pitch Service **(Pontuação: 13)**
  - F01: Geração automática de pitches
    - US04: Eu, como um empreendedor/startup, desejo gerar um pitch com base nas informações da minha empresa, para que eu possa aumentar as chances de obter investimentos ou parcerias.
    - US05: Eu, como um estudante de EPS, desejo gerar um pitch com base nas informações do meu projeto, para que eu possa apresentar de forma eficiente e profissional.
    - US06: Eu, como um usuário, desejo acessar templates de pitches para diferentes setores e objetivos, para que eu possa escolher o modelo mais adequado para a minha apresentação.
  - F02: Fornecer orientações sobre apresentação
    - US07: Eu, como um usuário, desejo acessar orientações sobre como estruturar minha apresentação, para garantir que meu pitch seja claro e eficaz.
    - US08: Eu, como um usuário, desejo obter dicas sobre como projetar visualmente minha apresentação, para torná-la mais impactante.
    - US09: Eu, como um usuário, desejo acessar orientações sobre habilidades de comunicação e oratória, para melhorar minha apresentação e aumentar minha confiança.
  - F03: Melhorias no pitch
    - US10: Eu, como um usuário, desejo saber quais são os principais tópicos do meu pitch, para garantir que abordei todos os pontos importantes.
    - US11: Eu, como um usuário, desejo sugerir melhorias no pitch gerado, para ajustá-lo às necessidades e expectativas do público-alvo.
  - F07: Salvar pitch
    - US12: Eu, como um usuário, desejo salvar meu pitch, para que possa revisá-lo posteriormente.
    - US13: Eu, como um usuário, desejo salvar meu pitch automaticamente, para que não perca o progresso caso ocorra um problema inesperado.
    - US14: Eu, como um usuário, desejo organizar meus pitches salvos por categorias/etiquetas, para que possa encontrar rapidamente os pitches relevantes quando necessário.
    - US15: Eu, como um usuário, desejo armazenar versões diferentes do meu pitch, para que possa acessar e comparar as versões conforme necessário.
  - F15: Editar da pitch
    - US16: Eu, como um usuário, desejo personalizar o pitch gerado com base no perfil do público-alvo, para que eu possa adaptar minha apresentação às necessidades do meu público.
    - US17: Eu, como um usuário, desejo editar o pitch gerado para adicionar ou remover conteúdo, para que eu possa personalizar a apresentação de acordo com as preferências e dados disponíveis.

- EP03: Post Service **(Pontuação: 8)**
  - F04: Gerar postagens automaticamente
    - US18: Eu, como um usuário, desejo gerar postagens a partir do pitch gerado, para que meu produto/startup tenha maior visibilidade e impacto.
    - US19: Eu, como um usuário, desejo gerar postagem sobre minha produto/startup, para que ele tenha maior visibilidade e alcance novos clientes.
  - F05: Compartilhamento de pitches nas redes sociais
    - US20: Eu, como um usuário, desejo compartilhar o pitch gerado no LinkedIn, para que possa divulgar minha apresentação e alcançar um público maior.
    - US21: Eu, como um usuário, desejo compartilhar o pitch gerado no Instagram, para que possa divulgar minha apresentação e alcançar um público maior.
    - US22: Eu, como um usuário, desejo compartilhar o pitch gerado no X/Twitter, para que possa divulgar minha apresentação e alcançar um público maior.
  - F06: Melhorias da postagem
    - US23: Eu, como um usuário, desejo sugerir melhorias no postagem gerado, para que a postagem seja mais atraente para o público-alvo.
    - US24: Eu, como um usuário, desejo receber dicas sobre frequência de postagem, para que minha estratégia de publicação seja mais eficaz e atinja maior engajamento.
    - US25: Eu, como um usuário, desejo personalizar a legenda das minhas postagens, para que possa adicionar toques pessoais e manter uma voz consistente com a meu produto/startup.

- EP04: Validação de negócio **(Pontuação: 2)**
  - F09: Obter métricas
    - US26: Eu, como um dono do Pitch It, desejo ver a quantidade de postagens geradas pela aplicação, para que possa validar as hipóteses de negócio.
    - US27: Eu, como um dono do Pitch It, desejo ver a quantidade de pitches gerados pela aplicação, para que possa validar as hipóteses de negócio.



## **Bibliografia**

1. Objetive. Planning Poker. Disponível em <https://www.objective.com.br/insights/planning-poker/>. Acesso: 08/07/2024.

</div>