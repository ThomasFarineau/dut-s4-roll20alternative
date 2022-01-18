Projet Étudiant DUT S4
*Projet en groupe lors de mon semestre 4 de DUT*

Pour installer mon application il faut faire `composer install` puis `composer dump-autoload` puis `php artisan migrate`.

Si une erreur proviens lors du `composer install` a cause du cache, effectuer ces commandes:

- `mkdir bootstrap/cache`
- `mkdir storage/framework`
- `mkdir storage/framework/cache`
- `mkdir storage/framework/views`
- `mkdir storage/framework/sessions`
