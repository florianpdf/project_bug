Dojo Debug
==============
####Objectif:
Débuguer un projet Symfony
Compéhension Symfony

####Pré-requis: 
composer ==> [Install Composer](https://getcomposer.org/doc/00-intro.md)

#### Initialisation du projet
1. **ssh**: git clone git@github.com:florianpdf/project_bug.git
2. **https**: git clone https://github.com/florianpdf/project_bug.git
3. cd project_bug
4. composer install
5. php app/console doctrine:database:create
6. php app/console asset:install

#### Contenu des branches:
1. **Sur la branche "master"** ==> Projet non bugger
2. **Sur la branche "with_bug"** ==> Projet bugger
