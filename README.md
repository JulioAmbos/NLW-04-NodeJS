<h1 align="center">NPS-NLW</h1>

<p align="center">
  <a href="#-tecnologias">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-projeto">Projeto</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-diagrama">Diagrama</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-como-executar">Como executar</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-licença">Licença</a>
</p>

<p align="center">
  <img alt="License" src="https://img.shields.io/static/v1?label=license&message=MIT&color=8257E5&labelColor=000000">

 <img src="https://img.shields.io/static/v1?label=NLW&message=04&color=8257E5&labelColor=000000" alt="NLW 04" />
</p>

<br>

<p align="center">
  <img alt="NPS" src="https://github.com/JulioAmbos/NLW-04-NodeJS/blob/main/Public/survey.jpg" width="100%">
</p>

## ✨ Tecnologias

Esse projeto foi desenvolvido com as seguintes tecnologias:

- [TypeScript](https://www.typescriptlang.org/)
- [Ethereal-Email](https://ethereal.email/)
- [SQL Editor Beekeeper Studio](https://www.beekeeperstudio.io/)
- [typeorm](https://typeorm.io/#/using-ormconfig) -  ORM baseado em entidades
- [express](https://expressjs.com/) - Framework para servidor
- [uuid](https://github.com/uuidjs/uuid) - gerador de ids únicos, como estamos usando uma ORM, pode ser que algum banco não comporte o autoincrement.
- [@types/express](https://www.npmjs.com/package/@types/express) - Permite visualizar métodos de henrança do express no modelo de typescript
- [jest](https://jestjs.io/docs/pt-BR/getting-started) - utilizado para realizar os testes
- [@types/jest](https://www.npmjs.com/package/@types/jest) - utilizado para setar a tipagem do pacote jest, recomendado para ambiente de dev
- [supertest](https://www.npmjs.com/package/supertest) - utilizado para simular fetchs, é utilizado junto com o jest
- [@types/supertest](https://www.npmjs.com/package/@types/supertest)
- [nodemailer](https://nodemailer.com/usage/) - utilizado para enviar email e tem um método de test que gera um link para visualizar como o email ira ficar
- [handlebars](https://handlebarsjs.com/) - auxiliar para criar views/templates de modo facil e dinâmico
- [yup validation](https://github.com/jquense/yup) - validador simples e objetivo de parametros
- [express-async-errors](https://www.npmjs.com/package/express-async-errors) - quando criamos um middleware para controlar erros é necessário ter essa lib

## Finalidade

Estudo e aplicação de novas técnicas.

## 💻 Projeto

O NPS-NLW é uma aplicação que consiste em calcular o NPS da empresa. Nele fazemos o cadastro de usuários, cadastro de pesquisas, envio de e-mail para os usuários responderem as pesquisas de satisfação e com isso podemos realizar o cálculo do NPS.

Esse projeto foi desenvolvido durante a trilha de NodeJS, na quarta edição da NLW. Aprendemos conceitos sobre o que é um API, como iniciar um projeto utilizando Typescript e Express para gerenciamento das rotas, TypeORM para manipulação dos dados, testes automatizados e envio de e-mail.
## Imagem ilustrativa de como é realizado o calculo do NPS:
<img src="https://github.com/JulioAmbos/NLW-04-NodeJS/blob/main/Public/gr%C3%A1fico-score-NPS-1024x419.jpg" alt="NPS" />

## 🔶 Diagrama


  <img alt="Diagrama da aplicação" src="https://github.com/JulioAmbos/NLW-04-NodeJS/blob/main/Public/diagrama.png" width="100%">

  <img alt="NODE" src="https://github.com/JulioAmbos/NLW-04-NodeJS/blob/main/Public/node.jpg" width="100%">



## 🚀 Como executar

- Clone o repositório
- Instale as dependências com `yarn`
- Inicie o servidor com `yarn dev`

A aplicação pode ser acessada em [`localhost:3333`](http://localhost:3333).

## 📄 Licença

Esse projeto está sob a licença MIT. 

## Agradecimentos

A dedicação da professora Daniele Leão. Muito obrigado Professora! 

---

Feito com ♥ by [Julio Moraes](https://www.linkedin.com/in/j%C3%BAlio-c%C3%A9sar-ambos-moraes-2685381ba/)
