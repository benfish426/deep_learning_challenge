# deep_learning_challenge

Overview: The purpose of this analysis was to develop a deep learning model in order to predict the success of charity donations for Alphabet Soup, with the goal of acheiving at least 75% accuracy. The necessary steps required to take to complete our analysis include data preprocessing, designing a neural network model, optimization, and evaluation of the performance.

Results:

    Data Preprocessing
    
    * Target Variable: application_df["IS_SUCCESSFUL"]
    * Feature Variables:  APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, and ASK_AMT
    * Removed Variables: EIN and NAME, since they were neither targets nor features


    Compiling, Training, and Evaluating the Model

    * For my models, I used 3-4 layers of varying neurons size to see how it would affect the accuracy. Similar to my approach with number of neurons/layer, 
    I tried using relu, leaky_relu, and tanh activation functions for all layers, except for the last layer. For the last layer, I used the sigmoid function
    * Despite various attempts and trying several different techniques, I was unable to achieve a 75% accuracy rate or higher
    * In my attempts to increase model performance, I tried changing the sizes of my models as well as seeing how choosing particular activation functions would effect my results

Summary: Ultimately, I was not able to achieve the 75% threshold. Without time constraints, I believe I could have met the goal. If I tried another model, I would perhaps look closer at the preprocessing section and see if there were a better choice (limiting) for the features to focus on. This would help when I train, test, and split the data.
