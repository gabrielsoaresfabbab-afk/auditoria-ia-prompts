# IA Generativa na Auditoria de Gastos Legislativos 🛡️💼

Este projeto foi desenvolvido como parte de um desafio da [DIO](https://dio.me), com o objetivo de explorar o uso de Inteligências Artificiais Generativas para criar soluções práticas e realistas no dia a dia.

Como auditor do Poder Legislativo, decidi aplicar essa tecnologia para otimizar a fiscalização do uso de recursos públicos, focando na identificação de possíveis irregularidades em verbas parlamentares e contratação de assessores.

---

## 🎯 Objetivo do Projeto

Demonstrar como prompts bem estruturados em ferramentas de IA (como ChatGPT, Gemini ou Claude) podem atuar como assistentes de auditoria, acelerando a identificação de "sinais de alerta" (*red flags*) em prestações de contas de deputados e vereadores.

---

## 🛠️ Prompts Desenvolvidos

### 1. Auditoria de Verba Parlamentar (Transporte e Publicidade)
Este prompt instrui a IA a atuar como um auditor especialista e analisar uma lista de reembolsos em busca de padrões de gastos suspeitos.

**Prompt:**
> Aja como um auditor sênior do Poder Legislativo especialista em identificar fraudes e desvios de recursos. Sua tarefa é analisar a lista de reembolsos de verba parlamentar fornecida e listar possíveis "sinais de alerta" (red flags). Preste atenção em: concentração de gastos em finais de semana/recessos, pagamentos repetidos para a mesma empresa, e valores redondos atípicos. Apresente os resultados em formato de tabela (Item, Valor, Alerta, Recomendação de Diligência).

---

## 📊 Exemplo Prático (Simulação)

### Entrada de Dados Fictícios na IA:
*   **05/Jan:** R$ 12.000,00 – Empresa "Silva Comunicação Ltda" (Divulgação parlamentar).
*   **12/Jan (Domingo):** R$ 450,00 – Posto de Combustível BR (Abastecimento).
*   **18/Jan (Sábado):** R$ 600,00 – Posto de Combustível BR (Abastecimento).
*   **20/Jan:** R$ 12.000,00 – Empresa "Silva Comunicação Ltda" (Divulgação parlamentar).
*   **25/Jan (Sábado):** R$ 380,00 – Posto de Combustível BR (Abastecimento).

### Saída Gerada pela IA:
| Item Analisado | Valor | Sinal de Alerta Identificado | Recomendação de Diligência (Ação do Auditor) |
| :--- | :--- | :--- | :--- |
| **Silva Comunicação Ltda** | R$ 24.000,00 | Dois pagamentos idênticos e redondos no mesmo mês durante o recesso. | Verificar o contrato de prestação de serviços e a existência física da empresa. |
| **Posto de Combustível BR** | R$ 1.430,00 | Abastecimentos frequentes aos finais de semana de recesso legislativo. | Confrontar placas com a frota oficial e solicitar agenda que justifique o trânsito. |

---

## 🚀 Como Executar
1. Copie o prompt da seção **Prompts Desenvolvidos**.
2. Cole na sua ferramenta de IA preferida (ChatGPT, Gemini, Claude).
3. Insira os dados de reembolso que deseja analisar e veja o resultado.
