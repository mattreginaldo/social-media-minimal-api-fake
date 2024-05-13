# Social REST API

Uma api fake que traz dados iniciais para posts, profile e roles e que pode ser usada para testar um CRUD.

## Requisitos

- NodeJS
- pnpm
- json-server

Veja mais em [json-server](https://github.com/typicode/json-server/tree/v0?tab=readme-ov-file#getting-started)

## Rodando projeto

Rodar este projeto é simples:

```sh
pnpm install ou pnpm i
```

```sh
json-server --watch db.json
```

## Routes/Endpoints

- /posts - Postagens
- /user - Dados fake de um usuário
- /roles - Ramos de atuação profissional da area de tecnologia

## Hospedagem

A hospedagem da API fo feita no Vercel, pode ser acessada em:

[API Fake](https://social-media-minimal-api-fake.vercel.app/)

Assim como as rotas: 

[https://social-media-minimal-api-fake.vercel.app/posts](https://social-media-minimal-api-fake.vercel.app/)

[https://social-media-minimal-api-fake.vercel.app/user](https://social-media-minimal-api-fake.vercel.app/)

[https://social-media-minimal-api-fake.vercel.app/roles](https://social-media-minimal-api-fake.vercel.app/)

## Consideranções sobre a API Fake

Você vai perceber que depois de um determinado tempo os dados são resetados na API e que ela volta ao estado inicial.

<p align="center"><img  src="https://user-images.githubusercontent.com/51330232/197884349-fec3877b-df77-4467-bd89-7d39a435530a.png"/></p>

<div align="center">
    <img width="75px" src="https://scontent.cdninstagram.com/v/t39.30808-6/410252134_18391801138066325_1508734687614870344_n.jpg?stp=dst-jpg_e35&efg=eyJ2ZW5jb2RlX3RhZyI6ImltYWdlX3VybGdlbi4xNDQweDE0NDAuc2RyLmYzMDgwOCJ9&_nc_ht=scontent.cdninstagram.com&_nc_cat=105&_nc_ohc=lRiQjY5Fw8YQ7kNvgEau2Cs&edm=APs17CUAAAAA&ccb=7-5&ig_cache_key=MzI1OTk2NTgxODY0NDUwNjc4Mw%3D%3D.2-ccb7-5&oh=00_AYBQs0a7pdtY637dcL0rhSmQAwQC4YCvGLAlRqHIw_Ug3A&oe=6645F5B3&_nc_sid=10d13b">
  <p align="center">
    Built and maintained by <a href="https://www.linkedin.com/in/mateusreginaldo/">Mateus Reginaldo</a>.
  </p>
</div>
