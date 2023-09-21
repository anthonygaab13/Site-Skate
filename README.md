# Plano de Testes de Software

Abaixo segue os casos de teste.

|**Caso de Teste**|**CT- Login – Realizar Login no site**|
| :-: | :- |
|**Requisitos Associados**|<p>**RF-03 -** O site deverá ter um sistema Login, para que o usuário acesse o painel do usuário.</p><p></p><p>**RNF-02 -** O site deve ser responsivo para diferentes plataformas de acesso como, celulares, tablets, notebooks e computadores.</p>|
|**Objetivo do Teste**|Verificar se após digitar o login e senha, o usuário será redirecionado para o painel do usuário.|
|**Passos**|<p>1) Fazer o download da pasta contafacil\_ContaFacil [Git Hub.](https://github.com/ICEI-PUC-Minas-PMV-ADS/pmv-ads-2023-2-e2-proj-int-t2-conta-facil/blob/main/docs/08-Plano%20de%20Testes%20de%20Software.md)</p><p>2) Acessar a pasta e clicar em index\.html</p><p>3) Visualizar a página Home\.</p><p>4) Clicar em Login</p><p>5) Digitar o login <eve.holt@reqres.in> e senha cityslicka</p><p>6) Clicar em Entrar</p>|
|**Critérios de Êxito**|<p>- Você deverá ser redirecionado a pagina painel de usuário</p><p>- Se for digitado um login e senha invalido deverá apresentar uma mensagem de erro.</p><p>- Se for digitado um e-mail invalido, o botão Entrar ficará indisponível</p><p>- Se for digitado uma senha menor de 6 caracteres, o botão Entrar ficará indisponível. </p>|

 
|**Caso de Teste**|**CT -  Inserir dados financeiros**|
| :-: | :- |
|**Requisitos Associados**|<p>RF-01 - O site deverá ter a aba de acesso aos dados financeiros do usuário disponíveis para alteração de cade valor. </p><p>RF-02 - O site deverá oferecer uma funcionalidade de pesquisa para permitir ao usuário localizar um determinado tipo de aplicação ou trasação realizada a um determinado tempo. RF-03 - O site deverá ter um sistema Login, para que o usuário acesse o painel do usuário.</p><p>RF-07 - O site deverá ter uma função de atualizar dados financeiros.</p>|
|**Objetivo do Teste**|Verificar se o campo de busca, filtro, solicitação e chat estão funcionais|
|**Passos**|<p>1) Após o Login tera acesso a página Solicitar </p><p>2) Colocar o nome do produto ou gasto realizado no campo de busca ou Filtrar por: data de pagamento</p><p>3) Caso não tenha o localizado o nome ou a data de pagamento, aparecera transação não localizada</p><p>4) Caso tenha localizado o valor, aparecera a imagem, informações</p><p>5) Clicando em editar valor financeiro, a descrição e o valor inserido poderam ser atualizados ou editados s </p>
|**Critérios de Êxito**|<p>* Os Dados financeiros inseridos pelo usuario devem aparecer</p><p>* Se não tiver os dados financeiros inseridos no sistema deve aparecer uma mensagem(informar valores) </p><p>* O filtro deve mostrar o historico de pagamentos e valores via mês e ano. </p><p>* Os dados financeiros inseridos devem ter um botam para edição</p><p>* Ao edita-lo deve aparecer o status de dados bancarios atualizados</p>



|**Caso de Teste**|**CT - Perfil do usuário/Historico**|
| :-: | :- |
|**Requisitos Associados**|<p>RF-06 - O site deverá ter uma tela histórico.</p><p>RF-02 - O site deverá oferecer uma funcionalidade de pesquisa para permitir ao usuário localizar um determinado tipo de medicamento.</p>|
|**Objetivo do Teste**|Verificar se o campo de busca e se as solicitaççoes aparecem no historico |
|**Passos**|<p>1) Após o Login tera acesso a página Solicitar </p><p>2) Visualizar se tem os campos de Status de Doação e Solicitação</p><p>3) Colocar o nome do medicamento no campo de busca </p><p>3) Caso não tenha o medicamento, aparecera medicamento indiponivel</p><p>4) Caso tenha o medicameto, aparecera a imagem, infrmações e o botão de solicitar</p><p>5) Solicitando aparecerá um infome para perguntando ser quer conversar com doador</p><p>6) Se clicar ok, abrira um chat pra mandar uma mensagem ao doador</p><p>7) Se clicar em cancelar, o medicamento será solicitado e aparecerá no historico de satus de solicitação</p>|
|**Critérios de Êxito**|<p>* O medicamento solicitado deve aparecer</p><p>* Se não tiver o medicamento deve aparecer uma mensagem informando a indiponibilidade dele </p><p>* O medicamento deve ter um botam de para solicitar</p><p>* Ao solicita-lo deve aparecer o status de solicitado</p><p>* E o botam de abrir chat dele abrir um modal para o chat com doador</p>|


