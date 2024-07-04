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
| [Dados Gov](https://dados.gov.pt/pt/docapi/) | Dados abertos em Portugal | API | [✅](https://dados.gov.pt/api/1/swagger.json) | [✅](https://dados.gov.pt/pt/docapi/)
| [GEO PT API](https://github.com/jfoclpf/geoptapi) | Dados gratuitos e abertos para Portugal sobre regiões administrativas oficiais, georreferenciação, censos e códigos postais | API | [✅](https://github.com/jfoclpf/geoapi.pt/blob/main/src/public/openapi.yaml) | [✅](https://docs.geoapi.pt/)
| [INE](https://www.ine.pt/xportal/xmain?xpid=INE&xpgid=ine_api&INST=322751522&xlang=pt) | Base de dados de difusão do INE | API | ❌ | [✅](https://www.ine.pt/ngt_server/attachfileu.jsp?look_parentBoui=322762582&att_display=n&att_download=y)
| [Lisboa Aberta](http://lisboaaberta.cm-lisboa.pt/index.php/pt/desenvolvedores) | Dados abertos de Lisboa | API | ⁉️ | ⁉️ |
| [NIF](https://www.nif.pt/api/) | Validação programatica de NIF | API | ❌ | ❌
| [Turismo de Portugal](https://dadosabertos.turismodeportugal.pt/) | Dados sobre informação turística | Open Data | ⁉️ | ⁉️
| [Cascais Data](https://data.cascais.pt/pt-pt/node/253) | Portal de dados abertos de Cascais | Open Data | ⁉️ | ⁉️
| [Dados Abertos de Guimarães](https://sig.cm-guimaraes.pt/dadosabertos/#one) | Portal de dados abertos de Guimarães | Open Data | ⁉️ | ⁉️
| [PORDATA](https://www.pordata.pt/) | Estatísticas sobre Municípios, Portugal e Europa | Open Data | ❌ | ❌
| [Dados Abertos do Porto](https://opendata.porto.digital/dataset/) | Portal de dados abertos do Porto | Open Data | ⁉️ | ⁉️
| [Lisboa GeoDados](https://geodados-cml.hub.arcgis.com/) | Plataforma de dados abertos georreferenciados da Câmara Municipal de Lisboa | Open Data | ⁉️ | ⁉️
| [Águeda Aberta](https://ckan.sig.cm-agueda.pt/dataset?_res_format_limit=0) | Portal de dados abertos de Águeda | Open Data | ⁉️ | ⁉️
| [JRC Data Catalogue](https://data.jrc.ec.europa.eu/dataset?q=portugal) | Catálogo de dados da União Europeia sobre Portugal | Open Data | ⁉️ | ⁉️
| [Faltas no Parlamento](https://labs.tretas.org/attendance/index/) | Portal contendo as faltas dos deputados a sessões plenárias do Parlamento | Open Data | ❌ | [✅](https://labs.tretas.org/attendance/index/)
| [Exames Nacionais](https://github.com/glima93/data_exams_06_18_PT) | Dados de todos os estudantes que realizaram exames nacionais entre 2006 e 2018 | Open Data | ❌ | [✅](https://github.com/glima93/data_exams_06_18_PT)
| [RNT - Consulta ao Registo](https://registos.turismodeportugal.pt/) | Informação dos empreendimentos e empresas do turismo, agentes de animação turística e agências de viagens e turismo | Open Data | ❌ | ❌
| [Portal Base](https://github.com/ajcerejeira/base.gov.pt) | Portal de contratos públicos  | Open Data | ❌ | [✅](https://www.base.gov.pt/base4)
| [Portal do Clima](http://portaldoclima.pt/pt/) | Dados de clima | Open Data| ❌ | ❌
| [SVN GOV](https://svn.gov.pt/) | Código fonte da administração pública | Open Data | ❌ | ❌
| [fogos.pt](https://fogos.pt) | Lista de fogos e estatisticas | API | ❌ | ❌ |

### Justiça

| API         |  Info | Tipo | Spec | Docs |
| ----------- | ----- | :--: | :--: | :--: |
| [Dados na Justiça](https://dados.justica.gov.pt/dataset) | Dados do Ministério da Justiça | Open Data | ❌ |  [✅](https://dados.justica.gov.pt/dataset)

### Saúde

| Nome         |  Info  | Tipo | Spec | Docs |
| :----------- | :----- | :--: | :--: | :--: |
| [Vost Covid](https://covid19-api.vost.pt/) | Dados DGS COVID-19 | API | [✅](https://covid19-api.vost.pt/swagger.json) | ❌ 
| [Transparência SNS v1](https://transparencia.sns.gov.pt/api/v1/console/) | Versão 1 da API de Dados Abertos do SNS | API | ❌ | [✅](https://help.opendatasoft.com/apis/ods-search-v1/)
| [Transparência SNS v2](https://transparencia.sns.gov.pt/api/v2/console/) | Versão 2 da API de Dados Abertos do SNS | API | [✅](https://transparencia.sns.gov.pt/api/v2/swagger.json) | [✅](https://transparencia.sns.gov.pt/api/v2/console/) 

### Educação

| Nome         |  Info  | Tipo | Spec | Docs |
| :----------- | :----- | :--: | :--: | :--: |
| [FenixEdu IST](https://fenixedu.org/dev/api/) | Plataforma FenixEdu do Instituto Superior Técnico | API | ❌ |  [✅](https://fenixedu.org/dev/api/)
| [Universidade de Aveiro](http://api.web.ua.pt/pt/services/universidade_de_aveiro/biblioteca) | Biblioteca da Unviersidade de Aveiro (UA) | API | ❌ |  [✅](http://api.web.ua.pt/pt/services/universidade_de_aveiro/biblioteca)
| [Salários dos Professores](https://github.com/glima93/teacher_salaries_PT) | Dados sobre os salários dos professores em Portugal entre 2006 e 2018 | Open Data | ❌ | ❌
| [INESCTEC](https://rdm.inesctec.pt/dataset?_res_format_limit=0) | Dados produzidos ou usados pelos investigadores do INESCTEC | Open Data | ❌ | ❌
| [Biblioteca Nacional de Portugal](https://opendata.bnportugal.gov.pt/oai-pmh.htm) | Catálogo bibliográfico da Biblioteca Nacional de Portugal, da Base Nacional de Dados Bibliográficos - PORBASE, a Bibliografia Nacional Portuguesa (desde 1931) e Biblioteca Nacional Digital | Open Data | ⁉️ | ⁉️

### Meteorologia

| Nome         |  Info  | Tipo | Spec | Docs |
| :----------- | :----- | :--: | :--: | :--: |
| [IPMA](https://api.ipma.pt/) | Dados meteorológicos e oceanográficos | API | ❌ | [✅](https://api.ipma.pt/)
| [meteoalarm.org](https://metoalarm.org) | Alertas meteorológicos para toda a Europa | API | ❌ | ❌ | 

### Transportes

| Nome         |  Info  | Tipo | Spec | Docs |
| :----------- | :----- | :--: | :--: | :--: |
| [CP](https://github.com/juliuste/comboios) | Cliente em JS para a API da CP | API | [✅]() | [✅](https://github.com/juliuste/comboios)
| [EMEL](https://emel.city-platform.com/opendata/) | Dados abertos da EMEL | API | [✅](https://emel.city-platform.com/opendata/) | ❌
| [Metro de Lisboa](https://api.metrolisboa.pt/store/apis/info?name=EstadoServicoML&version=1.0.1&provider=admin) | Conjunto de APIs disponibilizadas pelo ML | API | [✅](https://api.metrolisboa.pt/store/api-docs/admin/EstadoServicoML/1.0.1?gwType=undefined&gwName=undefined) | [✅](https://api.metrolisboa.pt/store/apis/info?name=EstadoServicoML&version=1.0.1&provider=admin#tab2)
| [TransporLis](https://www.transporlis.pt/Default.aspx?tabid=258&language=pt-PT) | Dados abertos dos transportes públicos de Lisboa | API | [✅](https://www.transporlis.pt/Webservice_dadosabertos/swagger/) | ⁉️
| [Transportes Urbanos de Braga](https://tub.pt/downloads/) | Portal de dados da TUB (Transportes Urbanos de Braga) | Open Data | ❌ | ❌
| [Carris Metropolitana](https://www.carrismetropolitana.pt/) | Carris Metropolitana Schedules API | API | ❌ | [✅](https://github.com/carrismetropolitana/schedules-api)
| [Sociedade de Transportes Colectivos do Porto](https://github.com/sgtpepperpt/stcp-api) | Dados sobre a rede da STCP e passagem de autocarros em tempo real | API | [✅ ](https://github.com/sgtpepperpt/stcp-api/blob/master/README.md)| [✅](https://github.com/sgtpepperpt/stcp-api/blob/master/examples.md)


### Media

| Nome         |  Info  | Tipo | Spec | Docs |
| :----------- | :----- | :--: | :--: | :--: |
| [Observador](https://observador.pt/wp-json/) | Dados do Observador | API | ❌ | ❌
| [PT-NEWS-EXTRACTOR](https://github.com/spamz23/PT-NEWS_EXTRACTOR) | Notícias de jornais | API | [✅](https://pt-news-extractor.herokuapp.com/#operation/cm_url_search_create) | ❌
| [Público](https://www.publico.pt/api/list/ultimas) | Dados do Público | API | ❌ | ❌
| [Jornal de Notícias](http://feeds.jn.pt/JN-Ultimas) | Dados do Jornal de Notícias | RSS | ⁉️ | ❌
| [ECO](https://eco.sapo.pt/wp-json/eco/v1/items) | Dados do ECO | API | ❌ | ❌
| [Diário de Notícias](http://feeds.dn.pt/DN-Ultimas) | Dados do Diário de Notícias | RSS | ❌ | ❌
| [O Jogo](http://feeds.ojogo.pt/OJ-Ultimas) | Dados d'Jogo | RSS | ⁉️ | ❌
| [Dinheiro Vivo](http://feeds.dinheirovivo.pt/DV-Ultimas) | Dados do Dinheiro Vivo | RSS | ❌ | ❌
| [TSF](http://feeds.tsf.pt/TSF-Ultimas) | Dados do TSF | RSS | ⁉️ | ❌
| [RTP Notícias](https://www.rtp.pt/noticias/rss/) | Dados da RTP Notícias | RSS | ⁉️ | ❌
| [Renascença](https://rr.sapo.pt/rss) | Dados da Renascença | RSS | ⁉️ | ⁉️

### Banking

| Nome         |  Info  | Tipo | Spec | Docs |
| :----------- | :----- | :--: | :--: | :--: |
| [SIBS API Market](https://www.sibsapimarket.com/) | Diretório de APIs de Contas, Multibanco, Pagamentos e Informações Bancárias | API | [✅](https://developer.sibsapimarket.com/sandbox/product) | [✅](https://developer.sibsapimarket.com/sandbox/product)
| [Banco de Portugal](https://bpstat.bportugal.pt/data/docs) | Acesso aberto a estatísticas e metadados do portal de estatística do Banco de Portugal | API | [✅](https://bpstat.bportugal.pt/data/docs?format=openapi) | [✅](https://bpstat.bportugal.pt/data/docs)

### Outros

| Nome         |  Info  | Tipo | Spec | Docs |
| :----------- | :----- | :--: | :--: | :--: |
| [arquivo.pt](https://arquivo.pt/) | Acesso a conteúdo histórico da Web | Open Data | ❌ | [✅](https://github.com/arquivo/pwa-technologies/wiki/Arquivo.pt-API)
| [Central de Dados](http://centraldedados.pt) | Repositório de dados abertos em Portugal (eleições, nomes, etc) | Open Data & API | [✅](http://centraldedados.pt/api.json) | [✅](http://centraldedados.pt/)
| [Feriados Portugueses](http://services.sapo.pt/Metadata/Contract/Holiday?culture=PT) | Lista de feriados nacionais, regionais e municipais. Suporta o cálculo dos feriados para os anos entre 1582 e 2299 | API | ❌ | ❌
| [ArcGis](https://services.arcgis.com/CCZiGSEQbAxxFVh3/ArcGIS/rest/services) | Repositório Arcgis do Estado Português, inclui dados COVID-19, incêndios, combustível, entre outros | API | ❌ | ❌
| [itjobs.pt](https://www.itjobs.pt/api/) | Anúncios de emprego na área de Tecnologias de Informação em Portugal.| API | ❌ | [✅]([http://centraldedados.pt/](https://www.itjobs.pt/api/docs))
| [e-redes](https://e-redes.opendatasoft.com/) | Repositório de dados abertos sobre a empresa portuguesa e-redes (setor elétrico).| Open Data & API | ❌ | [✅](https://help.opendatasoft.com/apis/ods-explore-v2/)
