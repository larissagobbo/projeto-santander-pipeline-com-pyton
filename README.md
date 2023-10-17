<p align="center"><img src="http://img.shields.io/static/v1?label=STATUS&message=%20CONCLUIDO&color=GREEN&style=for-the-badge"/></p>
<br>
</br>

# :computer: _**Projeto de pipeline com IA Generativa de ETL com Python**_ :bar_chart:
<p> </p>

## _**Informações do Projeto**_:
<br> 

_Este projeto foi criado para testar os conhecimentos obtidos no curso de ciências de dados do Santander em parceiria com a Dio.me. Foi proposto uma criação de um pipeline em python com integração de Inteligência Artificial. Neste projeto foi proposto que a partir de uma planilha simples CSV fosse elaborado uma rede de sistema bancário com python e intregração com IA. Neste caso, teriamos que criar uma planilha de dados de clientes ficticios e com isso a IA teria que apresentar uma mensagem sobre marketing bancário e assegurar os clientes sobre a importância dos investimentos_.
</br>

## :pushpin: _Linguagens Utilizadas:_
<br>

_Para construção deste projeto foi utilizado a linguagem de programação Python com integração da IA gpt-3.5 turbo._
- :exclamation: _Primeiro foi utilizado o python em conjunto com swagger para que fosse construido algumas informações de usuários._
-  :exclamation: _Após a criação de usuários ficticios houve a implementação da OPENAI para a construção das mensagens personalizadas para o usuário_
-  :exclamation: _Após a criação de mensagens personalizadas para os usuários foi feito o envio de volta para a API, ocorrendo a atualização na lista "news" de cada usuário usando endpoint/ `PUT https://sdw-2023-prd.up.railway.app/users/{id}`._

  ## :clipboard: _Extração_:
<br>

:exclamation: _Nesta etapa foi necessário extrair os IDs de usuário a partir do arquivo CSV. Sendo assim, para cada usuário foi necessário fazer uma requisição GET para obter os dados do usuário correspondente_.

## :paperclip: _Transformação_:
<br>

:exclamation: _Nesta etapa utilizamos a API da OpenAI (aqui poderia ser feita a modificação para versão, no projeto foi ofertado que poderia ser feito com o GPT-4, porém, optei por usar o GPT-3.5 turbo, que teve o mesmo desempenho do gpt-4) para gerar a mensagem personalizada de marketing para cada usuário cadastrado na tabela._

## :bookmark_tabs: _Atualização:_
<br>

:exclamation: _Nesta etapa atualizamos a lista "news" de cada usuário na API com a nova mensagem gerada._

## :books: _Repositorio da API_: 
<br>

:exclamation: O repositorio da API pode ser encontrado pelo seguinte link: https://github.com/digitalinnovationone/santander-dev-week-2023-api
sdw2023_api_url 

## :bangbang: _Informações Úteis:_
<br>

:exclamation: _Para conseguir integrar o pipeline com a IA é necessário gerar uma key pelo site da OpenAI, e caso haja alguma dificuldade, segue o passo a passo de como pode ser gerado essa key no site da openAI (a chave é de segurança, deste modo, deve ter cuidado ao posta-lá, sendo assim, cancele no site, ou coloque uma chave que não foi gerada, ou seja, uma chave aleatória)_

:one:   **_Crie uma conta no site da OpenAI: https://openai.com/_**
<p>  
  
:two:  **_Acesse a secão "API Keys"_** 
<p>
  
:three: **_Clique em "Create API Key" - segue link direto: https://platform.openai.com/account/api-keys_**
</p>

<br>

:round_pushpin: **_Lembrando que todos os usuários e dados criados dentro deste código são fictícios._**
</br>


