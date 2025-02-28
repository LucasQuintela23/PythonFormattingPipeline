# PythonFormattingPipeline

![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)
![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![GitHub Actions](https://img.shields.io/github/actions/workflow/status/LucasQuintela23/PythonFormattingPipeline/ci.yml)

## 📖 Descrição

**PythonFormattingPipeline** é um pipeline automatizado para formatação e padronização de código Python. Ele integra ferramentas populares para garantir um código limpo, consistente e bem estruturado.

## 🚀 Funcionalidades

- 🛠 **Formatação automática** com `black`
- 📏 **Organização de imports** com `isort`
- 🔍 **Linting** para detecção de problemas com `flake8`
- 📝 **Análise estática** com `mypy`
- ✅ **Execução automatizada** via GitHub Actions

## 📦 Tecnologias Utilizadas

- [Python](https://www.python.org/) (3.8+)
- [Black](https://github.com/psf/black) - Formatação de código
- [Isort](https://pycqa.github.io/isort/) - Organização de imports
- [Flake8](https://flake8.pycqa.org/en/latest/) - Linter de código
- [Mypy](https://mypy-lang.org/) - Verificação de tipos
- [GitHub Actions](https://docs.github.com/en/actions) - Automação do pipeline

## 🔧 Instalação

Para utilizar este projeto localmente, siga os passos abaixo:

### 1️⃣ Clone o repositório:

```bash
git clone https://github.com/LucasQuintela23/PythonFormattingPipeline.git
cd PythonFormattingPipeline
```

### 2️⃣  Crie um ambiente virtual (opcional, mas recomendado):

```bash
python -m venv venv
source venv/bin/activate  # No Windows, use 'venv\Scripts\activate'
```

### 3️⃣  Instale as dependências:
```bash
pip install -r requirements.txt
```