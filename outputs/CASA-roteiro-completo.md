# CASA — Roteiro de Apresentação
## Computer-Assisted Sperm Analysis

**Apresentadoras:** Iara Macêdo Petelinkar · Letícia dos Santos Rebelo
**Disciplina:** Vivência Prática Aplicada à Andrologia de Grandes Animais
**Programa:** Pós-Graduação em Biotecnologia Animal · FMVZ-UNESP Botucatu

---

## Resumo de Tempo

| Parte | Slides | Tempo estimado |
|-------|--------|----------------|
| **Parte 1 — Revisão** | Slides 1-10 | ~23 min |
| **Parte 2 — Artigo** | Slides 11-20 | ~19 min |
| **TOTAL** | 19 slides | **~42 min** |

---

## Tempo por Slide

| Slide | Título | Tempo | Palavras |
|-------|--------|-------|----------|
| 01 | CASA | 1.8 min | 236 |
| 02 | Estrutura da Apresentação | 1.6 min | 204 |
| 03 | O que é CASA? | 2.7 min | 355 |
| 04 | Evolução Histórica do CASA | 1.1 min | 139 |
| 05 | Trajetórias Espermáticas e Parâmetros | 2.7 min | 348 |
| 06 | Padrões de Trajetória Espermática | 2.4 min | 315 |
| 07 | Fatores de Variação nos Resultados | 3.0 min | 389 |
| 08 | CASA × Fertilidade | 2.8 min | 366 |
| 09 | Subpopulações Espermáticas | 2.4 min | 313 |
| 10 | Perspectivas Futuras | 2.6 min | 335 |
| 12 | A New Approach of Sperm MotilitySubpopulation Stru | 1.4 min | 182 |
| 13 | Contextualização e Objetivos | 2.3 min | 304 |
| 14 | Delineamento Experimental | 3.2 min | 418 |
| 15 | Jumento vs Cavalo | 2.3 min | 296 |
| 16 | Espanhol vs Árabe | 1.9 min | 252 |
| 17 | Subpopulações Identificadas | 2.6 min | 344 |
| 18 | Pontos Críticos da Discussão | 2.5 min | 320 |
| 19 | Conclusões — Gacem et al., 2021 | 1.6 min | 204 |
| 20 | Obrigada! | 1.2 min | 152 |

---


---

## Slide 01 — CASA
**Seção:** PARTE 1 — REVISÃO
**Tempo estimado:** 1.8 min (~236 palavras)

### O que falar:

Boa noite a todos. Somos a Iara Petelinkar e a Letícia Rebelo, discentes do Programa de Pós-Graduação em Biotecnologia Animal da UNESP Botucatu. Esta apresentação é para a disciplina de Vivência Prática Aplicada à Andrologia de Grandes Animais.

    Hoje vou apresentar sobre o sistema CASA — Computer-Assisted Sperm Analysis — que é a tecnologia de análise computadorizada de sêmen. A apresentação está estruturada em duas partes complementares.

    Na primeira parte, com duração de aproximadamente 20 minutos, trago uma revisão de literatura fundamentada principalmente na revisão clássica de Amann e Waberski publicada na Theriogenology em 2014 — que permanece como referência fundamental na área — complementada com publicações recentes de alto impacto que atualizam o panorama da tecnologia.

    Na segunda parte, também com 20 minutos, apresento em detalhes o artigo original de Gacem e colaboradores, publicado na Frontiers in Veterinary Science em 2021, que trouxe uma abordagem inovadora ao estudar a estrutura de subpopulações de motilidade espermática em garanhões e jumentos utilizando taxa de captura de 250 frames por segundo.

    Antes de começar, quero contextualizar a relevância deste tema para nossa linha de pesquisa: no CERAN trabalhamos com avaliação de qualidade seminal em garanhões — seja em protocolos de criopreservação, estudos de senescência reprodutiva ou no nosso projeto FAPESP sobre síndrome metabólica equina. O CASA é uma ferramenta central em todos esses projetos, e compreender suas capacidades e limitações é fundamental para a qualidade dos nossos dados.


---

## Slide 02 — Estrutura da Apresentação
**Seção:** Revisão de Literatura
**Tempo estimado:** 1.6 min (~204 palavras)

### O que falar:

Antes de entrar no conteúdo propriamente dito, quero mostrar a estrutura completa da apresentação para que possam acompanhar o raciocínio.

    A Parte 1 cobre a revisão de literatura em 8 tópicos interconectados. Começo definindo o que é CASA e como a tecnologia funciona. Em seguida, traço a evolução histórica desde as primeiras observações de Leeuwenhoek em 1677 até os sistemas modernos com inteligência artificial. Depois, entro no coração da tecnologia: os parâmetros cinéticos — VCL, VSL, VAP, LIN, STR, WOB, ALH e BCF — com suas definições científicas, interpretações biológicas e representações visuais. Abordo os fatores que afetam os resultados — e esse é um ponto crucial que muitas vezes é subestimado na literatura. Discuto a relação complexa entre dados de CASA e fertilidade real. Apresento o conceito de subpopulações espermáticas, que é o paradigma atual da área. E fecho com perspectivas futuras, incluindo a integração com inteligência artificial e dispositivos portáteis.

    A Parte 2 segue rigorosamente a estrutura científica: introdução, objetivos, material e métodos, resultados, discussão e conclusão. O artigo de Gacem é particularmente relevante porque foi o primeiro a usar 250 fps para comparar subpopulações entre espécie equina e asinina, incluindo comparação entre raças de cavalos — Espanhol e Árabe.

    Vamos começar.


