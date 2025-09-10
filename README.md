# FarmTech Solutions — PBL Fase 4

## Sobre o Projeto
A FarmTech Solutions está prestando serviços de IA para uma fazenda de médio porte (200 hectares) que produz várias culturas. O objetivo é analisar condições de solo e temperatura para prever rendimentos de safra e identificar tendências de produtividade.

**Dataset**: Análise de dados agrícolas incluindo:
- Precipitação (mm/dia)
- Umidade específica e relativa a 2m
- Temperatura a 2m
- Rendimento das culturas (t/ha)

## Funcionalidades Implementadas
1. **Análise Exploratória**: Visualização e compreensão inicial dos dados
2. **Detecção de Outliers**: Usando IQR e IsolationForest
3. **Clusterização**: Identificação de padrões via KMeans
4. **Previsão de Rendimento**: 5 modelos de machine learning implementados:
   - Regressão Linear
   - Ridge
   - Random Forest
   - Gradient Boosting
   - SVR (RBF)

## Integrantes
- Pedro Henrique Zani — RM 564956
- Flavia Nunes Bocchino — RM 564213

## Como Executar o Projeto

1. Clone o repositório
2. Instale as dependências:
```bash
pip install -r requirements.txt
```
3. Abra o notebook principal:
```bash
jupyter notebook notebooks/PedroHenriqueZani_rm-564956_and_FlaviaNunesBocchino_rm-564213_pbl_fase4.ipynb
```

> **Importante**: O dataset `crop_yield.csv` já está incluído na pasta `data/`. Execute as células do notebook em ordem para reproduzir as análises.

## Detalhes da Implementação
O notebook contém uma documentação detalhada de cada etapa, incluindo:
- Análise exploratória dos dados agrícolas
- Identificação e tratamento de outliers
- Análise de clusters para identificar padrões
- Implementação e avaliação de 5 modelos preditivos
- Conclusões e limitações do trabalho

## Vídeo Demonstrativo
[Clique aqui para assistir à demonstração](https://youtu.be/51HRzj52Fgw)
