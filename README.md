# Sistema de Busca Avançada com RAG e Qdrant

<p align="center">
  <img src="https://img.shields.io/badge/license-MIT-blue.svg" alt="License">
  <img src="https://img.shields.io/badge/python-3.9%2B-blue.svg" alt="Python Version">
  </p>

<h3 align="center">Sistema de Busca com RAG e Bancos Vetoriais</h3>

<p align="center">
  Sistema de busca inteligente que utiliza a arquitetura RAG e bancos de dados vetoriais para fornecer respostas precisas e contextuais a partir de uma base de conhecimento customizada. No meu caso, utilizei 3 pdfs sobre o assunto de Física do Ensino Médio.
  <br />
  <a href="#sobre-o-projeto"><strong>Explore a documentação »</strong></a>
  <br />
  <br />

## 📝 Índice

* [Sobre o Projeto](#sobre-o-projeto)
  * [Tecnologias Utilizadas](#tecnologias-utilizadas)
* [Começando](#começando)
  * [Pré-requisitos](#pré-requisitos)
  * [Instalação](#instalação)
* [Como Usar](#como-usar)
* [Estrutura do Projeto](#estrutura-do-projeto)
* [Resultados e Demonstração](#resultados-e-demonstração)
* [Roadmap](#roadmap)
* [Contribuição](#contribuição)
* [Licença](#licença)
* [Contato](#contato)
* [Agradecimentos](#agradecimentos)

## 🌟 Sobre o Projeto

Este projeto implementa um sistema de busca avançado que vai além das buscas tradicionais por palavras-chave. Utilizando a técnica de **Retrieval Augmented Generation (RAG)**, o sistema combina a capacidade de recuperação de informações relevantes de uma base de dados vetorial com o poder de geração de linguagem natural de Modelos de Linguagem Grandes (LLMs).

**Principais Funcionalidades:**
* Busca semântica em documentos ou bases de conhecimento.
* Geração de respostas contextuais e diretas em vez de apenas listar documentos.
* Capacidade de ingerir e indexar novos documentos para manter a base de conhecimento atualizada.

### 🛠️ Tecnologias Utilizadas

Liste as principais tecnologias, frameworks e bibliotecas que você usou.
* [Python](https://www.python.org/) (linguagem principal)
* [Langchain](https://python.langchain.com/) / [LlamaIndex](https://www.llamaindex.ai/) (framework para aplicações com LLMs, RAG)
* [Qdrant]
* [gemini]
* [Gradio](https://www.gradio.app/)
* [Outras bibliotecas importantes - ex: Transformers, Sentence-Transformers, Pandas]

## 🚀 Começando

Siga estas instruções para obter uma cópia do projeto em funcionamento na sua máquina local para desenvolvimento e testes.

### ✅ Pré-requisitos

* Python 3.9 ou superior
* Git
* (Opcional) Um gerenciador de ambientes como `venv` ou `conda`.

Exemplo de instalação de pré-requisitos (se necessário):
```bash
# Exemplo para instalar Python (pode variar dependendo do SO)
sudo apt-get install python3.9 python3.9-venv
