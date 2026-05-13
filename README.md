#  Sales & Inventory Intelligence: Automação e Análise de Dados

Este projeto aplica engenharia de dados para transformar planilhas operacionais em relatórios estratégicos, conectando performance de vendas, hierarquia de cargos e gestão crítica de estoque.

##  Diferenciais Técnicos
- **Data Merging & Cleaning:** Integração de múltiplas fontes de dados (Vendas, Funcionários e Estoque) com tratamento de strings para garantir integridade analítica.
- **Lógica de Suprimentos:** Algoritmo de cálculo de reposição automática baseado em níveis mínimos de segurança e custo médio.
- **Data Visualization Dinâmica:** Gráficos com mapeamento condicional de cores e indicadores de investimento necessário.
- **Relatórios Multi-Sheet:** Exportação automatizada em Excel (`.xlsx`) com abas segmentadas por faturamento, cargos e urgência de compra.

##  Tecnologias
- **Python 3**
- **Pandas** | **Matplotlib** | **Openpyxl**

##  Insights Gerados

###  Análise de Performance por Vendedor
O pipeline consolida o volume de vendas individual, permitindo identificar os maiores contribuidores da operação.

<p align="left">
  <img src="https://github.com/user-attachments/assets/9def5901-06b2-4774-844f-f476e145d5cd" width="250">
</p>

### Desempenho por Cargo
Cruzamento de dados que revela a eficiência de cada nível hierárquico na força de vendas.

<p align="left">
  <img src="https://github.com/user-attachments/assets/b1c489f1-bf96-472c-8338-4bee8da5ce26" width="450">
</p>

###  Gestão de Estoque Crítico
O sistema identifica automaticamente produtos abaixo do estoque mínimo e projeta o **investimento financeiro total** necessário para a normalização do inventário.

![Gráfico de Investimento](https://github.com/user-attachments/assets/85254217-3f20-49c4-91ea-5d23a0c50d2f)

##  Estrutura do Repositório

O projeto está organizado para garantir a separação entre dados brutos, lógica de processamento e resultados:

```text
├── empresa_dados.xlsx          # Base de dados (Vendas, Estoque, Funcionários)
├── dados_empresa.ipynb         # Notebook com a lógica de análise em Python
├── Relatorio_Final.xlsx        # Output gerado com os resultados consolidados
├── LICENSE                     # Licença MIT
└── README.md                   # Documentação do projeto
