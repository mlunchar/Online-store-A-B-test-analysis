# Online-store-A-B-test-analysis
This project was made as an assignment for Practicum100 Data Analyst course as a part of the Final Project. 

In this project the most interesting and surprising part was finding out that technical description contained errors and coming to decision how to deal with it.

Project description: 

We've received task from international online store. Our predecessor failed to complete it: they launched an A/B test and then quit (to start a watermelon farm in Brazil). They left only the technical specifications and the test results. Our task is to analyse the results of a new A/B test, launched after the predecessor.

Technical description given by predecessor.

    Test name: recommender_system_test
    Groups: А (control), B (new payment funnel)
    Launch date: 2020-12-07
    Date when they stopped taking up new users: 2020-12-21
    End date: 2021-01-01
    Audience: 15% of the new users from the EU region
    Purpose of the test: testing changes related to the introduction of an improved recommendation system
    Expected result: within 14 days of signing up, users will show better conversion into product page views (the product_page event), instances of adding items to the shopping cart (product_cart), and purchases (purchase). At each stage of the funnel product_page → product_cart → purchase, there will be at least a 10% increase.
    Expected number of test participants: 6000

Project structure:

1. General information and data preparation. We're going to take a look at the data we have, check whether it has no errors and prepare it for analysis.
2. EDA. Studying distributions.
3. A/B Test Analysis. We're going to analyse the results we've got after launching an A/B test.
4. We'll present the overall conclusion and advice for business.

Additional information:

* The project was created in Jupyter Notebook, so to run it you should have Anaconda installed. It has a Table of Contents for easier navigation.

* When downloaded, the data has to be stored in the same folder with the notebook.

This project was created by Mila Lunacharska, in April 2022.
