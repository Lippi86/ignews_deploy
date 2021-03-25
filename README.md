<h1 align="center">
    IG.News
</h1>
<p align="center">Aplicação para inscrição de newsletter com pagamento via stripe</p>


<p align="center">
 <a href="#sobre-o-projeto">Sobre o Projeto</a> •
 <a href="#tecnologias">Tecnologias</a> •
 <a href="#configurações-necessárias">Configurações necessárias</a> •
 <a href="#licença">Licença</a> •
 <a href="#autor">Autor</a>
</p>

## Sobre o projeto

O projeto tem como objetivo o estudo e desenvolvimento de uma aplicação em ReactJS com NextJS para listagem de posts e sistema de inscrição(subscription).

A aplicação foi desenvolvida utilizando o framework NextJS aplicando conceitos como consumo de API externas, API Root, Server Side Rendering (SSR), Static Site Generation (SSG), utilização do STRIPE para pagamentos, NextAuth para autenticação com Github e FaunaDB para salvar as informações do usuário em um banco de dados.

O projeto foi desenvolvido como pratica das aulas do modulo 03 do [Ignite da Rocketseat](https://rocketseat.com.br/)

---

## Tecnologias

Abaixo as tecnologias utilizadas para construção da aplicação

- [ReactJS](https://reactjs.org/)
- [NextJS](https://nextjs.org/)
- [TypeScript](https://www.typescriptlang.org/)
- [SASS](https://sass-lang.com/)
- [Stripe](https://stripe.com/)
- [NextAuth](https://next-auth.js.org/)
- [FaunaDB](https://fauna.com/)

---

## Configurações necessárias

### **Requisitos**

Necessário ter instalado o [Git](https://git-scm.com/), [Yarn](https://classic.yarnpkg.com),
[Stripe CLI](https://stripe.com/docs/stripe-cli)


### **Clone do projeto**

```bash
# Execute o comando git clone para realizar o clone do repositório
$ git clone https://github.com/nelsonsantosaraujo/ignews.git
# Entre na pasta do repositório clonado
$ cd ignews
```

### **Iniciando o projeto**

```bash
# Execute yarn para instalar as dependências
$ yarn

# Execute stripe listen para ouvir eventos do webhook em modo de desenvolvimento
$ stripe listen --forward-to localhost:3000/api/webhooks 

# Para iniciar a aplicação
$ yarn dev

```

---

## Licença

Distribuído sob a licença MIT. Veja [LICENSE](LICENSE) para mais informações.

---

## Autor

Feito por Nelson Araújo 👋🏽 Entre em contato!

[![Linkedin Badge](https://img.shields.io/badge/-Nelson-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/tgmarinho/)](https://www.linkedin.com/in/nelsonsantosaraujo/)
[![Gmail Badge](https://img.shields.io/badge/-nelsonsantosaraujo@hotmail.com-red?style=flat-square&link=mailto:nelsonsantosaraujo@hotmail.com)](mailto:nelsonsantosaraujo@hotmail.com)