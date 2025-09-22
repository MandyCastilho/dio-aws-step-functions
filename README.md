# 🚀 Desafio DIO - AWS Step Functions

Esse repositório é meu registro do desafio prático da DIO sobre **AWS Step Functions**. Aqui organizei tudo que aprendi e como coloquei em prática meus workflows automatizados.

---

## 🎯 Objetivo
Aprender na prática como criar e gerenciar **workflows automáticos** usando Step Functions e documentar todo o processo.

---

## 🛠 Tecnologias usadas
- AWS Step Functions  
- AWS Lambda  
- Git/GitHub

---

## 🔹 Como fiz
1. Criei minha *State Machine* direto no console da AWS.  
2. Estruturei o fluxo em **JSON (Amazon States Language)**.  
3. Integrei o workflow com funções Lambda.  
4. Executei e acompanhei tudo no console para ver o resultado.  

Exemplo de JSON simples que usei:

```json
{
  "StartAt": "TarefaInicial",
  "States": {
    "TarefaInicial": {
      "Type": "Pass",
      "Result": "Workflow iniciado com sucesso!",
      "End": true
    }
  }
}

    }
  }
}

