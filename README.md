# DIO-AWS-Step-Functions
# Amazon Step Functions - Visão Geral

## O que é
O Amazon Step Functions é um serviço serverless de orquestração que permite automatizar e coordenar fluxos de trabalho entre múltiplos serviços AWS.

## Por que usar
- Coordena vários serviços em um fluxo único.
- Facilita a modelagem visual do processo.
- Ajuda no tratamento de erros com retries automáticos.
- Torna o sistema mais resiliente e organizado.
- Permite separar lógica de negócio da execução bruta.

## Conceitos principais
- State Machine: a máquina de estados que representa o fluxo.
- State (Estado): cada etapa do processo.
- Transitions: como um estado leva ao próximo.
- Tasks: etapas que executam ações, ex: chamar uma Lambda.
- Serverless: você não gerencia infraestrutura.

## Exemplos de uso comuns
- Orquestrar Lambdas.
- Aguardar processos assíncronos (SQS, EventBridge, Step Functions Callback).
- Workflows longos (ex: processos de dias).
- Processar dados em etapas.

## Modelo mental simples
Em vez de colocar toda a lógica dentro de uma Lambda, eu coloco a lógica de orquestração no Step Functions e deixo cada Lambda responsável apenas por uma tarefa específica.


