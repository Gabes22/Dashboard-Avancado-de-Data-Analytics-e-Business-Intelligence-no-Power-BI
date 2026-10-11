# Dashboard de Data Analytics Avançado e Análises Estatísticas com Power BI

Este repositório apresenta o desenvolvimento de um ecossistema completo de Business Intelligence voltado para *Data Analytics*, atendendo às modificações e diretrizes avançadas a fim de criar visuais baseados em análises com viés estatístico profundo.

## 📊 Estrutura e Abas do Projeto Analítico

O projeto foi construído de forma integrada, permitindo que todas as informações se comuniquem perfeitamente por meio de filtros cruzados (cross-filtering) e navegação fluida entre *5 páginas completas*:

### 1. Home page (Capa de Entrada)
- Uma interface de boas-vindas limpa e intuitiva com o título *REPORT FINANCEIRO*. 
- O menu lateral esquerdo foi estruturado para guiar o usuário, e o botão central "Explorar análise" foi configurado com uma ação de navegação direcionada para abrir imediatamente o relatório de vendas.

### 2. Dashboard de Vendas
- Tela focada na análise volumétrica de faturamento bruto e unidades vendidas por período, segmento e país. Os gráficos foram redimensionados e alinhados para garantir simetria em relação aos painéis roxos de fundo.

### 3. Análise de Lucro
- Página focada em rentabilidade corporativa. Todos os elementos visuais de receita foram substituídos pela métrica de Lucro Líquido (Profit), oferecendo aos gestores uma visão clara de rentabilidade por produto e segmento.

### 4. Análise Estatística (Nova Página Analítica)
- *Histograma de Unidades Vendidas:* Implementação de uma distribuição de frequência (histograma com compartimentos de 500 em 500 unidades) para analisar a consistência e a recorrência do volume das vendas.
- *Gráfico de Dispersão Geral (Scatter Chart):* Análise bivariada correlacionando o volume de unidades vendidas com o faturamento, ideal para identificar outliers de mercado.
- *Matriz de Sazonalidade com Mapa de Calor:* Tabela analítica cruzando anos e trimestres com os totais financeiros, utilizando formatação condicional em degradê para identificação imediata dos períodos de pico.
- *Gráfico de Colunas Ordenadas:* Mapeamento decrescente de vendas brutas por produto.

### 5. Análise de Causa Raiz (Nova Página Analítica)
- *Árvore de Decomposição (Decomposition Tree):* Visual de Inteligência Artificial do Power BI que permite quebrar a métrica de Lucro Líquido (Profit) navegando hierarquicamente por Segmento, País e Produto para investigar a causa raiz dos resultados.
- *Gráfico em Cascata (Waterfall Chart):* Demonstração visual do impacto incremental e decremental no lucro de acordo com a virada dos trimestres históricos.
- *Gráfico de Funil de Custos:* Ranqueamento vertical do Custo de Mercadorias Vendidas (COGS) por produto, evidenciando quais itens geram maior despesa para a operação.

---

## 🛠️ Recursos de Navegação e UX Implementados

Para tornar o relatório fluido e profissional, foram feitas as seguintes melhorias técnicas de Experiência do Usuário:
- *Menu de Navegação Dinâmico:* Utilização do recurso nativo Page Navigator do Power BI, fornecendo um indicador visual claro (linha de destaque verde) que aponta exatamente em qual página o usuário se encontra.
- *Simetria em Faixas Horizontais/Verticais:* Alinhamento perfeito dos cards gerenciais no topo e na lateral das páginas para dar um respiro visual ao usuário.
- *Botões Inteligentes de Reset ("Limpar Filtros"):* Criação de indicadores (Bookmarks) exclusivos para as páginas analíticas acoplados a *Botões em Branco (invisíveis)* por cima do desenho da borracha azul. Ao clicar com Ctrl + Clique, o usuário limpa todas as seleções de uma vez só sem mudar de aba.

---

## 📐 Visualização do Ecossistema Analítico

### 1. Início (Capa)
![Capa do Relatório](/imagens/analise_estatistica.png)

### 2. Dashboard de Vendas
![Dashboard de Vendas](/imagens/relatorio_vendas.png)

### 3. Análise de Lucro
![Análise de Lucro](/imagens/analise_lucro.png)

### 4. Análise Estatística
![Análise Estatística](/imagens/analise_estatistica.png)

### 5. Análise de Causa Raiz
![Análise de Causa Raiz](/imagens/analise_causa_raiz.png)

---

## 📂 Arquivos do Repositório
- .pbix: Arquivo completo contendo a estrutura de dados, o modelo dimensional otimizado, as medidas criadas e as 5 páginas de relatórios gerenciais e analíticos prontas para uso.

## 👨‍💻 Autor
Desenvolvido por **Gabriela Pereira das Neves** no âmbito da jornada de transição e especialização em Dados e Tecnologia.
