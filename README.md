# Infraestrutura de Software - Exemplos Práticos

Este repositório contém exemplos de código e projetos desenvolvidos para a cadeira de Infraestrutura de Software. O objetivo destes exemplos é ilustrar conceitos fundamentais da construção e operação de sistemas de software em um nível de sistema operacional, incluindo gerenciamento de processos, threads, sincronização e comunicação entre processos.

## Sobre a Cadeira

A cadeira de Infraestrutura de Software aborda temas centrais no estudo de sistemas operacionais e infraestruturas de software essenciais para a operação de sistemas computacionais. Os tópicos incluem, mas não estão limitados a:

- Gerenciamento de memória
- Sistemas de arquivos
- Threads e concorrência
- Sincronização e comunicação entre processos
- Virtualização e gerenciamento de recursos

## Projetos

### Problema do Produtor/Consumidor

Um dos projetos desenvolvidos foi uma implementação do problema clássico do produtor/consumidor, que é um excelente exemplo para entender a sincronização entre threads em um ambiente de sistema operacional. Duas versões deste problema foram implementadas:

1. **Usando Semáforos:** Esta versão utiliza semáforos para controlar o acesso a um buffer compartilhado entre produtor e consumidor.
2. **Usando Variáveis de Condição:** Esta versão faz uso de mutexes e variáveis de condição para oferecer uma sincronização efetiva entre as threads envolvidas.

### Problema dos Leitores/Escritores

Este problema explora os desafios da sincronização entre múltiplos leitores e escritores acessando o mesmo recurso. Foram desenvolvidas duas abordagens com priorização para os escritores:

1. **Usando Semáforos:** Implementação que prioriza escritores usando semáforos POSIX.
2. **Usando RWLocks:** Implementação que prioriza escritores utilizando RWLocks (locks de leitura e escrita) POSIX para controlar o acesso.

## Ferramentas e Tecnologias

- **Linguagem de Programação:** C
- **Ambiente de Desenvolvimento:** VSCode com extensões para C/C++
