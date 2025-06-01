# Projeto-Casos-de-Dengue-no-Brasil
Análise Preditiva da Evolução de Casos de Dengue no Brasil

Problema da Vida Real
A dengue é uma arbovirose que representa um grave problema de saúde pública no Brasil. A doença, transmitida pelo mosquito Aedes aegypti, apresenta quadros clínicos que podem variar de leves a fatais, exigindo uma gestão eficiente dos recursos de saúde pública para prevenir surtos e reduzir óbitos.

No entanto, a grande quantidade de notificações, associada à complexidade clínica e social da doença, dificulta a identificação precoce dos casos com maior risco de agravamento. Isso compromete a alocação de recursos e estratégias de vigilância.
Assim, surge a seguinte problemática:

Como utilizar análise de dados e aprendizado de máquina para prever a evolução de casos de dengue, identificando com antecedência os casos mais críticos?

Fontes de Dados Públicas e Não Confidenciais:
Para responder a essa pergunta, utilizei dados extraídos do Sistema de Informação de Agravos de Notificação (SINAN), acessível por meio do portal DATASUS. Essa base é pública e contempla notificações de diversas doenças de notificação obrigatória no Brasil.

Dados utilizados:

Data de notificação, início dos sintomas e encerramento

Localização geográfica (UF, município)

Classificação final do caso (Dengue, descartado, etc.)

Evolução do caso (cura, óbito, etc.)

Hospitalização

Resultados de exames sorológicos

Relevantes Identificados na Análise de Dados
Durante a análise exploratória e a modelagem, observei os seguintes fatores fortemente associados ao desfecho dos casos:

✅ Fatores temporais:
Tempo entre início dos sintomas e notificação
Casos notificados mais tardiamente tendem a apresentar maior risco.

Tempo até encerramento do caso
Casos que demoram muito a serem encerrados podem indicar maior gravidade.

✅ Fatores clínicos e administrativos:
Hospitalização
Forte indicador de gravidade.

Tipo de classificação final (Dengue, descartado, inconclusivo)
Pode refletir precisão do diagnóstico e nível de investigação.

✅ Fatores sazonais:
Mês do início dos sintomas
Casos aumentam e se agravam durante períodos quentes e chuvosos (sazonalidade da dengue).


#Conclusão e Aplicações Práticas
O uso de modelos preditivos, como o Random Forest, mostrou-se eficaz para antecipar a evolução dos casos de dengue, com boa precisão. Essa abordagem pode:

Ajudar autoridades de saúde a priorizar atendimentos

Reduzir óbitos preveníveis

Aumentar a eficiência da vigilância epidemiológica

Apoiar campanhas de prevenção em períodos críticos
