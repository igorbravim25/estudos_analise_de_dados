## Estudo em Análise de Dados com Notebook LM 📊

## 📍Guia de estudos sobre analise de dados (mySQL, Python/Pandas e power bi), usando notebbok lm como ferramenta de aprendizagem.
---
Este projeto tem como objetivo desenvolver um guia prático de análise de dados, utilizando Inteligência Artificial (NotebookLM) como ferramenta de apoio ao aprendizado. A escolha do tema se dá por ser uma meta de aprendizados, relacionado a minha área de estudo, um conteúdo que desejo desenvolver e me aperfeiçoar. 
A proposta vai além da teoria, focando em:

* Entendimento do processo de análise de dados

* Uso de IA para auxiliar na interpretação

* Desenvolvimento de pensamento analítico

* Criação de um material reutilizável de estudo

---

## 🎯 Objetivos de Estudo

* Compreender o processo de análise de dados (do início ao fim)
* Aprender conceitos fundamentais de dados
* Utilizar IA para explorar, interpretar e resumir informações
* Desenvolver habilidade de fazer perguntas estratégicas
* Criar um guia reutilizável para estudos futuros

---

## 🔎 Curadoria de Fontes

Fontes utilizadas no NotebookLM:

1. 📘 Introdução à Análise de Dados (PDF acadêmico)
2. ▶️ Vídeos e Playlists do YouTube
3. 🛠️ PDF introdutório de primeiros contatos com ferramentas

## Links de Uploads

vídeo de estratégia de estudos: https://www.youtube.com/watch?v=QBPHjFnAZEU

PDF introdutório: https://repositorio.enap.gov.br/bitstream/1/7657/1/M%C3%B3dulo%201%20-%20An%C3%A1lise%20de%20Dados_Apresenta%C3%A7%C3%A3o%20e%20%20Ferramentas%20B%C3%A1sicas.pdf

Pandas para iniciantes: https://www.youtube.com/watch?v=sODNyvVW8wY

---

## 🤖 Engenharia de Prompts e "Cicatrizes"

---

### 🔹 Prompt 1 (Inicial)

"Explique análise de dados."

Resposta: De forma bem simples, a análise de dados é o processo de transformar dados "crus" e dispersos em informações e conhecimentos úteis para a tomada de decisões
.

❌ Problema:
Resposta muito genérica

---

### 🔹 Prompt 1 (Ajustado)

"Explique o processo completo de análise de dados, desde a definição do problema até a geração de insights, destacando riscos comuns e boas práticas em cada etapa."

Resposta: O processo completo de análise de dados é uma jornada estruturada que transforma dados brutos em informações e conhecimentos úteis para a tomada de decisão em negócios, políticas públicas ou pesquisas. O objetivo central não é apenas dominar ferramentas, mas gerar valor respondendo a perguntas específicas. O processo pode ser dividido nas seguintes fases principais:

1. Compreensão do Problema e Fundamentos Estatísticos
Antes de manipular qualquer informação em softwares, é fundamental entender o que os dados representam. A base de uma análise robusta é a estatística, que se divide em passos de aprofundamento:
* Estatística Descritiva: É o básico para entender o dado, envolvendo o cálculo de médias, moda, mediana, percentis, desvio padrão e a criação de gráficos simples (linha, barra, colunas).
  
* Probabilidade e Relacionamentos: Compreender distribuições (normal, uniforme, binomial) e analisar como diferentes variáveis interagem através da correlação e causalidade.
  
* Inferência Estatística: Aplicação de testes de hipóteses e intervalos de confiança para extrapolar resultados de uma amostra para toda a população.

Além disso, a análise inicial pode ter uma abordagem quantitativa (focada em números e métricas objetivas), qualitativa (subjetiva, focada em qualidades e perfis) ou ser uma abordagem híbrida (quali-quantitativa) para garantir uma leitura crítica e minimizar vieses de interpretação.

