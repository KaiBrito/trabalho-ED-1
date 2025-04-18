# 📖 Dicionário de Sinônimos — Estrutura de Dados

## 📚 Disciplina
**Estrutura de Dados e Programação I**

## 📌 Descrição do Projeto
Este trabalho consiste em implementar um **dicionário de sinônimos** no idioma português, utilizando uma **tabela de dispersão (hash table)** como estrutura de dados principal.

O objetivo é permitir a organização e manipulação de palavras e seus respectivos sinônimos, de forma eficiente. O programa é **persistente**, ou seja, os dados inseridos são salvos em arquivo e podem ser recuperados em execuções futuras.

## 🧠 Funcionalidades

O sistema suporta os seguintes comandos:

- `insere <palavra> <sinônimo>`  
  Adiciona um novo sinônimo à palavra.  
  **Exemplo:** `insere carro automóvel`

- `busca <palavra>`  
  Exibe todos os sinônimos associados à palavra.  
  **Exemplo:** `busca carro`

- `remove <palavra>`  
  Remove a palavra e todos os seus sinônimos do dicionário.  
  **Exemplo:** `remove carro`

- `remove <palavra> <sinônimo>`  
  Remove apenas o sinônimo especificado da palavra.  
  **Exemplo:** `remove carro automóvel`

- `fim`  
  Encerra a execução do programa e salva os dados.  
  **Exemplo:** `fim`

## 🧰 Estrutura de Dados Utilizada

- **Tabela de Dispersão (Hash Table)**  
  Utilizada para armazenar eficientemente as palavras e seus sinônimos, garantindo buscas, inserções e remoções rápidas.

## 💾 Persistência

Os dados são armazenados em um arquivo .csv ao final da execução e são automaticamente carregados quando o programa é iniciado novamente, garantindo a continuidade das informações.
