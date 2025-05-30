# Sistema de Recomendação

## Pré-requisitos

Antes de começar, garanta que você tenha os seguintes softwares instalados em sua máquina:

* **Python** (versão 3.12.0)
    * Você pode verificar sua versão com: `python --version` ou `python3 --version`
    * Recomendamos o uso de [pyenv](https://github.com/pyenv/pyenv) ou [asdf](https://asdf-vm.com/) para gerenciar múltiplas versões do Python.
* **Git**
    * Você pode verificar sua instalação com: `git --version`

## ⚙️ Configuração do Ambiente (Setup)

Siga estes passos para configurar o ambiente de desenvolvimento local:

1.  **Clone o Repositório:**
    Abra seu terminal e clone este repositório para sua máquina local:
    ```bash
    git clone git@github.com:guilhermediniz1/recommendation.git
    ```
    Substitua `<URL_DO_SEU_REPOSITORIO_GIT_AQUI>` pela URL correta do repositório (ex: `https://github.com/seu-usuario/nome-do-seu-projeto-incrivel.git`).

2.  **Navegue até a Pasta do Projeto:**
    ```bash
    cd recommendation
    ```

3.  **Crie o Ambiente Virtual (venv):**
    Recomendamos nomear o ambiente virtual como `venv`. Este comando cria uma pasta `venv` dentro do diretório do projeto, que conterá as dependências específicas deste projeto.
    ```bash
    python -m venv venv
    ```
    *Nota: Se você usa `python3` como comando principal, substitua `python` por `python3`.*

4.  **Ative o Ambiente Virtual:**
    A ativação do ambiente virtual isola as dependências do seu projeto.

    * **No Windows (Git Bash ou PowerShell):**
        ```bash
        source venv/Scripts/activate
        ```
        *Se estiver usando o Prompt de Comando (CMD):*
        ```bash
        venv\Scripts\activate
        ```

    * **No macOS e Linux:**
        ```bash
        source venv/bin/activate
        ```
    Após a ativação, você deverá ver `(venv)` no início do seu prompt de comando.

5.  **Instale as Dependências:**
    Com o ambiente virtual ativo, instale todas as bibliotecas Python necessárias listadas no arquivo `requirements.txt`:
    ```bash
    pip install -r requirements.txt
    ```
    *Dica: Se você tiver problemas com a versão do pip, pode tentar atualizá-lo dentro do venv com `pip install --upgrade pip`.*

Pronto! Seu ambiente de desenvolvimento está configurado.

## 🚀 Executando o JupyterLab

Com o ambiente virtual ainda ativo (`(venv)` visível no seu terminal), inicie o JupyterLab:

```bash
jupyter lab
