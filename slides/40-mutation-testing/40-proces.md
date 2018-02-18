### How it works

1. Production code is mutated
    * Collecting _mutants_
1. Run your tests for each Mutant
    * If tests _fail_, the mutant is _killed_
    * If tests _pass_, the mutant _survives_
1. The % of killed mutants is your _mutation score_