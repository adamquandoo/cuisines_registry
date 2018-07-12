# Cuisines Registry

## The story:

Cuisines Registry is an important part of Book-That-Table Inc. backend stack. It keeps in memory customer preferences for restaurant cuisines and is accessed by a bunch of components to register and retrieve data. 


The first iteration of this component was implemented by rather inexperienced developer and now may require some cleaning while new functionality is being added. But fortunately, according to his words: "Everything should work and please keep the test coverage as high as I did"


## Your tasks:
1. **[Important!]** Adhere to the boy scout rule. Leave your code better than you found it.
It is ok to change any code as long as the CuisinesRegistry interface remains unchanged.
2. Make is possible for customers to follow more than one cuisine (return multiple cuisines in de.quandoo.recruitment.registry.api.CuisinesRegistry#customerCuisines)
3. Implement de.quandoo.recruitment.registry.api.CuisinesRegistry#topCuisines
4. Create a short write up on how you would plan to scale this component to be able process in-memory billions of customers and millions of cuisines (Book-That-Table is already planning for galactic scale). (100 words max)

## Submitting your solution

+ Fork it to a private github repository, make it accessible via key:
```
ssh-rsa AAAAB3NzaC1yc2EAAAADAQABAAABAQDGLeS0c6nx/4lUpdPCLugvQmO0wxjjm5XbgreXY+8o0YRBStpkzdDRABOK+1rNEjP6NGFOJ10mfe2TovItRHEqkyobOuPlHRRhYX65Grxh4gLq4umlCCSXAInT3RY7JvLncZumpSxWlsDuNpKfGwPd7V6x6XXPvCqeVYEFdLOSVmPPgWXUG0YcaWaV/u2fNaXI9tYll8VTDX0kiNORVhyANaT4CMBfNLmtdx6+U9sof/3sOtkUpH3MZX2Ip5qMSARCZ6VmHr5RT9iVrkg9rO1ZnvYVQObwycxiEhMvOIhdGWhh67DuL+bzA1K6OnFE3wcGa2Z8Tb8b4nsrLYJsvt2/ adg@adams15.local
```
+ Put write up mentioned in point 4. into this file.
+ Send us a link to repository.