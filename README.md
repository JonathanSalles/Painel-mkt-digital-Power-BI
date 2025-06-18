# Painel-mkt-digital-Power-BI

https://dncgroupbr.notion.site/Desafio-Crie-um-painel-gerencial-automatizado-utilizando-Power-BI-12fb1bb2b5334062a876a613275b4d81

Painel de Performance de Marketing Digital com Power BI
Este repositório apresenta um dashboard gerencial desenvolvido no Power BI para uma agência de marketing digital. O projeto visa automatizar o acompanhamento de indicadores de desempenho (KPIs), permitindo uma análise estratégica das campanhas e auxiliando na tomada de decisões para atingir metas trimestrais.

📝 Sumário
Contexto de Negócio
Objetivo do Projeto
Estrutura do Dashboard
Insights e Planos de Ação
Detalhes Técnicos
Autor
1. Contexto de Negócio
Uma agência de marketing digital ("Empresa X") precisava de uma ferramenta analítica para monitorar seus resultados e alcançar uma meta de performance ambiciosa. A ausência de um acompanhamento centralizado dificultava a identificação rápida de oportunidades e gargalos nas campanhas.

2. Objetivo do Projeto
O objetivo principal foi criar um painel gerencial automatizado no Power BI para fornecer à equipe de gestão uma visão clara e atualizada dos principais indicadores de marketing do mês de Março de 2023. A ferramenta deveria permitir:

Avaliar o desempenho financeiro e de engajamento das campanhas.
Identificar os canais de aquisição e os perfis de público mais valiosos.
Basear a escolha de planos de ação em dados concretos.
3. Estrutura do Dashboard
O painel foi organizado para apresentar as informações de forma lógica e intuitiva, com um filtro de data que permite a análise do período completo de 1 a 31 de Março de 2023. As visualizações foram distribuídas em duas páginas para garantir clareza.

KPIs Principais (Cartões)
Visão geral dos indicadores mais importantes para um diagnóstico rápido da saúde do negócio.

Receita Total: Valor total faturado no período.
Receita Média por Compra: Valor médio de cada transação realizada.
Total de Compradores: Número total de clientes únicos que realizaram uma compra.
Total de Visualizações: Quantidade total de visualizações nas páginas.


Análise de Público
Gráficos para segmentar e entender o perfil dos usuários ativos.

Usuários por Gênero (Gráfico de Pizza): Distribuição percentual do público entre os gêneros masculino e feminino.
Usuários por Plataforma (Gráfico de Pizza): Mostra como os usuários se dividem entre as plataformas (ex: Mobile, Desktop).
Usuários por Cidade (Gráfico de Barras): Ranking das cidades com maior concentração de usuários.


Análise de Aquisição e Comportamento
Visualizações focadas em entender a origem dos clientes e seu comportamento ao longo do tempo.

Compradores por Origem (Gráfico de Barras): Detalha a quantidade de compradores por cada canal de marketing (ex: busca orgânica, social media, email).
Compradores por Dia (Gráfico de Linhas): Evolução diária do número de compradores, permitindo identificar picos e tendências.
Taxa de Visualização por Dia (Gráfico de Linhas): Acompanha a variação da porcentagem de visualizações em relação aos usuários ativos, um indicador chave de engajamento.


4. Insights e Planos de Ação
A análise integrada do dashboard permite gerar insights estratégicos para a agência:

Otimização de Canais:

Insight: Ao cruzar o gráfico de Compradores por Origem com os dados de Receita Total, é possível identificar quais canais não só trazem mais clientes, mas também geram maior receita.
Plano de Ação: Realocar o orçamento de marketing para os canais com maior Retorno sobre o Investimento (ROI). Se um canal tem muitos compradores mas baixa receita média, criar campanhas de upsell específicas para esse público.
Foco Geográfico e de Plataforma:

Insight: A análise de Usuários por Cidade e Usuários por Plataforma pode revelar que a maioria dos clientes se concentra em uma cidade específica e acessa via mobile.
Plano de Ação: Priorizar a otimização de campanhas e sites para a experiência mobile (Mobile First). Criar campanhas de marketing geolocalizadas para as cidades de maior performance.
Análise de Sazonalidade:

Insight: O gráfico de Compradores por Dia pode mostrar picos de vendas recorrentes em determinados dias da semana (ex: fins de semana).
Plano de Ação: Concentrar os esforços de marketing, como o envio de e-mails e a veiculação de anúncios pagos, nos dias de maior probabilidade de conversão para maximizar os resultados.
5. Detalhes Técnicos
Ferramenta de BI: Microsoft Power BI
Transformação de Dados: Foi criada uma nova coluna calculada utilizando DAX para obter a taxa de visualização, através da fórmula:
Fragmento do código

% de visualização = DIVIDE([Visualizações], [Usuários totais])
Este indicador é essencial para medir o nível de engajamento do público com o conteúdo da página.
6. Autor
JONATHAN SALLES QUEIROZ
