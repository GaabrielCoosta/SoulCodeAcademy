# Ciclo de vida do projeto!

[![NPM](https://img.shields.io/npm/l/react)](https://github.com/GaabrielCoosta/Changelle_HandTalk/blob/main/LICENSE)

![Design sem nome (2)](https://github.com/GaabrielCoosta/SoulCode/assets/108695592/e93df3c2-3724-40d9-840c-451c683d9229)

### ENTENDENDO O PROBLEMA
**Informação obtida:**
- *“A empresa XPTO está preocupada com a retenção de talentos na companhia [...] Os funcionários pediram demissão e saíram da empresa por se sentirem desgastados com a XPTO"*

#### 💎 Técnica dos 5W-s

**📌 Porque é importante essa análise para o negócio?**

- Para que possamos entender o que está causando o desgaste dos funcionários e consequentemente diminuir os pedidos de demissão

**📌 Quem iremos analisar?**

- Iremos analisar os funcionários da empresa XPTO

**📌 O que iremos analisar?**

- O possível motivo de desgaste dos funcionários, que pediram demissão

**📌 Qual período será considerado para as análises?**

- Será considerado o periódo de vínculo do funcionário com a empresa XPTO

**📌 Onde?**

- Especificamente dentro da empresa XPTO através dos dados fornecidos pelo RH da empresa

### COLETA DE DADOS 

- Análise feita a partir de **dados internos e secundários**

### PROCESSAMENTOS DE DADOS

- Organização da planilha "base_rh", fornecida pela empresa XPTO, colocando em ordem os atributos por coerência e relação, separando os dados pessoais de cada funcionário dos dados relacionado à empresa

### EXPLORACAÇÃO DE DADOS 

- Nessa etapa, realizamos uma análise exploratória dos dados, utilizando apenas as ferramentas Google Planilhas e Excel. 
Primeiramente, fizemos cálculos de correlação de todos os atributos com o atributo “desgaste” para termos uma melhor visualização,
e podermos definir os atributos como relevantes ou não para nossa análise. 
  
#### DISTRUIBUIÇÕES DE FREQUÊNCIA

Frequência de demissão por nivel hierarquico |   |   |   |  
-- | -- | -- | -- | --
Nivel | Quantidade | Quantidade acum | % Quantidade | % Quantidade acum
1 | 143 | 143 | 60,34% | 60,34%
2 | 52 | 195 | 21,94% | 82,28%
3 | 32 | 227 | 13,50% | 95,78%
4 | 5 | 232 | 2,11% | 97,89%
5 | 5 | 237 | 2,11% | 100,00%
Total | 237 |   | 100,00% |  

- Ao total, 237 funcionários pediram demissão. 60,34% possuiam nivel 1 e 21,94% nível 2, sendo eles os níveis mais baixos de uma escala de 1 à 5. A soma dos dois níveis representam 82,28% dos funcionários desgastados.

Frequência de demissão por idade |   |   |   |  
-- | -- | -- | -- | --
Idade | Quantidade | Quantidade acum | % Quantidade | % Quantidade acum
18 - 25 | 44 | 44 | 18,57% | 18,57%
26 - 36 | 122 | 166 | 51,48% | 70,04%
37 - 45 | 37 | 203 | 15,61% | 85,65%
46 - 58 | 34 | 237 | 14,35% | 100,00%
Total | 237 |   | 100,00% |  

- Através dessa análise obtivemos o dado que **70,04%** dos funcionários desgastados possuíam entre **18 e 36 anos**, e que **51,48%** possuíam entre **26 e 36 anos de idade**.
