# Workflow
A method of checking if images match before creating a dataset.

## Visual Mindmap
![Workflow Schedule](https://github.com/LWFlouisa/Workflow/blob/main/workflow.png?raw=true)

## Pseudocode
~~~txt
Workflow

A distinction between the user and the ai.
    Create User Image The user must have and process a set of images into ASCII.
    Create   AI Image The AI is trained on these image, based on its height, width, and depiction.

The user has a description of the image, and the AI has a description of the image.
    ( COMPARE user and AI image.

    ( If the image matches, the AI uses that image model to train its data set.
      A. CREATE an DSXML file of the results of the test.
      B. After the DATASET is trained the Baysian model can be used for later.

    ( Else if the image image doesn't match.
      A. Reattempt to find image until match is found.
      B. CREATE an DSXML file of the results of the test.
      C. Once found, that image trains the DATASET, which can be used later for ANALYSES.
~~~
