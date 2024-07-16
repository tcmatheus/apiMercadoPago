
<h3 align="center">Integração NodeJs com Mercado Pago</h3>
<p align="center">
Integração simples do nodejs com o mercado pago.
  <br>
</p>


Crie sua conta no mercado pago para fazer a integração do seu projeto.

### Rodando a aplicação
Agora rode o comando 'npm install' para instalar os pacotes que a aplicação exige e excute o arquivo index.js com o comando

```shell
npm install

Salve o token no arquivo **'.env'**, por padrão de segurança o arquivo .env é inserido ao gitignore então insira o arquivo na pasta raiz do projeto.

ACCESS_TOKEN="SEU_TOKEN"

Após isso insira o comando a baixo e abra em seu navegado http://localhost:3000 

node index.js
```

Para fazer os teste use os cartões de teste :
https://www.mercadopago.com.br/developers/pt/docs/your-integrations/test/cards

Lembrese de usar um navegador que nao esteja logado a sua conta propria do mercado pago pois você nao pode fazer o pagamento para si proprio. Use uma aba anonima ou limpe o seu cache para fazer os testes.

