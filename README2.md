# Esercizio di oggi: Laravel Primi Passi
nome repo: laravel-primi-passi
Ciao ragazzi,
oggi iniziamo a muovere i primi passi con questo fantastico framework che è Laravel!
Per prima cosa, creiamo un nuovo progetto Laravel 10, utilizzando questo comando:
composer create-project laravel/laravel laravel-primi-passi
Al termine dell'installazione, entriamo nella cartella del progetto
cd laravel-primi-passi
e avviamo l'artisan serve con uno di questi due comandi:
php artisan serve oppure php -S localhost:8000 -t public
A questo punto, iniziamo a prendere confidenza con le rotte e le views: cancelliamo la view welcome.blade.php e creiamo una nostra homepage. Facciamo quindi sì che la rotta / visualizzi home.blade.php
Inizialmente stampiamo un Hello World, poi passiamo dei dati alla view in modo da visualizzarli dinamicamente con Blade.
Bonus:
Creiamo più di una pagina e visualizziamo un header menu con i link di tutte le pagine (modificato) 




Passi per laravel (Se avete difficoltà con github):
# 1 Lanciare il comando, dentro la vostra cartella progetti o htdocs: 
composer create-project laravel/laravel laravel-primi-passi
# 2 Creare la repo su github, sempre VUOTA e senza README
# 3 Entrare dentro la cartella di laravel da terminale
# 4 Dare questi comandi


    git init
    git add .
    git commit -m "Primo Commit"
    git remote add origin link_repo_github
    git branch -M main
    git push -u origin main