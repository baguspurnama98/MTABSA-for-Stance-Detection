# Multi-task-Aspect-based-Sentiment-for-Stance-Detection
This repository for Stance Detection on Tweets with Multi-task Aspect-based Sentiment: A Case  Study of COVID-19 Vaccination


Public opinion analyses on Twitter conducted based on sentiment analysis cannot identify the author’s stance 
regarding agreement or disagreement with a given target. Stance detection determines whether the author of a text is in 
favor, against, or neutral towards a target. However, stance detection based on text-only is less representative opinion, 
especially on a tweet, which is a short text with slightly contextual information. Therefore, more information is needed 
to represent the author's stance better. In previous research, most research on stance detection was carried out using 
simple sentiment information to measure the support to target. This study addresses multi-task aspect-based sentiment 
analysis (ABSA) and social features for stance detection based on deep learning models of BiGRU-BERT on tweets.
Our contribution combines aspect-based sentiment information with features based on textual and contextual 
information that does not emerge directly from Twitter texts. ABSA approach can provide more accurate sentiment 
information at aspect level on tweets, which is possible contains multiple issues discussed. Aspect information on 
tweets can reflect the issue that influences the author’s stance toward a target. Multi-task learning was applied to help 
improve the generalization performance of ABSA with simultaneous processes. We extracted social attributes and 
online behavioral features for contextual information. Since same community tends to have the same opinion towards a 
target, we applied a community detection task and combine with the Twitter social attributes. The proposed method has 
significantly improved evaluation metrics (>10%) than textual features only for stance detection on tweets
