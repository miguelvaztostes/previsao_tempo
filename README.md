Visualização Rápida de Informações Meteorológicas Simples

Esta é uma aplicação web construída com HTML, CSS e JavaScript que permite aos usuários obter rapidamente informações meteorológicas para uma localização específica. Ela busca dados na API OpenWeatherMap para fornecer informações de temperatura, umidade e velocidade do vento e utiliza a API Flags para exibir a bandeira correspondente ao país com base na localização da cidade.
Recursos

    Exibir a temperatura, umidade e velocidade do vento de uma localização específica.
    Alterar dinamicamente a bandeira do país com base na localização.
    Interface amigável para facilitar a obtenção de informações meteorológicas.

Demonstração

Você pode experimentar a demonstração ao vivo do SitQ aqui.
Como Usar

Siga estas etapas para usar o SitQ:

    Clone ou baixe o repositório para a sua máquina local.

    Abra o arquivo index.html no seu navegador da web preferido.

    Insira o nome da cidade para a qual deseja obter informações meteorológicas no campo de entrada.

    Clique no botão "Obter Informações Meteorológicas".

    O SitQ exibirá a temperatura, umidade e velocidade do vento para a cidade fornecida, juntamente com a bandeira do país correspondente.

Tecnologias Utilizadas

    HTML
    CSS
    JavaScript
    API OpenWeatherMap: API OpenWeatherMap
    API Flags: API Flags

Instalação

Para executar o SitQ na sua máquina local, siga estas etapas:

    Clone o repositório:

    bash

git clone https://github.com/seu-nome-de-usuario/sitq.git

Navegue até o diretório do projeto:

bash

    cd sitq

    Abra o arquivo index.html no seu navegador da web.

Configuração

Para fazer o código funcionar com sua chave da API OpenWeatherMap, você precisa atualizar o código JavaScript com sua chave da API.

    Acesse API OpenWeatherMap e registre-se para obter uma chave da API, se ainda não a tiver.

    Abra o arquivo script.js e encontre a seguinte linha:

    javascript

    const apiKey = 'SUA_CHAVE_DA_API_OPENWEATHERMAP';

    Substitua 'SUA_CHAVE_DA_API_OPENWEATHERMAP' pela sua chave da API real.


Reconhecimentos

    Agradeço à OpenWeatherMap por fornecer os dados meteorológicos.
    Agradeço à API Flags pelas imagens das bandeiras dos países.
