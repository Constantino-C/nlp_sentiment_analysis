### Detection of stress in social media with NLP 

Social media has a major role in people's lives. Social platforms are a way for people to connect with others, inform and get informed as well as express opinions & feelings. Reddit is an example of a social media 
platform which helps people bring their ideas and experiences together. <p>

In this project I will examine posts from Reddit among them which are posts expressing various forms of stress. The dataset I will use is based on the paper by Turcan, McKeown; _Dreaddit: A Reddit Dataset for Stress Analysis in Social Media_ and is publicly shared.
The paper can be found online in this [directory](https://www.researchgate.net/publication/337005802_Dreaddit_A_Reddit_Dataset_for_Stress_Analysis_in_Social_Media).

I will build a classifer model to detect the stressed posts, use Natural Language Processing methods including
topic modelling and clustering methods to categorise the posts and use semantic analysis to detect the potential stressors in each post.

_keywords_: <kbd>NLP</kbd>, <kbd>topic modelling</kbd>, <kbd>spaCy</kbd>, <kbd>classification</kbd>, <kbd>semantic analysis</kbd>
<br/>


#### Notes:
- Download the datasets and save them in the folder 'data/raw'.
- On command line navigate to the directory of the project where requirements.txt is saved and run:
`pip install -r requirements.txt`
- Data processed in the study should be saved under 'data/interim'.
- To run the notebooks effectively, clone the repo and keep the directoty structure consistent. 
- To install hdbscan use in command line:  
`pip install hdbscan==0.8.27 --no-cache-dir --no-binary :all: --no-build-isolation`
This is a known issue; due to discrepancies between numpy and hdbscan version. This issue is discussed [here](https://github.com/scikit-learn-contrib/hdbscan/issues/457)


### Notebooks description<p>

`1.LIWC-API-Feature-extraction:` Inlcudes commands and set out used to call the LIWC API to extarct the vocabulary features and the semantic analysis.

