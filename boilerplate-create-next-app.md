# Boilerplate Create-Next-App

Utilize o comando abaixo para iniciar um novo app Next.js

```bash
npx create-next-app
# or
yarn create next-app
```

No decorrer da instalação insira o nome do app, no nosso caso se chamará 'client' e se quiser escolha um boilerplate pronto.

## Scripts

O NextJS já oferece scripts prontos que referem-se aos diferentes estágios de desenvolvimento de um app:

- dev (next dev): Inicia Next.js em um servidor no modo de desenvolvimento e sincroniza as alterações.
- build (next build): Gera o código do aplicativo para uso em produção, seja estático ou SSR.
- start (next start): Inicia um servidor de produção Next.js com o código gerado no build.

## Estrutura

O Create-Next-App já vem com um estrutura básica com os seguintes pastas e arquivos:

- **node_modules**: Pasta com os todos pacotes e dependências do projeto.
- **pages**: Onde ficarão as páginas do Next.js.
- **pages/api**: Apesar de ser um framework front-end, O Next também permite a criação de REST API's, como a API desse projeto será feita no Strapi, então vamos remover essa pasta.
- **public**: Arquivos públicos, em greal arquivos estáticos como Favicon, logos, imagens, robots, enfim, tudo o que queremos que seja público, acessado direto numa rota.
- **index.js**: Página padrão com o exemplo de código.

## Referência

- [NextJS](https://nextjs.org/docs)
