# Análise de Dados da Ice - Loja Online de Videogames

## Descrição do Projeto
Análise exploratória de dados históricos de vendas de jogos de videogame (até 2016) para a loja online Ice, com o objetivo de identificar padrões associados ao sucesso de jogos.

**Contexto:** Este projeto integrador foi desenvolvido durante o bootcamp de Análise de Dados da [Nome da Instituição].

## Objetivos
✅ Identificar fatores que influenciam o sucesso de jogos (ex.: gênero, plataforma, avaliações).
✅ Analisar tendências de mercado por região (Américas, Europa, Japão).
✅ Fornecer insights para orientar investimentos em campanhas publicitárias.

## Fontes de dados

* **Base de dados:** games.csv (disponível no diretório data/ deste repositório).
* **Período abrangido:** Dados históricos até 2016.
* **Variáveis incluídas:**
    * Vendas por região (Américas, Europa, Japão, outros).
    * Plataforma (ex.: PS4, Xbox One, PC).
    * Gênero (Ação, Esportes, RPG, etc.).
    * Avaliações de usuários e críticos.

## Metodologia
1. Limpeza e pré-processamento:
    Tratamento de valores ausentes.
    Filtragem de dados irrelevantes (ex.: plataformas descontinuadas).

2. Análise Exploratória (EDA):
    Correlações entre vendas e avaliações.
    Distribuição de vendas por gênero/plataforma.
    Identificação de outliers.

3. Visualização de dados:
    Gráficos de barras, boxplot e scatter plots (Matplotlib/Seaborn).

4. Análise Estatística:
    Testes de hipóteses (ex.: diferenças regionais nas preferências).

### Principais resultados
📊 **Gêneros mais lucrativos:** Ação, Esportes e Shooter lideram vendas globais.

🌎 **Diferenças regionais:** RPGs são populares no Japão, enquanto Action dominam nas Américas.

🎮 **Plataformas:** PS3, PS4 e Xbox One tiveram maior volume de vendas.

⭐ **Avaliações:** Jogos com nota acima de 85% em críticas tendem a ter melhor desempenho comercial.

### Visualizações-chave
* Gráfico de linhas: *Número de jogos lançados e vendidos por ano* e *Vendas globais por plataforma por ano de lançamento*
* Gráfico de barras: *Ciclo de vida as plataformas*, *Vendas globais por plataforma (a partir de 2013)* e *Total de vendas por plataforma por região*
* Gráfico de barras com linha de erro: *Vendas médias e desvio padrão por jogo e plataforma a partir de 2013*
* Boxplot: *Distribuição de vendas anuais por plataforma*
* Scatterplot: *Avaliações dos usuários vs vendas*, *Avaliações dos críticos vs vendas* e *Relação entre lançamentos e total de vendas por gênero*

### Tecnologias utilizadas
* Linguagem: Python
* Bibliotecas: Pandas, NumPy, Matplotlib, Seaborn
* Ferramentas: Jupyter Notebook

## Instalação e uso  
### Pré-requisitos  
- Python 3.8+  
- Gerenciador de pacotes `pip`  

### Passo a Passo  
1. **Clone o repositório:**  
   ```bash  
   git clone https://github.com/seu-usuario/ice-games-analysis.git  
   cd ice-games-analysis  

2. **Instale as dependências:**
   pip install -r requirements.txt  

3. **Execute o Jupyter Notebook:**
    jupyter notebook ice_analysis.ipynb  
