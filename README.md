# Docker To-Do List

Este projeto foi desenvolvido durante o módulo de Back-end na Trybe. O objetivo do projeto é a criação de imagens Docker, para a aplicação disponibilizada pela Trybe, e configurá-las usando o Docker Compose.

## Tecnologias Utilizadas
<hr>

- Comandos na Interface de Linha de Comando (CLI) do Docker

- Dockerfile

- Docker Compose

## Instruções
<hr>

- Clone este repositório para o seu ambiente de desenvolvimento local.

```bash
git@github.com:nataliaschmidt/project-docker-to-do-list.git
```
- Navegue até o diretório docker projeto.

- Execute os seguintes comandos no para construir as imagens Docker para cada componente:

```bash
docker image build ./todo-app/back-end -t todobackend

docker image build ./todo-app/front-end -t todofrontend

docker image build ./todo-app/tests -t todotests
  ```

- Após a conclusão da construção das imagens individuais, execute o seguinte comando para iniciar os contêineres usando o Docker Compose:
```bash
docker-compose up
```
- Acesse a aplicação em seu navegador web através do seguinte endereço:
```html
http://localhost:3000
```