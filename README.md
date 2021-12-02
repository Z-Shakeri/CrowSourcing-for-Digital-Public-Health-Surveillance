# CrowSourcing-for-Digital-Public-Health-Surveillance

The main objective of this study is to explore and evaluate the application of crowdsourcing, in general, and AMT, in specific, for developing digital public health surveillance systems.

## Dataset and Labels
A full version of the dataset used for this study is available at the dataset's [Github repository](https://github.com/data-intelligence-for-health-lab/Lpheada-Labelled-Public-HEAlth-DAtaset). As sample dataset for replicating the results of this study is provided in this repository, under the 'sample datase' folder. The following figure presents the labels defined for each of the binary and multi-class classification tasks. 

<img src="/Figures/Labels.jpg" width="370">

## Tasks and Labelling process
The following figure resents a a sample labelling task (i.e., HIT) for the sedentary behaviour category. Each HIT contains four questions (section 1), and each asks if the presented tweet is a self-reported PASS-related behaviour (section 2). The fourth question is a pre-defined qualification question that was designed in addition to the qualification requirements defined by AMT (section 3). The answer to this question was always choice#1, and it was easy enough to detect spammers or irresponsible workers. Also, each HIT contains an illustrative example that explains each choice of the questions. Workers were asked to select exactly one choice, and HITs with zero or more than one label were rejected during the approval process.

<img src="/Figures/TaskSample.png" width="370">

### Active Learning and SHAP Analysis 

Please check the TranditionalModels notebook for more details about the implementation of these techniques. 

## Citation

The manuscript that presents this study has been accepted for publication at the Journal of Medical Internet Research (JMIR). You can cite our paper as follows:

``` 
@article{PASSDS,
	author = {Shakeri Hossein Abad, Zahra and Butler, Gregory and Thompson, Wendy and Lee, Joon},
	title = {Crowdsourcing for machine learning in public health surveillance: lessons learned from Amazon Mechanical Turk},
	year = {forthcoming},
	doi = {10.2196/28749},
	journal = {JMIR}
}
```

## More Questions
Please use issues on this Github for any questions or feedback. You can also contact us at dih[at]ucalgary.ca or joonwu.lee[at]ucalagry.ca for specific inquiries.
