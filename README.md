# Food preference data

This dataset is capable of making preference judgments for food images in federated learning.
Ten evaluators were each provided with 100 images per class, selected from the Food-101 dataset [1], resulting in 1,000 images across 10 classes.
Evaluators rated their preferences for each image on a 10-point scale, where one indicates a low preference, and ten indicates a high preference.

## Classes used
This data covers the following 10 food classes.

- cheesecake
- cupcake
- French toast
- fried rice
- grilled salmon
- hamburger
- miso soup
- pizza
- ramen
- sushi

## Contents of csv file
Each line of this csv file represents the information of one image.

- First row: Client name (A to J)
- Second row: Food class
- Third row: Image file name in Food-101
- Fourth row: Rating score (1 to 10)

## References
[1] L. Bossard, M. Guillaumin, and L. Van Gool, "Food-101 -- mining discriminative components with random forests," in European Conference on Computer Vision, pp. 446--461, 2014.
