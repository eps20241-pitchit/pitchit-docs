# Backlog do Produto

## **1. Introdução**

Neste documento de Backlog do Produto está organizado todas as funcionalidades do sequenciador elaborado no Lean Inception, os requisitos funcionais traduzidos em histórias de usuário e os requisitos não funcionais relacionadas ao desenvolvimento do FGAad.

## **2. Metodologia**

Utilizando as práticas do Lean Inception, a equipe mapeou as funcionalidades do projeto nas atividades de Brainstorm e na identificação das personas, conhecendo seus perfis e jornadas. Essas reuniões nos deram uma visão das necessidades do pitch it. Em seguida, nos reunimos em duplas para traduzir essas funcionalidades em User Stories do backlog do produto, garantindo que cada aspecto fosse alinhado com nossa visão do projeto.

## **3. Objetivo**

O objetivo deste documento é identificar e agrupar de forma adequada as necessidades do _FGAad_. Aqui estão apresentadas as User Stories, que surgiram a partir das funcionalidades identificadas durante as atividades de Lean Inception realizadas pela equipe de Marketing Digital.

## **3. Sequenciador**

### **1ª Onda**

| ID  | Valor                | Funcionalidade                                                |
| --- | -------------------- | ------------------------------------------------------------- |
| F01 | 🚴‍♂️🚴‍♂️ 💰💰💰 ❤️       | Integração com a API do likedin                               |
| F02 | 🚴‍♂️🚴‍♂️ 💰💰💰 ❤️ ❤️ ❤️ | Gerador de publicação para redes sociais(post service)        |
| F03 | 🚴‍♂️ 💰💰 ❤️ ❤️ ❤️     | Template de publicação em redes sociais usando o post service |

### **2ª Onda**

| ID  | Valor          | Funcionalidade                                     |
| --- | -------------- | -------------------------------------------------- |
| F04 | 🚴‍♂️🚴‍♂️ 💰💰💰 ❤️ | Integração com a API do chatgpt                    |
| F05 | 🚴‍♂️ 💰💰 ❤️❤️   | É esperado o MVP fique pronto ao final desta onda. |
| F06 |                | Template de resposta do gerador de pitch           |

### **3ª Onda**

| ID  | Valor                | Funcionalidade                               |
| --- | -------------------- | -------------------------------------------- |
| F07 | 🚴‍♂️🚴‍♂️🚴‍♂️ 💰💰💰 ❤️❤️❤️ | Integração com a API do Instagram            |
| F08 | 🚴‍♂️🚴‍♂️🚴‍♂️ 💰💰💰 ❤️❤️❤️ | Utilizar um microsserviço de CRUD de usuario |
| F09 |                      | Ter controle de acesso                       |

### **4ª Onda**

| ID  | Valor | Funcionalidade                                                     |
| --- | ----- | ------------------------------------------------------------------ |
| F10 |       | Realizar engenharia de prompt com a IA                             |
| F11 |       | Obter informações de quantas vezes o gerador de pitch foi utlizado |
| F12 |       | Obter informações de quantas vezes o post service foi utilizado    |

### **5ª Onda**

| ID  | Valor            | Funcionalidade                                     |
| --- | ---------------- | -------------------------------------------------- |
| F13 | 🚴‍♂️🚴‍♂️ 💰💰 ❤️❤️❤️ | personalização de template de acordo com o cliente |

## 4. Requisitos Funcionais

As User Stories deste documento seguem o padrão papel-ação-valor:

> _Eu como **tipo de usuário**,
> desejo **uma ação**
> para que **um benefício/valor**._

| ID   | User Stories                                                                                                                                                                                      | Tasks                                                                                                                                                                                                                                  | Prioridade |
| ---- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------- |
| US01 | Eu como desenvolvedor desejo utilizar a API liberada pelo Likedin                                                                                                                                 | <ul> <li> Implementar consumo da API; <li> Garantir a integridade do consumo;| Alta       |

| US02 | Eu como usuario desejo postar uma imagem junto com pitch gerado | <ul> <li> Criar um template de publicação; </ul>                                                                                                                                                   | Alta       |
| US03 | Eu como um usuario desejo realizar postagens sobre o pitch desenvolvido com a plataforma| <ul> <li> Postar no Likedin<li> <li> Postar a imagen no Likedin </li>  </ul>                                                                                                                             | Alta       |

| US04 | Eu como desenvolvedor desejo utilizar a API liberada pelo Instagram                                                                                                                                | <ul> <li> Implementar consumo da API; <li> Garantir a integridade do consumo;| Alta       |
| US05 | Eu como desenvolvedor desejo utilizar a API liberada pelo chatGPT | <ul> <li> Implementar consumo da API; <li> Garantir a integridade do consumo; | Alta       |
| US06 | Gerar o pitch usando a inteligencia artificial | <ul><li> Coletar os dados do cliente <li> Enviar para a IA gerar o pitch <li> Retornar o pitch para o cliente; </li> </ul>                                                                                                 | Alta       |
| US07 | Eu como usuario gostaria de administrar minha conta | <ul> <li> Cadastrar conta; <li> Acessar conta; </li> <li> Editar dados da conta; <li> Apagar conta </li>  | Alta       |
| US08 | Eu como usuario gostaria de garantir login | <ul> <li> autenticar usuario <li> | Média      |
| US09 | Eu como desenvolvedor quero treinar a IA para garantir respostas mais acertivas | <ul> <li> Respostas mais adequadas </li>  | Média      |
| US10 | Eu como desenvolvedor quero saber quantas vezes o gerador de pitch foi utlizado| <ul> <li> quantidade de uso </li>                            | Baixa      |
| US11 | Eu como desenvolvedor quero saber quantas vezes o gerador de publicação foi utlizado | <ul> <li> quantidade de uso </li>   | Baixa      |

## **5. Requisitos Não Funcionais**

|  ID   |        Requisito         |
| :---: | :----------------------: |
| RNF01 |   Criar banco de dados   |
| RNF02 | Validar entrada de dados |

### **Bibliografia**

- Beck, Kent. Programação extrema (xp) explicada. bookman, 2004.
- Caroli, Paulo. "Lean inception." São Paulo, BR: Caroli. org (2017).

## **Histórico de Versão**

| Data       | Versão | Descrição                                                                                              | Autor                        |
| ---------- | ------ | ------------------------------------------------------------------------------------------------------ | ---------------------------- |
|06/05/2024 | 0.1    | Estrutura inicial do documento | Douglas, Iago, Lucas, Pedro |

