🌊 Identificação de Áreas Alagáveis via NDWI e Precipitação

1.	OBJETIVO
Analisar padrões espaciais e temporais de alagamento a partir de NDWI (Sentinel -2) e precipitação (CHIRPS) sobre a sub-bacia do Monjolinho, São Carlos (SP).
2.	Questões da pesquisa:
 - Se existe uma relação direta de inundação com anomalias de precipitação
- E como a mudança no uso da cobertura do solo agravam a frequência e severidade das inundações.
  
3.	Metodologia
3.1	Ferramentas utilizadas
As ferramentas utilizadas para o processamento dos dados serão todas plataformas WEB sendo a principal Google Colab, que permite criar e executar códigos, uma facilidade para quem está no início da fase de aprendizado de programação. Uma segunda ferramenta auxiliadora é o Google Earth Engine que permitirá uma facilidade para acesso aos dados, e posteriormente ao acesso dos resultados na plataforma https://code.earthengine.google.com/. 
E para a realização de todos o processo principalmente na parte de elaboração dos códigos, é utilizado o ChatGPT como auxiliador de cada etapa.

3.2	Passo a passo
Pensando na delimitação da área de estudo necessitamos de um arquivo com delimitações em arquivo shapefile (.shp) ou uma planilha de Comma-Separeted Values com as coordenadas da delimitação (.csv). 

O primeiro passo é a criação e validação de conta juntamente com o login na plataforma do https://earthengine.google.com/ . E lembrando que a organização faz parte do processo, portanto a criação de uma pasta no Drive com nome do projeto e criar um arquivo ficheiro de texto com a extensão para ser utilizado peço Jupyter Notebook (.ipynb ) do Google Colab. 
E assim organizaremos em etapas a criação dos códigos. 
#Importação da pasta de trabalho criada no Drive
# 🔧 Instalação de bibliotecas
# 📦 Importações e autenticação
# 📍 Área de estudo: Sub-bacia Monjolinho 
(contendo o arquivo de localização/delimitação da área de estudo)
# 🌧️ Coleta de dados de precipitação (CHIRPS)
# 💧 Coleta e cálculo do NDWI (Sentinel-2)
# 📊 Visualização conjunta

Nesta etapa para a seguir para obter o resultado das exportações é necessário abrir a plataforma do https://code.earthengine.google.com/ para acompanhar o andamento e posteriormente realizar o download para a pasta do Drive.

# Exportar NDWI como tabela .CSV para o Google Drive
# Exportar Precipitação como tabela .CSV para o Google Drive
# Cálculo do NDWI para cada imagem