---

## Slide 03 — O que é CASA?
**Seção:** Revisão de Literatura
**Tempo estimado:** 2.7 min (~355 palavras)

### O que falar:

O CASA — Computer-Assisted Sperm Analysis — não é um único aparelho, mas sim uma categoria de tecnologia que integra três componentes: microscopia óptica, captura de imagem em alta velocidade e processamento computacional.

    O funcionamento pode ser compreendido em 4 etapas sequenciais:

    **Etapa 1 — Captura:** Uma amostra de sêmen diluído é colocada numa câmara de contagem rasa — tipicamente 10 ou 20 micrômetros de profundidade — sobre uma platina aquecida a 37°C. Uma câmera de vídeo acoplada ao microscópio captura imagens sequenciais a taxas que variam de 25 a 250 frames por segundo, dependendo do sistema.

    **Etapa 2 — Detecção:** O software proprietário identifica cada espermatozoide pela diferença de intensidade de pixels em relação ao fundo — geralmente por contraste de fase negativo. Para cada célula detectada, calcula o centroide — o centro geométrico da cabeça espermática — em cada frame.

    **Etapa 3 — Rastreamento:** O algoritmo conecta os centróides de cada célula entre frames consecutivos, gerando a trajetória real de cada espermatozoide individual. Os sistemas modernos requerem um mínimo de 30 frames consecutivos para gerar uma trajetória confiável. É neste ponto que a taxa de frames se torna crítica: com 25 fps, a resolução temporal é de 40 milissegundos entre pontos; com 250 fps, cai para 4 milissegundos — uma diferença de 10 vezes na resolução.

    **Etapa 4 — Análise:** A partir de cada trajetória, o software calcula um conjunto de parâmetros cinéticos — velocidades, índices de progressividade, amplitude de oscilação e frequência de batimento — para cada célula individual. Em seguida, gera estatísticas populacionais: médias, medianas, distribuições. Sistemas mais avançados permitem análise de subpopulações por clustering.

    Um ponto fundamental que precisa ser enfatizado desde o início: existem mais de 12 sistemas CASA comercializados globalmente — Hamilton-Thorne IVOS, SpermVision, ISAS, SCA, entre outros. Cada um tem hardware, software e algoritmos proprietários diferentes. Isso significa que os resultados de um sistema NÃO são automaticamente comparáveis com outro. Mortimer, em 1997, já alertava para esse problema, e 27 anos depois ele persiste. É por isso que a padronização metodológica e o relato completo das condições experimentais são absolutamente essenciais em qualquer publicação que utilize CASA.


---

## Slide 04 — Evolução Histórica do CASA
**Seção:** Revisão de Literatura
**Tempo estimado:** 1.1 min (~139 palavras)

### O que falar:

A trajetória histórica do CASA acompanha a evolução da própria espermatologia e da tecnologia computacional.

    1677: Leeuwenhoek observou espermatozoides pela primeira vez — descreveu "animálculos" à Royal Society. Já notou que "alguns nadavam mais rápido".

    1974: primeiro protótipo na Colorado State University — computador PDP-11 que ocupava um rack de 76 cm, analisava menos de 30 espermatozoides em 4-8 frames.

    1985: CellSoft, primeiro sistema comercial. Tecnologia de rastreamento adaptada da corrida espacial.

    1986: HTM-2000 — marco porque foi desenvolvido ESPECIFICAMENTE para garanhão. A espécie equina sempre esteve no centro do CASA.

    2014: Amann e Waberski publicaram a revisão clássica — mais de 12 sistemas disponíveis, padronização como preocupação central.

    2020+: ISAS v1.2 com 250 fps, portáteis validados (iSperm, Ongo), IA com deep learning (YOLOv8+DeepSORT), CASA 3D por holografia digital. A tecnologia está se tornando mais acessível e precisa simultaneamente.


---

## Slide 05 — Trajetórias Espermáticas e Parâmetros
**Seção:** Revisão de Literatura
**Tempo estimado:** 2.7 min (~348 palavras)

### O que falar:

