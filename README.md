# Laravel

## O que é?

Um framework PHP, robusto que serve o padrão **MVC**:
**M** (como registra no banco) **V** (as páginas) **C** (requisições).

## Principais características

* Estrutura MVC;
* Roteamento simples;
* Conexão rápida com o BD (banco de dados);
* Sistema de autenticação/autorização.

## Estrutura de pastas

⇢ App (controllers, models)

⇢ Route (rotas do programa, ligações, API)

⇢ Resources (views, assets)

⇢ Database (migrations, banco de dados)

⇢ Public (index.php)

⇢ Config (.env)

**"PHP Artisan" é a interface de linha de comando incluída no framework Laravel.**
Exemplos:

* php artisan list: Lista todos os comandos disponíveis do Artisan. 
* php artisan serve: Inicia um servidor de desenvolvimento local para a aplicação. 
* php artisan migrate: Executa as migrações do banco de dados. 
* php artisan make:migration: Cria um novo arquivo de migração. 
* php artisan tinker: Permite interagir com a aplicação via linha de comando, incluindo o ORM Eloquent. 
* php artisan route:list: Lista todas as rotas definidas na aplicação. 
* php artisan config:cache: Cria uma versão armazenada em cache da configuração da aplicação para melhor desempenho, ideal para produção, mas deve ser usado com cautela em desenvolvimento. 
* php artisan cache:clear: Limpa o cache da aplicação. 
