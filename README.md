# Este é um projeto de análise exploratória simples sobre a correlação entre acidentes de veículos em Porto Alegre e a COVID-19 #

Para a criação dessa análise, utilizei o conjunto de dados abertos para registro de acidentes de trânsito no município de Porto Alegre extraídos do [site oficial dados abertos POA.](https://dadosabertos.poa.br/dataset/acidentes-de-transito-acidentes)

Neste arquivo com formato CSV, contém informações como: 

- Data, localidade, região da cidade e de que forma ocorreu aquele acidente;
- Nome da rua;
- Coordenadas latitudenal e longitudenal;
- Tipo de Veículo;
- Número de vítimas e outros tipos de dados.

Serão utilizados as bibliotecas:
1. Pandas para a visualização do dataframe;
<br>

2. Folium e os plugins HeatMap para gerar um mapa de calor na região dos acidentes juntamente o MarkerCluster, apontando exatamente onde ocorreu cada acidente, agrupando por regiões.
<br>

3. Matplotlib para plotagem dos dados baseado em cada ano.

Execute o código através de um editor de código notebook e acompanhe o que as funções fazem através dos comentários.
