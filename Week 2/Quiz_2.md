## 1.
Here are the heights, in feet, of the hightest points in the 50 United States:
```
2413, 20310, 12637, 14505, 14440, 2379, 447, 345, 4784, 13803, 12668, 1235, 1257, 1671, 4041, 4145, 535, 5270, 3360, 3489, 1979, 2302, 807, 1772, 12807, 5427, 13147, 6288, 1803, 13167, 5343, 6684, 3508, 1549, 4975, 11249, 3213, 811, 3560, 7244, 6643, 8751, 13534, 4395, 5729, 14417, 4863, 1951, 13809
```
Use `c()` to put them in an R vector called `heights`.

Run `sort(heights)` to see a sorted version of your vector.

What is the smallest of the state high points?

###answer: 345

## 2.
What is the largest state high point?

(You don't need to answer this parenthetical question in the quiz. Do you know which states has the lowest high point, and which state has the highest?)

### answer: 20310

## 3.
What is the average height? (Give an exact answer. It has two decimal places.)

###answer: 6164.28

## 4.
What is the median height? (Give an exact answer. It has one decimal place.)

###answer: 4589.5

## 5.
Make a dot plot of the heights by running `stripchart(heights)`. On which side is the outlying point?

### answer: right side

## 6.
Use `boxplot(heights, horizontal=TRUE)` to make a boxplot of the heights. Use `rug(heights)` in the same code chunk to add the data points themselves to the boxplot. Note that the median is marked by the thick vertical line inside the box. Half the data are to the left of the median and half are to the right. Which half extends further? (The data are said to be skewed in that direction.)

### answer: right half

## 7.
Use `hist(heights)` to make a histogram of the heights. About how many state high points are in the range 0 to 5000 feet? That is, how high is the bar over the interval from 0 to 5000?

### answer: 28