2. Manipulação e Tratamento dos Dados
Nesta etapa, o analista extrai, limpa, filtra e organiza os dados para que deixem de ser um "amontoado" e passem a ter estrutura.
Existem duas trilhas principais adotadas no mercado para essa fase:
O Caminho Tradicional:
* Planilhas (Excel / Google Sheets): Inicia-se com a organização de planilhas limpas, uso de fórmulas lógicas e de busca (SE, PROCV, PROCX), agregações com tabelas dinâmicas e formatação condicional.

*SQL: Quando o volume de dados cresce, utiliza-se a linguagem SQL para consultar Bancos de Dados Relacionais. O analista usa comandos como SELECT, WHERE e uniões de tabelas (JOIN) para cruzar informações de diferentes fontes, além de agrupar resultados com GROUP BY e funções como soma (SUM) ou média (AVG).

O Caminho da Programação (Python):
* Substitui-se as múltiplas ferramentas por uma única linguagem: o Python, focando primeiramente na biblioteca Pandas.

* O Pandas permite ler arquivos (Excel, CSV, SQL), aplicar filtros booleanos, e realizar tratamento de dados faltantes (nulos) deletando-os com dropna ou preenchendo-os com médias via fillna. Permite também agregações complexas em poucas linhas de código, calculando múltiplas métricas simultaneamente de forma automatizada e escalável.

3. Data Storytelling e Apresentação
Ter os dados limpos e agrupados não é o fim do processo. A etapa de Data Storytelling (narrativa de dados) é frequentemente considerada a mais importante, pois é onde o resultado é comunicado. Definição do "Porquê": Antes de construir painéis visuais, deve-se definir a pergunta inicial e entender quais métricas fundamentam a história que o dado está contando.

* Apresentações Executivas: Muitas vezes, o alto escalão de uma empresa não acessa planilhas complexas ou linguagens de programação. É preciso saber sintetizar os resultados em apresentações sucintas (PPTs de 2 ou 3 slides) para otimizar o tempo dos tomadores de decisão.

4. Visualização e Criação de Dashboards
Para o acompanhamento contínuo dos indicadores (KPIs), constroem-se painéis interativos (dashboards).
No modelo tradicional, utiliza-se o Power BI para conectar as bases de dados e criar visualizações amigáveis, onde os usuários podem interagir e filtrar informações ativamente.

* Na trilha de programação em Python, utilizam-se bibliotecas como Plotly (para gráficos interativos e customizáveis) e Streamlit (para transformar os scripts em aplicações e sistemas web completos, sem necessidade de saber HTML ou CSS).

5. Análise Avançada e Automação (Machine Learning)
Com o processo estruturado, a análise pode ser elevada a um nível preditivo. Utilizando programação (Python), o analista aplica a biblioteca Scikit-Learn para inferência estatística complexa e Machine Learning, permitindo que o sistema aprenda com os dados e automatize predições. Além disso, a vantagem de programar a análise (em vez de usar planilhas manuais) é que o código pode ser salvo e reutilizado; sempre que chegarem dados novos, basta rodar o mesmo script para atualizar os relatórios automaticamente.

✔️ Resultado:
Resposta estruturada e mais útil

---

### 🔹 Prompt 2 (Inicial)

"Explique como identificar vieses?"

Resposta: Para lidar com isso, a recomendação para minimizar esses vieses é utilizar diferentes métodos de investigação de forma complementar: combinando métodos qualitativos, quantitativos e híbridos.


❌ Muito resumido

---

### 🔹 Prompt 2 (Ajustado)

"Explique como identificar vieses em um conjunto de dados e quais impactos eles podem causar na análise e tomada de decisão."

Resposta: Segundo o material, a análise de dados é uma abstração e um "esboço estatístico" da realidade que possui imperfeições inerentes e não é perfeito. Para combater e minimizar esses vieses, a recomendação é não depender de um único tipo de visão, mas sim utilizar diferentes métodos de investigação em conjunto:

* Métodos Quantitativos: Análises objetivas focadas em números e métricas.
* Métodos Qualitativos: Análises subjetivas focadas em qualidades e contextos.
* Métodos Híbridos (Quali-quantitativos): A combinação de ambos, garantindo uma leitura crítica, visto que esses vieses são considerados complementares.

