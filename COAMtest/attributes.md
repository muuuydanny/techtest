turkey_sandwich  

number_of_layers = 1
ingredients = ["bread", "tomato", "lettuce", "turkey"]
edible = true
calories = 300
protein_type = ["turkey", "seitan"]

Method results

add_layer: adds 1 to current_layers = 3
take_bite: removes 10 from 300 = 290
spoil: edible = false
add_protein: Add bacon = ["turkey", "seitan", "bacon"]




Attributes
current_layers (integer)
number_of_layers (integer)

ingredients (array)

edible (boolean)

calories (integer)

protein_type (array)

methods

add_layer (adds 1 to current_layers integer)

take_bite (removes 10 to calories integer)

spoil (When called on the sandwich it flips boolean  edible to false)

add_protein (adds protein to protein_type array)
