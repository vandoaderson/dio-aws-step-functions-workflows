dio-aws-step-functions-workflows/
│
├── README.md
├── images/
│   ├── step-functions-console.png
│   ├── workflow-execution.png
│   └── state-machine-definition.png
│
└── docs/
    └── anotacoes.md

# Desafio DIO - AWS Step Functions

## Descrição

Este repositório foi desenvolvido como parte do laboratório da DIO com foco em **AWS Step Functions**. O objetivo do desafio foi compreender como criar e orquestrar fluxos de trabalho automatizados utilizando máquinas de estado na AWS.

---

## Objetivos de Aprendizagem

* Aplicar os conceitos aprendidos durante as aulas em um ambiente prático;
* Entender o funcionamento das AWS Step Functions;
* Documentar processos técnicos de forma clara e estruturada;
* Utilizar o GitHub como ferramenta de compartilhamento de conhecimento técnico.

---

## O que são AWS Step Functions?

AWS Step Functions é um serviço totalmente gerenciado que permite coordenar múltiplos serviços da AWS por meio de **workflows visuais**, utilizando o conceito de **State Machines**.

Com ele, é possível:

* Orquestrar funções AWS Lambda;
* Integrar diversos serviços da AWS;
* Implementar fluxos de aprovação;
* Automatizar processos complexos;
* Tratar falhas e realizar retentativas automaticamente.

---

## Conceitos Aprendidos

### State Machine

Representa o fluxo completo da aplicação.

### States

São as etapas que compõem o workflow.

Tipos comuns:

* Task
* Choice
* Wait
* Pass
* Succeed
* Fail
* Parallel
* Map

### Amazon States Language (ASL)

Linguagem baseada em JSON utilizada para definir o comportamento das máquinas de estado.

---

## Fluxo desenvolvido durante o laboratório

1. Criação da máquina de estados;
2. Definição das etapas do processo;
3. Configuração das integrações necessárias;
4. Execução do workflow;
5. Análise do histórico de execução;
6. Validação dos resultados.

---

## Insights Obtidos

* Step Functions simplifica significativamente a orquestração de processos distribuídos;
* O monitoramento visual facilita a identificação de falhas;
* O tratamento de erros pode ser implementado diretamente no fluxo;
* A reutilização de componentes torna as soluções mais organizadas e escaláveis.

---

## Evidências

As capturas de tela utilizadas durante a execução do laboratório estão disponíveis na pasta `images`.

---

## Tecnologias Utilizadas

* AWS Step Functions
* AWS Management Console
* Git
* GitHub
* Markdown

---

## Conclusão

Este laboratório proporcionou uma visão prática sobre automação de workflows na AWS, demonstrando como as Step Functions podem ser utilizadas para construir soluções mais robustas, escaláveis e de fácil manutenção.

---

## Referências

* Documentação oficial da AWS Step Functions
* Materiais disponibilizados pela DIO durante o curso
* Documentação oficial do GitHub
