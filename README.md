# [PYTHON Assistence Coder]

![Python](https://img.shields.io/badge/Python-3.13-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![Groq](https://img.shields.io/badge/Groq-00C65E?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMjQgMjQiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyI+PHBhdGggZD0iTTEyIDBDNS4zNzMgMCAwIDUuMzczIDAgMTJzNS4zNzMgMTIgMTIgMTIgMTItNS4zNzMgMTItMTJTMTguNjI3IDAgMTIgMHptMCAyMS42QzYuNzAzIDIxLjYgMi40IDE3LjI5NyAyLjQgMTJTNi43MDMgMi40IDEyIDIuNCAxNy4yOTcgNi43MDMgMjEuNiAxMiAyMS42IDE3LjI5NyAxMiAyMS42ek0xMiA0LjhjLTMuOTcgMC03LjIgMy4yMy03LjIgNy4yIDAgMy45NyAzLjIzIDcuMiA3LjIgNy4yIDMuOTcgMCA3LjItMy4yMyA3LjItNy4yIDAtMy45Ny0zLjIzLTcuMi03LjItNy4yek0xMiAxNi44Yy0yLjY1MiAwLTQuOC0yLjE0OC00LjgtNC44cyAyLjE0OC00LjggNC44LTQuOCA0LjggMi4xNDggNC44IDQuOC0yLjE0OCA0LjgtNC44IDQuOHoiIGZpbGw9IiNmZmYiLz48L3N2Zz4=)

PYTHON AI Coder é um assistente de programação inteligente, construído com Streamlit e alimentado pela API da Groq. Projetado para ajudar desenvolvedores iniciantes, ele responde a perguntas sobre a linguagem Python, fornecendo explicações claras, exemplos de código comentados e links para a documentação oficial.

## ⚙️ Tecnologias Utilizadas

* **Linguagem:** Python 3.13
* **Framework:** Streamlit
* **IA:** API da Groq
* **Gerenciador de Pacotes:** Anaconda/Conda

## 📋 Pré-requisitos

Antes de começar, você precisará ter o seguinte programa instalado e configurado:

-  **Anaconda Distribution**: A aplicação utiliza um ambiente virtual gerenciado pelo Conda. Faça o download e instale a partir do [site oficial da Anaconda](https://www.anaconda.com/download).

Após a instalação do Anaconda, criar uma conta Groq.

-  **Conta na Groq**: É necessário ter uma conta na plataforma Groq para obter uma chave de API.
    * Acesse [groq.com](https://groq.com/) e crie sua conta.
    * No painel de controle (dashboard), vá para a seção de **API Keys** e crie uma nova chave.

> **⚠️ Importante:** Ao criar sua chave de API na Groq, copie e guarde-a em um local seguro. **Ela será exibida apenas uma vez** por motivos de segurança.

## 🚀 Instalação e Execução

Siga os passos abaixo para configurar e rodar a aplicação localmente.

**1. Clone o Repositório**

```bash
git clone [https://github.com/GuilhermeITrama/PythonAssistence.git](https://github.com/GuilhermeITrama/PythonAssistence.git)
cd seu-repositorio
```

**2. Crie e Ative o Ambiente Virtual**

Abra seu terminal (ou Anaconda Prompt) acesse a pasta onde esta os arquivos (normalmente onde esta o seu git clone) e execute os comandos abaixo para criar e ativar o ambiente Conda.

```bash
# Crie o ambiente com Python 3.13
conda create --name gtrama python=3.13

# Ative o ambiente
conda activate gtrama
```

**3. Instale as Dependências**

Com o ambiente ativado, instale as bibliotecas necessárias que estão listadas no arquivo `requirements.txt`.

```bash
# Garanta que o pip está instalado no ambiente
conda install pip

# Instale as dependências do projeto
pip install -r requirements.txt
```

**4. Execute a Aplicação**

Finalmente, execute a aplicação Streamlit com o seguinte comando:

```bash
streamlit run python_assistente.py
```

Seu navegador será aberto automaticamente no endereço local onde a aplicação está sendo executada (geralmente `http://localhost:8501`).

---

## ✒️ Autor

* **[Guilherme Irving Trama]** - [linkedin](https://www.linkedin.com/in/guilhermetrama/)
