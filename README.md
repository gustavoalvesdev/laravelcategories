<h1 align="center">Bem-vindo ao Projeto Laravel Categorias 👋</h1>
<p>
  <img alt="Version" src="https://img.shields.io/badge/version-1.0.0-blue.svg?cacheSeconds=2592000" />
</p>

> CRUD de Tarefas, Usuários e Categorias, com Factories, Seeders, Relacionamentos e eMigrations. 

## Install

```sh
composer install
```

##  Configurar o .env a partir do .env.example

```sh
copy .env.example .env
```

## Gerar a chave da aplicação

```sh
php artisan key:generate
```

## Rodar as Migrations (após BD estar configurado no .env)

```sh
php artisan migrate
```

## Rodar o DB Seeder

```sh
php artisan db:seed
```

## Subir a aplicação localmente

```sh
php artisan serve
```