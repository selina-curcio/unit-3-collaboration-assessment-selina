Welcome to **TreeLife**, your guide to learning about the beauty, diversity, and importance of trees around the world. 


# About us
At **TreeLife**, we're passionite about forests and green living.

Our mission is to:
- Educate people about the different types of trees.
- Promote sustainable forestry.
- Encourage reforestation projects.

  "The best time to plant a tree was 20 years ago. The second best time is now."

  -- *Chinese Proverb*

# Featured Trees

### Oak Tree
**Scientific Name:** *Quercus robur*

Known for its strength and longestivity, the oak is a symbol of endurance. 
![image 1](https://s3-eu-west-1.amazonaws.com/blog-ecotree/blog/0001/01/ad46dbb447cd0e9a6aeecd64cc2bd332b0cbcb79.jpeg)

### Pine Tree

**Scientific Name:** *Pinus*

Evergreen and aromantic, pine trees thrive in colder regions.
![image 2](https://www.fertilome.com/media/klowrey/Article%20Images/Tree.jpg)

# Tree Identification Tool

You can user this simple **Javascript** function to identify a tree by its characteristics:

```
  function identify_tree(leaf_shape, region) {
   if (leaf_shape == "meedle" && region == "cold") {
       return "Pine Tree"
   } else if (leaf_shape == "broad" && region == "temperate) {
       return "Oak Tree"
   } else {
      return "Unknown Tree"
   }
}
console.log(identify_tree{"needle", "cold"})