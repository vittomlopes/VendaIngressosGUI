# VendaIngressosGUI


# 🎫 VendaIngressosGUI

Projeto da disciplina **Sistemas Operacionais (2025.1)** com o Prof. Fernando Parente Garcia.

Simulação da venda de ingressos para um jogo de futebol, utilizando **threads**, **semáforos** e **interface gráfica com Java Swing**.

---

## 🧠 Objetivo

Simular várias pessoas (threads) tentando comprar ingressos limitados. Quando os ingressos acabam, nenhuma outra pessoa consegue comprar.

---

## 🛠️ Tecnologias usadas

- Java 17+
- Swing (interface gráfica)
- Semáforo (`java.util.concurrent.Semaphore`)
- VSCode

---

## 🧩 Funcionamento

- O usuário define:
  - Quantidade de ingressos
  - Tempo (em segundos) que leva para comprar
- Pode criar novos compradores a qualquer momento (botão)
- Cada comprador tenta comprar 1 ingresso:
  - Se conseguir, aparece "✅ ingresso comprado"
  - Se não conseguir, aparece "❌ ingressos esgotados"
- Log mostra todos os eventos em tempo real

---

## 🖥️ Como executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/SEU_USUARIO/VendaIngressosGUI.git
