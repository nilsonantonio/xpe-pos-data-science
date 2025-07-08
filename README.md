# 🔍 Análise do Consumo de Energia Elétrica no Brasil

Projeto desenvolvido como parte do desafio do Bootcamp de Ciência de Dados da XP Educação, etapa final antes do projeto aplicado da pós-graduação.

Este repositório contém o notebook, relatório e dados utilizados na análise do consumo de energia elétrica no Brasil entre os anos de 2004 e 2023, com recortes por estado, região e tipo de consumo (residencial, industrial, comercial etc).

---

## 🎯 Objetivos

- Realizar uma análise descritiva e temporal do consumo de energia elétrica no Brasil.
- Identificar padrões regionais e setoriais de consumo.
- Explorar a sazonalidade e tendências ao longo dos anos.
- Criar modelos preditivos para estimar o consumo futuro.
- Classificar os estados brasileiros com base em perfis de consumo.

---

## 🛠️ Técnicas e Ferramentas Utilizadas

- **Linguagem:** Python  
- **Bibliotecas:** pandas, matplotlib, seaborn, scikit-learn, statsmodels  
- **Análises:** estatísticas descritivas, visualizações, decomposição de séries temporais, regressão linear, Random Forest Regressor, Box-Cox transformation  
- **Clustering:** KMeans com definição de k pelo método do cotovelo

---

## 📈 Principais Descobertas

- O consumo **residencial** apresenta forte **sazonalidade**.
- O consumo **industrial** tem crescido nas regiões **Nordeste** e **Centro-Oeste**.
- As regiões **Sudeste e Sul** concentram os maiores volumes de consumo energético.
- Há correlação entre tipos de consumo em estados com características econômicas semelhantes.
- Modelos como **Random Forest** se mostraram mais eficazes na previsão em cenários não-lineares.

---

## 📊 Visualizações

O projeto inclui gráficos e análises como:

- Séries temporais por região e tipo de consumo.
- Boxplots para identificar outliers e distribuições.
- Mapas de calor de correlação entre tipos de consumo.
- Gráficos de dispersão e análise de clusters.

---

## 💡 Aprendizados

- Aplicação prática do ciclo completo de análise de dados: ingestão, limpeza, transformação, modelagem e comunicação dos resultados.
- Integração entre engenharia de software e ciência de dados para entregar soluções analíticas com clareza e reprodutibilidade.
- Importância da experimentação com múltiplos modelos e transformações para alcançar previsões robustas.

---

## 📁 Estrutura do Repositório

```
📦 xpe-pos-data-science
 ┣ 📦 arquivos
   ┣ 📊 consumo_energia_eletrica.csv
   ┣ 🌍 estado_regiao.csv
 ┣ 📓 desafio_final_nilson.ipynb
 ┣ 📄 Relatorio_Desafio_Final.pdf
 ┗ 📘 README.md
```

---

## 🔗 Acesse também

📌 [Relatório completo em PDF](./Relatorio_Desafio_Final.pdf)  
📌 [Notebook com todas as análises](./desafio_final_nilson.ipynb)

---

## 🤝 Conecte-se comigo

Caso esse tipo de abordagem — que integra engenharia de software com análise de dados aplicada — dialogue com os desafios que você ou sua equipe enfrentam, será um prazer trocar ideias, compartilhar experiências e construir novas conexões profissionais.  
📫 [LinkedIn](https://www.linkedin.com/in/nilson-antonio-b63b3428)

---

## ⚙️ Montando ambiente de execução

Para reproduzir a análise localmente, recomenda-se a criação de um ambiente virtual Python:

```bash
python -m venv venv
source venv/bin/activate  # ou .\venv\Scripts\activate no Windows
pip install -r requirements.txt
```