Para identificar vieses em um conjunto de dados, você deve fazer perguntas críticas durante a exploração:
* Identifique a fonte (Viés de Seleção/Interesse): Pergunte-se quem coletou os dados e com qual objetivo. Se uma pesquisa sobre os malefícios de um alimento for financiada por uma empresa que vende um produto concorrente, os dados podem estar enviesados para favorecer um lado.
* Analise a amostra (Viés de Amostragem): Verifique se o subconjunto de dados realmente representa o todo. Por exemplo, realizar uma pesquisa de intenção de voto nacional entrevistando pessoas de apenas um bairro rico de uma única cidade.
* Busque dados omitidos (Viés de Sobrevivência): Analise se os dados estão contando apenas a história de quem "teve sucesso". Por exemplo, avaliar a taxa de sucesso de startups baseando-se apenas nas empresas que ainda estão abertas, ignorando os dados de todas as que faliram.
* Analise a sua própria interpretação (Viés de Confirmação): Verifique se você está escolhendo e filtrando apenas as métricas que confirmam uma crença ou hipótese que você já tinha antes de iniciar a análise, ignorando números que provem o contrário.

Quais os impactos dos vieses e de dados ruins na análise e tomada de decisão? Com base nos documentos, os impactos recaem diretamente na qualidade da informação entregue aos tomadores de decisão:
* Decisões prejudicadas por falta de qualidade: Uma tomada de decisão eficiente exige qualidade do dado, qualidade no seu processamento e adequação às necessidades do tomador de decisão.
* Se os dados contiverem vieses, eles afetarão as características fundamentais de uma boa informação, como sua precisão, relevância, completude, concisão e clareza
* Geração de análises superficiais: O analista que apenas manipula dados sem o devido entendimento estatístico acaba gerando muitas informações sem saber o que elas realmente significam.
* O impacto disso são análises "bobas" e sem profundidade, que falham em gerar o valor esperado pela empresa.

* Visualização inadequada: Escolhas ruins na visualização também enviesam a interpretação. Por exemplo, utilizar gráficos de pizza para exibir dados com muitas categorias é considerado altamente prejudicial, pois impede que o leitor analise a informação corretamente.


✔️ Resultado:
Melhor compreensão do processo completo

---

### 🔹 Prompt 3

"Quais os problemas de qualidade de dados?"

Resposta: 
* Inconsistências por redundância: Ocorre quando a mesma informação é armazenada em locais diferentes, gerando duplicidade e conflito de dados.

* Falhas de integridade: Problemas estruturais, como inserir texto em campos numéricos, tentar cadastrar registros com chaves primárias já existentes (duplicação)
 ou a exclusão de dados que deixam outros registros "órfãos" (perda de integridade referencial).

* Processamento inadequado: A falta de qualidade na manipulação do dado faz com que a informação gerada não seja adequada para a necessidade do tomador de decisão.

* Imperfeições e vieses inerentes: Como a representação dos dados é um "esboço estatístico" abstrato da realidade, ela não é perfeita e possui vieses que exigem métodos complementares para serem minimizados.

❌ Muito resumido

### 🔹 Prompt 3 (Ajustado)
"Quais são os principais problemas de qualidade de dados (dados ausentes, inconsistentes, duplicados) e como tratá-los na prática?"

Resposta: Os principais problemas de qualidade de dados envolvem falhas que prejudicam a interpretação e confiabilidade das informações. Com base nas fontes, eles se dividem nestas categorias principais:
Dados ausentes (nulos): Ocorrem quando informações vitais estão em falta nas tabelas e bases de dados, sendo frequentemente representados em sistemas de análise como valores vazios.

* Inconsistências por redundância e duplicação: Acontecem quando a mesma informação é armazenada em locais diferentes, causando duplicidade descontrolada e conflitos nos dados.

* Falhas de integridade: Problemas estruturais nas bases, como a inserção de textos em campos exclusivos para números, cadastros duplicados que violam chaves primárias existentes e a exclusão de registros que deixam outros dados "órfãos" (perda de integridade referencial).

