# Script de Automação Web com Selenium

<img src="https://metro-news-s3-prod.s3.eu-west-2.amazonaws.com/wp-content/uploads/2017/08/Header_1195724_16.9.jpg"/>

Este é um script de automação web escrito em Python usando a biblioteca Selenium. O script automatiza a tarefa de obter a cotação do dólar, euro e libra esterlina do site do Google. Abaixo, você encontrará informações detalhadas sobre o funcionamento do script e como utilizá-lo.

## Pré-requisitos
Antes de executar este script, você precisa ter os seguintes pré-requisitos instalados em seu ambiente de desenvolvimento:

- Python: Certifique-se de que você tenha o Python instalado em seu sistema. Você pode fazer o download em python.org.

- Selenium: Instale a biblioteca Selenium para Python. Você pode instalar usando o pip:

```Copy code
pip install selenium
```

- WebDriver para o Google Chrome: Certifique-se de que você tenha o WebDriver do Google Chrome instalado e que corresponda à versão do seu navegador. Você pode baixar o WebDriver do Chrome em ChromeDriver Downloads.

## Como Utilizar o Script
- Baixe o script para o seu ambiente de desenvolvimento.

- Certifique-se de que todos os pré-requisitos estejam instalados.

- Abra o script em um editor de código Python de sua escolha.

- Substitua o caminho do WebDriver para o Google Chrome na linha:

```python
driver = webdriver.Chrome()
```
Pelo caminho correto para o WebDriver em seu sistema. Por exemplo:

```python
driver = webdriver.Chrome(executable_path="/caminho/para/chromedriver")
```
Execute o script. Ele abrirá uma janela do Chrome e automatizará as seguintes ações:

- Acessar o site do Google.
- Pesquisar a cotação do dólar, euro e libra esterlina.
- Extrair as cotações e armazená-las nas variáveis cotacao_dolar, cotacao_euro e cotacao_lib.
- Imprimir as cotações no console.
## Observações
- O script usa seletores XPath para interagir com elementos na página. Certifique-se de que esses seletores ainda são válidos no site do Google, pois eles podem mudar com o tempo.

- O tempo de espera (time.sleep) foi incluído para garantir que a página tenha tempo suficiente para carregar os resultados da pesquisa. Você pode ajustar esses tempos de espera conforme necessário.

- Este script é apenas um exemplo de automação web com Selenium e pode ser personalizado para atender às suas necessidades específicas.

Aproveite a automação da obtenção das cotações do dólar, euro e libra com facilidade usando este script!
