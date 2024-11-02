Antes de levantar o Container do Moodle é necessário criar os diretórios de persistência do MariaDB e Moodle.

Diretórios de Persistência
=========================
Para criar os diretórios de persistência do MariaDB e Moodle, basta executar o comando abaixo:

```bash
sudo mkdir -p /path/to/mariadb-persistence /path/to/moodle-persistence /path/to/moodledata-persistence
```

Após criar os diretórios de persistência, é talvez seja necessário alterar as permissões dos diretórios para o usuário
do Docker.

Execução do Container do Moodle
==============================
Para executar o container do Moodle, basta executar o comando abaixo:

```bash
docker-compose up -d
```

Para acessar o Moodle, basta acessar o endereço `http://localhost` no navegador.

O login padrão do Moodle é `user` e a senha é `bitnami`.