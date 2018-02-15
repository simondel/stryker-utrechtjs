### Mutation testing process

1. Production code is mutated
    * A mutated version of your app is called a Mutant
1. Your tests are ran for each Mutant
    * If tests fail, the mutant is killed
    * If tests pass, the mutant survived
1. The percentage of mutants that got killed is your mutation score