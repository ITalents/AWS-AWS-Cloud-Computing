# Tarefa 1: Criar um Instancia EC3

Nessa tarefa você criará uma instância do Amazon EC2, selecionando a as opções de Free Tier, dessa forma não haverá cobranças no seu cartão de crédito.

É extremamente importante inserir o script a baixo no campo user-date, conforme demonstrado no vídeo.

```bash
#!/bin/bash
apt-get upgrade
apt update -y
apt install apache2 -y
systemctl enable apacahe2
```
![GIF mostrando como criar uma instância EC2](./imagens/tarefa-1.gif)


# Tarefa 2: Testando a instância criada

Nessa tarefa você testará se a instância e o servidor http que foi criado estão funcionais.

![GIF mostrando como testar uma instância EC2](./imagens/tarefa-2.gif)


# Tarefa 2: Encerrando a instância criada

Nessa tarefa você encerrará a instância que foi criada para não gerar custos adicionais.

![GIF mostrando como encerrar uma instância EC2](./imagens/tarefa-3.gif)
