# Hasheado Basic Stack
Basic stack to build a web application with admin interface for the backend and SPA for frontend.

### Assumptions:
Backend:  
* [Symfony 2.3 (LTS)](http://symfony.com/download)
* [SonataAdminBundle](https://sonata-project.org/bundles/admin/2-3/doc/index.html).
* [SonataUserBundle](https://sonata-project.org/bundles/user/2-2/doc/index.html).
* [FOSUserBundle](https://github.com/FriendsOfSymfony/FOSUserBundle).

Frontend:  
* To be defined

## Installation
1) Clone this repo:  
> git clone https://github.com/emiliano-viada-developer/hasheado-basic-stack.git  
DO NOT forget to change the remote url. See how [here](https://help.github.com/articles/changing-a-remote-s-url/).

2) Update the parameters.yml with yours.

3) Install dependencies with Composer:  
> php composer.phar install  

4) Update the schema:  
> php app/console doctrine:schema:update --force  

5) Create a super admin user:  
> php app/console fos:user:create adminuser --super-admin  
