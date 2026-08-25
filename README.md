# Repositório de dados públicos portugueses

Este repositório é um agregador de dados públicos, ou semi públicos, de entidades Portuguesas.

## Regras de contribuição

Se quiseres contribuir, corrigir algo, ou até recomendar melhorias, cria um pull request. Caso queiras adicionar alguma entrada nova, garante que segues a estrutura usada. Cada entrada deverá conter:
- Nome (nome e ligação)
- Info (curta explicação)
- Categoria (Governo, Saúde, Meteorologia, Transportes, Media, Outros)
- Tipo (API, RSS, Open Data)
- Spec (link, com ícone, para a spec se aplicável)
- Docs (link, com ícone, para documentação se aplicável)

### Como posso começar?

1. Faz fork do projeto (<https://github.com/devpt-org/public-api-portugal/fork>)
2. Cria uma branch para a tua feature (`git checkout -b add/bank-public-api`)
3. Faz commit das tuas alterações (`git commit -am 'Add some bank public api'`)
4. Faz push da tua branch para master (`git push origin add/bank-public-api`)
5. Cria um novo Pull Request

## Conteúdos
- [Governo](#governo)
- [Justiça](#justiça)
- [Saúde](#saúde)
- [Educação](#educação)
- [Meteorologia](#meteorologia)
- [Transportes](#transportes)
- [Media](#media)
- [Banking](#banking)
- [Outros](#outros)

## Dados

### Governo

| Nome         |  Info  | Tipo | Spec | Docs |
| :----------- | :----- | :--: | :--: | :--: |
| [Dados Gov](https://dados.gov.pt/) | Dados abertos em Portugal | API | [✅](https://dados.gov.pt/api/1/swagger.json) | [✅](https://dados.gov.pt/pt/recursos/desenvolvimento/tutorial-api)
| [GEO PT API](https://geoapi.pt) | Dados gratuitos e abertos para Portugal sobre regiões administrativas oficiais, georreferenciação, censos e códigos postais | API | [✅](https://geoapi.pt/docs/) | [✅](https://geoapi.pt/docs/)
| [INE](https://www.ine.pt/xportal/xmain?xpid=INE&xpgid=ine_api_v2&xlang=PT) | Base de dados de difusão do INE | API | — | [✅](https://www.ine.pt/ngt_server/attachfileu.jsp?look_parentBoui=322762582&att_display=n&att_download=y)
| [Lisboa Aberta](https://lisboaaberta.cm-lisboa.pt/index.php/pt/) | Dados abertos de Lisboa | Open Data | — | [✅](https://lisboaaberta.cm-lisboa.pt/index.php/pt/faqs) |
| [NIF](https://www.nif.pt/api/) | Validação programatica de NIF | API | — | [✅](https://www.nif.pt/api/)
| [Turismo de Portugal](https://dadosabertos.turismodeportugal.pt/) | Dados sobre informação turística | Open Data | [✅](https://dadosabertos.turismodeportugal.pt/api/feed/definition/) | [✅](https://dadosabertos.turismodeportugal.pt/)
| [Cascais Data](https://data.cascais.pt/geral/dados/dados-abertos) | Portal de dados abertos de Cascais | Open Data | [✅](https://dadosabertos.cascais.pt/pt_PT/dataset/) | [✅](https://dadosabertos.cascais.pt/pt_PT/dataset/)
| [Dados Abertos de Guimarães](https://sig.cm-guimaraes.pt/dadosabertos/#one) | Portal de dados abertos de Guimarães | Open Data | [✅](https://sig.cm-guimaraes.pt/cgi-bin/wms/PDM?SERVICE=WMS&REQUEST=GetCapabilities) | [✅](https://sig.cm-guimaraes.pt/dadosabertos/downloads/PDM_wms.pdf)
| [PORDATA](https://www.pordata.pt/) | Estatísticas sobre Municípios, Portugal e Europa | Open Data | — | [✅](https://www.pordata.pt/)
| [Dados Abertos do Porto](https://opendata.porto.digital/dataset/) | Portal de dados abertos do Porto | Open Data | [✅](https://opendata.porto.digital/api/3) | [✅](https://opendata.porto.digital/api/3)
| [Lisboa GeoDados](https://geodados-cml.hub.arcgis.com/) | Plataforma de dados abertos georreferenciados da Câmara Municipal de Lisboa | Open Data | [✅](https://geodados-cml.hub.arcgis.com/api/feed/dcat-us/1.1.json) | [✅](https://geodados-cml.hub.arcgis.com/)
| [Águeda Aberta](https://dadosabertos.cm-agueda.pt/dataset?_res_format_limit=0) | Portal de dados abertos de Águeda | Open Data | [✅](https://dadosabertos.cm-agueda.pt/api/3) | [✅](https://dadosabertos.cm-agueda.pt/api/3)
| [JRC Data Catalogue](https://data.jrc.ec.europa.eu/dataset?q=portugal) | Catálogo de dados da União Europeia sobre Portugal | Open Data | [✅](https://ec-jrc.github.io/dcat-ap-jrc/) | [✅](https://data.jrc.ec.europa.eu/swagger)
| [Faltas no Parlamento](https://labs.tretas.org/attendance/index/) | Portal contendo as faltas dos deputados a sessões plenárias do Parlamento | Open Data | — | [✅](https://labs.tretas.org/attendance/index/)
| [RNT - Consulta ao Registo](https://rnt.turismodeportugal.pt/) | Informação dos empreendimentos e empresas do turismo, agentes de animação turística e agências de viagens e turismo | Open Data | — | [✅](https://rnt.turismodeportugal.pt/rnt/Termosecondicoes.aspx)
| [Portal Base](https://www.base.gov.pt/base4) | Portal de contratos públicos  | Open Data | [✅](https://www.base.gov.pt/APIBase2) | [✅](https://www.base.gov.pt/Base4/pt/documentacao/formas-de-obter-dados-sobre-os-contratos-publicos/)
| [Portal do Clima](http://rna2100.portaldoclima.pt/pt/) | Dados de clima | Open Data | — | [✅](http://rna2100.portaldoclima.pt/pt/)
| [fogos.pt](https://fogos.pt) | Lista de fogos e estatisticas | API | [✅](https://api.fogos.pt/docs/) | [✅](https://www.fogos.pt/pt/api) |

### Justiça

| API         |  Info | Tipo | Spec | Docs |
| ----------- | ----- | :--: | :--: | :--: |
| [Dados na Justiça](https://dados.justica.gov.pt/dataset) | Dados do Ministério da Justiça | Open Data | [✅](https://dados.justica.gov.pt/api/action/package_search?q=justica) | [✅](https://dados.justica.gov.pt/dataset)

### Saúde

| Nome         |  Info  | Tipo | Spec | Docs |
| :----------- | :----- | :--: | :--: | :--: |
| [Transparência SNS v2](https://transparencia.sns.gov.pt/api/v2/console/) | Versão 2 da API de Dados Abertos do SNS | API | [✅](https://transparencia.sns.gov.pt/api/v2/swagger.json) | [✅](https://transparencia.sns.gov.pt/api/v2/console/) 

### Educação

| Nome         |  Info  | Tipo | Spec | Docs |
| :----------- | :----- | :--: | :--: | :--: |
| [FenixEdu IST](https://fenixedu.org/dev/api/) | Plataforma FenixEdu do Instituto Superior Técnico | API | — | [✅](https://fenixedu.org/dev/api/)
| [Salários dos Professores](https://github.com/glima93/teacher_salaries_PT) | Dados sobre os salários dos professores em Portugal entre 2006 e 2018 | Open Data | — | [✅](https://github.com/glima93/teacher_salaries_PT/blob/master/README.md)
| [INESCTEC](https://rdm.inesctec.pt/dataset?_res_format_limit=0) | Dados produzidos ou usados pelos investigadores do INESCTEC | Open Data | [✅](https://rdm.inesctec.pt/api/3) | [✅](https://rdm.inesctec.pt/dataset?_res_format_limit=0)
| [Biblioteca Nacional de Portugal](https://opendata.bnportugal.gov.pt/) | Catálogo bibliográfico da Biblioteca Nacional de Portugal, da Base Nacional de Dados Bibliográficos - PORBASE, a Bibliografia Nacional Portuguesa (desde 1931) e Biblioteca Nacional Digital | Open Data | [✅](https://opendata.bnportugal.gov.pt/oai-pmh.htm) | [✅](https://opendata.bnportugal.gov.pt/)

### Meteorologia

| Nome         |  Info  | Tipo | Spec | Docs |
| :----------- | :----- | :--: | :--: | :--: |
| [IPMA](https://api.ipma.pt/) | Dados meteorológicos e oceanográficos | API | [✅](https://api.ipma.pt/open-data/) | [✅](https://api.ipma.pt/)
| [MeteoAlarm](https://api.meteoalarm.org/edr/v1) | Alertas meteorológicos para toda a Europa | API | [✅](https://api.meteoalarm.org/edr/v1/api) | [✅](https://api.meteoalarm.org/edr/v1) |

### Transportes

| Nome         |  Info  | Tipo | Spec | Docs |
| :----------- | :----- | :--: | :--: | :--: |
| [EMEL](https://dados.emel.pt/dataset/) | Dados abertos da EMEL | Open Data | [✅](https://dados.emel.pt/pt_BR/api/1/util/snippet/api_info.html?resource_id=7da833e7-ad6e-4594-9ce9-78ef4c1128cd) | [✅](https://dados.emel.pt/dataset/)
| [Metro de Lisboa](https://api.metrolisboa.pt/store/apis/info?name=EstadoServicoML&version=1.0.1&provider=admin) | Conjunto de APIs disponibilizadas pelo ML | API | [✅](https://api.metrolisboa.pt/store/api-docs/admin/EstadoServicoML/1.0.1?gwType=undefined&gwName=undefined) | [✅](https://api.metrolisboa.pt/store/apis/info?name=EstadoServicoML&version=1.0.1&provider=admin#tab2)
| [Transportes Urbanos de Braga](https://tub.pt/downloads/) | Portal de dados da TUB (Transportes Urbanos de Braga) | Open Data | [✅](https://gtfs.org/documentation/schedule/reference/) | [✅](https://dados.gov.pt/en/datasets/gtfs-transportes-urbanos-de-braga)
| [Carris Metropolitana](https://api.carrismetropolitana.pt/v2/) | Carris Metropolitana Schedules API | API | [✅](https://github.com/carrismetropolitana/api/blob/v2/README.md) | [✅](https://backoffice.carrismetropolitana.pt/opendata/)
| [Sociedade de Transportes Colectivos do Porto](https://github.com/sgtpepperpt/stcp-api) | Dados sobre a rede da STCP e passagem de autocarros em tempo real | API | [✅](https://github.com/sgtpepperpt/stcp-api/blob/master/README.md) | [✅](https://github.com/sgtpepperpt/stcp-api/blob/master/examples.md)


### Media

| Nome         |  Info  | Tipo | Spec | Docs |
| :----------- | :----- | :--: | :--: | :--: |
| [Público](https://www.publico.pt/api/list/ultimas) | Dados do Público | API | — | —
| [Jornal de Notícias](http://feeds.jn.pt/JN-Ultimas) | Dados do Jornal de Notícias | RSS | — | —
| [ECO](https://eco.sapo.pt/wp-json/eco/v1/items) | Dados do ECO | API | — | —
| [Diário de Notícias](http://feeds.dn.pt/DN-Ultimas) | Dados do Diário de Notícias | RSS | — | —
| [O Jogo](http://feeds.ojogo.pt/OJ-Ultimas) | Dados d'Jogo | RSS | — | —
| [Dinheiro Vivo](http://feeds.dinheirovivo.pt/DV-Ultimas) | Dados do Dinheiro Vivo | RSS | — | —
| [TSF](http://feeds.tsf.pt/TSF-Ultimas) | Dados do TSF | RSS | — | —
| [RTP Notícias](https://www.rtp.pt/noticias/rss/) | Dados da RTP Notícias | RSS | — | [✅](https://www.rtp.pt/noticias/rss/)
| [Renascença](https://rr.pt/rss.aspx) | Dados da Renascença | RSS | — | [✅](https://rr.pt/rss.aspx)

### Banking

| Nome         |  Info  | Tipo | Spec | Docs |
| :----------- | :----- | :--: | :--: | :--: |
| [SIBS API Market](https://developer.sibsapimarket.com/sandbox/product) | Diretório de APIs de Contas, Multibanco, Pagamentos e Informações Bancárias | API | [✅](https://developer.sibsapimarket.com/sandbox/product) | [✅](https://developer.sibsapimarket.com/sibs-qly/apimarket/start)
| [Banco de Portugal](https://bpstat.bportugal.pt/data/docs) | Acesso aberto a estatísticas e metadados do portal de estatística do Banco de Portugal | API | [✅](https://bpstat.bportugal.pt/data/docs?format=openapi) | [✅](https://bpstat.bportugal.pt/data/docs)

### Outros

| Nome         |  Info  | Tipo | Spec | Docs |
| :----------- | :----- | :--: | :--: | :--: |
| [arquivo.pt](https://arquivo.pt/) | Acesso a conteúdo histórico da Web | Open Data | — | [✅](https://github.com/arquivo/pwa-technologies/wiki/Arquivo.pt-API)
| [Feriados Portugueses](http://services.sapo.pt/Metadata/Contract/Holiday?culture=PT) | Lista de feriados nacionais, regionais e municipais. Suporta o cálculo dos feriados para os anos entre 1582 e 2299 | API | [✅](https://services.sapo.pt/Metadata/Contract/Holiday?culture=PT) | —
| [ArcGis](https://services.arcgis.com/CCZiGSEQbAxxFVh3/ArcGIS/rest/services) | Repositório Arcgis do Estado Português, inclui dados COVID-19, incêndios, combustível, entre outros | API | [✅](https://services.arcgis.com/CCZiGSEQbAxxFVh3/ArcGIS/rest/services?f=pjson) | [✅](https://services.arcgis.com/CCZiGSEQbAxxFVh3/ArcGIS/rest/services)
| [itjobs.pt](https://www.itjobs.pt/api/) | Anúncios de emprego na área de Tecnologias de Informação em Portugal.| API | [✅](https://www.itjobs.pt/api/docs) | [✅](https://www.itjobs.pt/api/docs)
| [e-redes](https://e-redes.opendatasoft.com/pages/homepage/) | Repositório de dados abertos sobre a empresa portuguesa e-redes (setor elétrico).| Open Data | [✅](https://e-redes.opendatasoft.com/api/explore/v2.1/swagger.json) | [✅](https://e-redes.opendatasoft.com/api-console/explore/v2.1/?flg=en-gb)
