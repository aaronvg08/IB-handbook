A decision tree, also called a probability tree, is a visual decision-making toolkit that helps businesses evaluate different options by estimating values and probabilities.

In order to make a decision tree, you need to do the following:

- **Identify decision**: Define the specific business question that needs answering.
- **Map options**: Diagram all possible paths and outcomes.
- **Calculate values**: Determine expected values for each branch.

Decision trees are forward-looking tools that answer questions like: "Given a 60% chance of success, should we expand our factory?"

# Elements

A decision tree looks something like this.

![[decision trees.png|center|500]]

- **Decision node**: Represented by a square. Points where the business must choose between options.
- **Probability node:** Represented by a circle. Points where uncertain outcomes occur based on probability.
- **Branches**: Line connecting the nodes, showing possible options and outcomes with associated probabilities or values.
- **Rejected options**: Branches crossed out with lines when an option os determined to be suboptimal.

# Solving the decision tree

Once a decision tree is drawn, to solve it is to view all possible situations and discard the ones that are deemed non-viable. There are multiple steps to solve the decision tree.

## Step 1: Get the expected value

The first step is to calculate the [[Expected value|expected value]] of the outcomes that are in the decision tree. 

So, for the previous decision tree, in option three, we calculate for success,

$$
0.6\cdot$20\;\text{million}=$12\;\text{million}
$$

And for failure,

$$
0.4\cdot$8\;\text{million}=$3.2\;\text{million}
$$

Then, for option two, we do the same.

$$
0.6\cdot$10\;\text{million}=$6\;\text{million}
$$
$$
0.4\cdot$7\;\text{million}=$2.8\;\text{million}
$$

## Step 2: Get the total expected value

Then, you must get the total expected value of the two possible outcomes, both success and failure. We do this by adding the two possible [[Revenue|revenues]] of each option.

So, for the previous example,

$$
$12\;\text{million}+$3.2\;\text{million}=$15.2\;\text{million}
$$
$$
$6\;\text{million}+$2.8\;\text{million}=$8.8\;\text{million}
$$

## Step 3: Get the net expected value

Then, we have to account for the expenses of each choice. Since expanding the factory would cost $10 million, then we have to account for that. So, we subtract it.

$$
$15.2\;\text{million}-$10\;\text{million}=$5.2\;\text{million}
$$
$$
$8.8\;\text{million}-$0=$8.8\;\text{million}
$$

## Step 4: Draw the solved tree

After all of this, we must indicate the values we have found on the tree.

![[solved decision trees.png|center|500]]

So, after all of this, we can conclude that the best choice is to not expand, since the final result is bigger than the other ($\$8.8\;\text{million}>\$5.2\;\text{million}$).