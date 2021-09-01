# SOCCER WIN OR LOSS CLASSIFICATION ⚽

### 1.Problem Statement
Soccer aka Football is the most popular game in the world. It’s a religion of its own. If groups of 10 people can stop time and make people watch them in awe and reverence, it’s this beautiful game. Also, anybody can play soccer- all it needs is 4 poles, a ground and a ball. You can just get started with the play.

We live in ambiguity and always need some information to just make a decision. Decisions are made based on possible outcomes. Win/ Loss/ Pass / Fail etc.

The problem statement is a classic study for decision-making and understanding the odds stacked against a particular situation.

### 2. Dataset
Dataset taken from [MachineHack competition](https://machinehack.com/hackathons/soccer_fever_weekend_hackathon_edition_2_the_last_hacker_standing/overview)

Train Dataset: 7443*21 Columns: 21 Target Column: Outcome

Test Dataset: 4008*20 Columns: 20

### 3. Evaluation
The submission will be evaluated using the Log Loss metric. One can use sklearn.metric.log_loss to calculate the same.

### 4. Modeling
After cleaning and imputing all the missing values in the dataset, I tried various Classification models, **XGBClassifier** performs well having log loss of **0.0262**.
