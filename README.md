# Pipeline CI/CD - Hands-On

Projeto educacional para demonstrar práticas de integração contínua e entrega contínua (CI/CD) em Python.

## 📋 Descrição

Este é um projeto simples que implementa uma função de soma e demonstra como configurar um pipeline de CI/CD com testes automatizados e verificação de qualidade de código.

## 🚀 Características

- Função de soma simples
- Testes automatizados com pytest
- Verificação de qualidade de código com flake8
- Estrutura pronta para integração contínua

## 📁 Estrutura do Projeto

```
pipeline-ci-cd/
├── README.md              # Esta documentação
├── app.py                 # Código principal da aplicação
├── requirements.txt       # Dependências do projeto
└── tests/
    └── test_app.py        # Testes unitários
```

## 🔧 Requisitos

- Python 3.7+
- pip

## 📦 Instalação

1. Clone ou navegue até o diretório do projeto:
```bash
cd pipeline-ci-cd
```

2. Instale as dependências:
```bash
pip install -r requirements.txt
```

## 💻 Como Usar

### Executar a função soma

```python
from app import soma

resultado = soma(2, 3)
print(resultado)  # Saída: 5
```

## 🧪 Testes

Execute os testes unitários:

```bash
pytest
```

Para executar testes com mais verbosidade:

```bash
pytest -v
```

## 🔍 Qualidade de Código

Verifique a qualidade do código com flake8:

```bash
flake8 .
```

## 📝 Funções Disponíveis

### `soma(a, b)`

Realiza a soma de dois números.

**Parâmetros:**
- `a` (int/float): Primeiro número
- `b` (int/float): Segundo número

**Retorno:**
- (int/float): Resultado da soma de a + b

**Exemplo:**
```python
>>> soma(2, 3)
5
>>> soma(1.5, 2.5)
4.0
```

## 🔄 Pipeline CI/CD

Este projeto é configurado para ser usado em pipelines de CI/CD. As etapas típicas incluem:

1. **Instalação de dependências** - Instala as bibliotecas necessárias
2. **Execução de testes** - Valida que todas as funções funcionam corretamente
3. **Verificação de qualidade** - Garante conformidade com padrões de código
4. **Deployment** - Disponibiliza a aplicação em produção

## 📚 Recursos Adicionais

- [Documentação do pytest](https://docs.pytest.org/)
- [Documentação do flake8](https://flake8.pycqa.org/)
- [Guia de CI/CD](https://en.wikipedia.org/wiki/CI/CD)

## 📄 Licença

Este é um projeto educacional.

## 👤 Autor

Desenvolvido como parte do programa hands-on.
