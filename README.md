OVERVIEW

   This project contains an improved version of a digits classification notebook. The main focus of this work is improving the structure of the code compared to the earlier version. Instead of keeping everything in a single flow, the code is now modular, cleaner, and easier to understand.


WHAT WAS DONE ?

i) Functions were created for different tasks:

ii) load_and_split_data() – loads the digits dataset and splits it into training and test sets.

iii) plot_sample_digits() – shows a few digit samples for quick visualization.

iv) evaluate_model() – trains a model, prints accuracy, and shows the confusion matrix.

v) Constants like TEST_SIZE and RANDOM_STATE were defined at the top for easy adjustments.

vi) The workflow is wrapped inside if __name__ == "__main__": so the notebook/script has a clear entry point.


WHY THIS IS BETTER ?

i) The code is easier to read and maintain.

ii) Each function can be reused or tested separately.

iii) The structure makes it simple to add new models or features later.
