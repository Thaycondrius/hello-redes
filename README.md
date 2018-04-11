# Trabalho Prático Redes

* O trabalho consiste em desenvolver 2 aplicações sobre o protocolo HTTP e o método GET: Um navegador e um servidor web.

### O Cliente

* O navegador deverá funcionar por linha de comando e baixar o arquivo requisitado, caso ele exista.
* Exemplo:
* $> navegador http://urldesejada Porta
* Caso o usuário não informar a porta, a porta 80 será utilizada.
* No caso de o servidor retornar uma mensagem de erro, como o erro 404, a aplicação deverá informar o erro e não salvar o documento.

### O Servidor

* O servidor deverá funcionar por linha de comando informando uma pasta de arquivos e uma porta.
* Exemplo:
* servidor public_html 8080
* Ao receber uma requisição o servidor deverá:
* a) ver se o arquivo existe na pasta, se existir, retornar o mesmo;
* b) se o arquivo não existir, retornar mensagem de erro.
* O servidor deverá aceitar conexões de mais de um cliente (multithread).

### Execução

* Para compilar o servidor: "python server.py".
* O servidor está configurado para executar na pasta em está sendo executado.
* Para compilar o servidor: "python cliente.py"
