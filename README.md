# Imagem corporal na adolescência: uma análise com Data Science
---
Este projeto foi desenvolvido durante o **Bootcamp de Data Science Aplicada (Alura)**, no Módulo 3. Neste módulo vimos, de forma resumida, alguns conceitos estatísticos da Inferência Estatística, e como aplicá-los na prática codando!

Observação: para melhorar a visualização de algumas imagens, por conta da resolução que foi comprometida, recomendo clicar em "Open in Colab", no começo do *notebook*.
# Contexto
---
A imagem corporal é um tema que deve ter a sua devida atenção, principalmente com o avanço tecnológico nesses últimos anos, em que as redes sociais vêm, cada vez mais, fazendo parte das nossas vidas.

Ter aquele "corpo perfeito" dos(as) nossos(as) amigos(as) ou influenciadores, publicados em suas redes sociais, podem acabar interferindo muito na visão do próprio corpo, prejudicando assim, a saúde física e mental. Além disso, podem existir outras pressões externas, como o bullying, que podem vir a atormentar ainda mais o psicológico sobre o assunto.

Entender o que acontece na mente dos menores é muito importante, afinal, elas que tomarão conta do mundo no futuro, passando os conhecimentos para as próximas gerações.

Sendo assim, neste projeto foi realizado uma **análise exploratória** a respeito da imagem corporal dos jovens e um pouco sobre o bullying na adolescência. Além de utilizar alguns testes com o **Qui-quadrado** para ver a relação que as variáveis tinham para os diferentes sexos.

**Base de dados:** PenSE 2015 - IBGE.

# Ferramentas utilizadas
---
- Linguagem de programação Python;
- Pacotes: pandas, numpy, matplotlib, seaborn, IPython, scipy;
- Notebook: Google Colaboratory.

# Descrição breve das etapas
---
## 1. Pré-processamento
- Fazer funções que melhorassem a procura e a visualização de determinada pergunta junto com as respostas, pois haviam muitas variáveis;
- Verificação de dados faltantes, porém não foi necessário dar atenção para elas.

## 2. Análise Exploratória dos Dados
Majoritariamente, houveram **tabelas cruzadas** e **gráficos de barras**:

![](https://github.com/Emersonmiady/imagem-corporal-ds/blob/main/img/corp_impression.png?raw=true)
![](https://github.com/Emersonmiady/imagem-corporal-ds/blob/main/img/sex_corp_impression.png?raw=true)
![](https://github.com/Emersonmiady/imagem-corporal-ds/blob/main/img/corp_consideration.png?raw=true)
![](https://github.com/Emersonmiady/imagem-corporal-ds/blob/main/img/corp_sentiment.png?raw=true)

## 3. Testes Estatísticos
- Qui-Quadrado para verificar as diferenças entre as populações, nesse caso, entre os sexos masculino e feminino.
 
Aqui vai uma das conclusões provindas deste teste:
> "Rejeitando-se a hipótese nula, temos que as impressões dos jovens em relação ao próprio corpo (massa corporal) são diferentes entre os sexos."
