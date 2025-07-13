
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

---

## 5. Análise: Sofrimento Mental em Estudantes da UNIFESP (2017-2021)

### 📊 Dados Comparativos

| Categoria                    | 2017-2019     | 2020-2021    | Variação relativa   | 
|------------------------------|---------------|--------------|---------------------|
| **Total**                    | 8414 (58,6%)  | 5934 (41,4%) | ▼ 29,36%            |
| **Não sofrem**               | 7129 (87,3%)  | 5015 (84,5%) | ▼ 3,21%             |
| **Sofrem sem psicofármacos** | 828 (10,1%)   | 759 (12,7%)  | ▲ 25,74%            |
| **Sofrem com psicofármacos** | 201 (2,4%)    | 160 (2,6%)   | ▲ 8,33%             |
| **Total com sofrimento**     | 1029 (12,5%)  | 919 (15,3%)  | ▲ 22,4%             |

### 🧠 Teste de hipótese:
- H₀ (nula): A distribuição dos tipos de sofrimento é igual nos dois períodos.
- H₁ (alternativa): A distribuição difere entre os períodos.

#### Tabela de valores de observados
| Categoria                    | 2017-2019     | 2020-2021    | Total               | 
|------------------------------|---------------|--------------|---------------------|
| **Não sofrem**               | 7129 (87,3%)  | 5015 (84,5%) | 12144               |
| **Sofrem sem psicofármacos** | 828 (10,1%)   | 759 (12,7%)  | 1587                |
| **Sofrem com psicofármacos** | 201 (2,4%)    | 160 (2,6%)   | 361                 |
| **Total**                    | 8414 (58,6%)  | 5934 (41,4%) | 14348               |

#### Tabela de valores esperados
| Categoria                    | 2017-2019          | 2020-2021         | Total   |
|-----------------------------|--------------------|-------------------|---------|
| Não sofrem                  | 7129,3 (58,7%)     | 5014,7 (41,3%)    | 12144   |
| Sofrem sem psicofármacos    | 929,5 (58,6%)      | 657,5 (41,4%)     | 1587    |
| Sofrem com psicofármacos    | 210,2 (58,2%)      | 150,8 (41,8%)     | 361     |
| Total                       | 8414 (58,6%)       | 5934 (41,4%)      | 14348   |

#### Calculando Qui-Quadrado de Pearson com 2 graus de liberdade
$$
\chi^2 = \sum \frac{(O - E)^2}{E} = 27,28
$$

#### Conclusão do cálculo:

- Seu X^2 = 27,28 é muito maior do que todos os valores da linha com 2 graus de liberdade
- Isso significa que a probabilidade de obter um X^2 >= 27,28 é menor que 0,005
- Isso implica em rejeição forte da hipótese nula H0.
- Em linguagem simples: a diferença entre os anos não é por acaso.

### 🔻 Queda no Total de Respostas
- O total de estudantes que responderam caiu de **8414 para 5934**, uma **redução de 29,36%**.
- Isso pode refletir menor engajamento ou mudanças no acesso durante a pandemia.

### ✅ Estabilidade nos Casos Sem Sofrimento Mental
- Percentual caiu de **87,3% para 84,5%** (**queda de 3,21%**).
- Ainda é a maioria, mas houve uma leve piora geral.

### ⚠️ Aumento de Sofrimento Mental sem Psicofármacos
- Passou de **10,1% para 12,7%**, um **aumento de 25,74%**.
- Indica que mais alunos apresentaram sofrimento, mas sem uso de medicação.

### ⚕️ Uso de Psicofármacos
- Subiu levemente de **2,4% para 2,6%** (**aumento de 8,33%**).
- Mostra que uma pequena parcela recorreu a tratamento medicamentoso.

### 📈 Aumento Total do Sofrimento Mental
- Percentual total com sofrimento (com ou sem medicamentos) subiu de **12,5% para 15,3%**, um **aumento de 22,4%**.

### ✅ Conclusão
Entre 2020 e 2021, houve um aumento relevante no sofrimento mental dos estudantes da UNIFESP, com destaque para os que não utilizam psicofármacos. O cenário reforça a necessidade de políticas institucionais de acolhimento psicológico, especialmente em contextos de crise como a pandemia.

---