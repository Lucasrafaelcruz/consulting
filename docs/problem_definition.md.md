\# Definição do Problema — Churn de Clientes



**## 1. Contexto de Negócio**



**Existe um problema de churn que gera perda de receita**



IBM Sample Data Sets - https://www.kaggle.com/datasets/blastchar/telco-customer-churn



Através deste dataset, irei predizer o comportamentos que retem clientes, analisar todos os dados e entender o que é relevante.



Estes conjuntos de dados, servem para estudo e aplicações de conceitos estudados de algoritimos de classificação.





***## 2. Problema a Ser Resolvido***



Precisamos entender quais são as informações mais relevantes para cliente que dão churn (clientes que cancelam o uso do produto em um determinado período).



O problema é recorrente quando não aproveitamos nossa lucratividade operacional devido a falta de uma estratégia especifica para cada cliente.



Com isso Identificar clientes com alto risco de churn antes do cancelamento.



Ao conseguir prever clientes que podem ter potenciais cancelamentos, iremos aplicar estratégias de retenção, como remarketing e promoções.







\## 3. Objetivo da Análise



Ordenar cliente por risco de churn através de dados históricos os clientes



Apoiar a decisão operacional potencializar sua lucratividade, ajeitando a estratégia para cada cliente.





\## 4. Decisão de Negócio Associada ao Modelo



O modelo será utilizado para priorizar clientes com maior risco de churn, permitindo que a empresa aloque recursos de retenção apenas para clientes com maior chance de cancelamento, otimização o uso de recursos do time comercial e operacional.





\## 5. O que é considerado um erro?



Falso Positivo: Usamos uma estratégia agressiva, diminuindo nosso ROI, quando o cliente nao for potencial churn.



Falso Negativo: Manter a Estratégia para clientes que vão dar churn.





\## 6. Métrica de Sucesso



Maximizar recall da classe churn com isso podemos potencializar a lucratividade operacional de nossos contratos.





\## 7. Restrições e Premissas



Este estudo assume que os dados históricos disponíveis representam de forma adequada o comportamento dos clientes no período analisado e que os padrões observados permanecem relativamente estáveis no curto prazo.



O modelo será construído a partir de dados estáticos, não considerando mudanças comportamentais em tempo real, eventos externos ou ações de retenção recentes que não estejam registradas no conjunto de dados.



Ressalta-se que a qualidade, consistência e representatividade dos dados impactam diretamente a capacidade do modelo em generalizar seus resultados, sendo possível que fatores relevantes para o churn não estejam plenamente capturados nas variáveis disponíveis.







\## 8. Resultado Esperado



O modelo vai nos trazer, uma interpretação de churn do cliente e dar suporte a decisão da melhor estratégia operacional e comercial.





