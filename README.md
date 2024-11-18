# NEWS, OPINION, AND CONSPIRACY ARTICLES DATASET

from the paper

The Thin Line Between Conspiracy Theories and Opinion: Why Humans and AI Struggle to Differentiate Them

by Paula Carvalho, Danielle Caled, and Mário J. Silva


Please cite as:

> Carvalho, P. Caled, D., & M. J. Silva (in press). The Thin Line Between Conspiracy Theories and Opinion: Why Humans and AI Struggle to Differentiate Them. International Journal of Communication`



## Description

This dataset comprises 81 articles sourced from 23 Portuguese mainstream and non-mainstream media outlets (see Table 1). The dataset includes:
- 27 news articles (118,921 tokens)
- 27 opinion pieces (164,716 tokens)
- 27 conspiracy narratives (374,306 tokens)

Each trio in the corpus, consisting of one news article, one opinion piece, and one conspiracy narrative, covers semantically related topics. Apart from a single news article, reporting an event occurred in 2000, all articles were published during the period spanning from 2020 to 2022, aiming to maximize coverage of events related to the topics. Furthermore, this timeframe aligns with the collection period of the MINT corpus, which was used to train [InfoRadar](https://inforadar.inesc-id.pt) (Caled et al., 2024).

Conspiracy articles were curated from five websites previously identified as prominent disseminators of conspiracy theories (Caled, Carvalho, & Silva, 2022). Each article was validated by the research team in accordance with Uscinski’s (2018) definition of conspiracy theories: narratives explaining historical, ongoing, or future events by attributing primary causality to a secretive group of powerful individuals (the conspirators) acting covertly for personal gain at the expense of collective welfare .

Table 1. Distribution of the Articles’ Sources by Category.
|    Category      |    Media Outlet                                                                                                                                                                                                                                                                                 |    Mainstream (M) / Non-Mainstream (NM)                                                                                                           |    # Articles                                                                                                                                           |    #Tokens    |
|----------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------|
|    News          |    Diário de   Notícias<br>   CNN Portugal<br>   Expresso<br>   Jornal de Negócios<br>   Jornal de Notícias<br>   Observador<br>   Público<br>   RTP Notícias<br>   TSF<br>   Visão                                                                     |    M<br>   M<br>   M<br>   M<br>   M<br>   M<br>   M<br>   M<br>   M<br>   M                                            |    8<br>   1<br>   1<br>   3<br>   1<br>   3<br>   5<br>   2<br>   2<br>   1                                        |    <br>                      |
|    Subtotal      |                                                                                                                                                                                                                                                                                                     |    <br>                                                                                                                                                         |    27                                                                                                                                                   |    118,921               |
|    Opinion       |    Diário de Notícias<br>   Esquerda Net<br>   Expresso<br>   Jornal Inevitável<br>   Jornal Médico<br>   Observador<br>   Página Um<br>   Público<br>   Rádio Renascença<br>   Sapo Atualidade<br>   Sic Notícias<br>   Sol<br>   Visão    |    M<br>   NM<br>   M<br>   NM<br>   NM<br>   M<br>   NM<br>   M<br>   M<br>   M<br>   M<br>   M<br>   M    |    3<br>   1<br>   3<br>   1<br>   2<br>   1<br>   1<br>   1<br>   2<br>   1<br>   2<br>   2<br>   7    |    <br>                      |
|    Subtotal      |                                                                                                                                                                                                                                                                                                     |    <br>                                                                                                                                                         |    27                                                                                                                                                   |    164,716               |
|    Conspiracy    |    Casa das Aranhas<br>   O Diário de um ET<br>   Portugal Misterioso<br>   Resisitir.info<br>   O Evento                                                                                                                                                                 |    NM<br>   NM<br>   NM<br>   NM<br>   NM                                                                                                   |    3<br>   8<br>   3<br>   8<br>   5                                                                                                    |    <br>                      |
|    Subtotal      |                                                                                                                                                                                                                                                                                                     |                                                                                                                                                                 |    27                                                                                                                                                   |    374,306               |
|    Total         |                                                                                                                                                                                                                                                                                                     |                                                                                                                                                                 |    81                                                                                                                                                   |    657,943               |

## Links to Collected Articles

The collected articles can be accessed at the following links:

**News**
- https://www.jornaldenegocios.pt/economia/detalhe/biden-considera-possivel-recessao-muito-ligeira-nos-estados-unidos
- https://www.tsf.pt/portugal/sociedade/como-se-explicam-os-diferentes-efeitos-secundarios-das-vacinas-contra-a-covid-13486959.html
- https://www.dn.pt/mundo/bill-gates-os-proximos-quatro-a-seis-meses-podem-ser-os-piores-da-pandemia--13134974.html
- https://www.dn.pt/internacional/zelensky-alvo-de-tres-tentativas-de-assassinato-ordenadas-por-moscovo-14648367.html
- https://www.publico.pt/2022/05/18/mundo/noticia/suecia-finlandia-entregam-pedidos-adesao-nato-2006611
- https://www.dn.pt/internacional/ucrania-russia-anuncia-inicio-da-retirada-militar-de-kherson-15338513.html
- https://visao.sapo.pt/atualidade/mundo/guerra-na-ucrania/2022-03-16-ucrania-africa-sofre-fortes-consequencias-economicas-com-invasao-russa/
- https://observador.pt/2021/12/16/covid-19-agencia-europeia-do-medicamento-aprova-dois-novos-tratamentos/
- https://cnnportugal.iol.pt/guerra/ucrania/guerra-da-desinformacao-como-a-palavra-nazi-contaminou-os-russos-contra-a-ucrania/20220702/62c0a72e0cf26256cd2bc9ce
- https://www.jornaldenegocios.pt/negocios-iniciativas/detalhe/alteracoes-climaticas-agravaram-se-e-generalizaram-se-a-todo-o-planeta
- https://observador.pt/2021/12/13/doencas-respiratorias-nao-covid-19-mataram-36-pessoas-por-dia-em-2019-aponta-estudo/
- https://www.rtp.pt/noticias/mundo/com-visoes-diferentes-berlim-e-pequim-propoem-se-desenvolver-cooperacao_n1444777
- https://www.publico.pt/2020/07/23/ciencia/noticia/teste-sangue-detecta-cancro-ate-quatro-anos-diagnostico-convencional-1925486
- https://expresso.pt/sociedade/coronavirus/2020-10-25-Havera-uma-vacina-segura-e-eficaz-contra-a-covid-19--Saberemos-isso-no-inicio-de-dezembro
- https://www.rtp.pt/noticias/mundo/novo-estudo-sobre-a-origem-da-covid-19-aponta-para-mercado-de-wuhan_n1364302
- https://www.publico.pt/2021/03/19/mundo/noticia/300-criancas-abusadas-sexualmente-membros-clero-colonia-1955236
- https://www.publico.pt/2000/12/05/portugal/noticia/jornalista-da-tvi-miguel-ganhao-pereira-morreu-na-noite-passada-2506
- https://www.jornaldenegocios.pt/sustentabilidade/social/detalhe/cidades-portuguesas-estao-a-transformar-se-em-smart-cities
- https://observador.pt/2022/01/20/acucares-adicionados-diminuem-a-capacidade-antioxidante-na-diabetes/
- https://www.dn.pt/internacional/bolsonaro-irrita-eua-por-visitar-putin-em-plena-crise-na-ucrania-14559114.html
- https://www.dn.pt/internacional/pelo-menos-oito-mortos-em-festival-do-rapper-travis-scott-14293789.html
- https://www.dn.pt/internacional/funcionario-de-laboratorio-de-wuhan-pode-ter-sido-o-primeiro-infetado-por-covid-19-14029792.html
- https://www.publico.pt/2022/09/20/ciencia/noticia/dgs-publica-norma-vacinacao-deixa-pessoas-multiplos-parceiros-sexuais-2021195
- https://www.jn.pt/mundo/ele-ganhou-porque-a-eleicao-foi-manipulada-trump-admite-que-perdeu-13037860.html
- https://www.dn.pt/sociedade/negacionistas-ha-centenas-de-policias-que-se-recusam-a-ser-vacinados-14359219.html
- https://www.dn.pt/internacional/elon-musk-altera-posicao-e-vai-continuar-a-financiar-a-rede-starlink-15258195.html
- https://www.tsf.pt/mundo/vacina-da-moderna-contra-a-variante-omicron-aprovada-no-reino-unido-15093406.html
- https://rr.sapo.pt/artigo/francisco-sarsfield-cabral/2022/10/16/o-fmi-e-portugal/303617/

**Opinion**
- https://www.dn.pt/opiniao/vacina-contra-a-covid-19-uma-obrigacao-coletiva-solidaria-13627624.html
- https://visao.sapo.pt/opiniao/ponto-de-vista/cronicas-d-c/2020-10-26-teorias-da-constipacao/
- https://www.publico.pt/2022/06/07/opiniao/opiniao/guerra-ucrania-paz-narrativas-2009249
- https://expresso.pt/opiniao/2022-07-05-Sao-as-armas.-E-a-economia-estupido-034286a3
- https://sicnoticias.pt/especiais/guerra-russia-ucrania/2022-10-20-Compreender-o-conflito-defender-Kherson-ou-inunda-la--800bf139
- https://visao.sapo.pt/opiniao/bolsa-de-especialistas/2022-04-21-fome-e-alteracoes-climaticas-em-tempos-de-guerra/
- https://ionline.sapo.pt/artigo/731260/portugal-o-acelerador-da-vacinacao-do-espaco-lusofono-?seccao=Opiniao_i&fbclid=IwAR1zanjbjLczRXHzKs_oD9byjSUyxMyPZ8HGYOQShzzLjveR8zoVs0CyH94
- https://visao.sapo.pt/opiniao/editorial/2022-05-12-afinal-quem-e-nazi-editorial-de-mafalda-anjos/
- https://visao.sapo.pt/opiniao/editorial/2018-08-09-aquecimento-global-agora-e-connosco/
- https://www.jornalmedico.pt/opiniao/42625-rita-boaventura-controlo-de-asma-e-gestao-de-crises.html
- https://sicnoticias.pt/especiais/guerra-russia-ucrania/2022-12-30-O-que-fica-de-2022-a-Guerra-que-pos-quase-tudo-em-causa-05d7d602
- https://visao.sapo.pt/opiniao/2022-05-13-afinal-o-que-e-o-cancro/
- https://visao.sapo.pt/opiniao/ponto-de-vista/linhas-direitas/2021-08-30-sera-que-chega-a-palavra-de-fauci/
- https://www.jornalmedico.pt/opiniao/39777-covid-19-a-ponta-do-iceberg.html
- https://sol.sapo.pt/artigo/777670/o-artigo-que-nunca-quis-escrever
- https://visao.sapo.pt/opiniao/ponto-de-vista/2022-11-07-suicidio-a-minha-historia-os-nossos-numeros-e-muitos-factos-assustadores/
- https://expresso.pt/opiniao/2022-11-11-8-mil-milhoes-e-agora--609a22bc
- https://lifestyle.sapo.pt/saude/peso-e-nutricao/artigos/a-culpa-e-do-pao
- https://rr.sapo.pt/artigo/francisco-sarsfield-cabral/2022/02/18/putin-e-a-extrema-direita/272966/
- https://24.sapo.pt/atualidade/artigos/travis-scott-a-tragedia-podia-ter-sido-evitada
- https://sol.sapo.pt/artigo/724933/covid-19-a-polemica-missao-a-wuhan-da-oms
- https://www.esquerda.net/opiniao/homossexuais-o-retrato-diabolico-e-doente/81050
- https://expresso.pt/opiniao/2020-12-01-EUA-quando-o-basico-ja-e-bom
- https://paginaum.pt/2022/02/11/o-jornalismo-e-a-banalizacao-do-extremismo/
- https://www.dn.pt/opiniao/elon-musk-e-a-liberdade-14822688.html
- https://lifestyle.sapo.pt/saude/noticias-saude/artigos/um-esforco-da-comunidade-cientifica-global-na-obtencao-da-imunidade-a-opiniao-de-germano-de-sousa

**Conspiracy**
- https://resistir.info/m_hudson/hudson_09nov22.html
- https://resistir.info/pandemia/engdahl_27mai21.html
- https://resistir.info/pandemia/agenda_bill_gates.html
- https://resistir.info/ucrania/assassinatos.html
- https://odiariodeumet.blogs.sapo.pt/a-finlandia-e-a-suecia-vao-entrar-para-370291
- https://resistir.info/russia/orlov_11nov22.html
- https://odiariodeumet.blogs.sapo.pt/a-ucrania-vai-exportar-graos-379523
- https://odiariodeumet.blogs.sapo.pt/agencia-europeia-do-medicamento-e-uma-359402
- https://www.oevento.pt/2022/03/12/aniron-marco-update/
- https://www.oevento.pt/2019/01/26/as-alteracoes-climaticas-e-o-aquecimento-global-sao-um-embuste/
- https://odiariodeumet.blogs.sapo.pt/beber-leite-com-alho-previne-e-cura-438623
- https://resistir.info/p_escobar/berlim_pequim_04nov22.html
- https://odiariodeumet.blogs.sapo.pt/detecao-precoce-de-doencas-e-crime-e-108033
- https://resistir.info/pandemia/fauci_28dez21.html
- https://casadasaranhas.com/2022/01/05/fomos-enganados-sobre-a-pandemia-agora-vamos-avancar-ou-amuar/
- https://www.oevento.pt/2021/02/09/freiras-venderam-criancas-orfas/
- https://casadasaranhas.com/2020/07/09/jornalista-que-investigou-camarate-atirou-se-da-ponte-e-foi-literalmente-apagado-da-internet/
- https://odiariodeumet.blogs.sapo.pt/nao-existe-excesso-populacional-mas-sim-372867
- https://odiariodeumet.blogs.sapo.pt/o-acucar-branco-refinado-nao-faz-mal-431712
- https://odiariodeumet.blogs.sapo.pt/o-bolsonaro-e-o-putin-estao-combinados-380493
- https://portugalmisterioso.blogspot.com/2021/11/ritual-satanico-em-concerto-de-travis.html
- https://casadasaranhas.com/2021/03/14/sera-mesmo-que-o-corona-virus-nao-vem-de-um-laboratorio/
- https://www.oevento.pt/2022/06/04/aniron-junho-update/
- https://www.oevento.pt/2020/10/01/trump-vence-biden-clone/
- https://portugalmisterioso.blogspot.com/2021/11/perseguicao-nao-vacinados-ja-comecou.html
- https://www.resistir.info/varios/twitter_musk_01mai22.html
- https://portugalmisterioso.blogspot.com/2022/01/o-que-contem-as-vacinas-para-o-covid-19.html

## References
- Caled, D., Carvalho, P., Sousa, F., & Silva, M. (2024). DOMAIN: Explainable credibility assessment tools for empowering online readers coping with misinformation. ACM Transactions on the Web. doi: 10.1145/3696472.
- Caled, D., Carvalho, P., & Silva, M. J. (2022). MINT-Mainstream and Independent News Text Corpus. In International Conference on Computational Processing of the Portuguese Language (pp. 26-36). Cham: Springer International - Publishing. doi: 10.1007/978-3-030-98305-5_3.
- Carvalho, P. Caled, D., & M. J. Silva (in press). The Thin Line Between Conspiracy Theories and Opinion: Why Humans and AI Struggle to Differentiate Them. International Journal of Communication.
- Uscinski, J. (2018). The study of conspiracy theories. Argumenta, 3(2), 233–245.
