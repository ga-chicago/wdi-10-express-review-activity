![ga_cog](https://camo.githubusercontent.com/6ca75e52ba7cf640161aefd5355a4fbfff7d5f18/687474703a2f2f6d6f62626f6f6b2e67656e6572616c617373656d622e6c792f67615f636f672e706e67)

# wdi-10-chi

![sisko thinking](http://images2.fanpop.com/image/photos/13600000/Benjamin-Sisko-benjamin-sisko-13605618-694-530.jpg)


# Review Exercise - REST: Index/Show

Adapted by: Reuben Ayres

## Superheros

### Basic Express App
1. Create a directory for this lab `express_rest_review_lab`
1. Create a new directory inside your labs dir called "superheroes"
1. cd into superheroes
1. perform an npm init, specify server.js as your entry
1. install express
1. create a server.js file
1. inside server.js, require express and save it to a variable named `express`
1. create a variable named app, and set it equal to `express()`
1. have app listen on port 3000
    - once it's listening, log "Here to save the day..."
1. test it by going to http://localhost:3000

### Routes

1. Create a variable called superheroes and set it to ['batman', 'superman', 'hulk']
1. Create a route to /superheroes
    - The route should send the entire superheroes array
1. Create a route to /superheroes/:index
    - The route should send the superhero that is at the index in the superheroes array as specified by req.params.index

### Enhancing Data

1. Change the entries in the superheroes array so that each element in the array is an object
    - E.g. Instead of 'superman' have: `{ name: "superman", powers: ['flight', 'invulnerability', 'x-ray vision']}`

## Friends

1. cd back (up) into the lab directory
1. create a directory called friends
1. cd into friends
1. Create a basic express app
1. Create a variable inside server.js that is an array of your friends
1. Create index and show routes
1. Enhance the data so that each friend is an object with age, location, eyeColor, hairColor attributes
