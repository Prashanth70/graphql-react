# graphql-react

## Graphql + React [simple example](https://graphql-react-example.netlify.app/)

Make query `GetExchangeRates` here https://48p1r2roz4.sse.codesandbox.io

```
query GetExchangeRates {
    rates(currency: "USD") {
      currency
      rate
    }
  }
```

![gif](gif.gif)

---

### Creat React typescript project

```shell
$ npx create-react-app my-app --template typescript
$ yarn add @apollo/client graphql
```

---
