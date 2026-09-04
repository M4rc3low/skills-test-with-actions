# Python Tests with GitHub Actions

![Python](https://img.shields.io/badge/Python-testing-3776AB?logo=python&logoColor=white)
![Pytest](https://img.shields.io/badge/pytest-automated_tests-0A9EDC?logo=pytest&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-CI-2088FF?logo=githubactions&logoColor=white)
![License](https://img.shields.io/badge/license-MIT-green)

Laboratório prático de **testes automatizados em Python e integração contínua**, criado a partir do GitHub Skills.

## Objetivo

Praticar a relação entre código, testes e pipelines: alterar uma função, executar testes automaticamente e usar o resultado do workflow como critério de qualidade antes de integrar mudanças.

## O que existe no projeto

- Funções Python para cálculo de área de círculo e sequência de Fibonacci
- Testes automatizados com `pytest`
- Configuração de cobertura em `.coveragerc`
- Exemplos de workflows para pacote Python e cobertura
- Workflows didáticos do GitHub Skills
- Dev Container para ambiente reproduzível de estudo

## Estrutura

```text
.
├── src/
│   └── calculations.py
├── tests/
│   └── calculations_test.py
├── .github/workflows/
├── .coveragerc
├── requirements.txt
└── README.md
```

## Executar localmente

Crie e ative um ambiente virtual:

```bash
python -m venv .venv
```

No Linux/macOS:

```bash
source .venv/bin/activate
```

No Windows PowerShell:

```powershell
.venv\Scripts\Activate.ps1
```

Instale as dependências e execute os testes:

```bash
pip install -r requirements.txt
pytest -v
```

Cobertura:

```bash
pytest --cov=src --cov-report=term-missing
```

## Conceitos praticados

- Arrange, Act, Assert
- Testes unitários com `pytest`
- Validação automática em CI
- Matriz de versões do Python
- Cobertura de testes
- Separação entre `src/` e `tests/`
- Workflows em YAML

## Observação

Os workflows numerados do GitHub Skills e os arquivos `.example` foram mantidos como parte do histórico didático. Além deles, o repositório possui uma pipeline de CI própria para validar os testes em pushes e pull requests.

## Autor

Laboratório realizado por Marcelo Gomes.
