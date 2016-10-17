# **form**

> - Representa a criação da seção de um documento, ou um **formulário**. 
> - Os formulários servem para *receber informações dos usuarios*. Para fazer um login na sua conta de e-mail, por exemplo, você deve preencher um formulário.
> - O leitor envia seus dados, um script pega esses dados e consulta um banco de dados.
> - Um exemplo de tipos de formulário que necessita marcar a opção, é o de aceitar termos de condição.[

## Atributos *action* e *method*

O **action** é utilizado como realizamos alguma ação. Quando clicamos em algo ou escrevemos estamos fazendo uma ação.
A ação pode ser um envio de e-mail ou até mesmo ao clicar em algum botão e limpar todos os campos preenchidos.
Normalmente essa ação é gerada por um script, nesse caso, faremos uma linha voltada para a URL do script.

Ex:
```html
<form action="Url">
```

O **method** é utilizado por dois valores. O *get* e o *post* servem para captar as informações recebidas pelo formulário e enviar para um código de programação
que vai lidar com as informações inseridas no formulário.

O valor *get* passa os dados recebidos diretamente para a URL do documento.
O valor *post* passa a informação do mesmo jeito mas não visivelmente no caso do get que mostra a informação na URL.

Ex:
```html
<form action="url" method="get">
<form action="url" method="post">
```