Este slide apresenta a base conceitual de toda a análise CASA: as trajetórias espermáticas e os parâmetros derivados delas.

    Vou usar uma analogia que facilita a compreensão. Imaginem que vocês estão filmando um corredor de 100 metros a partir de um drone. Eu consigo medir três coisas muito diferentes sobre ele:

    **VCL — Velocidade Curvilínea:** É a distância REAL que ele percorreu — com todas as curvas, desvios e zigue-zagues do caminho. É o GPS registrando cada passo. Para um espermatozoide que bate a cabeça lateralmente enquanto nada, essa é a maior das três velocidades.

    **VSL — Velocidade em Linha Reta:** Se eu traçar uma linha reta do ponto de saída até onde ele chegou no final — qual seria a velocidade nessa linha imaginária? É a distância em linha reta dividida pelo tempo total. Se o corredor deu muitas curvas, essa velocidade será muito menor que a VCL.

    **VAP — Velocidade do Caminho Médio:** O GPS suavizado — sem os micro-tremores. O software "alisa" a trajetória curvilínea e calcula a velocidade desse caminho médio. Fica entre VCL e VSL.

    E daí derivam as razões:

    **LIN = VSL/VCL:** Se o corredor foi 100% em linha reta, LIN = 100%. Se ele deu muitas curvas, LIN fica baixo — como 25-30% que vemos nos garanhões.

    **STR = VSL/VAP:** Quão reta é a rota suavizada.

    **WOB = VAP/VCL:** O quanto a rota média oscila em relação à trajetória real.

    E o **ALH**? É a largura do corredor que ele usa para se balançar. Um garanhão com ALH alto bate muito a cabeça — consome energia, pode indicar hiperativação. **BCF** é quantas vezes por segundo a trajetória curvilínea cruza a trajetória média — o ritmo do batimento.

    Uma observação metodológica importante: os valores absolutos de VCL, VAP e consequentemente LIN e WOB dependem diretamente da taxa de frames. Com fps baixo, as oscilações entre frames são "achatadas" pelo software e VCL é subestimada, inflando artificialmente LIN e WOB. Esse é um dos motivos pelos quais o artigo de Gacem utilizou 250 fps — para capturar a trajetória real com máxima fidelidade.


---

## Slide 06 — Padrões de Trajetória Espermática
**Seção:** Revisão de Literatura
**Tempo estimado:** 2.4 min (~315 palavras)

### O que falar:

Este slide é fundamental para a compreensão visual dos dados que veremos na segunda parte da apresentação.

    Observem as três representações de trajetória. À esquerda, o padrão **progressivo linear**: o espermatozoide avança rapidamente em linha relativamente reta. A trajetória curvilínea (linha mais fina) oscila pouco ao redor da trajetória média. Este é o padrão que associamos à capacidade de transporte no trato reprodutivo feminino — o espermatozoide que efetivamente atravessa o muco cervical e percorre o oviduto. No artigo de Gacem, essa é a subpopulação SP2 — a dominante, representando 38-42% do ejaculado.

    No centro, o padrão **progressivo não-linear**: alta velocidade curvilínea, mas com oscilação ampla da cabeça. A VCL é alta porque o caminho percorrido é longo — mas a VSL é baixa porque em linha reta o avanço é modesto. Este padrão pode representar dois estados fisiológicos diferentes: hiperativação espermática — que é um evento fisiológico necessário para a penetração da zona pelúcida — ou simplesmente um padrão de nado errático. A distinção entre hiperativação verdadeira e nado errático requer critérios adicionais como ALH alto combinado com VCL alta e LIN baixa, conforme definido por Mortimer e Mortimer em 2013. No artigo de Gacem, essa é a SP3.

    À direita, o padrão **lento/errático**: deslocamento mínimo, trajetória irregular. São espermatozoides com motilidade residual — podem estar em processo de morte celular, com dano mitocondrial ou de membrana. No artigo, é a SP1 — a subpopulação mais lenta e menos linear.

    A relevância biológica está na proporção: um ejaculado com 42% de SP2 (progressiva linear), 31% de SP3 (rápida não-linear) e 27% de SP1 (lenta) tem um perfil funcional muito diferente de um ejaculado com 15% de SP2, 25% de SP3 e 60% de SP1 — embora ambos possam ter a mesma "motilidade progressiva" quando avaliada de forma convencional. É exatamente por isso que a análise de subpopulações traz informação que a média não revela.


---

## Slide 07 — Fatores de Variação nos Resultados
**Seção:** Revisão de Literatura
**Tempo estimado:** 3.0 min (~389 palavras)

### O que falar:

Este é possivelmente o slide mais importante de toda a revisão, porque aborda um problema que muitos pesquisadores subestimam: a variabilidade técnica dos resultados CASA.

    **Taxa de frames:** Valverde e colaboradores, em 2019, demonstraram de forma elegante em varrões que a VCL é o parâmetro mais sensível ao frame rate, atingindo um ponto assintótico — ou seja, se estabilizando — apenas em torno de 212 fps. Abaixo disso, a VCL é progressivamente subestimada porque o software "perde" as oscilações rápidas da cabeça entre frames. Com 25 fps, essa subestimação pode chegar a 40%. Para motilidade simples (total e progressiva), 100 fps já é suficiente; mas para cinética precisa — especialmente VCL, ALH e BCF — são necessários no mínimo 212-250 fps. Bompart e colaboradores confirmaram achado semelhante em touros em 2019.

    **Câmara de contagem:** A profundidade da câmara determina o espaço vertical disponível para o espermatozoide. Uma câmara de 10 μm restringe mais o movimento vertical; uma de 20 μm dá mais liberdade. Isso afeta todos os parâmetros porque o CASA mede em 2D, mas o espermatozoide se move em 3D. Para equinos, a Spermtrack de 10 μm é o padrão utilizado pelo grupo de Barcelona.

    **Diluidor:** Cada diluidor altera a viscosidade, osmolaridade e composição do meio, afetando diretamente o comportamento cinético. Leite desnatado, INRA96, BotuSemen — cada um gera resultados diferentes para a mesma amostra. Como observam Amann e Waberski, nenhum diluidor reproduz as condições reais do trato reprodutivo feminino.

    **Temperatura:** A platina deve estar rigorosamente a 37°C. Uma queda de 2-3°C já é suficiente para reduzir significativamente a motilidade e as velocidades medidas.

    **Concentração:** Amostras muito concentradas geram tracking errors — o software confunde espermatozoides que se cruzam ou se aproximam. Para garanhões, o ideal é diluir a 40-50 milhões por mL antes da análise.

    **Software e operador:** Os thresholds de detecção (área mínima e máxima de pixels), o cutoff de VAP para classificar como "móvel" (geralmente ≥10 μm/s), a conectividade dos centroides e o número mínimo de frames rastreados — tudo isso varia conforme a configuração e afeta os resultados.

    A mensagem final é inescapável: dados de CASA são laboratório-específicos. Quando lemos um artigo com dados de CASA, a primeira coisa a verificar é: qual sistema, qual fps, qual câmara, qual diluidor, qual concentração, quais configurações de software. Sem essa informação, os números são essencialmente não-interpretáveis.


