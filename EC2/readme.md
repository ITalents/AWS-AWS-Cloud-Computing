# Tarefa 1: Criar um Instancia EC2

Nessa tarefa você criará uma instância do *Amazon EC2*, selecionando as opções de [*Free Tier*](https://aws.amazon.com/pt/free/), dessa forma não haverá cobranças no seu cartão de crédito.

Ao acessar a console, na barra de pesquisa, procure pela opção **EC2**. Depois clique no botão **launch instance**, no menu **Application and OS Images (Amazon Machine Image)** selecione a opção Ubuntu.

Expanda o menu **Advanced details**, e procure por **User data** e preencha com os comandos abaixo conforme demonstrado no vídeo (gif-animado):

```bash
#!/bin/bash
apt-get upgrade
apt update -y
apt install apache2 -y
systemctl enable apache2
```
![GIF mostrando como criar uma instância EC2](./imagens/tarefa-1.gif)


# Tarefa 2: Testando a instância criada

Nessa tarefa você testará se a instância e o servidor http que foi criado estão funcionais.

![GIF mostrando como testar uma instância EC2](./imagens/tarefa-2.gif)


# Tarefa 3: Encerrando a instância criada

Nessa tarefa você encerrará a instância que foi criada para não gerar custos adicionais.

![GIF mostrando como encerrar uma instância EC2](./imagens/tarefa-3.gif)
