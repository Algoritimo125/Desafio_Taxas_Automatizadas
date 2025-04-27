# 🚖 Sistema de Cálculo de Corrida de Táxi Automatizado

Este projeto simula um sistema de cálculo de tarifas para corridas de táxi com base na distância percorrida, bandeira tarifária e horário da viagem.

## 🚀 Funcionalidades

- Entrada de dados do usuário:
  - Nome do passageiro.
  - Distância em quilômetros.
  - Bandeira da corrida (1, 2 ou 3).
  - Horário da viagem.
- Cálculo dinâmico do preço da corrida conforme bandeira e horário.
- Exibição do valor final da corrida para o passageiro.

## 📌 Como Utilizar

1. Insira o nome do passageiro.
2. Informe a distância até o destino em quilômetros.
3. Selecione a bandeira tarifária desejada (1, 2 ou 3).
4. Insira o horário da viagem (de 0h a 23h).
5. Clique no botão **CALCULAR CORRIDA**.
6. O sistema calculará e mostrará o valor final.

## 🔢 Regras de Tarifação

### **Preço Base**
- R$ **1,25 por km** percorrido.

### **Multiplicadores de Tarifa por Bandeira e Horário**
| Bandeira | Horário (00:00h - 06:59h) | Horário (07:00h - 12:59h) | Horário (13:00h - 23:59h) |
|----------|----------------|----------------|----------------|
| 1        | 1.05x          | 1.10x          | 1.15x          |
| 2        | 1.10x          | 1.20x          | 1.30x          |
| 3        | 1.05x          | 1.10x          | 1.15x          |

## 💻 Tecnologias Utilizadas

- HTML5
- JavaScript

## 📜 Exemplo de Saída

| Passageiro | Distância (km) | Bandeira | Horário | Valor Final (R$) |
|------------|---------------|----------|--------|------------------|
| João       | 10 km         | 1        | 08h    | R$ 13,75        |
| Maria      | 15 km         | 2        | 14h    | R$ 24,38        |
| Carlos     | 20 km         | 3        | 22h    | R$ 28,75        |