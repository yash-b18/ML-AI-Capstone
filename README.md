### Project Title

<p>Yash Bhargava</p>

#### Executive summary

#### Rationale
Why should anyone care about this question?

#### Research Question
<p>Predict whether a user will click on an advertisement based on their browsing behavior and ad features.</p>

#### Data Sources
<p>The dataset being used is <a href="https://www.kaggle.com/datasets/marius2303/ad-click-prediction-dataset?resource=download">Ad Click Prediction Dataset</a> from Kaggle.com.</p>

<h3>About Dataset</h3>
<p>This dataset captures key aspects of user behavior and online advertising, aiming to predict whether a user will engage with an advertisement by clicking on it. It includes information on user demographics, browsing activities, and specific attributes of the displayed advertisement.</p>
<p>There are 9 features: 
    <ul>
        <li>id: Unique identifier for each user.</li>
        <li>full_name: User's name formatted as "UserX" for anonymity.</li>
        <li>age: Age of the user (ranging from 18 to 64 years).</li>
        <li>gender: The gender of the user (categorized as Male, Female, or Non-Binary).</li>
        <li>device_type: The type of device used by the user when viewing the ad (Mobile, Desktop, Tablet).</li>
        <li>ad_position: The position of the ad on the webpage (Top, Side, Bottom).</li>
        <li>browsing_history: The user's browsing activity prior to seeing the ad (Shopping, News, Entertainment, Education, Social Media)</li>
        <li>time_of_day: The time when the user viewed the ad (Morning, Afternoon, Evening, Night).</li>
        <li>click: The target label indicating whether the user clicked on the ad (1 for a click, 0 for no click).</li>
    </ul>
</p>

<p>Note: The dataset previously chosen to be used has changed. Before, the dataset to be used was <a href="https://www.kaggle.com/c/avazu-ctr-prediction/data">Click-Through Rate Prediction</a></p>

#### Methodology
<p>The methodology involved several steps including:
    <li>Data preprocessing to clean and prepare data.</li>
    <li>Feature engineering and transformation to make features suitable for modeling.</li>
    <li>Model training and evaluation using Logistic Regression, Decision Trees, and Random Forest.</li>
    <li>Hyperparameter tuning to optimize each model's performance.</li>
</p>

#### Results
<p>After building 3 types of models: Logistic Regression, Decision Tree, and Random Forest, we hyperparameter tuned these models to achieve the best result possible. As a result, the best model was Decision Tree where the best parameters for this model was a max depth of 2 and min samples split of 2. The model achieved a 0.7265 or 72.65% accuracy on test data.</p>
<p>Random Forest came a close second and achieved a accuracy of 0.7150 or 71.50% accuracy on test data. Logistic Regression peformed the worst.</p>

#### Next steps
Some things that can be done to further improve the model built include further hyperparamter tuning. Some hyperparameters that can be used include:

min_samples_leaf: Minimum number of samples required to be at a leaf node.
max_features: Number of features to consider when looking for the best split.
ccp_alpha: Use to reduce overfitting.

We can also examine feature importance to understand which features contribute the most and remove the less important ones if necessary.

Another step that can be taken are feature selection techniques such as recursive feature selection (RFE) to improve model focus.

Further more, model should be tested on more data.

#### Outline of project

- <a href="https://github.com/yash-b18/ML-AI-Capstone/blob/main/ad-click.ipynb">Link to notebook 1</a>

##### Contact and Further Information