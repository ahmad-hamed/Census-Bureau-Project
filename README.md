# Census-Bureau
Overview about the problem, Analyze Dataset of Census Bureau, Build business insights, Make Recommendation for Business, Build machine learning model(i use Catboost and Evaluate  its performance and get accuracy 90%) for classification problem (income >50K or <= 50k annual income)

OverView

The United States Census Bureau (USCB), officially the Bureau of the Census, is a principal agency of the U.S. Federal Statistical System, responsible for producing data about the American people and economy. The Census Bureau's primary mission is conducting the U.S. Census every ten years, which allocates the seats of the U.S. House of Representatives to the states based on their population. The Bureau's various censuses and surveys help allocate over $675 billion in federal funds every year and it helps states, local communities, and businesses make informed decisions. The information provided by the census informs decisions on where to build and maintain schools, hospitals, transportation infrastructure, and police and fire departments.
why this is analysis important ?

    Census statistics can help businesses to understand customers and answer important decisions including, depending on the type of commercial activity.

    Where are the best places for new retail outlets?

    What products and services should be offered in stores?

    Where is the best place to advertise?

    Which areas and people should be surveyed?

    Major business decisions invariably carry an element of risk, so anything that increases confidence and minimises risk is to be welcomed.

    Census statistics can inform growth plans and provide management, board and investors with reliable evidence and the confidence to enable them to make those important decisions.

    The data can also help to identify where your business might benefit from more detailed market research to address specific business development issues

Problem Definition:

Given a Census with general information about randomly choosen US citizens, can we predict whether their annual income is above or below 50K?

1- Data

Data provided in CSV file format with approximtly 33000 Observations
2- Data Cleaning
3- Exploratory Data Analysis & Build insights
4-Feature Encoding
5- Building Model

  in this part we tried many algorithms (KNN,Logistic Regression, Random Forest, XGboost, Catboost)

6- Tuning Hyperparameters

Choosing best_model and tune its hyperparameter to get more performed model

7-Evaluation

Will be the model able to reach a 90% Accuracy at predicting whether a US citizen has an yearly income higher or lower than 50K?

8-Important Features

In this part we try to get the features which affect the model prediction and Training

Data Features

    age:

    continuous value

    workclass:

    Private Self-emp-not-inc, Self-emp-inc, Federal-gov, Local-gov, State-gov, Without-pay, Never-worked.

    education:

    Bachelors, Some-college, 11th, HS-grad, Prof-school, Assoc-acdm, Assoc-voc, 9th, 7th-8th, 12th, Masters, 1st-4th, 10th, Doctorate, 5th-6th, Preschool.

    education_num:

    continuous value

    marital_status:

    Married-civ-spouse, Divorced, Never-married, Separated, Widowed, Married-spouse-absent, Married-AF-spouse.

    occupation:

    Tech-support, Craft-repair, Other-service, Sales, Exec-managerial, Prof-specialty, Handlers-cleaners, Machine-op-inspct, Adm-clerical, Farming-fishing, Transport-moving, Priv-house-serv, Protective-serv, Armed-Forces.

    relationship:

    Wife, Own-child, Husband, Not-in-family, Other-relative, Unmarried.

    race:

    White, Asian-Pac-Islander, Amer-Indian-Eskimo, Other, Black.

    sex:

    Female, Male.

    capital_gain:

    continuous value. profit one earns on the sale of an asset like stocks, bonds or real estate

    capital_loss:

    continuous value. loss one incurs on the sale of an asset like stocks, bonds or real estate.

    hours_per_week:

    continuous value.number of working hours per week

    native_country:

    United-States, Cambodia, England, Puerto-Rico, Canada, Germany, Outlying-US(Guam-USVI-etc), India, Japan, Greece, South China, Cuba, Iran, Honduras, Philippines, Italy, Poland, Jamaica, Vietnam, Mexico, Portugal, Ireland, France, Dominican-Republic, Laos, Ecuador, Taiwan, Haiti, Columbia, Hungary, Guatemala, Nicaragua, Scotland, Thailand, Yugoslavia, El-Salvador, Trinadad&Tobago, Peru, Hong, Holand-Netherlands.

    class:

    >50K or <=50K (annual income )

    income value

    Actual income


