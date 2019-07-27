# NLP Essay Grader

The goal of this project is to develop a natural language processing (NLP) tool that can provide automatic feedback on essays to students and teachers.
This feedback would be used to help students decide where to focus their revision efforts and help teachers focus on what aspects of the essay may need more detailed constructive feedback.

## Phase I (NLP Organization Scorer)
Using labeled essay data from the Hewlett Foundation, compare the computed organization scores of essays with the hand-graded scores to determine model accuracy and the effectiveness of the organization scoring function.

## Phase II (Score AI)
To better generalize the scorer, this phase used ~7,700 essays scraped based on 40 keywords from 2 sites where essays were made freely available. After cleaning and processing the texts, I performed topic modeling to get the percent contribution of the essay text to the essay topic. Then I scored the logical flow based on the cosine similarity of sentence vectors within the same paragraph.
