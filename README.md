
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

## 4. Análise Consolidada: Isolamento Social em Estudantes (2012, 2015, 2019)

### 📊 Dados Comparativos por Região

| Região        | 2012   | 2015   | 2019   | Tendência 2012-2019 |
|---------------|--------|--------|--------|---------------------|
| Norte         | 3,61%  | 4,51%  | 3,59%  | ▼ 1%                |
| Nordeste      | 2,9%   | 3,9%   | 3,68%  | ▲ 27%               |
| Sudeste       | 3,08%  | 3,65%  | 3,08%  | - 0%                |
| Sul           | 2,93%  | 3,33%  | 2,7%   | ▼ 7,85%              |
| Centro-Oeste  | 3,83%  | 4,53%  | 3,93%  | ▲ 2,61%              |

**Legenda**:
- ▲ = Aumento
- ▼ = Redução

### 🔍 Principais Achados

1. **Nordeste e Centro-Oeste** registraram aumento no percentual de estudantes sem amigos próximos entre 2012 e 2019 — destaque para o **Nordeste**, com crescimento de 27%.
2. **Sul** apresentou a maior redução proporcional (−7,85%), com melhora contínua ao longo dos anos.
3. **Sudeste** manteve estabilidade nos três períodos, com leve variação em 2015, retornando ao patamar de 2012.
4. **Norte** teve um pico preocupante em 2015, mas voltou praticamente ao nível inicial em 2019.


### ✅ Conclusões

- **Regiões em Alerta**: Nordeste e Norte merecem atenção por apresentarem os maiores percentuais e/ou crescimento do isolamento social.
- **Exemplo Positivo**: O Sul mostra uma trajetória consistente de queda, podendo servir de modelo para outras regiões.
- **Estabilidade**: O Sudeste permanece com níveis constantes, o que indica possível efetividade de políticas já em vigor.


### 📌 Recomendações

- **Ampliar programas de integração social nas escolas**, especialmente no Nordeste e Norte.
- **Investir em boas práticas regionais**, como as do Sul, promovendo a troca de experiências e estratégias entre redes de ensino.

**Fonte**: PeNSE/IBGE (2012-2019) | Valores em porcentagem  