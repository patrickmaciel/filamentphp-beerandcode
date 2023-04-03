
## Instalação

Clonar o repositório:

```bash
git clone https://github.com/patrickmaciel/filamentphp-beerandcode.git
```

Acessar a pasta do repositório:

```bash
cd filamentphp-beerandcode
```

Copiar o arquivo env.example e nomear para .env e configure com os dados do seu banco local:

```bash
cp .env.example .env
```

Instale as dependências:

```bash
composer install
```

Execute as migrações necessárias com o comando:

```bash
php artisan migrate --seed
```

Crie uma conta de acesso do Painel Administrativo do Filament:

```bash
php artisan make:filament-user
```

Compile os assets:

```bash
npm install
npm run build
```

Execute o artisan para iniciar o projeto localmente:

```bash
php artisan serve
```

Acesse a aplicação [http://localhost:8000](http://localhost:8000)

## Acessando a aplicação do Filament

Com o projeto instalado e configurado, você pode acessar no browser a url [http://localhost/admin](http://localhost/admin) e logar.

Caso tenha alguma dúvida ou problema, envie um email: *patrickmaciel.info@gmail.com*

## License
[MIT](https://choosealicense.com/licenses/mit/)
