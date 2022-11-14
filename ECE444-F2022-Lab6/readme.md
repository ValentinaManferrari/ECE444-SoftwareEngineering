Valentina Manferrari

The ``` flaskr-tdd ``` repo follows the instructions of https://github.com/mjhea0/flaskr-tdd from “First Test” to “Conclusion” 
to generate a Flask project similar to the Flaskr project shown in the Tutorial.

## Pros and Cons of TDD ##

#### Advantages ####
1. **No redundancy**: following the principles, you need to prevent writing production code when all of your tests pass. If your project needs another feature, you would like a test to drive the implementation of the feature. The code you write is the simplest code possible. So, all the code ending up within the product is really needed to implement the features.
2. **Easy to maintain and refactor**: because the different parts of the application are decoupled from one another and have clear interfaces, the code becomes easier to take care of. In addition, every feature is thoroughly tested so there is no need of being afraid of drastic changes because as long as all the tests pass, everything is still ok. 
3. **High test coverage of edge-cases**: having a test for each feature leads to a high test coverage.

#### Disadvantages ####
1. **No silver bullet**: tests help to seek out bugs, but they can not find bugs that are introduced within the test code and in implementation code. 
2. **Initial Slow Process**: initially, TDD slows down development. For rapidly iterative startup environments the implementation code may not be ready for some time due to spending time writing tests first, but in the long run, it actually speeds up development.
3. **The entire team has to do it**: as TDD influences the planning of code, it’s recommended that either all the members of a team use TDD or nobody.
5. **Tests for some features/components can be difficult to implement**: e.g. frontend components, creating tests for failures, existing legacy code

