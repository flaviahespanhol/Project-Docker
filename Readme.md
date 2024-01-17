# Título do Projeto

## Descrição

Nesse projeto foi desenvolvido o aprendizado do bloco de Docker (seu conceito e comandos de manipulação de containers e imagens).


## Conteúdo

Os objetivos desse projeto são:

1. Conhecimento dos comandos dockers no CLI - Interface de linha de comando.
2. Criar um container Docker.

## Desenvolvimento do projeto

`Requisito 1`
Criar um container em modo interativo, sem rodá-lo, nomeando-o como 01container e utilizando a imagem alpine na versão 3.12.

`Requisito 2`
Iniciar o container 01container.

`Requisito 3`
Listar os containers filtrando pelo nome 01container.

`Requisito 4`
Executar o comando cat /etc/os-release no container 01container sem se acoplar a ele.

`Requisito 5`
Remover o container 01container.

`Requisito 6`
Fazer o download da imagem nginx com a versão 1.21.3-alpine sem criar ou rodar um container.

`Requisito 7`
Rodar um novo container com a imagem nginx com a versão 1.21.3-alpine em segundo plano nomeando-o como 02images e mapeando sua porta padrão de acesso para porta 3000 do sistema hospedeiro.

`Requisito 8`
Parar o container 02images que está em andamento.

`Requisito 9`
Gerar uma build a partir do Dockerfile do back-end do todo-app nomeando a imagem para todobackend.