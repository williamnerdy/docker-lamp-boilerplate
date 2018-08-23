Docker LAMP Boilerplate
--
Boilerplate que configura o Mysql, Apache, PHP, PHPMyadmin e OpenSSL

**Auhor:** will.cunha.nd@gmail.com

---

Para rodar o docker composer

````bash
$ docker-compose up
````

Acessar o apache:

http://0.0.0.0:8080

Acessar em HTTPS:

http://0.0.0.0:4043

Acessar o phpmyadmin:

http://0.0.0.0:8081

Dados de acesso do phpmyadmin:

````json
{
  "host": "mysql",
  "user": "root",
  "password": "my-secret-pw"
}
````