---

## Slide 08 — CASA × Fertilidade
**Seção:** Revisão de Literatura
**Tempo estimado:** 2.8 min (~366 palavras)

### O que falar:

Este slide aborda um tema que frequentemente gera debate em bancas e congressos: a relação entre os parâmetros CASA e a fertilidade real.

    A citação de Amann e Waberski é deliberadamente provocativa e categórica: é inapropriado perpetuar o mito de que a avaliação de motilidade pode predizer com precisão o potencial fértil. Essa afirmação, embora pareça radical, é sustentada por décadas de evidências.

    **Por que a predição é limitada?**

    Primeiro, a análise CASA é feita em condições completamente artificiais: câmara rasa de 10-20 μm (o espermatozoide se move em 3D no trato), meio de diluição que não reproduz o fluido do oviduto, temperatura controlada mas estática. O ambiente real do trato reprodutivo feminino é radicalmente diferente — com gradientes químicos, seleção mecânica pelo muco cervical, interações com o epitélio oviductal.

    Segundo, a fêmea não é um recipiente passivo. Ela seleciona ATIVAMENTE espermatozoides ao longo do trato — modificando atributos celulares, eliminando células defeituosas, reservando subpopulações no reservatório istmo-oviductal. O espermatozoide que performa bem no CASA pode não ser o selecionado in vivo.

    Terceiro — e isso é particularmente revelador — estudos em suínos demonstraram que o sêmen e o macho explicam MENOS DE 7% da variação total na taxa de parição. Os outros 93% vêm da fêmea, do manejo, do técnico de IA e de fatores ambientais. Broekhuijse e colaboradores, em 2012, confirmaram isso com dados de milhares de inseminações.

    **Então qual é o valor real do CASA?**

    Primeiro, controle de qualidade: o CASA é incomparável para avaliação objetiva e reprodutível. Ele elimina o viés do observador que contamina a avaliação subjetiva visual.

    Segundo, descarte de amostras ruins: PM abaixo de 40% no sêmen fresco de garanhão está associada a queda de fertilidade. PM acima de 45% no sêmen resfriado está associada a alta taxa de recuperação embrionária. Esses limiares são úteis para decisão clínica.

    Terceiro, identificação de fenótipos extremos: astenozoospermia total, oligozoospermia severa — nesses casos, o CASA é diagnóstico.

    Quarto, pesquisa: a análise de subpopulações, efeitos de criopreservação, suplementação antioxidante — o CASA é a ferramenta de escolha para comparar tratamentos e protocolos.

    Para uma banca de doutorado, é essencial demonstrar esse pensamento crítico: reconhecer o poder da ferramenta sem superestimar suas capacidades preditivas.


---

## Slide 09 — Subpopulações Espermáticas
**Seção:** Revisão de Literatura
**Tempo estimado:** 2.4 min (~313 palavras)

### O que falar:

O conceito de subpopulações espermáticas é o paradigma que transformou a análise CASA nas últimas duas décadas — e é o tema central do artigo que discutiremos na segunda parte.

    O ponto de partida é simples mas profundo: o ejaculado não é uma população homogênea de células equivalentes. Dentro de um mesmo ejaculado de um único garanhão, coexistem espermatozoides com padrões de movimento fundamentalmente diferentes — rápidos e lineares, rápidos e oscilantes, lentos e erráticos. Quando calculamos a média de VCL ou motilidade progressiva, mascaramos completamente essa heterogeneidade funcional.

    O trabalho pioneiro de Quintero-Moreno e colaboradores, publicado na Theriogenology em 2003, foi o primeiro a demonstrar formalmente a existência de subpopulações com motilidade específica em ejaculados de garanhões. Eles usaram análise multivariada — VARCLUS seguido de ANOVA — para identificar 5 clusters cinéticos distintos em 2649 observações espermáticas.

    A metodologia atual, refinada ao longo dos anos, segue dois passos: primeiro, PCA para redução de dimensionalidade — os 8 parâmetros cinéticos são condensados em 2-3 componentes principais independentes. PC1 geralmente carrega velocidades (VCL, VSL, VAP), PC2 carrega progressividade (LIN, STR, WOB) e PC3 carrega oscilação (BCF, ALH). Segundo, análise de cluster — Ward hierárquico seguido de K-means — para agrupar espermatozoides com padrões semelhantes.

    O consenso atual aponta para 2-4 subpopulações na maioria das espécies domésticas, embora esse número dependa criticamente da taxa de frames utilizada — como veremos no artigo de Gacem.

    A implicação prática é poderosa: dois ejaculados podem ter exatamente a mesma motilidade progressiva de 65%, mas distribuições de subpopulações completamente diferentes. Um pode ter 45% de SP2 (rápida linear — a "favorita" para fertilização) e o outro apenas 20% de SP2. A média não distingue esses dois ejaculados — a análise de subpopulações sim. Essa é a razão pela qual Amann e Waberski já em 2014 recomendavam que o software CASA deveria permitir agrupamento por atributos, não apenas reportar médias.


