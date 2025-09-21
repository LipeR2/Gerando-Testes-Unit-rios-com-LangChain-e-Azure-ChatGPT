# **_BaresDev: Machine Learning Training_** - DIO

## Desafio de Projeto: Gerando Testes Unitários com LangChain e Azure ChatGPT

### 🧑🏻‍💻 Projeto de Criação de um Agente para Gerar Testes Unitários com LangChain e Azure ChatGPT
O projeto consiste em criar um agente para gerar testes unitários em Python no ambiente de desenvolvimento integrado VSCode, uma IDE (Integrated Development Environments).

O LangChain é uma framework para desenvolvimento de aplicativos baseados em grandes modelos de linguagem (LLM's). Ele simplifica cada etapa do ciclo de vida do processo no modelo.

O Azure chatGPT é uma IA (Inteligência Artificial) em nuvem da Microsft.

### 💻 Tecnologias
Esse projeto foi desenvolvido com as tecnologias:

- VSCode; (Ambiente de Desenvolvimento Integrado)
- Python. (Com seus Frameworks e suas Bibliotecas. Como exemplo: KERAS, TensorFlow, Pytorch)

### 🗂️ Descrição do Projeto:
Colocar em prática os conceitos vistos na aula construindo um agente de IA que, a partir de um código Python, gera automaticamente testes unitários com a biblioteca pytest.

Sugestão de Entrega 
Um repositório público no GitHub contendo:

1. Código do agente

Implementação em Python usando LangChain + Azure OpenAI.

O agente deve receber um trecho/arquivo Python como entrada.

Ele deve retornar um arquivo de testes (test_<nome>.py) em formato puro de Python, contendo:

import pytest na primeira linha,

funções def test_* para casos de sucesso e falha.

2. Exemplos de uso

Pelo menos duas funções simples criadas por você (ex.: soma, subtração, divisão).

O agente deve gerar os testes correspondentes a essas funções.

Os testes devem rodar corretamente com o comando: pytest

3. README.md com:

Descrição do projeto,

Passo a passo de como rodar o agente,

Instruções de configuração das variáveis de ambiente (.env.example com as chaves do Azure OpenAI).

⚠️ Atenção: Este desafio é flexível! Você pode optar por implementar o agente completo com LangChain + Azure ChatGPT ou documentar em detalhes o que aprendeu sobre os conceitos apresentados, criando um repositório que registre seus estudos, reflexões e exemplos de código. O mais importante é demonstrar seu entendimento e compartilhar sua jornada de aprendizado no GitHub.
