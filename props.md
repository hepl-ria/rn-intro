## Making the header reusable
* Dans notre cas, c'est la fonction App qui rendra le header, ça serait donc mieux si elle pouvait décider du contenu à afficher en fonction du contexte
* Pour se faire, on utilise les props, je ne vais pas trop expliquer ce que c'est aujourd'hui. Props = property. Que dit la doc : Most components can be customized when they are created, with different parameters. These creation parameters are called props.
* Passer un(e) props à l'enfant (Header)
* S'assurer que le parent (App) passe bien la props à l'enfant (Header)
