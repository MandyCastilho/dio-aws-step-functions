# 🚀 Desafio DIO - AWS Step Functions

Documentação do desafio prático da DIO sobre **AWS Step Functions**.

---

## 🎯 Objetivo
Aplicar Step Functions em um workflow real e documentar o aprendizado.

---

## 🛠 Tecnologias
- AWS Step Functions  
- AWS Lambda  
- Git/GitHub

---

## 🔹 Passo a Passo
1. Criar a *State Machine* no console AWS.  
2. Definir fluxo em **JSON (Amazon States Language)**.  
3. Integrar com funções Lambda.  
4. Executar e monitorar o workflow.

Exemplo:

```json
{
  "StartAt": "TarefaInicial",
  "States": {
    "TarefaInicial": {
      "Type": "Pass",
      "Result": "Fluxo iniciado!",
      "End": true
    }
  }
}