Na prática, o tratamento e a correção desses problemas ocorrem em duas frentes:
1. Prevenção e correção na origem (via SGBD) Para evitar que o dado seja gravado de forma incorreta, os Sistemas Gerenciadores de Bancos de Dados (SGBDs) aplicam rigorosos controles de integridade e redundância. A ferramenta centraliza a informação em um único local (evitando duplicatas) e força restrições estruturais, bloqueando automaticamente a inserção de dados inconsistentes ou a deleção de chaves referenciadas.

2. Tratamento analítico automatizado (Usando Python e Pandas) Quando os dados já foram exportados (como em arquivos CSV ou Excel) e o analista precisa manipulá-los, o uso de linguagens de programação como o Python, em especial a biblioteca Pandas, é altamente recomendado para limpar colunas com dados incorretos e tratar dados faltantes. As estratégias práticas no código incluem:
* Remoção de dados nulos: Quando as linhas em branco prejudicam a análise, você pode removê-las completamente da tabela através do método dropna. Se quiser focar a limpeza apenas em nulos de uma coluna específica, adiciona-se o argumento subset à função.

* Preenchimento de dados ausentes (Substituição): Quando há uma quantidade significativa de dados vazios e descartar as linhas reduzirá drasticamente sua base, a prática comum é usar o método fillna. Com ele, você sobrescreve os espaços nulos utilizando uma estimativa estatística, como o valor da média de todas as idades ou salários presentes naquela coluna.
* 
* Padronização de tipos de dados: Para lidar com inconsistências de formatação (como sistemas que leem números inteiros como casas decimais quebradas), utiliza-se o método astype (ex: astype(int)) para padronizar e forçar a conversão correta daquela coluna.

✔️ Resultado:
Esclareceu conceitos fundamentais

---

### 📉 Dificuldades Encontradas

* IA tende a simplificar demais
* Falta de exemplos em respostas iniciais
* Necessidade de refinar perguntas

---

### 📈 Aprendizados

* Prompts específicos geram respostas melhores
* Pedir exemplos é essencial
* A IA funciona melhor como apoio, não substituição do estudo

---

## 📘 Miniguia de Estudo

---

### 🧠 O que é Análise de Dados?

Processo de inspecionar, transformar e interpretar dados para extrair informações úteis e apoiar decisões.

---

### 🧠 Etapas da Análise de Dados

1. **Coleta de dados**
2. **Limpeza de dados**
3. **Exploração dos dados (EDA)**
4. **Análise e interpretação**
5. **Comunicação dos resultados**

---

### 🧠 Tipos de Análise

* **Descritiva:** o que aconteceu
* **Diagnóstica:** por que aconteceu
* **Preditiva:** o que pode acontecer
* **Prescritiva:** o que deve ser feito

---

### 🧠 Exemplo Prático

Situação: análise de vendas de uma loja

* Dados: vendas mensais
* Pergunta: por que as vendas caíram?
* Insight: queda em determinado período pode indicar sazonalidade

---

### 🧠 Ferramentas Utilizadas

* Planilhas (Excel/Google Sheets/power BI)
* Linguagens como Python (pandas)

---

## 📖 Glossário

* **Dados:** valores brutos
* **Informação:** dados organizados
* **Insight:** conclusão útil extraída dos dados
* **EDA:** análise exploratória de dados
* **Dataset:** conjunto de dados

---

## 🔁 Prompts Reutilizáveis

* "Explique [conceito] com exemplo prático"
* "Quais são as etapas de [processo]?"
* "Resuma [tema] em tópicos"
* "Explique a diferença entre [A] e [B]"
* "Crie um exemplo prático de análise de dados"
* "Quais insights podem ser extraídos desse cenário?"

---

## 🚀 Conclusão

Este projeto demonstrou que a Inteligência Artificial pode ser utilizada como uma poderosa aliada no aprendizado de análise de dados.

Através da engenharia de prompts e da análise crítica das respostas, foi possível construir um guia prático e reutilizável.

---

## 💡 Próximos Passos

* Aprender Python para análise de dados
* Trabalhar com datasets reais
* Criar visualizações de dados
* Evoluir para ciência de dados

---

## 👨‍💻 Autor

Projeto desenvolvido por Igor Bravim Azeredo
