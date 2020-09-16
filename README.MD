### Install Magento 2 Community Edition

```
docker-compose build
```

```
docker-compose up
```

The instruction below will download a current version of Magento2 CE and install all dependencies.
```
docker exec -it magentotest_magento-test-php_1 composer create-project --repository-url=https://repo.magento.com/ magento/project-community-edition magento2
```
We take authentication data from https://marketplace.magento.com/customer/accessKeys/ . If there is no Access Key yet, please create a new one then "username" is your "public key" and "password" is your "private key".
