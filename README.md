# Controle-meteorológico
Monitor de Temperatura por Localização (Integração Google Sheets + Open-Meteo API)
Este projeto foi desenvolvido em Python para ler coordenadas geográficas (Latitude e Longitude) a partir de uma planilha do Google Sheets e obter as condições climáticas em tempo real para cada localidade utilizando a API pública do Open-Meteo.

🚀 Funcionalidades
Interface HTML Amigável: Foi criada uma página HTML para a inserção dos dados e visualização, eliminando a necessidade de lidar diretamente com formulários padrão e tornando a experiência muito mais visual.
Integração com Google Sheets: Carrega dinamicamente os dados armazenados na planilha pública exportada em formato CSV.
Consulta de API Externa: Faz requisições HTTP para a API do Open-Meteo enviando as coordenadas de cada local.
Exibição em Tempo Real: Retorna e exibe a temperatura atual (temperature_2m) de cada ponto mapeado.

🛠️ Tecnologias Utilizadas
Python
Pandas (Manipulação e leitura dos dados da planilha)
Requests (Requisições HTTP para a API de clima)
Open-Meteo API (Dados meteorológicos gratuitos)
HTML/CSS (Interface visual do projeto)

📂 Estrutura do Código
Interface Visual: Página HTML para interação do usuário.
Configuração inicial: Definição dos endpoints da planilha (Google Sheets) e da API de previsão.
Coleta de dados: Leitura e visualização dos dados estruturados utilizando o pandas.read_csv.
Processamento e Integração: Iteração sobre cada linha da planilha, extração de Latitude/Longitude e envio dos parâmetros para a API de previsão para obter a temperatura atual de cada local cadastrado.
