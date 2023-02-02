# Web Scraping
Raspagem de dados dos Fundos imobiliarios

<p align="center">
  <img src="WEB SCRAPING.jpg" >
</p>

O termo Web Scraping ou "raspagem de dados" está associado a uma forma de mineração de dados na web que permite a extração de dados de sites, plataformas, online, redes sociais entre outros que estão publicamente acessíveis, transformando esses dados em informação estruturada para analises que geram insights valiosos.

Essa "raspagem" pode ser feita de forma automatizada através de frameworks tanto no Python, como é o caso do BeautifulSoup que será usado nesse projeto, como em outra linguagem de programação e inclusive pode ser feita até pelo Excel.

Basicamente o fluxo da raspagem é feita dessa forma:

* *Identifica o site de destino*
* *Coleta URLs das páginas de onde você deseja extrair dados*
* *Faz uma solicitação a esses URLs para obter o HTML da página*
* *Usa localizadores para encontrar os dados no HTML*
* *Salva os dados em um arquivo JSON ou CSV ou algum outro formato estruturado*

Será utilizado os dados dos papeis FIIs do site Fundamentos, que é um sistema on-line que disponibiliza informações financeiras e fundamentalistas das empresas com ações listadas na Bovespa e que possui completo banco de dados apresentado de forma acessível para auxiliar investidor a encontrar as melhores opções de investimento.
