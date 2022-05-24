# Color Variables Proposal

In the JSON data of the design tokens, I noticed something about the relationship between the color variables. In the below diagram of minified version of our design tokens, we see this relationship. There is a category called "main source", which has all the color variables in it. In this "main source", there are other categories as well: "brand categories" and "text colors" for the moment. We have other categories but I omitted them so we can focus easily. At the moment, as far as I can see, this relationship of categories doesn't give a clear idea how do we deal with multiple labels.

![](colors-visualization.png "Color visualization")

My idea of this relationship is a bit different. Instead of we have this "main source", we have it as the brand's name. This will allow us to incorporate multiple labels' color variables. Therefore, my initial thought of this relationship is this:

![](color-visualization-proposed.PNG "Proposed color variable structure")

In this diagram, each label we have has the same variable names, but they have different colors. This way we can incorporate different labels' colors with the same variable names. In the above diagram, both "funxtion" and "goodlife" brands have brand colors and text colors. But their values are different.

## Adding New Colors

In this proposed relationship, if we want to introduce a new variable in the design, we need to define that variable's name in each label in each color category.