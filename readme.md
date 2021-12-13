# Skelbimu portalas

Skelbimų portalas

## Funkcionalumas:

1. Vartotojo registracija,
2. Prisijungimas, (jwt)
3. Skelbimu įkėlimas,
4. Galimybė prisidėt skelbimą į favorites
5. MyAccount puslapis kuriame matome tik savo skelbimus ir galime sukurti nauja
6. HomePage, prisijunge ir neprisijunge matome visus skelbimus

## Techonolgija

1. Front end React.js
2. Back end node.js, express.js
3. DB mysql arba mongoDb.

<!-- ## Eiga (nebutinai tokia tvarka) -->

## Reikia:

1. Susikuriam frontui create-react-app pasivadinam `skelbiu-fe-(jusu vardu inicialai)`. Susiejam su to paties vardo repozitorija github
   pvz `skelbiu-fe-mk`
2. Susikuriam backui node express projekta(pradziai gali but tik packacege.json ir index.js failai) pasivadinam `skelbiu-api-(jusu vardu inicialai)`. paties vardo repozitorija github
   pvz `skelbiu-api-mk`

## Front end struktura

- HomePage

  - navbar - home, login, register
  - content - ateje matom visus skelbimus
  - footer

- HomePage (prisiloginus)

  - navbar - home, logout, MyAccount
  - content - ateje matom visus skelbimus
  - footer

- MyAccount - (matomas tik prisijungus)

  - content
    - createAdd - sukurti skelbima
    - listOfMyAdds - mano skelbimai

- RegisterPage

  - Register component

- LoginPage

  - LoginComponent

## BACK END response

Lets always respond in a same way

```
Success response:
{
  msg: 'success message',
  data: []/{}
}
Error response:
{
  error: 'error message',
  errors: [] // optional
}
Let respond with 2 error response codes:
- 500 (server error)
- 400 (bad input)
```

## Pavyzdziai

1. [Radiustheme](https://www.radiustheme.com/demo/wordpress/themes/classilist/)
