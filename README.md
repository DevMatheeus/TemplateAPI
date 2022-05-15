# **Basic GraphQL Template v3.097**

## **Como usar?**

Já está tudo configurado! Simplesmente substitua o campo `[username]` ao chamar a função `getData`

Exemplo:
```js
getData('MatheeusDev');
```

Output:
```js
{
  karma: 653,
  firstName: 'MatheeusDev',
  lastName: 'Sim',
  bio: 'Biografia',
  isVerified: true,
  timeCreated: '2022-05-09T12:47:49.218Z',
  isLoggedIn: false,
  organization: { name: 'Equipe' },
  subscription: { planId: 'Sua colocação' },
  roles: [ { name: 'Nome do Cargo' }, { name: 'explorer' } ]
}
```
