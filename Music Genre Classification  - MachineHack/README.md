# MUSIC GENRE CLASSIFICATION USING MACHINE LEARNING 🎧
This notebook looks into using various python-based machine learning and data science libraries in an attempt to build a machine learning model capable of classify the music based on their genre.

### 1. Problem Definiton
Music has been an important part of our lives since time immemorial. Every artist has a signature, making music a subjective art. We have scales/metrics to measure the quality of music. But, is it possible to train a machine learning model to predict the genre and quality of the music?

### 2. Data
Data is taken form [MACHINE HACK COMPETITION](https://machinehack.com/hackathons/music_genre_classification_weekend_hackathon_edition_2_the_last_hacker_standing/data)

Training dataset: 17,996 rows with 17 columns

Test dataset: 7,713 rows with 16 columns

### 3. Evaluation
The submission will be evaluated using the Log Loss metric. One can use sklearn.metric.log_loss to calculate the same

### 4. Modeling
After cleaning and imputing all the missing values in the dataset, I tried various Classification models, **GradientBosstingClassifier** performs well having **log loss of 1.27.**