---

## Slide 10 — Perspectivas Futuras
**Seção:** Revisão de Literatura
**Tempo estimado:** 2.6 min (~335 palavras)

### O que falar:

Para fechar a revisão, vamos olhar para onde o CASA está indo — e o cenário é fascinante.

    **Inteligência artificial:** Sistemas baseados em deep learning estão revolucionando o CASA. Zhang e colaboradores em 2024 demonstraram a viabilidade de YOLOv8 combinado com DeepSORT para detecção e rastreamento multi-objeto de espermatozoides em tempo real — sem necessidade de câmaras de contagem especiais. O sistema AISA (Automated Intelligent Sperm Analyzer), publicado na Frontiers em 2023, usa redes neurais que substituem completamente a detecção baseada em área de pixels — eliminando artefatos ópticos que confundem os sistemas convencionais. A classificação automática de subpopulações sem supervisão humana já é uma realidade em laboratórios de pesquisa avançados.

    **Dispositivos portáteis:** O iSperm, baseado em iPad, foi validado para múltiplas espécies com coeficientes de concordância de 0.87-0.92 versus CASA desktop. O Ongo Vision é um dispositivo standalone que gera resultados comparáveis ao SCA/Microptic. Esses dispositivos viabilizam a espermatologia a campo e a telemedicina reprodutiva — o veterinário analisa no campo e envia dados para o especialista na universidade.

    **CASA 3D:** A holografia digital — DHM, Digital Holographic Microscopy — permite obter parâmetros 3D de espermatozoides vivos sem marcação fluorescente. Publicações em Scientific Reports (2022) e APL Photonics (2023) demonstraram reconstrução 3D de trajetória incluindo movimento flagelar. O sistema FAST de van der Horst (2020) também converte coordenadas X-Y do CASA-2D em tracks 3D. Isso elimina a limitação fundamental de analisar um movimento tridimensional em apenas dois eixos.

    **Integração com ômicas:** O futuro não é o CASA sozinho, mas o CASA integrado com proteômica e metabolômica. O conceito é usar o CASA como fenotipagem funcional e as ômicas como genotipagem molecular — cruzando os dados para identificar biomarcadores de fertilidade no plasma seminal. Isso representa uma mudança de paradigma: de "quanto ele nada" para "o que determina como ele nada".

    **Big Data:** A análise de grandes bancos de dados — milhares de ejaculados ao longo de anos — permitirá identificar tendências temporais, efeitos de raça, sazonalidade e interações complexas que estudos individuais não capturam.


---

## Slide 12 — A New Approach of Sperm MotilitySubpopulation Structurein Donkey and Horse
**Seção:** PARTE 2 — ARTIGO
**Tempo estimado:** 1.4 min (~182 palavras)

### O que falar:

Entramos agora na segunda parte: a apresentação detalhada do artigo original.

    O artigo intitulado "A New Approach of Sperm Motility Subpopulation Structure in Donkey and Horse" foi publicado na Frontiers in Veterinary Science em maio de 2021. O primeiro autor é Sabrina Gacem, e o autor sênior é Jordi Miró — ambos do Serviço de Reprodução Equina da Universidade Autônoma de Barcelona. Anthony Valverde, da Costa Rica, contribuiu com a análise estatística multivariada, e Carles Soler, da Universidade de Valência, é um dos desenvolvedores do sistema ISAS utilizado no estudo.

    Este artigo é particularmente relevante por três motivos: primeiro, é o primeiro estudo a utilizar 250 fps para comparar sistematicamente a cinética de jumentos e cavalos. Segundo, inclui comparação entre raças de cavalos — Espanhol e Árabe — o que raramente é feito na literatura. E terceiro, demonstra como a alta taxa de frames muda fundamentalmente a identificação de subpopulações espermáticas — encontrando 3 subpopulações consistentes onde estudos anteriores com fps menores encontravam 4 a 6.

    Vou apresentar seguindo a estrutura científica clássica: introdução, objetivos, material e métodos, resultados, discussão e conclusão.


---

## Slide 13 — Contextualização e Objetivos
**Seção:** Introdução · Objetivos
**Tempo estimado:** 2.3 min (~304 palavras)

### O que falar:

