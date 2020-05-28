# Devemos ter alguns cuidados na hora do deploy da aplicação

O comando composer install é utilizado para baixar todas as dependências do projeto
O comando php artisan key:generate gera uma nova chave para criptografar os dados sensíveis
No arquivo .env, a propriedade APP_ENV deve ser prod e APP_DEBUG deve ser false


https://laravel.com/docs/5.8/deployment
