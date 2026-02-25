
# Análise Estatística de Dados. Receitas de dois Planos Pré-Pagos (Surf e Ultimate) da empresa Megaline de telecomunicações.

Este projeto tem como objetivo analisar o comportamento de clientes da operadora de telecomunicações Megaline, com foco em identificar qual dos dois planos pré-pagos — **Surf** ou **Ultimate** — gera maior receita para o negócio.
Nesse projeto eu sou o analista da empresa de telecomunicações Megaline. O departamento comercial quer saber qual dos planos gera mais receita para ajustar o orçamento de publicidade.

Eu realizo uma análise preliminar dos planos com base em uma pequena seleção de clientes da Megaline: que clientes são, de onde eles são, qual plano usam e o número de chamadas e mensagens realizadas em um ano. Meu trabalho é analisar o comportamento dos clientes e determinar qual plano pré-pago gera mais receita.
Os resultados obtidos podem auxiliar a empresa na **alocação estratégica de recursos de marketing e tomada de decisão comercial**.

---

## Sobre os Dados
- Amostra de **500 clientes**
- Informações disponíveis:
  - Número de chamadas
  - Duração das ligações
  - Mensagens enviadas
  - Volume de dados de internet
  - Plano do cliente
  - Receita gerada

---

## Tecnologias utilizadas
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy (para testes estatísticos)

---

## Etapas do projeto

1. **Preparação dos dados**
   - Carregamento
   - Inspeção
   - Limpeza e tratamento de inconsistências

2. **Análise exploratória**
   - Estatísticas descritivas do uso dos serviços
   - Visualização comparativa entre os planos

3. **Cálculo de receita**
   - Receita individual por cliente
   - Receita total por plano

4. **Testes estatísticos**
   - Avaliação de significância nas diferenças de receita entre os planos

5. **Conclusões e recomendações**
- Plano mais rentável:
   Minhas recomendações finais é que o Plano Ultimate deve ser o foco central dos investimentos, tanto em aquisição quanto em retenção, já que gera maior receita média e representa maior potencial de lucratividade.
   Já o Plano Surf pode continuar sendo oferecido como produto de entrada, mas precisa ser complementado com estratégias de conversão para Ultimate para aumentar o ticket médio ao longo do ciclo de vida do cliente.
   Sobre a hipótese levantada comparanado a região NY-NJ com as demais regiões, o estudo merece atenção especial, pois a receita média da região NY-NJ está abaixo da média nacional, nesse caso a recomendação seria testar campanhas de fidelização e incentivos para migração ao Plano Ultimate na localidade.
   Já nas demais regiões, elas apresentam receita média mais elevada, o que reforça a necessidade de consolidar a base atual e expandir a presença do Plano Ultimate.
- Implicações estratégicas
   Concluo a análise desse projeto da Megaline baseada em Dados, informando que o Plano Ultimate é o plano mais rentável e deve receber prioridade estratégica da empresa.
   O Plano Surf pode ser reposicionado como canal de aquisição, mas precisa estar integrado a estratégias de migração.
   Sobre a região New York-New Jersey (NY-NJ) exige ações específicas para elevar a receita média e reduzir a distância em relação às demais regiões.
---

## Principais Resultados - Hipóteses
Durante a análise, conduzi dois testes de hipótese voltados para avaliar diferenças significativas na receita média dos usuários. 
Minhas conclusões foram apresentadas de forma analítica e comparativa. 
Na primeira hipótese sobre a comparação geral dos planos Surf e Ultimate (Estatística t = -10,49, p-valor ≈ 4,88e-25) o resultado foi altamente significativo (p < 0,05), indicando que a diferença de receita média entre os grupos analisados não pode ser atribuída ao caso. 
Há forte evidência estatística de que as receitas médias diferem substancialmente entre os grupos. Esse resultado sugere que o tipo de plano ou condição financeira do usuário exerce impacto direto sobre a receita. 
Na segunda hipótese sobre a comparação entre região NY-NJ e demais regiões (Estatística t = -2,36, p-valor ≈ 0,0186) rejeitei a hipótese H₀ ao nível de 5%, porém o efeito foi mais moderado em relação ao primeiro teste. 
Embora a diferença seja estatisticamente significativa, a magnitude prática da diferença entre as médias (NY-NJ ≈ 57,19 X outras regiões ≈ 62,88) é menos expressiva do que a encontrada na primeira hipótese.
A conclusão é de que ambos os testes mostraram que a receita média não é homogênea entre grupos de usuários, reforçando a importância de segmentações mais granulares. 
A diferença detectada no primeiro teste foi robusta, quase incontestável do ponto de vista estatístico, enquanto a diferença regional (NY-NJ x demais regiões) é mais sutil, embora ainda relevante. 
Esse contraste mostra que, ao analisar dados de receita, não apenas a localização geográfica, mas também outros fatores (como planos ou perfil de uso) parecem ser determinantes e mais fortes.


