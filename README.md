# EBA-Aula 08: ParaCasa

Agora sua missão é continuar trabalhando no nosso dataset house price.

1) Crie uma função usando regressão linear para prever os preços das casas

2) Entenda os coeficientes. Quais variáveis são mais importantes para a previsão?

**Importante:** 
- **Cuidado para não usar a coluna "caro" e "barato" na sua previsão, pois isso é um spoiler para seu modelo!**


ATENÇÃO: O notebook deste repositório não é um gabarito, nele temos apenas a análise descritiva do conjunto de dados!

Neste repositório você irá encontrar:

- Na pasta `data`: Todos `csv's` e `xlsx` utilizados na aula

- Na pasta `notebooks`: Notebook com o código utilizado durante a aula.


## INSTRUÇÕES PARA O USO DESTE REPOSITÓRIO:

### **Como utilizar este repositório?**

Este repositório contém os arquivos e códigos necessários para a aula de Estatística Descritiva. Abaixo estão as instruções simplificadas para configurar o ambiente com Pyenv e Poetry.

- **Passo a Passo para Configuração do Ambiente:**

1. **Clonar o Repositório:**

No terminal, clone este repositório:

```bash
git clone https://github.com/EbaPed/EBA-aula08-ParaCasa.git
cd EBA-aula08-ParaCasa
```

2. **Configurar a versão do Python com Pyenv**

Defina a versão do Python para o projeto. Para esta aula, vamos usar o Python 3.10.11 (ou outra versão compatível):

```bash
pyenv local 3.10.11
```

3. **Ativar o Ambiente Virtual Poetry**

Agora, ative o ambiente virtual:

```bash
poetry shell
```

4. **Instale as dependências do projeto usando Poetry:**

```bash
poetry install
```

Isso criará automaticamente um ambiente virtual isolado.


5. **Configurar o Kernel do Jupyter Notebook**

Se você for usar Jupyter Notebook, instale o ipykernel:

```bash
poetry add ipykernel
python -m ipykernel install --user --name=venv --display-name "Python (venv)
```

No Jupyter Notebook, escolha o kernel "Python (venv)" ao iniciar ou criar um novo notebook.


6. **Desativar o Ambiente Virtual**

Para sair do ambiente virtual, basta usar:

```bash
exit
```

7. **Executar o Código**

Agora que o ambiente está configurado, você pode executar os códigos Python fornecidos no repositório.

### **Comandos úteis**

- Ativar o ambiente virtual Poetry:

```bash
poetry shell
```