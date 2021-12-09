# Skelbimu portalas

Skelbimų portalas

## Funkcionalumas:

1. Vartotojo registracija,
2. Prisijungimas, (jwt)
3. Produktų įkėlimas,
4. Galimybė prisidėt skelbimą į favorites

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

  - navbar - home, logout, MyAdds
  - content - ateje matom visus skelbimus
  - footer

- MyAdds - (matomas tik prisijungus)

  - content
    - createAdd - sukurti skelbima
    - listOfMyAdds - mano skelbimai

- RegisterPage

  - Register component

- LoginPage

  - LoginComponent

### createAdd component

form than allows to create new add,

### fields:

1. title
2. body
3. price
4. image - upload field

## Pavyzdziai

1. [Radiustheme](https://www.radiustheme.com/demo/wordpress/themes/classilist/)
2. [Clasic shop](https://flatsome3.uxthemes.com/demos/shop-demos/classic-shop/)
3. [Clasic simple slider](https://flatsome3.uxthemes.com/demos/shop-demos/simple-slider/)
4. [Bridgelanding](https://bridgelanding.qodeinteractive.com/shop-with-sidebar/)
