# To-Do List em Python

![Python Version](https://img.shields.io/badge/Python-3-blue?logo=python&logoColor=white)
![Status](https://img.shields.io/badge/Status-Concluído-brightgreen)
![License](https://img.shields.io/badge/License-MIT-lightgrey)

Esse é um projeto prático e eficiente de gerenciamento de tarefas (To-Do List) via terminal, desenvolvido em Python. Ele permite a organização das suas atividades diárias e oferece um menu interativo com as seguintes funcionalidades:
- Adicionar novas tarefas
- Listar tarefas cadastradas
- Remover tarefas concluídas ou indesejadas
- Salvar dados automaticamente em um arquivo de texto

### Detalhamento do Código

O código foi estruturado utilizando os seguintes comandos e conceitos fundamentais em Python:

* **Manipulação de Arquivos (`open`, `read`, `write`, `close`):** Utilizados para criar, ler e atualizar o arquivo de texto onde as tarefas são salvas, garantindo a persistência dos dados mesmo após fechar o programa.
* **Listas (`list` e `.append()`):** Estrutura de dados principal utilizada para armazenar as tarefas na memória de forma dinâmica durante a execução do programa.
* **`def`:** Utilizado para criar funções personalizadas e reaproveitáveis, como `adicionar_tarefa()`, `listar_tarefas()` e `salvar_arquivo()`.
* **`while True`:** Estrutura de repetição que cria um loop infinito, mantendo o menu principal ativo até que o usuário decida sair.
* **`print()` e `input()`:** Comandos de entrada e saída de dados. O `input()` captura as escolhas e os nomes das tarefas digitadas pelo usuário, enquanto o `print()` exibe a lista e as mensagens de confirmação na tela.
* **`if`, `elif` e `break`:** Estruturas condicionais que direcionam o programa com base na escolha do menu, além do comando `break` para interromper o loop e encerrar a aplicação.

## Pré-requisitos

Certifique-se de ter o **Python 3** instalado em sua máquina. Você pode verificar a versão instalada executando o seguinte comando no seu terminal:

```
  python --version
```
