# WebscrappingPelando

O objetivo principal deste projeto é extrair informações de produtos diretamente do site Pelando (https://www.pelando.com.br/) utilizando técnicas de web scraping e processamento de imagem. Será utilizada a biblioteca BeautifulSoup para a extração de informações sobre os produtos do site da empresa:

Título do produto
Preço
Marca
Temperatura
Número de comentários
Neste caso, a "Temperatura" é equivalente aos likes das pessoas. Ou seja, quanto mais quente (maior a temperatura), mais em alta está o produto.

Em conjunto com o BeautifulSoup, será utilizado o Selenium para a possibilitar a extração de dados no site, o qual usa Javascript, o que significa que as informações podem não estar presentes no HTML imediatamente. Desta forma, o Selenium pode ser usado para executar o Javascript da página e fazer com que as informações sejam adicionadas ao HTML, para que possam ser analisadas pelo Beautiful Soup.

Em seguida, será possível utilizar a biblioteca Pandas para organizar esses dados em um Dataframe a fim de estudar o que leva um produto a aparecer primeiro nas buscas ou ter determinado preço. Serão usadas técnicas de análise de dados, como correlação e regressão para identificar padrões e relações entre as informações coletadas, assim como analisar as marcas presentes na descrição do produto para entender quais são as marcas priorizadas nas buscas.

**Obs.:** Não foram feitas análises sobre os Preços dos produtos, afinal, eles são muito variados em razão de que os produtos em si são diversificados, apenas ficam disponíveis aleatoriamente pelas promoções oferecidas pelas empresas.