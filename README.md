Sample GraphQL server implementation using Javascript

Steps to run the server:
`yarn && yarn start`


Then add something in the left panel:

```
{
  posts(id: 1) {
    body
    user {
      age
    }
  }
}
```

Explanation: https://blog.bitsrc.io/so-what-the-heck-is-graphql-49c27cb83754

![](https://github.com/anyexinglu/graphql-server-example/blob/master/WechatIMG5553.png)
