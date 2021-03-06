# Assignment 1 - 25 Marks

**Due before 5pm, Friday 3rd August**

Your answers to all questions should be submitted to myUni as a single R markdown file with the file suffix `.Rmd`.

- A compiled html, MS Word or PDF document is not required, but will be generated when marking.[*1 mark*]
- Ensure your submitted file begins with your student number.
- Add appropriate text and/or comments making your thoughts clear to any collaborators. [*2 marks*]

## Obtaining Your Data

All data is in the file [available here](DataForA1.zip).
Please extract the set of files, and use the file labelled with your student id.

## Tasks in R

1. Load your allocated file removing all comments, blank rows and changing any encoded missing values to `NA`. [*4 marks*]
2. Extract the CellType and Treatment information from the sample names, placing them in separate columns after converting from wide to long form. [*4 marks*]
3. Create a correctly labelled boxplot of your `dCt` values for each of the four conditions. [*4 marks*]
4. Conduct a simple linear regression on your data using the model `dCt~CellType + Treatment + CellType:Treatment` and include the model output from the function `summary()` without interpretation. [*2 marks*]

## Research questions

Please answer on the same `*.Rmd` file as the first section, using a new markdown heading for this section.

1. Two common file types are `.csv` and `tsv`. What is the difference between the two, and can you suggest a function for loading a `.tsv` file into R? [*3 marks*]
2. Three types of message output commonly seen in R are 1) error messages, 2) warnings and 3) general messages. Briefly describe the importance of each type of message and what information they are conveying. [*3 marks*]
3. What is the difference between an integer and a floating point value? Floats are sometimes called "doubles". What does this mean? [*2 marks*]
