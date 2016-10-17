# **form**

> - Representa a cria��o da se��o de um documento, ou um **formul�rio**. 
> - Os formul�rios servem para *receber informa��es dos usuarios*. Para fazer um login na sua conta de e-mail, por exemplo, voc� deve preencher um formul�rio.
> - O leitor envia seus dados, um script pega esses dados e consulta um banco de dados.
> - Um exemplo de tipos de formul�rio que necessita marcar a op��o, � o de aceitar termos de condi��o.[

## Atributos *action* e *method*

O **action** � utilizado como realizamos alguma a��o. Quando clicamos em algo ou escrevemos estamos fazendo uma a��o.
A a��o pode ser um envio de e-mail ou at� mesmo ao clicar em algum bot�o e limpar todos os campos preenchidos.
Normalmente essa a��o � gerada por um script, nesse caso, faremos uma linha voltada para a URL do script.

Ex:
```html
<form action="Url">
```

O **method** � utilizado por dois valores. O *get* e o *post* servem para captar as informa��es recebidas pelo formul�rio e enviar para um c�digo de programa��o
que vai lidar com as informa��es inseridas no formul�rio.

O valor *get* passa os dados recebidos diretamente para a URL do documento.
O valor *post* passa a informa��o do mesmo jeito mas n�o visivelmente no caso do get que mostra a informa��o na URL.

Ex:
```html
<form action="url" method="get">
<form action="url" method="post">
```