Na introdução, os autores constroem 5 argumentos que justificam o estudo:

    **1. Proximidade filogenética:** Cavalos e jumentos pertencem ao gênero Equus e compartilham ancestral comum de aproximadamente 4 milhões de anos. São geneticamente tão próximos que produzem híbridos viáveis — mulas (garanhão × jumenta) e bardotos (jumento × égua) — embora estéreis na grande maioria dos casos. Apesar dessa proximidade, a cinética espermática difere significativamente entre as espécies.

    **2. Seleção artificial:** A domesticação do cavalo e do jumento ocorreu há cerca de 5000 anos, mas com pressões de seleção muito diferentes. O cavalo sofreu seleção intensiva para desempenho atlético, morfologia e temperamento. O jumento sofreu seleção menos intensa, mantendo características mais próximas do tipo selvagem. Os autores argumentam que essa divergência de seleção pode ter impactado a espermatogênese e, consequentemente, a cinética espermática.

    **3. Limitação de fps:** A maioria dos estudos anteriores sobre subpopulações em garanhões utilizou taxas de 16 a 25 fps — o que, como vimos na revisão, subestima gravemente VCL e pode fragmentar artificialmente subpopulações. O próprio grupo de Gacem demonstrou em 2020 que o frame rate é o fator que mais influencia os valores cinéticos em garanhões.

    **4. Lacuna na literatura:** Não existia até então comparação de subpopulações entre jumento e cavalo utilizando alta taxa de frames. A literatura sobre cinética de jumento é particularmente escassa.

    **5. Diferenças entre raças:** Os autores incluíram duas raças de cavalos com histórias genéticas distintas — o Puro Raça Espanhol (PRE), resultado de cruzamentos europeus/orientais, e o Árabe, uma das raças mais puras geneticamente — para testar se a variação interraça é biologicamente significativa.

    Os 4 objetivos são claros e focados: caracterizar com 250 fps, definir subpopulações, comparar espécies e comparar raças. A hipótese implícita — embora não explicitamente declarada — é que a alta resolução temporal revelará diferenças não detectáveis com sistemas convencionais.


---

## Slide 14 — Delineamento Experimental
**Seção:** Material e Métodos
**Tempo estimado:** 3.2 min (~418 palavras)

### O que falar:

O delineamento experimental merece atenção detalhada porque a qualidade metodológica é um dos pontos fortes deste artigo.

    **Animais:** Foram utilizados 57 ejaculados frescos provenientes de três grupos: 26 ejaculados de 13 garanhões Puro Raça Espanhol, 16 ejaculados de 8 garanhões Árabes e 10 ejaculados de 5 jumentos Catalães, mais ejaculados extras totalizando 57. Todos os animais tinham entre 6 e 15 anos de idade e fertilidade previamente comprovada. Isso é importante porque elimina o viés de incluir animais subférteis que poderiam distorcer os padrões de motilidade. As coletas eram realizadas 3 vezes por semana ao longo do ano, garantindo que os animais estavam em regime estável de produção seminal.

    **Sistema CASA:** O sistema utilizado foi o ISAS versão 1.2, fabricado pela Proiser em Valência, Espanha. A câmera é a Proiser HS640m, uma câmera de alta velocidade dedicada. A câmara de contagem é a Spermtrack de 10 micrômetros de profundidade. O objetivo é de 10× com contraste de fase negativo. A platina aquecida mantém 37°C constantes.

    O ponto diferencial: **250 frames por segundo**. Isso significa que o intervalo entre frames é de apenas 4 milissegundos — permitindo capturar as oscilações mais rápidas da cabeça espermática. Compare com 25 fps (40 ms entre frames) ou 60 fps (16,7 ms) — a resolução temporal é 4 a 10 vezes maior.

    Foram analisados 10 campos não consecutivos por ejaculado, com mínimo de 500 espermatozoides. Essa amostragem garante representatividade da população espermática.

    **Preparo da amostra:** Diluição padronizada a 40 milhões/mL em leite desnatado com 4,9% de glicose. Cutoff de VAP ≥ 10 μm/s para classificar como móvel — espermatozoides com VAP abaixo disso são classificados como imóveis. Área de detecção entre 4 e 75 μm² — isso exclui debris menores que 4 μm² e aglomerados maiores que 75 μm².

    **Estatística:** Os dados foram primeiro testados para normalidade (Shapiro-Wilk) e homogeneidade de variâncias (Levene). A PCA utilizou o critério de Kaiser — apenas componentes com eigenvalue >1 foram retidos. O clustering foi feito em dois passos: primeiro Ward hierárquico para determinar o número ótimo de clusters, depois K-means para atribuir cada espermatozoide a uma subpopulação. Comparações entre grupos por GLM com correção de Bonferroni para múltiplas comparações. Significância em P < 0,05.

    **Ponto metodológico crucial:** A combinação específica de 250 fps com Spermtrack 10 μm foi validada previamente pelo mesmo grupo em dois artigos de 2020 — Gacem et al. para jumentos e Catalán et al. para garanhões — garantindo que as condições técnicas foram otimizadas ANTES do estudo principal. Isso demonstra rigor metodológico.


---

## Slide 15 — Jumento vs Cavalo
**Seção:** Resultados
**Tempo estimado:** 2.3 min (~296 palavras)

### O que falar:

