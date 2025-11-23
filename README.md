# Trabalho-Econometria---IEE-2025.2


README – Trabalho de Econometria I (IEE/UFRJ – 2025.2)

Autores:
- Matheus Ferreira da Silva Costa (DRE: 122144910)
- Arthur Moura da Silva (DRE: 122121629)
- Igor Mato Grosso (DRE: 122150042)

Professor: Vitor Perreira
Curso: Econometria I – Instituto de Economia/UFRJ

LINK PARA O ARQUIVO DO PROJETO: https://drive.google.com/drive/folders/1_uNc-hE6_GybuZwa1A2uu3UQB5o6mziF?usp=drive_link
(Faça o download da pasta raiz(Econometria) por completo. Nela há o projeto e demais pastas)


Estrutura do projeto
------------------------------------------------------------
Arquivos principais:
- Trabalho.Rmd → relatório RMarkdown com todo o código e análises
- cod_logo.html → inclusão de logotipo no cabeçalho do HTML


Pacotes R utilizados:
- dplyr, ggplot2, stargazer, lmtest, sandwich, car, plotly, extrafont,
  rmdformats, showtext, readxl, purrr, broom, lubridate, tibble, spuRs,
  knitr, kableExtra, writexl, htmlwidgets







------------------------------------------------------------
Arquivos de entrada
------------------------------------------------------------
- /input/T2dados.xlsx → base para o estudo de repasse cambial (Questão 2)

------------------------------------------------------------
Saídas geradas (pasta ../output/)
------------------------------------------------------------
Questão 1 – tabelas (Excel):
- **Tabela 1.1:** ../output/Tabela_1.1.xlsx → estatísticas descritivas
- **Tabela 1.4:** ../output/Tabela_1.4.xlsx → regressão OLS (log_wage_homo)
- **Tabela 1.5:** ../output/Tabela_1.5.xlsx → resultados detalhados da regressão (OLS)
- **Tabela 1.8:** ../output/Tabela_1.8.xlsx → regressão com log_wage_hetero (OLS)
- **Tabela 1.9:** ../output/Tabela_1.9.xlsx → teste de White (log_wage_homo)
- **Tabela 1.10:** ../output/Tabela_1.10.xlsx → teste de White (log_wage_hetero)
- **Tabela 1.11:** ../output/Tabela_1.11.xlsx → regressão por FGLS (log_wage_hetero)
- **Tabela 1.12.1:** ../output/Tabela_1.12.1.xlsx → OLS com N=200.000 (log_wage_hetero)
- **Tabela 1.12.2:** ../output/Tabela1.12.2.xlsx → FGLS com N=200.000 (log_wage_hetero)

Questão 1 – imagens (PNG):
- **Gráfico 1.2.1:** ../output/Imagem_1.2.1.png → salário vs educação (OLS line)
- **Gráfico 1.2.2:** ../output/Imagem_1.2.2.png → log salário vs educação (OLS line)
- **Gráfico 1.3:** ../output/Imagem_1.3.png → log salário vs experiência (OLS line)
- **Gráfico 1.7:** ../output/Imagem_1.7.png → histograma dos resíduos (OLS)
- **Gráfico 1.8.3:** ../output/Imagem_1.8.3.png → histograma dos resíduos (hetero)
- **Gráfico 1.8.4:** ../output/Imagem_1.8.4.png → resíduos vs educação (hetero)
- **Gráfico 1.8.5:** ../output/Imagem_1.8.5.png → resíduos² vs educação (hetero)

Questão 1 – gráficos interativos (HTML):
- **Gráfico 1.6:** ../output/Imagem_1.6.html → 3D predito (log_wage_homo)
- **Gráfico 1.8.2:** ../output/Imagem_1.8.2.html → 3D predito (log_wage_hetero)

Questão 2 – tabelas (Excel):
- **Tabela 2.3:** ../output/Tabela_2.3.xlsx → coeficientes por setor (câmbio, IBC-Br, defasagens)
- **Tabela 2.4:** ../output/Tabela_2.4.xlsx → Ljung–Box por setor (modelo 2.3)
- **Tabela 2.5.1:** ../output/Tabela_2.5.1.xlsx → estimações com dummies sazonais
- **Tabela 2.5.2:** ../output/Tabela_2.5.2.xlsx → ranking de repasse cambial (β_câmbio)
- **Tabela 2.7:** ../output/Tabela_2.7.xlsx → Ljung–Box após dummies sazonais
- **Tabela 2.8.1:** ../output/Tabela_2.8.1.xlsx → modelo com y(t−1) e câmbio(t−1)
- **Tabela 2.8.2:** ../output/Tabela_2.8.2.xlsx → repasse total do câmbio por setor
- **Tabela 2.9:** ../output/Tabela_2.9.xlsx → Ljung–Box + Breusch–Pagan consolidados
- **Tabela 2.10:** ../output/Tabela_2.10.xlsx → resultados com erros HAC (Newey–West)


------------------------------------------------------------
Observações:
------------------------------------------------------------
- **Reprodutibilidade:** seed definida (ex.: set.seed(122121629)).          # DRE DO ARTHUR
- Todo o código esta consolidado em um Arquivo em R markdown. É necessario abrir o projeto(Econometria) previamente e logo em seguida abrir o script(trabalho_econometria), presente na pasta code, dentro do projeto. Isto para que os caminhos para o arquivo de input e os diretórios de output sejam respeitados e funcionem plenamnete.

------------------------------------------------------------
Fim
------------------------------------------------------------
