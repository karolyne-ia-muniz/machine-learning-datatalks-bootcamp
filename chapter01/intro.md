-> ML and rule based systems
rule based systems (if/else) can work, but as the system grows and becomes more complex, managing it becomes harder - it breaks, filters things (like in the example spam) incorrectly, and its not fully automated too. 
A useful solution is to use ML, we give the ML a dataset we know the results of and it predicts new answers to a new dataset based on the one that was given to it.

-> one of the different types of classification:
- regression: outputs numbers, like in the examples prices of houses, retail of car, etc
- classification: like the name implies, it outputs a classification of the thing, like input -> picture of car, output -> car. or classifying spam
    - multiclass: classify an image in a number of categories 
    - binary: spam or not spam (Dr Perceptron, futurama)
- ranking: a recomendation system, like visiting an online shop, usually ranked by relevance in a scale from 1 to 0

CRISP-DM
a robust system, still useful to this day used for vairous applications, like ML for spam
Bussiness understanting: is there really a reason to build an ml?
data understading: understading how it works and whats happening
data prep: classifying the data, making etl
modeling: choosing the right model, evaluating features, fixing data
evaluation: was the model good enough? what was the overall goal? have we reduced it (incresead)? is that amount good enough? 
    restrospective: was the goal achiavable in the beggining? did we measure the right thing?
    then:
        go back and adjust the goal;
        roll the model to more users or all
        or stop working on the project enterily
if everything went well, we deploy: online evaluation, evaluation of live users


Model evaluation process