Entrando nos resultados — e este é o slide com os dados brutos da comparação entre espécies.

    Observem a tabela com atenção. As colunas mostram Árabe, Espanhol, cavalo total e jumento. Os valores são média ± erro padrão da média.

    O resultado mais marcante está na coluna do jumento — destacada em teal. O espermatozoide do jumento foi significativamente superior ao do cavalo em praticamente TODOS os parâmetros cinéticos.

    **VCL:** 230 μm/s no jumento versus 225 no cavalo. A diferença em VCL parece discreta — apenas 5 μm/s — mas lembrem-se que VCL depende fortemente do fps e da espécie. O que chama atenção são os outros parâmetros.

    **VSL:** Aqui a diferença é grande — 78 μm/s no jumento contra 60 no cavalo. Isso é uma diferença de 30% na velocidade em linha reta. O jumento avança mais em distância efetiva.

    **LIN:** 34% no jumento versus 26% no cavalo. Oito pontos percentuais de diferença em linearidade é biologicamente significativo — significa que o jumento nada de forma substancialmente mais retilínea.

    **STR:** 43% versus 36%. Mesma tendência — o jumento é mais direto em sua trajetória.

    **ALH:** 1,41 μm no jumento versus 1,25 no cavalo. Interessantemente, o jumento tem maior amplitude de deslocamento lateral, mas mesmo assim mantém linearidade superior. Isso sugere um padrão de nado com batimento flagelar mais amplo porém mais eficiente em termos de progressão.

    **BCF:** Único parâmetro sem diferença significativa — 34 Hz no jumento versus 38 Hz no cavalo. A frequência de batimento cruzado é semelhante entre as espécies.

    A mensagem é clara: o espermatozoide do jumento combina velocidade com direção de forma mais eficiente que o do cavalo. Isso tem implicações práticas diretas: protocolos de criopreservação e avaliação seminal desenvolvidos para cavalos podem não ser diretamente aplicáveis a jumentos, e vice-versa.


---

## Slide 16 — Espanhol vs Árabe
**Seção:** Resultados
**Tempo estimado:** 1.9 min (~252 palavras)

### O que falar:

A comparação entre raças de cavalos trouxe resultados igualmente interessantes.

    O Puro Raça Espanhol apresentou maiores velocidades absolutas — VAP, VCL e BCF superiores aos do Árabe. O espermatozoide do PRE é fundamentalmente mais rápido.

    Já o Árabe mostrou tendência a maior linearidade — LIN e WOB ligeiramente superiores, embora a diferença não tenha atingido significância estatística em todos os parâmetros. O espermatozoide do Árabe é mais constante na direção.

    Os autores interpretam essas diferenças à luz da história genética de cada raça:

    O **Árabe** é reconhecido como uma das raças equinas mais ancestrais. Estudos de DNA mitocondrial — como os de Glazewska em 2010 e Royo em 2005 — demonstram grande uniformidade genética, indicando pouca hibridização ao longo dos séculos. A linhagem se manteve relativamente pura, especialmente nas populações do Oriente Médio. Essa homogeneidade genética pode se refletir numa cinética espermática mais uniforme e linear.

    O **Espanhol**, por outro lado, é descrito como o primeiro "warmblood" europeu — resultado de cruzamentos entre cavalos nativos da Península Ibérica e linhagens orientais introduzidas ao longo de séculos de comércio e conquista. Essa hibridização teria introduzido maior variabilidade genética — e potencialmente afetado a cinética espermática, produzindo espermatozoides mais rápidos porém mais heterogêneos em seus padrões de movimento.

    Um achado particularmente provocativo: os autores sugerem que a variação entre raças pode ser tão grande ou maior que a variação entre espécies. Isso tem implicações metodológicas diretas: estudos que agrupam "cavalos" como um único grupo sem considerar a raça podem estar mascarando variações biologicamente significativas.


---

## Slide 17 — Subpopulações Identificadas
**Seção:** Resultados
**Tempo estimado:** 2.6 min (~344 palavras)

### O que falar:

Este slide apresenta o resultado central do artigo: a identificação de 3 subpopulações espermáticas distintas em ambas as espécies.

    **SP1 — Lenta e não-linear:** Representa 28% no cavalo e 27-34% no jumento. São os espermatozoides com os menores valores de TODOS os parâmetros cinéticos — VCL baixa, VSL baixa, LIN baixa, BCF baixo. Biologicamente, são células com motilidade residual — podem estar em estágio avançado de deterioração mitocondrial, com dano de membrana, ou simplesmente em estágio final de seu ciclo de vida funcional. Clinicamente, é a subpopulação de menor interesse para fertilização.

    **SP2 — Rápida e linear:** A subpopulação DOMINANTE — 38% no cavalo e 42% no jumento. Apresenta os maiores valores de LIN, STR e VSL, combinados com VCL alta. É o perfil cinético ideal para transporte no trato reprodutivo: velocidade suficiente para atravessar barreiras anatômicas combinada com direção para alcançar o oócito. Biologicamente, esta é a subpopulação de maior interesse para a fertilização.

    **SP3 — Muito rápida e não-linear:** Representa 34% no cavalo e 31% no jumento. Tem a VCL mais alta de todas — acima de 280 μm/s no cavalo e 420 μm/s no jumento —, mas com LIN baixa e ALH e BCF altos. Esse padrão de alta velocidade com alta oscilação pode representar dois estados fisiológicos: hiperativação espermática genuína — que é um evento necessário para a penetração da zona pelúcida — ou simplesmente um nado errático rápido sem valor funcional. A distinção requer marcadores adicionais.

    Um dado particularmente revelador: mesmo comparando a MESMA subpopulação (SP2) entre espécies, a linearidade do jumento é superior — LIN de 50,3% versus 36,6% no cavalo. Isso confirma que a diferença de linearidade é intrínseca à espécie, não apenas um efeito da proporção das subpopulações.

    **Comparação com estudos anteriores:** Estudos com 16-25 fps identificaram 4 a 6 subpopulações. Com 250 fps, apenas 3 foram encontradas — porém com maior consistência biológica. Os autores argumentam que fps insuficiente gera ruído que fragmenta artificialmente subpopulações em clusters que não têm significado biológico real. A alta resolução temporal "limpa" esse ruído e revela a estrutura verdadeira.


