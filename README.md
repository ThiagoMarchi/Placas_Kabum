<h1 align="center"> Python + Selenium </h1>

<p align="center"> Web Scraping usando Selenium e Python </p>

# Web Scraping de Placas de Vídeo - Kabum

## :rocket: Sobre o projeto

Este projeto utiliza a biblioteca **Selenium** para realizar web scraping em uma página de placas de vídeo do site Kabum. O script coleta informações sobre as placas de vídeo, incluindo imagem, nome e preço, e salva esses dados em um arquivo CSV.

## :thinking: Por que?

Apenas para praticar minhas habilidades.

## :warning: Pré-requisitos

Antes de executar o script, você precisa ter o seguinte instalado:

- [Python](https://www.python.org/downloads/)
- [Selenium](https://pypi.org/project/selenium/)
- [ChromeDriver](https://sites.google.com/a/chromium.org/chromedriver/downloads) (certifique-se de que a versão do ChromeDriver corresponde à versão do seu navegador Chrome)

## Descrição do Código

- **URL**: O script acessa a URL https://www.kabum.com.br/hardware/placa-de-video-vga.
- **Configuração do Selenium**: O navegador Chrome é configurado para rodar em modo headless.
- **Extração de Dados**: O script coleta o src da imagem, o nome e o preço de até 20 produtos e salva essas informações em um arquivo CSV chamado Placas_Kabum.csv.
- **Tratamento de Erros**: Se não for possível extrair as informações, o script imprime uma mensagem de erro.



<h1 align="center"> Python + Selenium </h1>

<p align="center"> Web Scraping usando Selenium e Python </p>

# Web Scraping Video Cards - Kabum

## :rocket: About the project 

This project uses the **Selenium** library to perform web scraping on a video card page from the Kabum website. The script collects information about video cards, including image, name, and price, and saves this data to a CSV file.

## :thinking:  Why?

Just practice my skills.

## :warning: Prerequisites

Before running the script, you need to have the following installed:

- [Python](https://www.python.org/downloads/)
- [Selenium](https://pypi.org/project/selenium/)
- [ChromeDriver](https://sites.google.com/a/chromium.org/chromedriver/downloads) (make sure the version of ChromeDriver matches your Chrome browser version)

## Code Description

- **URL**: The script accesses the URL https://www.kabum.com.br/hardware/placa-de-video-vga.
- **Selenium Configuration**: The Chrome browser is set up to run in headless mode.
- **Data Extraction**: The script collects the image `src`, name, and price of up to 20 products and saves this information in a CSV file named `Placas_Kabum.csv`.
- **Error Handling**: If the information cannot be extracted, the script prints an error message.
