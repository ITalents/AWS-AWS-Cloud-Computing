# SITE ESTÁTICO COM S3

## Tarefa 1: Criar um Bucket S3
![GIF mostrando como criar bucket](./imagens/terefa-1.gif)

## Tarefa 2: Habilitar a opção de site estático
![GIF mostrando como habilitar opção de site estático](./imagens/terefa-2.gif)

## Tarefa 3: Fazer download do conteúdo de exemplo

Faça o download do arquivo .zip necessário para essa atividade: [Download](https://aws-tc-largeobjects.s3-us-west-2.amazonaws.com/ILT-TF-200-ACACAD-20-EN/Module-3-Challenge-Lab/static-website.zip)

## Tarefa 4: Fazer upload do conteúdo para o bucket S3
Faça upload do arquivo index.html e também das pastas images e css

![GIF mostrando como fazer o upload do conteúdo para o bucket](./imagens/terefa-3.gif)

## Tarefa 5: Criar uma política para conceder acesso publico de leitura
```json
{
    "Version": "2012-10-17",
    "Statement": [
        {
            "Sid": "PublicRead",
            "Effect": "Allow",
            "Principal": "*",
            "Action": [
                "s3:GetObject",
                "s3:GetObjectVersion"
            ],
            "Resource": [
                "arn:aws:s3:::NOME-DO-BUCKET/*"
            ]
        }
    ]
}
```
![GIF mostrando como inserir a bucket policy para acesso publico](./imagens/terefa-4.gif)


## Tarefa 6: Acessar o site que hospedamos através da Object URL
![GIF mostrando como acessar o site](./imagens/terefa-5.gif)
