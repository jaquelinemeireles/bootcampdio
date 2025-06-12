# bootcampdio
# 📈 Simulador de Investimentos em Fundos Imobiliários (FII)

Este projeto foi desenvolvido como parte do desafio prático do bootcamp da DIO: **"Criando uma Ferramenta de Controle de Investimentos com Excel"**.  
O objetivo é simular investimentos em FIIs com base em parâmetros como valor inicial, aportes mensais, tempo de investimento e rendimento, ajudando o usuário a tomar decisões mais informadas.

## ✅ Funcionalidades

- Entrada de dados: valor inicial, aporte mensal, tempo (em meses) e rendimento mensal (%);
- Cálculo automático mês a mês do saldo final com base nos aportes e rendimento composto;
- Estimativa dos dividendos mensais embutida no rendimento;
- Gráfico de linha que mostra a evolução do investimento;
- Interface amigável para o usuário final fazer simulações rapidamente.

## 💡 Como usar

1. Abra a planilha `Simulador_FII_Atualizado.xlsx` no Excel ou Google Sheets;
2. Preencha as células:
   - **Valor Inicial Investido (R$)**
   - **Aporte Mensal (R$)**
   - **Tempo (meses)**
   - **Rendimento Mensal (%)**
3. Os resultados serão atualizados automaticamente, com gráfico exibindo a evolução do investimento.

## 📊 Exemplo de Simulação

| Mês | Saldo Inicial | Aporte | Rendimento | Saldo Final |
|-----|----------------|--------|------------|--------------|
| 1   | 10.000,00      | 500    | 80,00      | 10.580,00    |
| 2   | 10.580,00      | 500    | 84,64      | 11.164,64    |
| ... | ...            | ...    | ...        | ...          |
| 24  | ...            | 500    | ...        | ...          |

## 🧠 Aprendizados

- Uso de fórmulas financeiras e condicionais no Excel;
- Automação de cálculos mensais para investimentos;****