---

## Slide 18 — Pontos Críticos da Discussão
**Seção:** Discussão
**Tempo estimado:** 2.5 min (~320 palavras)

### O que falar:

Na discussão, quatro pontos merecem destaque crítico:

    **1. O frame rate define a estrutura de subpopulações:** Este é talvez o achado metodológico mais impactante. Estudos anteriores com 16-25 fps encontraram 4 a 6 subpopulações. Com 250 fps, os autores encontraram apenas 3. A explicação é que fps insuficiente introduz ruído nas trajetórias — as oscilações entre frames são subestimadas ou distorcidas — e o clustering estatístico interpreta esse ruído como clusters biológicos distintos quando na verdade são artefatos. É uma analogia com resolução de imagem: uma foto de 1 megapixel mostra detalhes que não existem (pixelização) — uma foto de 100 megapixels mostra a realidade. Valverde e colaboradores demonstraram que o ponto assintótico de VCL — onde ela se estabiliza — é atingido apenas em ~212 fps. Abaixo disso, os dados cinéticos são fundamentalmente comprometidos.

    **2. Jumento é diferente do cavalo:** Essa diferença espécie-específica tem implicação prática direta. Centrais de reprodução de asininos que utilizam protocolos desenvolvidos para cavalos podem estar subotimizando seus resultados. Diluentes, curvas de refrigeração, crioprotectores — tudo pode precisar de ajuste para acomodar a cinética diferente do espermatozoide asinino.

    **3. Raça importa:** A divergência PRE vs Árabe reflete séculos de seleção artificial diferenciada. Os autores citam que o Árabe manteve DNA mitocondrial muito uniforme — evidência de pureza genética — enquanto o PRE é resultado de hibridização documentada desde o século XV. Essa divergência genética se manifesta na cinética espermática. O implicação é clara: estudos que agrupam "cavalos" sem especificar raça podem estar introduzindo variável de confusão significativa.

    **4. Limitação metodológica honesta:** Os autores reconhecem que avaliaram apenas sêmen fresco. A estrutura de subpopulações MUDA após criopreservação — a proporção de SP2 (a dominante) tende a diminuir e a de SP1 (lenta) tende a aumentar. Para nosso grupo no CERAN, que trabalha com criopreservação, isso é diretamente relevante: precisamos incluir análise de subpopulações nos nossos estudos comparativos pré e pós-criopreservação para capturar essa mudança na distribuição.


---

## Slide 19 — Conclusões — Gacem et al., 2021
**Seção:** Conclusões
**Tempo estimado:** 1.6 min (~204 palavras)

### O que falar:

Sintetizando as conclusões do artigo em 6 pontos:

    Primeiro: a utilização de 250 fps revelou trajetórias mais precisas e uma estrutura de 3 subpopulações com maior consistência biológica do que os 4-6 clusters encontrados por estudos anteriores com fps inferiores. A resolução temporal não é um detalhe técnico — ela muda fundamentalmente os resultados.

    Segundo: o espermatozoide do jumento é significativamente mais rápido E mais linear que o do cavalo. Essa diferença espécie-específica é clinicamente relevante para o manejo reprodutivo de equídeos.

    Terceiro: entre raças, o PRE é mais rápido e o Árabe mais linear — refletindo a divergência genética causada por séculos de seleção artificial diferenciada.

    Quarto: a SP2 é a subpopulação dominante em ambas as espécies, representando 38-42% do ejaculado, com perfil cinético de alta velocidade e alta linearidade — biologicamente a mais relevante para fertilização.

    Quinto: a estrutura geral de subpopulações é surpreendentemente similar entre espécie equina e asinina — 3 subpopulações com proporções comparáveis. A variação entre raças pode ser tão importante quanto a variação entre espécies.

    Sexto: a recomendação para estudos futuros é dupla — considerar o efeito da raça como variável nas análises CASA, e padronizar a taxa de frames em pelo menos 250 Hz para cinética precisa.


---

## Slide 20 — Obrigada!
**Seção:** PARTE 2 — ARTIGO
**Tempo estimado:** 1.2 min (~152 palavras)

### O que falar:

Muito obrigada pela atenção!

    Resumindo o que percorremos: na primeira parte, vimos como o CASA evoluiu desde Leeuwenhoek até sistemas com inteligência artificial. Compreendemos os 8 parâmetros cinéticos — VCL, VSL, VAP, LIN, STR, WOB, ALH e BCF — e como eles se relacionam com o movimento real do espermatozoide. Discutimos os fatores que afetam os resultados e a relação complexa entre CASA e fertilidade. E vimos como o paradigma de subpopulações mudou a forma como interpretamos dados de motilidade.

    Na segunda parte, o artigo de Gacem e colaboradores demonstrou que o uso de 250 fps revela uma estrutura de 3 subpopulações consistentes, que o espermatozoide do jumento é mais rápido e linear que o do cavalo, e que diferenças entre raças são biologicamente significativas.

    As referências estão no slide. O artigo do Gacem está disponível em acesso aberto na Frontiers in Veterinary Science.

    Estou à disposição para perguntas e discussão. Obrigada!

