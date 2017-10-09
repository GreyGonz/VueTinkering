# Vue

https://vuejs.org

## Watch i computed

https://vuejs.org/v2/guide/computed.html

watch actuara en quant el que definim dins cambie

En el cas següent si la variable tasks cambia s'executara el console.log

    watch: {
        tasks() {
            console.log('OK');
        }
    }

## mounted

tot el que declarem dins de mounted s'executara a l'inici del programa

https://vuejs.org/v2/api/#mounted

# JSON

- parse: llegir un objecte

- stringify: guardar un objecte

## Extensió vue per a chrome

https://chrome.google.com/webstore/detail/vuejs-devtools/nhdogjmejiglipccpnnnanhbledajbpd/related?hl=es

# ES6

Format per definir variables

# CSS 

CDN de font awesome, una llibreria de icones

    <link href="https://maxcdn.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css" rel="stylesheet" integrity="sha384-wvfXpqpZZVQGK6TAh5PVlGOfQNHSoD2xbE+QkPxCAFlNEevoEH3Sl0sibVcOQVnN" crossorigin="anonymous">

# JS

Funció anonima o closure

    add('hey', function() {})

o

    add('hey', () => {})