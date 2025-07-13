
# Análise de Dados sobre Bullying Escolar no Brasil

## 1. Boxplot: Percentual de Alunos que Alegaram Serem Vítimas de Bullying (por Ano e Região)

### 🧩 Entendimento do Eixo do Tempo
Os dados foram coletados apenas nos anos de: **2008**, **2012**, **2015** e **2019**, o que indica coletas pontuais em anos específicos, não contínuos.

### 📈 Tendências Observadas
- **Crescimento até 2015**: houve um aumento constante nos relatos de bullying, com pico em 2015.
- **Queda ou estabilização em 2019**: a partir de 2015, há uma leve queda ou estabilização nas denúncias.
- **Inversão em 2019**: Regiões **Norte** e **Nordeste**, que historicamente apresentavam menores taxas de denúncia, passaram a liderar em 2019.

### ✅ Conclusão
Entre 2008 e 2015 houve um crescimento no número de denúncias, com pico em 2015. Em 2019, houve uma redistribuição regional significativa, com destaque para o aumento de casos nas regiões Norte e Nordeste, superando as demais.

---

## 2. Mapa e Gráfico de Barras: Análise por Sexo

### 🗺️ Mapa de Peso de Distribuição
- Os círculos mostram a distribuição de denúncias por região e sexo.
- Regiões com maior número de denúncias: **Sudeste** e **Centro-Oeste**.
- Nessas regiões, a cor rosa (feminino) domina, indicando maior número de denúncias por meninas.

### 📊 Gráfico de Barras por Sexo
- **Antes de 2019**: os **meninos** relataram mais casos de bullying que as meninas.
- **Em 2019**: as **meninas ultrapassam os meninos**, com 46% contra 36% respectivamente.

### ✅ Conclusão
Historicamente, meninos eram os principais a relatar bullying. A partir de 2019, meninas passaram a reportar mais casos em todas as regiões mais populosas. Isso pode refletir mudanças sociais, culturais e institucionais na forma de percepção e denúncia do bullying.

---

**Fonte das imagens: autoria própria.**

---

## 3. Análise de Tendência com Regressão Linear

### 📈 Contexto
Foi aplicada uma regressão linear para analisar a evolução do percentual de alunos que relataram casos de bullying entre os anos de 2009 e 2019, separando por sexo (meninos e meninas).

### 🔵 Meninos
- **Equação da reta**: y = 0,5786·x - 1,116
- **Interpretação**: crescimento anual médio de aproximadamente **0,58 pontos percentuais**.
- **Coeficiente de determinação (R²)**: **0,9688**
  - 96,88% da variação nos dados é explicada pela linha de tendência.
  - Excelente ajuste do modelo linear.

### 🟣 Meninas
- **Equação da reta**: y = 1,9916·x - 9,373
- **Interpretação**: crescimento anual médio de aproximadamente **1,99 pontos percentuais** — **mais de 3 vezes** o crescimento dos meninos.
- **Coeficiente de determinação (R²)**: **0,9787**
  - 97,87% da variação nos dados é explicada pela linha de tendência.
  - Ajuste ainda melhor que o dos meninos.

### ✅ Conclusão
Ambos os sexos apresentam crescimento no percentual de denúncias de bullying ao longo do tempo, mas o ritmo de crescimento entre as meninas é significativamente maior. A qualidade dos ajustes (R² > 0,96) indica que a regressão linear é um modelo confiável para essa análise.

---

## Análise Consolidada: Isolamento Social em Estudantes (2012, 2015, 2019)

### 📊 Dados Comparativos por Região

| Região        | 2012   | 2015   | 2019   | Tendência 2012-2019 |
|---------------|--------|--------|--------|---------------------|
| Norte         | 3,8%   | 4,5%   | 4,3%   | ▲ 13%               |
| Nordeste      | 2,8%   | 3,2%   | 3,1%   | ▲ 11%               |
| Sudeste       | 3,2%   | 3,2%   | 3,0%   | ▼ 6%                |
| Sul           | 3,0%   | 2,8%   | 2,7%   | ▼ 10%               |
| Centro-Oeste  | 3,7%   | 3,9%   | 3,4%   | ▼ 8%                |

**Legenda**:
- ▲ = Aumento
- ▼ = Redução

### 🔍 Principais Achados

1. **Tendências Regionais**:
   - Norte: Pico em 2015 (+0,7pp), ainda acima de 2012
   - Sul: Redução constante (-0,3pp por pesquisa)
   - Sudeste: Estabilidade com leve melhora

### ✅ Conclusões
1. **Prioridades**:  
   - Intervenções no Norte (índices persistentemente altos)  
   - Manutenção de políticas no Sul (modelo de sucesso)  

2. **Recomendações**:  
   - Expandir programas de integração escolar  
   - Monitorar uso excessivo de redes sociais  

**Fonte**: PeNSE/IBGE (2012-2019) | Valores em porcentagem  