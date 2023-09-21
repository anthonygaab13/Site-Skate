# Plano de Testes de Software

Abaixo segue os casos de teste.

|**Caso de Teste**|**CT- Login – Realizar Login no site**|
| :-: | :- |
|**Requisitos Associados**|<p>**RF-01 -** O site deverá ter um sistema Login, para que o usuário acesse o painel do usuário.</p><p></p><p>**RF-02 -**O sistema deverá ter uma tela de cadastro de usuários.</p>|
|**Objetivo do Teste**|Verificar se após digitar o login e senha, o usuário será redirecionado para o painel do usuário.|
|**Passos**|<p>1) Fazer o download da pasta contafacil\_ContaFacil [Git Hub.](https://github.com/ICEI-PUC-Minas-PMV-ADS/pmv-ads-2023-2-e2-proj-int-t2-conta-facil/blob/main/docs/08-Plano%20de%20Testes%20de%20Software.md)</p><p>2) Acessar a pasta e clicar em index\.html</p><p>3) Visualizar a página Home\.</p><p>4) Clicar em Login</p><p>5) Digitar o login <eve.holt@reqres.in> e senha cityslicka</p><p>6) Clicar em Entrar</p>|
|**Critérios de Êxito**|<p>- Você deverá ser redirecionado a pagina painel de usuário</p><p>- Se for digitado um login e senha invalido deverá apresentar uma mensagem de erro.</p><p>- Se for digitado um e-mail invalido, o botão Entrar ficará indisponível</p><p>- Se for digitado uma senha menor de 6 caracteres, o botão Entrar ficará indisponível. </p>|

 
|**Caso de Teste**|**CT -  Inserir dados financeiros**|
| :-: | :- |
|**Requisitos Associados**|<p>RF-03 - O sistema deverá ter a função de visualização de saldo atual. </p><p>RF-06 - O sistema deverá ter função de cadastro de despesas.</p><p>RF-04 - O sistema deverá ter um relatório de despesas.</p>
|**Objetivo do Teste**|Verificar se as funcionalidades de inserção de dados financeiros, busca, filtro e edição estão funcionando conforme o esperado.|
|**Passos**|<p>1) Efetue o login no sistema. </p><p>2) Colocar o nome do produto ou gasto realizado no campo de busca ou Filtrar por: data de pagamento</p><p>3) No campo de inserção, preencha o nome do produto ou descrição do gasto realizado, bem como o valor financeiro correspondente.</p><p>4) Verifique se há um botão para cadastrar a despesa ou inserir os dados financeiros.</p><p>5) Após a inserção, verifique se os dados financeiros inseridos pelo usuário aparecem corretamente na interface. </p><p>6) Utilize o campo de busca para inserir o nome do produto ou descrição do gasto realizado. Verifique se os resultados são filtrados corretamente. <p/><p>7)Utilize a opção "Filtrar por data de pagamento" para verificar se o sistema filtra os dados com base na data de pagamento especificada. <p/><p>8)Caso o nome do produto, descrição ou data de pagamento não sejam localizados, verifique se uma mensagem informativa, como "Transação não localizada", é exibida. <p/><p>9)Se os dados forem localizados, verifique se a imagem e outras informações relevantes estão sendo exibidas corretamente. <p/><p>10)Clique na opção "Editar valor financeiro" e verifique se a descrição e o valor inseridos podem ser atualizados ou editados. <p/>
|**Critérios de Êxito**|<p>* Os dados financeiros inseridos pelo usuário devem aparecer corretamente na interface após a inserção.</p><p>* Se não houver dados financeiros inseridos no sistema, uma mensagem informativa deve ser exibida, informando que nenhum dado foi encontrado. </p><p>* O filtro de busca deve mostrar o histórico de pagamentos e valores com base nas opções selecionadas, incluindo mês e ano. </p><p>* Os dados financeiros inseridos devem ter um botão de edição que permite a atualização das informações.</p><p>* Ao editar os dados, o sistema deve exibir uma confirmação de que os dados financeiros foram atualizados com sucesso.</p>
