# Backlog do Produto

## **Histórico de Versão**
| Data | Versão | Descrição | Autor |
|--|--|--|--|
| 09/04/2024 | 0.1 | Estrutura inicial do documento | Douglas Farias e Edvan Gomes |
| 09/04/2024 | 0.2 | Adicionado a metodologia utilizada, o objetivo e algumas user stories da primeira onda do sequenciador | Douglas Farias |
| 10/04/2024 | 0.3 | Adicionado as ondas do projeto | Douglas Farias |
| 10/04/2024 | 0.4 | Ajustando primeiras USs e criando primeiros RNF | Edvan Gomes |
| 16/04/2024 | 0.5 | Adicionado introdução e USs da 2ª onda | Douglas Farias |

## **1. Introdução**
Neste documento de Baxklog do Produto está organizado todas as funcionalidades do sequenciador elaborado no Lean Inception, os requisitos funcionais traduzidos em histórias de usuário e os requisitos não funcionais relacionadas ao desenvolvimento do FGAad.

## **2. Metodologia**
Utilizando as práticas do Lean Inception, a equipe mapeou as funcionalidades do projeto nas atividades de Brainstorm e na identificação das personas, conhecendo seus perfis e jornadas. Essas reuniões nos deram uma visão das necessidades do FGAad. Em seguida, nos reunimos em duplas para traduzir essas funcionalidades em User Stories do backlog do produto, garantindo que cada aspecto fosse alinhado com nossa visão do projeto.

## **3. Objetivo**
O objetivo deste documento é identificar e agrupar de forma adequada as necessidades do *FGAad*. Aqui estão apresentadas as User Stories, que surgiram a partir das funcionalidades identificadas durante as atividades de Lean Inception realizadas pela equipe de Marketing Digital.

## **3. Sequenciador**

### **1ª Onda**
| ID | Valor | Funcionalidade |
| -- | -- | -- |
| F01 | 🚴‍♂️🚴‍♂️ 💰💰💰 ❤️  | Ter controle de acesso |
| F02 | 🚴‍♂️🚴‍♂️ 💰💰💰 ❤️ ❤️ ❤️  | Cadastro das soluções tecnologicas |
| F03 | 🚴‍♂️ 💰💰 ❤️ ❤️ ❤️  | Rotular os projetos |

### **2ª Onda**
| ID | Valor | Funcionalidade |
| -- | -- | -- |
| F04 | 🚴‍♂️🚴‍♂️🚴‍♂️ 💰💰💰 ❤️❤️❤️ | Mantenedor atualiza projeto com noticias/atualizações |
| F05 | 🚴‍♂️🚴 💰💰 ❤️❤️ | Atualização das informações do projetos |
| F06 | 🚴‍♂️ 💰💰 ❤️❤️❤️ | Filtragem de projetos com base nas categorias |

### **3ª Onda**
| ID | Valor | Funcionalidade |
| -- | -- | -- |
| F07 | 🚴‍♂️🚴‍♂️ 💰💰💰 ❤️ | Captar informações com potencial analítico do projeto e usuário |
| F08 | 🚴‍♂️ 💰💰 ❤️❤️ | Exibição dos detalhes dos projetos na pesquisa do usuário |

### **4ª Onda**
| ID | Valor | Funcionalidade |
| -- | -- | -- |
| F08 | 🚴‍♂️🚴‍♂️🚴‍♂️ 💰💰💰 ❤️❤️❤️ | Dashboard do projeto para os mantenedores |
| F09 | 🚴‍♂️🚴‍♂️🚴‍♂️ 💰💰💰 ❤️❤️❤️ | Mais acessados da semana |

### **5ª Onda**
| ID | Valor | Funcionalidade |
| -- | -- | -- |
| F10 | 🚴‍♂️🚴‍♂️ 💰💰 ❤️❤️❤️ | Cadastro de newsletter |
| F11 | 🚴‍♂️🚴‍♂️ 💰💰💰 ❤️❤️ | Níveis de acesso para diferentes tipos de usuário |
| F12 | 🚴‍♂️ 💰💰 ❤️❤️❤️ | Filtrar assuntos que deseja receber na newsletter |

## **4. Requisitos Funcionais**
As User Stories deste documento seguem o padrão papel-ação-valor:

>*Eu como __tipo de usuário__,
desejo __uma ação__
para que __um benefício/valor__.*

| ID | User Stories | Tasks |
| -- | -- | -- |
| US01 | Como um mantenedor de projeto, eu quero ter a capacidade de cadastrar, editar e gerenciar projetos na plataforma, para divulgar os serviços por ele prestados e encontrar patrocinadores. | <ul> <li> Implementar autenticação; <li> Definir niveis de acesso; <li> Definir e implementar formulário de  cadastro; </ul> |
| US02 | Como um mantenedor de projeto, eu quero poder cadastrar imagens e outras mídias do meu projeto, para melhor divulgar as informações necessárias | <ul> <li> Definir quais tipos de mídia são permitidos <li> Criar página para editar projetos </ul> | 
| US03 | Como um mantenedor de projeto, eu quero ter a capacidade de rotular os projetos com labels, para organizar e categorizar os projetos com o objetivo de identificar facilmente projetos similares. | <ul> <li> Definir categorias; <li> Adicionar ao formulário de cadastro;</ul> |
| US04 | Como um mantenedor de projeto, eu quero compartilhar atualizações e notícias do projeto, para manter os usuários interessados atualizados nas novidades do projeto.  | <ul> <li>Fazer migration para tabela de notícia/atualização</li> <li> Criar crud para notícia/atualização; <li> Adicionar página para cadastro de Notícias/Atualizações;</ul> |
| US05 | Como um usuário, quero poder filtrar os projetos com base nas categorias, para que eu possa encontrar rapidamente os projetos que são do meu interesse.  | <ul><li>Adicionar lógica de filtragem ao Backend</li> <li>Adicionar Opções de Filtragem na Interface</li> <li>Atualizar página de visualização de projetos</li> <li>Testar a funcionalidade de filtragem</li></ul> |

## **5. Requisitos Não Funcionais**

|  ID   | Requisito |
| :--:  | :--: |
| RNF01 | Criar banco de dados |
| RNF02 | Validar entrada de dados |

### **Bibliografia**
- Beck, Kent. Programação extrema (xp) explicada. bookman, 2004.
- Caroli, Paulo. "Lean inception." São Paulo, BR: Caroli. org (2017).

