# Previsão de Inadimplência com Machine Learning

Este projeto foi desenvolvido com o objetivo de aprofundar conhecimentos em Machine Learning por meio da construção de um modelo de classificação binária para previsão de inadimplência. Utilizando o dataset **Default of Credit Card Clients**, o modelo busca identificar se um cliente entrará em situação de inadimplência no mês seguinte.

Durante o desenvolvimento, foram aplicados conceitos importantes de ciência de dados e aprendizado de máquina, incluindo divisão de dados para treino e teste (train_test_split), otimização de hiperparâmetros com RandomizedSearchCV e avaliação de desempenho por meio de métricas como matriz de confusão, precisão, recall e F1-score. O projeto também serviu como oportunidade para adquirir experiência prática em todo o ciclo de desenvolvimento de modelos de ML.


## Como Executar o Projeto

Siga os passos abaixo para configurar o ambiente virtual e instalar as dependências necessárias.

### 1. Clone o repositório

```
bash
git clone https://github.com/AllanoSantos/projeto_previsao_inadimplencia_ML.git

```

### 2. Crie e ative o ambiente virtual dentro do repositório

Windows

```bash
python -m venv .venv
.\venv\Scripts\activate
```

Linux/macOS

```bash
python3 -m venv venv
source venv/bin/activate
```

### 3. Instale as dependências

Com o ambiente virtual ativado, instale as bibliotecas necessárias utilizando o arquivo `requirements.txt`:

```bash
pip install -r requirements.txt
```

### 4. Execute o projeto

Caso o projeto seja um notebook Jupyter:

```bash
jupyter lab
```

### 5. Abra o notebook

No navegador, abra o arquivo ML-banco.ipynb presente no projeto e execute as células em sequência.