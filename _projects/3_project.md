---
layout: page
title: Food Safety Data Analysis and Visualization
description: A food safety visualization system
img: assets/img/project_food_safety_visualization/cover.jpg
importance: 3
category: work
---
# Introduction
With the improvement of detection technology and the wide application of Internet technology, the scale and types of food safety data continue to increase.Therefore, how to make good use of food safety data for analysis, and knowing the internal pattern inside the data, is the most important part of China's food safety protection at this stage. This study will use the existing food unqualified data, using the current popular computer technology, mining the internal rules of food data, and reveal the internal association of food data.
# Data Processing
Based on the dimensions and contents of food safety data, appropriate algorithms and big data technologies are selected to process and analyze them effectively. We design three different kinds of data processing tasks based on three different kinds of computer data processing tasks which are weight calculation, keyword extraction, and correlation analysis respectively. ‘
In terms of weight calculation, we want to explore the extent to which different additives contribute to food insecurity, we use the traditional entropy weight method based on data, the AHP method based on expert evaluation, and the improved AHP-EW method to calculate the weight results, and compare the results. In terms of keyword extraction, we want to know the keyword information of a particular province or a particular category, so we use three different methods of natural language processing techniques to get our keyword results. We use tf-idf method based on frequency, textrank method based on co-occurrence, and the machine learning method word2vec based on a high dimensional vector. In terms of correlation analysis, we want to explore the correlation among the food additives. We use the k-means algorithm to cluster features.
## Weight Calculation Algorithms
Combined with previous studies, this research calculates the weight of food additives from from objective and subjective point of view, and make comparisons in representation.
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/project_food_safety_visualization/img1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/project_food_safety_visualization/img2.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/project_food_safety_visualization/img3.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Work flow of three weight calculation algorithms, which are EW, AHP, AHP-EW respectively.
</div>
## Keyword Extraction Algorithms
For each province or category, there are some specific information about food safety, and we can extract these words to help people to raise awareness about the influence of food additives.
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/project_food_safety_visualization/img1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/project_food_safety_visualization/img2.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/project_food_safety_visualization/img3.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Work flow of three keyword extraction algorithms, which are tf-idf, textrank, word2vec respectively.
</div>

## Correlation Analysis Algorithm
For each category, there are several types of food additives, and we can use clustering algorithms to figure out there are correlations between those features.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/project_food_safety_visualization/img6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Work flow of k-means correlation analysis algorithm.
</div>

# Visualization Design
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/project_food_safety_visualization/img7.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    visualization system
</div>
After processing the original dataset using the above method, we need to do visualization. System visualization includes text visualization, geographic location visualization, relational visualization. We use different types of charts on the web page to comprehensively show the data of multiple dimensions of information. In addition, we design a friendly way of interaction to bring a better user experience in the visualization system.

**Category** **pipeline:** By switching the category on the left console, the user can get information about this food category information as shown
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/project_food_safety_visualization/img9.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    category pipeline
</div>

**Province pipeline:** By switching the province on the map, the user can get information about the province information as shown.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/project_food_safety_visualization/img10.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    province pipeline
</div>
# Risk Prediction
Based on previous work in food safety risk prediction, we train artificial intelligence model in the dataset we constructed and compare their effects. Firstly, we train the linear model, BP model and RBF model with the data of a specific food category according to the method in the paper. Next, we use all types of food data we constructed to train more general models to predict food risk with BP model, RBF model and transformer model respectively.

# Conclusion
In this paper, a food safety visualization system is presented, which illustrates the internal law of data from spatial, textual, and relational dimensions. During data processing, we do several tasks such as keyword extraction, weight calculation, and clustering and present the results in the visualization system. In terms of weight calculation, we use AHP, EW, and AHP-EW to explore the importance of each additive. In terms of keyword extraction, we use tf-idf, textrank, and word2vec to extract the keywords of each category or province to illustrate the key information. In terms of clustering, we use k-means to explore the correlation among different features.
In addition, we use a machine learning model to predict the risk to food safety. In this paper, we train the linear model, BP, and RBF model for a specific category and compare their effectiveness. Besides, we train a more generalized model to predict the risk of food among all categories. The model has greater generalization ability and is more general, which can be applied to different food data to predict its risk value.