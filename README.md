# 📊 Análise Estratégica de Vendas - Alura Store

## 📝 Descrição do Projeto
Este projeto consiste na análise de dados operacionais e financeiros de quatro filiais fictícias da rede de lojas **Alura Store**. O objetivo principal da análise é gerar *insights* baseados em dados para auxiliar o dono da rede, Senhor João, a tomar uma decisão estratégica: **qual das 4 lojas deve ser vendida para financiar um novo empreendimento?**

A análise foi conduzida avaliando métricas-chave de desempenho (KPIs), comparando pontos fortes e fracos de cada unidade para chegar a uma recomendação embasada.

## 🎯 Objetivos Específicos
- Carregar e manipular dados de vendas a partir de arquivos CSV.
- Consolidar as informações de 4 lojas em um único conjunto de dados.
- Analisar faturamento total, frete médio e avaliação média dos clientes por loja.
- Identificar as categorias de produtos mais e menos vendidas.
- Identificar os produtos de maior e menor sucesso em cada unidade.
- Criar visualizações gráficas para facilitar a interpretação dos resultados.

## 🛠️ Tecnologias Utilizadas
A análise foi desenvolvida no **Google Colab**, utilizando a linguagem **Python** e as seguintes bibliotecas:
- **`pandas`**: Manipulação, limpeza e agregação dos dados.
- **`matplotlib`**: Criação de gráficos estáticos (Rosca, Barras Empilhadas).
- **`seaborn`**: Criação de gráficos estatísticos (Boxplot) com visual aprimorado.

## 📈 Principais Descobertas
Durante a análise exploratória, identificamos dois cenários distintos:

1. **Lojas de Alto Desempenho (Lojas 2 e 3):** Apresentaram operações saudáveis, com altos faturamentos e as melhores médias de avaliação pelos clientes.
2. **Lojas em Risco (Lojas 1 e 4):** - A **Loja 1** possui o maior faturamento da rede (R$ 1.534.509,12), mas sofre com ineficiência logística (frete mais caro) e a pior avaliação dos clientes.
   - A **Loja 4** possui o menor faturamento da rede (R$ 1.384.497,58), apesar de ter o frete mais barato.

## 💡 Conclusão e Recomendação
Após cruzar todos os dados, a recomendação final para o Senhor João é **vender a Loja 4**. 

**Justificativa:** O faturamento da Loja 4 destoa negativamente de todas as outras filiais. Embora a Loja 1 tenha problemas de satisfação do cliente e custos de frete altos, ela é a principal geradora de caixa da empresa (impulsionada pelas vendas de eletrodomésticos). Vender a Loja 4 representa o menor impacto financeiro para a receita global da rede Alura Store.

## 🚀 Como executar este projeto
1. Clone este repositório:
   ```bash
   git clone [https://github.com/Enrico3115/analise-vendas-alura-store.git](https://github.com/Enrico3115/analise-vendas-alura-store.git)
