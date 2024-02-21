# FastAPI + SQLAlchemy + GraphQL + NextJS

<!-- toc -->

- [Site](#site)
- [Getting Started](#getting-started)
- [Interactive GraphQL and NextJS app: `http://127.0.0.1:3000/graphql`](#interactive-graphql-and-nextjs-app-http1270013000graphql)

<!-- tocstop -->

## Site

https://blog.logrocket.com/using-graphql-strawberry-fastapi-next-js/

This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app). It demonstrates how to use Strawberry, FastAPI, SQLAlchemy, and NextJS together. It makes use of `graphql-codegen` to automatically generate `urql` hooks based on GraphQL API that are ready to use in your React/NextJS code.

## Getting Started

```bash
$ pip install -r requirements.txt # dependencies
$ npm install #install the npm based dependencies:
$ python models.py # Create the db:
$ uvicorn app:app --reload --host '::' # run the `uvicorn` server:
$ npm run dev # Finally, run the NextJS development server:
    # or
    # yarn dev
```

## Interactive GraphQL and NextJS app: `http://127.0.0.1:3000/graphql`
