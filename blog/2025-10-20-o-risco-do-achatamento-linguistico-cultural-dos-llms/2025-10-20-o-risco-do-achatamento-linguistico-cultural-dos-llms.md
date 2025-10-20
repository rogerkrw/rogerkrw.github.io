---
title: O risco do "achatamento" linguístico-cultural dos LLMs
author: Rogério Kreidlow
date: 2025-10-20
description: Sabe a sensação de que IAs escrevem em português, mas parecem pensar em inglês? Fiz um apanhado de estudos e dados para entender por que isso ocorre e suas possíveis consequências.
image: gpt-human-similarity-cultura-distance-from-usa.png
categories:
  - IA
  - Linguagem
  - Cultura
keywords:
  - LLMs
  - GPT
  - viés cultural
  - diversidade linguística
  - aculturamento
  - IA generativa
  - padronização cultural
toc: true
---

![Quanto maior a distância cultural dos EUA, menor a correlação entre respostas do GPT e o pensamento humano. Fonte: PsyArXiv Preprints](gpt-human-similarity-cultura-distance-from-usa.png "A imagem é um gráfico de dispersão com o título 'Correlação entre GPT e Humanos' no eixo Y e 'Distância Cultural dos Estados Unidos' no eixo X. Ele mostra pontos de dados para vários países. Uma linha de regressão preta com uma faixa de confiança cinza sombreia os dados, indicando tendência negativa. Os pontos de dados no canto superior esquerdo (baixa distância cultural, alta correlação) incluem Estados Unidos, Canadá, Reino Unido e Austrália. Países como Egito, Paquistão e Líbia estão no canto inferior direito (alta distância cultural, baixa correlação)."){#fig-correlacao}

Há algum tempo vi o gráfico que ilustra este artigo em um [post](https://www.linkedin.com/posts/ctaurion_ai-technology-analytics-activity-7329196572716486656-a5qb/) de Cezar Taurion no LinkedIn, em que ele compartilhava outro post de Keith McNulty.

Após me deter um pouco na imagem e ver rapidamente o estudo que deu origem a ela, lembro de ter elaborado uma hipótese mais ou menos assim: o fato de IAs como o ChatGPT e similares "pensarem" e "responderem" majoritariamente a partir do inglês (mesmo que traduzindo a outros idiomas) não pode enviesar a nós e a novas gerações a pensar e responder cada vez mais "em inglês" (não na língua em si, mas com a carga cultural de países onde o inglês é falado)? Não há risco de um processo de aculturamento, padronização, homogeneização, "achatamento" sócio-cognitivo, em detrimento de diversidade cultural, linguística, étnica?"

Taurion, que questiona a confiança efusiva na IA generativa, diz no post:

> *"O mundo não se limita ao Vale do Silício…"* — [Cezar Taurion](https://www.linkedin.com/posts/ctaurion_ai-technology-analytics-activity-7329196572716486656-a5qb/).

E McNulty, em tradução livre:

> "Este artigo publicado no ano passado por biólogos evolutivos de Harvard indica que — quando usado para tarefas cognitivas típicas — a similaridade entre respostas de modelos LLMs e respostas humanas diminui à medida que nos afastamos das grandes economias ocidentais 'semelhantes aos EUA'. Isso levanta questões sobre se podemos generalizar globalmente conclusões sobre o uso seguro e produtivo da tecnologia de IA integrada em processos de trabalho. [...]" — [Keith McNulty](https://www.linkedin.com/feed/update/urn:li:activity:7326237398617501696/).

O print da postagem, para referência:

![Postagem de Cezar Taurion compartilhando a de Keith McNulty, que citou o artigo. Fonte: LinkedIn](print-post-cesar-taurion-keith-mcnulty.png "A imagem é uma captura de tela de uma postagem no LinkedIn de Keith McNulty, compartilhada por Cezar Taurion. Inclui o mesmo gráfico de dispersão que mostra a correlação entre as respostas de LLMs (como o GPT) e as respostas humanas em relação à distância cultural dos Estados Unidos. O texto da postagem de Keith McNulty explica que a pesquisa indica que a similaridade entre os modelos de linguagem e as respostas humanas diminui à medida que se afastam das economias ocidentais dominantes, o que levanta questões sobre a generalização de tecnologias de IA em fluxos de trabalho."){#fig-postagem}

---

O estudo me chamou a atenção porque confirmava o que eu já intuía no uso quase diário de LLMs para escrita: havia sempre incômodos com termos, construções frasais, gerúndios, nuances, que não eram uma maneira "natural" de eu pensar e escrever em português do Brasil. Causavam fricção, incômodo. Não é um achado revelador e provavelmente você também já tenha tido o mesmo incômodo ou chegado à mesma constatação.

E nem falo de termos como o "crucial" do GPT-3.5, que, de tão banalizado, surtia praticamente o efeito oposto, de nada mais ter importância. Qualquer "nariz de cera" (início de frase no estilo "encheção de linguiça", que LLMs usam bastante), como "me fale sobre escovar os dentes todos os dias", resultava em algo como: *"Escovar os dentes todos os dias é um hábito crucial para…"*. A evolução do GPT-4 e outros modelos ao menos parece ter melhorado tal comportamento.

Mas sempre sobram termos e construções como:

* *"em constante evolução"* (exemplo: "o mercado de trabalho em 2025 está em *constante evolução*…");
* *"ressoar"* ("o importante é que esses conselhos *ressoem* em você");
* *"certifique-se de"*, principalmente em listas de tarefas, com voz no imperativo ("*certifique-se de* ter preenchido todos os campos…");
* *"incluindo"* para quaisquer locuções substantivas (exemplo: "[...] todos os departamentos da empresa, *incluindo* vendas, marketing e RH.");
* *"significativo"*, no mesmo sentido de "crucial";
* gerúndios que alongam sentenças (exemplo de uma típica frase de LLM: "a implementação do novo sistema representou um avanço significativo, *permitindo*…");
* adjetivos desnecessários (o "significativo", o "crucial", entre vários outros);
* e por aí segue.

Isso, é claro, para não falar de erros irritantes, como a mania de capitalizar todas as palavras em títulos ou itens de lista e em capitalizar a primeira palavra após dois-pontos, mesmo quando [não seguem a regra](https://www.dicio.com.br/depois-de-dois-pontos-letra-maiuscula-ou-minuscula/).

É claro que se você fornecer textos com seu estilo, LLMs irão mimetizá-los. Mas aí lidamos com outras consequências, como o modelo enviesar para aquela abordagem, adotar quase *ipsis litteris* a mesma construção do texto fornecido e aumentar de forma até caricata certas características. 

E mesmo isso ainda obriga a escrever um "manual" na tentativa de o modelo não adotar um tom que soa sempre a texto de marketing ou copywriting. Do contrário, é comum ele tender a destacar e "vender" qualquer assunto, por mais irrelevante que seja ou quando se quer uma abordagem mais neutra, sem qualificações.

---

O *paper* *"[Which Humans?](https://osf.io/preprints/psyarxiv/5b26t_v1)"* (*"Quais humanos?"*, em tradução livre), que contém o gráfico que ilustra esse artigo, basicamente compara o desempenho de LLMs com o comportamento humano em testes psicológicos e ressalta a falta de diversidade cultural no treinamento dos LLMs.

Metodologicamente, usa outro estudo chamado *"[World Values Survey (WVS)](https://www.worldvaluessurvey.org/wvs.jsp)"*, que coletou respostas de 94.278 indivíduos de 65 nações, para comparar respostas do GPT com as de grupos humanos. 

Foi, então, feita uma análise de "cluster hierárquico", o que mostrou que o GPT estava mais próximo dos EUA e mais distante de culturas como as do Oriente Médio e da Ásia Central (a distância no eixo X). E uma correlação inversa foi encontrada entre a distância cultural dos Estados Unidos e a semelhança GPT-humano (a linha preta).

Uma das conclusões do estudo, portanto, é que o desempenho dos LLMs em tarefas cognitivas e psicológicas se assemelha mais ao de pessoas de sociedades "WEIRD" (*"Western, Educated, Industrialized, Rich, and Democratic"* ou "Ocidental, Educado, Industrializado, Rico e Democrático", em tradução livre) e diminui à medida que se distancia dessas populações.

Para nota rápida, WEIRD é um conceito que surgiu em um paper intitulado *"[The neglected 95%: why American psychology needs to become less American](https://pubmed.ncbi.nlm.nih.gov/18855491/)"* (*"Os 95% negligenciados: por que a psicologia americana precisa se tornar menos americana"*), de Jeffrey J. Arnett, de 2008. 

No estudo, Arnett argumenta que a pesquisa em Psicologia publicada nos periódicos da American Psychological Association (APA) se concentrava excessivamente em amostras americanas, que representam menos de 5% da população mundial. 

Ou seja, a abordagem resulta em uma compreensão não representativa da psicologia humana, já que 95% da população global vive em condições culturais e socioeconômicas bem diferentes. 

É mais ou menos como tentar classificar todos os humanos a partir da ótica geracional que o marketing criou, dos *baby boomers*, X, *millennials*, Z, alfa, entre outras. Provavelmente, não fará muito sentido para entender povos esquimós, curdos, uigures ou guajajaras brasileiros.

O gráfico em si, para entendimento nos detalhes, mostra:

* no *eixo X* (horizontal), a distância cultural de países em relação aos Estados Unidos (quanto maior o valor, mais diferente culturalmente é o país);
* no *eixo Y* (vertical), a correlação entre GPT e humanos (quanto maior, mais similaridade entre o desempenho do LLM e o modo de pensar daqueles humanos).

A linha preta mostra correlação negativa (r = -0,7), o que significa que quanto mais distante culturalmente um país está dos EUA, pior o GPT performa se comparado à forma de pensar e se expressar das pessoas daquele país.

Na prática, países culturalmente próximos aos EUA, como Austrália, Canadá e Reino Unido, têm alta correlação entre GPT e humanos (~0,85). Já países como Alemanha, Japão e Coreia do Sul ficam em uma faixa média (~0,78-0,8). E países culturalmente distantes (Paquistão, Líbia, Egito) apresentam correlações menores (~0,62-0,7).

Qual o motivo disso? Bastaria um exercício dedutivo mental para respondermos. Em quais dados LLMs como o GPT foram treinados? Web, principalmente Wikipedia, periódicos, livros. Qual o idioma predominante na web? Inglês, sobretudo americano. Mesmo chutando, você acertaria. 

Resultado: o GPT tem um viés cultural alinhado com o inglês e toda a cultura que o fala e o molda no dia a dia, a qual, não há como negar, é uma *cultura ocidentalizada*, formalmente *educada*, *industrializada*, *rica* e — alguns questionarão — *democrática*.

---

Pesquisando manualmente e com ajuda de *deep research* de vários LLMs, não há nenhuma fonte oficial e cabal de qual a proporção de idiomas presentes em cada LLM *mainstream*. O fato de a maioria dos grandes modelos ter parado de compartilhar *papers* detalhados, por questões de concorrência e segredo industrial, após o GPT-3, em 2020, tornou esse campo mais especulativo do que exato.

De qualquer modo, não é difícil deduzir que o inglês seja a língua predominante na maioria dos conjuntos de dados de treinamentos. Basta fazer alguma extrapolação por fontes comuns e populares de dados. 

Uma das principais dessas fontes é o [Common Crawl](https://commoncrawl.org/), organização sem fins lucrativos que, desde 2008, faz *web scraping* (raspagem de dados) da internet mensalmente e disponibiliza seus dados de forma pública. 

No site da instituição, é informado que 250 bilhões de páginas web foram raspadas em 18 anos e que de 3 a 5 bilhões de páginas são adicionadas por mês. No relatório de julho de 2025, por exemplo, a instituição obteve conteúdo de 2,42 bilhões de páginas web ou 419 TB (Terabytes) de conteúdo não compactado. 

Conforme os dados de julho, disponíveis no [GitHub](https://commoncrawl.github.io/cc-crawl-statistics/plots/languages), o inglês está presente em 44,6% dos conteúdos coletados. O segundo colocado é o russo, com apenas 5,8%, seguido do chinês (5,59%), alemão (5,58%) e japonês (5,27%). O português representa 2,16% do total. 

A proporção do inglês caiu 1,46% entre os dois últimos levantamentos, enquanto outras línguas vêm crescendo vagarosamente. Exemplos: chinês (+4,59%), japonês (+5,24%), italiano (+10,3%) e persa (41,14%), embora todos longe de equilibrar a predominância do inglês.

Vale ressaltar, porém, que o Common Crawl é apenas um dos muitos *datasets* massivos disponíveis. Há outros usados para treinamentos de modelos, além de versões otimizadas deles e, cada vez mais, dados sintéticos — gerados pelos próprios LLMs, por heurísticas ou por regras determinísticas para suprir a falta de dados de alta qualidade necessária às IAs.

Nem seria necessário ir tão longe para verificar os números. Só o fato da maioria dos artigos científicos (*papers*) serem escritos em inglês dá uma dimensão da proporção do idioma. A própria [Wikipédia](https://pt.wikipedia.org/wiki/Lista_de_Wikip%C3%A9dias) é uma boa bússola: 63,6 milhões de páginas são em inglês, contra 19,5 milhões do segundo colocado, o vietnamita.

(Se você tem curiosidade sobre quantos dados haveria disponível para treinamento de LLMs no mundo, um post de 2024 [deste site](https://www.educatingsilicon.com/2024/05/09/how-much-llm-training-data-is-there-in-the-limit/) se propôs a fazer tal exercício. Não é científico, mas as ideias são bem referenciadas e logicamente construídas.)

Há ainda outra questão em relação ao inglês e outros idiomas nos LLMs: consumo de tokens. Token, para entendimento rápido, é a menor unidade de texto que um modelo de IA "entende". É um "pedaço" de uma palavra ou um caractere. Para que uma IA processe texto, ela precisa convertê-lo em números, e tokens servem a isso.

Para um exemplo simplório, na frase "Olá, mundo!", um tokenizador (ferramenta usada para converter textos em tokens) pode quebrar "Olá," em "Olá" e ",", e "mundo!" em "mundo" e "!". Cada parte recebe um número no vocabulário do modelo, o que permite que a IA trabalhe com o texto como matrizes numéricas multidimensionais.

Em inglês, com base na análise na maioria dos tokenizadores, uma palavra corresponde a 0,75 token. Em outros idiomas, a tendência é a [correspondência ser maior](https://medium.com/data-science/all-languages-are-not-created-tokenized-equal-cd87694a97c1), o que significa que modelos têm de "gastar" mais tokens para responder às entradas. 

Para o português do Brasil, é consenso que cada palavra corresponde a 1,5 token ([este post no Reddit](https://www.reddit.com/r/OpenAI/comments/124v2oi/hindi_8_times_more_expensive_than_english_the/) de 2023 calculava 1,9). O número aumenta em línguas como as asiáticas, da Índia, russo, grego e outras. Se formos olhar pelo lado de custos, [é mais "caro"](https://towardsdatascience.com/why-openais-api-is-more-expensive-for-non-english-languages-553da4a1eecc/) para um LLM genérico falar em outras línguas do que o inglês, o que pode reforçar ainda mais a comunicação na "língua-mãe" da tecnologia.

---

Ao que essa argumentação nos leva? Embora não se pretenda científica, ela ajuda a pensar na hipótese que introduzi no início. Pode ocorrer de vermos novas gerações terem um "achatamento" cultural ainda maior do que a minha geração (*"millennials"*, para usarmos a classificação do marketing). 

Não que seja simplesmente bom ou ruim. Nada na realidade é tão simplista. Comércio, relações entre países e globalização são sobre *padronização*, "achatamentos" e sobre falamos a mesma língua, literal e metaforicamente. A própria História talvez seja um conflito por homogeneização cultural — seja via *hard power* (guerras, dominação etc.) ou *soft power* (influência cultural, religião, costumes etc.), até para nos entendermos uns aos outros e não parecermos alienígenas em um mesmo planeta, o que suspeito que possa ter ocorrido num passado remoto. 

No entanto, de outro ponto de vista, isso inevitavelmente implica em perda de diversidade cultural, de identidade e outras consequências desconhecidas. No extremo, pode levar todos a viverem, comportarem-se, falarem e a *pensarem* da mesma forma — ou de forma muito similar, o que em certa medida ocorre no "ocidente clássico" (Europa e EUA).

---

Outro [estudo](https://arxiv.org/abs/2409.01754) bastante recente, aliás, vai nessa linha. Pesquisadores do [Instituto Max Planck](https://www.mpg.de/institutes), na Alemanha, detectaram um aumento "abrupto" no uso de palavras geradas pelo ChatGPT — e isso em inglês. Estão na lista *"delve"*, *"comprehend"*, *"boast"*, *"swift"* e *"meticulous"* (respectivamente, "aprofundar", "compreender", "gabar-se/ostentar", "veloz" e "meticuloso", em tradução livre, mas que podem não captar as nuances dos originais em inglês).

São evidências empíricas de que a linguagem gerada por IA pode estar moldando a comunicação falada por nós com implicações desconhecidas para a diversidade cultural e linguística.

Para chegar a tal conclusão, a pesquisa analisou 740.249 horas de discurso humano, de 360.445 palestras acadêmicas do YouTube e 771.591 episódios de podcast em diversas disciplinas.

O estudo quantificou as preferências de palavras do ChatGPT e, em seguida, comparou as distribuições de frequência de palavras em textos humanos com suas versões editadas pelo ChatGPT.

Foi observado que a influência linguística dos LLM é presente na fala de *early adopters* (adotantes iniciais), como pessoas da academia, da ciência e da tecnologia. Mas se estende também a outros domínios, como negócios. E o comportamento não ocorre só em falas roteirizadas, mas em conversas informais, como nos podcasts.

Não se sabe exatamente o que leva a essa adoção de termos do GPT na fala, segundo os pesquisadores. Pode ser imitação direta, maior facilidade cognitiva de lembrar ou algo mais profundo e desconhecido do processo cognitivo humano.

O estudo levanta preocupações sobre a homogeneização cultural (o "achatamento"). Um efeito interessante (vale um artigo futuro) é no chamado "colapso do modelo": a degradação da qualidade de IAs generativas, por serem cada vez mais treinadas em dados gerados por elas mesmas.

Na busca crescente por otimização de tudo, pode haver uma *"redução da entropia"*, tornando tudo mais e mais igual, a ponto de não haver mais variedade de dados. Isso limitaria os próprios dados de treinamento, fazendo-os serem menos "generativos" cada avanço. Em um extremo hipotético, LLMs se tornariam "determinísticos" a diversas entradas.

---

Se enxergarmos isso como problema, como resolvê-lo? Não é uma questão trivial. Dado o uso crescente de LLMs e dado que, inevitavelmente, os dados disponíveis na web, livros ou em quaisquer outras mídias parecem ser em sua maioria em inglês — o que, repito, reflete um determinado tipo de cultura, jeito de se comunicar, de pensar e de viver —, não parece haver muita saída.

O que pode mudar um pouco o cenário, e em alguma medida isso acontece de 2022 para cá — mas, novamente, dentro da disponibilidade de dados para treinamento —, é a inclusão de mais dados de outras línguas que não o inglês em *datasets*. 

Uma terceira medida é, sim, o treinamento de LLMs com um peso maior para um idioma em detrimento de outros. É o que vem acontecendo em relação ao chinês, já que a China está em uma corrida geopolítica com os EUA para domínio em vários campos, entre eles a IA. 

Há [relatos](https://pub.towardsai.net/why-do-chinese-llms-switch-to-chinese-in-complex-interactions-d18daac872b8) do DeepSeek, por exemplo, gerar saídas em chinês sem motivo aparente, em especial em tarefas difíceis. Tal comportamento pode ocorrer por haver uma maior quantidade de dados em chinês do que em inglês no pré-treinamento do modelo ou por características adicionadas no pós-treinamento, como no [RLHF](https://aws.amazon.com/pt/what-is/reinforcement-learning-from-human-feedback/) (*"Reinforcement Learning from Human Feedback"* ou "Aprendizagem por Reforço com Feedback Humano", em tradução livre).

Em relação ao português do Brasil, os LLMs da [Amazônia IA](https://amazoniaia.com.br/iniciativa) e da [Maritaca](https://www.maritaca.ai/) vão na mesma direção. Ainda não testei ambos a fundo, mas em uma comparação rápida com GPT, Claude e Gemini, notei que tanto o modelo Sabiá 3.1 quanto Sabiá 3 e Sabiazinho, da Maritaca, adotam nuances da escrita em português do Brasil que costumam exigir *prompt engineering* nos LLMs *mainstream*. 

Um exemplo rápido é quanto às construções frasais, que nos LLMs da moda tendem a se estender com gerúndios e seguir padrões facilmente encontrados em *reports* e artigos acadêmicos em inglês americano. Notei que eles ocorrem menos ou não ocorrem nos modelos da Maritaca. Vale mencionar outros exemplos como [Bode](https://arxiv.org/abs/2401.02909) ou [Clarice](https://clarice.ai/), mas não os testei para ter uma impressão.

A conjectura que fica é se, dentro de 3, 5 ou 10 anos — longo prazo para a IA, dado os seus avanços — ainda fará sentido querermos nuances de determinadas línguas nos LLMs. Porque muito mais pessoas já terão recorrido e estarão recorrendo a eles. E uma gama muito maior de pessoas já pode estar habituada a falar, a pensar e se comportar com base na escrita em inglês, ou seja, em todo o contexto cultural que o idioma carrega.

Em outras palavras: se mais pessoas pensam e agem de maneira parecida, não irão buscar "mais do mesmo" em vez de ainda sentirem necessidade de nuances diferentes? Outros modos de registrar a fala e, portanto, o pensamento, não irão virar, quando muito, peça de museu, já que não haverá mais necessidade delas? É uma questão filosófica, que só o tempo responderá.
