# Plano de custos

## 1. Introdução

O plano de custos descreve como os custos do projeto serão planejados, estruturados e controlados, fornecendo detalhes dos processos e ferramentas usadas. A primeira etapa é a estimativa de custos, realizada para estimar o custo dos recursos necessários para a execução do projeto. Depois é determinado o orçamento, agregando todos os custos estimados. Por fim, é feito o controle desses custos para monitorar e possivelmente atualizar o orçamento.

Este documento apresenta a estimativa de custos, orçamentos e controle, para que o projeto possa ser realizado dentro do orçamento planejado.


## 2. Estimativa de custos

### 2.1 Pessoas
Para essa estimativa de custos foi utilizado o custo médio anual por aluno de instituto federal. De acordo com [jornal da unesp](https://jornal.unesp.br/2022/06/08/cobranca-de-mensalidade-nao-e-a-solucao-para-o-financiamento-da-universidade-publica/) [5], esse custo é de R$40.900 anual por aluno. Para essa estimativa, leva-se também em consideração o curso da equipe, Engenharia de Software, que é um curso de 5 anos, de 232 créditos. Considerando também as 14 semanas de projeto e os 4 integrantes da equipe, temos os seguintes cálculos.

**Custo médio por crédito**
* custo médio anual por integrante x quantidade padrão de anos de curso ÷ quantidade de créditos para formação no curso
* 40.900 x 5 ÷ 232 = R$**881,50**

**Custo médio por integrante na disciplina de EPS**
* custo médio por crédito x quantidade de créditos da disciplina
* 881,5 x 4 = R$**3.526,00**

**Custo TOTAL por equipe**
* custo médio por integrante na disciplina de EPS x quantidade de integrantes da equipe
* 3526,00 x 4 = R$**14.104,00**

**Custo médio semanal por equipe**
* custo TOTAL por equipe ÷ quantidade de semanas do projeto
* 14.104,00 ÷ 14 = R$**1.007,43**

### 2.1.1 Remuneração
Serão considerados os estudantes como desenvolvedores júnior e adotando um salário mensal de R$4000,00 por uma carga horária de 36h semanais. Para os 4 estudantes do grupo teremos o seguinte:
**Custo semanal de remuneração**
* custo mensal ÷ quantidade de semanas no mês
* 4000,00 ÷ 4 = **R$1000,00**

**Custo total semanal de remuneração por equipe**
* custo semanal individual X quantidade de integrantes
* 1000,00 X 4 = **R$4000,00**

**Custo total de remuneração**
* custo total semanal X quantidade de integrantes X quantidade de semanas
* 4000,00 X 4 X 14 = **R$224.000,00**

### 2.2 Equipamentos
Para a estimativa de custos dos equipamento será considerado o preço de um _notebook_ com as configurações mínimas de um Intel Core I5 ou AMD Ryzen 5 com 8gb de memória RAM em 2024. Segundo [Kabum](https://www.kabum.com.br/computadores/notebooks) [7], o preço de um notebook com essas características está em torno de R$ 2,5 mil. Considerando os 4 integrantes da equipe:

**Custo TOTAL dos equipamentos**
* custo médio do notebook x quantidade de integrantes da equipe
* 2.500 x 4 = R$**10.000,00**

### 2.3 Ferramentas
A estimativa de custos com ferramentas será considerado como R$25, pois as plataformas e ferramentas utilizadas pela equipe são gratuitas, mas a API do chatGPT é paga e custa esse valor.

### 2.4 Capacitação
A estimativa de custos com cursos de capacitação será considerado como R$0, pois as plataformas e ferramentas utilizadas pela equipe foram gratuitas.


### 2.5 Infraestrutura
A estimativa de custos de infraestrutura foi planejada considerando o uso de energia elétrica e internet.

#### Internet
Para cálculo do custo de internet utilizaremos o preço médio de planos de 250 MB por mês que, de acordo com [melhorescolha](https://melhorescolha.com/internet-banda-larga/brasilia-df/) [4],é cerca de R$ 89,99.

**Custo semanal de internet por integrante**
* custo mensal da internet ÷ quantidade de semana no mês
* 90,00 ÷ 4 = R$**22,50**

**Custo semanal de internet por equipe**
* custo semanal da internet por integrante x quantidade integrantes
* 22,50 x 4 = R$**90,00**

**Custo TOTAL de internet por equipe**
* custo semanal da internet por equipe x quantidade de semanas do projeto
* 90,00 x 14 = R$**1.260,00**

#### Energia
Para a estimativa de energia, seguiu-se os dados da [tabela de tarifas](https://www.neoenergiabrasilia.com.br/residencial-e-rural/Documents/tafiras%20vigentes/01_nbsb_tarifas_energia_eletrica_grupoB_nov_2022_reh3134.pdf) [2] da [neoenergiabrasilia](https://www.neoenergiabrasilia.com.br/Paginas/default.aspx), com os dados vigentes de novembro de 2022 à outubro de 2023. Segundo essa tabela, o custo do KW/h residencial, consumo ativo, de Brasília é cerca de R$0,70.
Segundo dados de 2021 da [cultura uol](https://cultura.uol.com.br/noticias/26097_6-maneiras-de-economizar-na-conta-de-luz-do-home-office.html) [3], um notebook consome em média cerca de 65W/h, conectado ao carregador. Consideramos que cada integrante da equipe trabalhará 4 horas por semana em sua residência, ao longo de 17 semanas. Utilizando esses dados para cálculo, temos:

**Consumo do notebook em KW/h:**
* potência x horas ÷ 1000  
* 65 x 1 ÷ 1000 = **0,065** KW/h

**Custo semanal de energia por integrante**

* horas de trabalho x consumo do notebook x tarifa
* 4h x x 0,065KW/h x R$0,70
* 4 x 0,065 x 0,70 = R$**0,18**

**Custo semanal de energia por equipe**
* custo semanal por aluno x quantidade de integrantes da equipe
* 0,18 x 4 = R$**0,72**

**Custo TOTAL de energia por equipe**
* custo semanal por equipe x quantidade de semanas do projeto
* 0,72 x 14 = R$**10,08**

#### Custo TOTAL infraestrutura
Somando as estimativas de custo semanal de internet (R$**90,00**) e energia (R$**0,72**) por equipe, têm-se um custo semanal de infraestrutura de **R$90,72**. Considerando as 14 semanas de projeto, o custo total de infrastrutura será de **R$1.270,08**.


### 2.6 Vales
Tendo em vista que temos custos de locomoção e de alimentação causados pela disciplina e pelo projeto, adotaram-se os seguintes valores: duas passagens de R$5,50 por dia de aula e R$6,10 destinados ao almoço no restaurante universitário da UnB. Logo, os custos são:
**Custo semanal de vale transporte**
* custo do transporte X quantidade de transportes por dia X quantidade de aulas por semana X quantidade de alunos 
* R$((5,50 * 2) * 2) * 4 = **R$88,00**

**Custo semanal de vale alimentação**
* custo do almoço X quantidade de aulas por semana X quantidade de alunos
* R$(6,10 * 2) * 4 = **R$48,80**

**Custo total semanal com vales pela equipe**
* Custo semanal de vale transporte + Custo semanal de vale alimentação
* R$88,00 + R$48,80 = **R$136,80**

**Custo total com vales pela equipe**
* Custo total semanal com vales X quantidade de alunos
* R$136,80 * 4 = **R$547,20**


## 3. Definição do orçamento

Considerando as estimativas de custos acima calculadas, o orçamento total para o projeto em 14 semanas é:

* custo pessoas + remuneração + custo equipamentos + custo ferramentas + custo capacitação + custo infraestrutura + custo vales
* R$14.104,00 + R$224.000,00 + R$10.000,00 + R$25 + R$0 + R$1.270,08 + R$547,20 = **R$249.946,28**


## 6. Referências Bibliográficas

> [1] Escritório de Projetos. Gerenciamento dos custos: O que é, objetivo e processos. Disponível em: https://escritoriodeprojetos.com.br/gerenciamento-dos-custos-do-projeto. Acesso em: 17 de setembro de 2023  
> [2] Neoenergia Brasília. Tarifas. Disponível em: https://www.neoenergiabrasilia.com.br/residencial-e-rural/Paginas/tarifas.aspx. Acesso em: 17 de setembro de 2023  
> [3] Cultura UOL. 6 maneiras de economizar na conta de luz do home office. Disponível em: https://cultura.uol.com.br/noticias/26097_6-maneiras-de-economizar-na-conta-de-luz-do-home-office.html. Acesso em: 17 de setembro de 2023  
> [4] Melhor escolha. Internet em Brasília. Disponível em: https://melhorescolha.com/internet-banda-larga/brasilia-df/. Acesso em: 17 de setembro de 2023  
> [5] Jonal da Unesp. Cobrança de mensalidade não é a solução para o financiamento da universidade pública. Disponível em: https://jornal.unesp.br/2022/06/08/cobranca-de-mensalidade-nao-e-a-solucao-para-o-financiamento-da-universidade-publica/. Acesso em: 17 de setembro de 2023  
> [6] Alectrion. Disponível em: https://fga-eps-mds.github.io/2023-1-Alectrion-DOC. Acesso em: 17 de setembro de 2023  
> [7] Kabum. Disponível em: https://www.kabum.com.br/computadores/notebooks. Acesso em: 17 de setembro de 2023  

## **Histórico de Versão**

| Data | Versão | Descrição | Autor |
| ---------- | --- | -------------------- | ----- |
| 07/05/2024 | 0.1 | Criação do documento | Lucas |