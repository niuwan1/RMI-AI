
#### A brief survey  : AI in Risk Management and Insurance

---------------

> #### Contents

- [Misc](#misc)
- [Finance Industry](#finance-industry)
- [Finance Technology](#finance-technology)
- [AI in Risk Management](#ai-in-risk-management)
- [AI in Insurance](#ai-in-insurance)
- [Literature review](#literature-review)
- [Literature ML Finance focused](#literature-mL-finance-focused)
- [Actuarial Science Program Worldwide](#actuarial-science-program-worldwide)
- [ML DL Finance Conference](#ml-dl-finance-conference)
- [Libraries](#libraries)
- [Startups](#startups)
- [Appendix](#appendix)


[Back to top](#contents)


--------------

#### Misc

[Back to top](#contents)

What's the future looks like for DL & Finance?
* Igor Halperin: RL on management [quora](https://www.quora.com/What-would-be-the-next-big-thing-in-quantitative-finance-after-machine-learning-big-data-high-frequency-algorithmic-trading-How-is-the-industry-going-to-evolve-in-the-next-10-years)
* Igor Halperin: deep learning is useful for mortgage risk, as was shown by Kay Giesecke and his group at Stanford, as well as for credit scoring/credit cards, P2P lending [quora](https://www.quora.com/Is-deep-learning-useful-in-finance-outside-of-high-frequency-trading)
* Igor Halperin: RL on credit scoring: [Quora](https://www.quora.com/Which-books-or-lecture-notes-should-I-learn-to-begin-develop-reinforcement-learning-models-for-credit-scoring)

Finance data property w.r.t. Deep Learning

* Too noisy to use ML model not stationary
* Data are small-to-medium, where deep learning needs large data
* Igor Halperin: (Deep) feedforward neural nets, autoencoders and LSTM seem to be the state of the art of ML in finance, based on what is published and presented at different conferences. [Quora](https://www.quora.com/What-is-the-state-of-the-art-in-simulating-financial-price-series)
* Igor Halperin: ML currently un-explainable in finance [Quora](https://www.quora.com/What-is-being-done-at-the-academic-level-so-as-to-make-ML-algorithms-more-interpretable-for-regulators-in-finance-risk-space)
* Financial time-series is a partial information game (POMDP), so needs RL
> * High frequency trading and algorithmic trading are the main drivers of price at short intervals (< 1 day).
> * Opening and closing prices have their own patterns - both in stocks and futures - the two asset classes I have worked with.
> * News and rumors are the driving forces when it comes to multi-day horizons. Specific company news can happen at any time without any prior notice. However, the timeline for some events is known beforehand. Company result schedule, as well as the economic data calendar, are known beforehand.
> * Value investing and economic cycles matter the most when it comes to price changes at a multi-year range.



------------

#### Finance Industry

[Back to top](#contents)



------------------

#### Finance Technology

[Back to top](#contents)

* How America’s Top 4 Insurance Companies are Using Machine Learning [article](https://emerj.com/ai-sector-overviews/machine-learning-at-insurance-companies/)



------------------

#### AI in Risk Management

[Back to top](#contents)

Financial Risk Management Categories
1. Market Risk
2. Credit Risk
3. Liquidity Risk
4. Operational Risk

Casualty Actuarial Society (CAS) define Enterprise risk management (ERM)
1. Hazard risk: Liability torts, Property damage, Natural catastrophe
2. Financial risk: Pricing risk, Asset risk, Currency risk, Liquidity risk
3. Operational risk: Customer satisfaction, Product failure, Integrity, Reputational risk; Internal Poaching; Knowledge drain
4. Strategic risks: Competition, Social trend, Capital availability


[GLM] Statistical Method can be classified by this
* Tree-based methods (e.g. Random Forest, AdaBoost, Gradient Boost Machine);
* Kernel-based methods (e.g. Support Vector Machine, Kernel Learning);
* Neuron-based methods (e.g. Neural Network, "Deep Learning" or Restricted Boltzmann Machine);
* Graph/network-based methods (e.g. Naïve Bayes, Hidden Markov Model, Deep Belief Network).

Insurance moves from reactive to predictive 
- not just using data but also create data
1. Underwriting: rating(Frequency and Severity)
- CNN: Identify Roof Type
- Flight delay insurance
- Lemonade Insurance
- Car Insurance chips
- Healthcare insurance: Medical Imaging eg. Google Deepmind AI detect eye disease [two mins paper's video](https://www.youtube.com/watch?v=wR2OlsF1CEY)
- Q: legistitive allow ratemaking? on automobile??
2. Underwriting: Fraud Detection
- Credit card fraud detection is successful, will that be able to apply to insurance?
3. Underwriting: Customer segmentation
-----------------------------------------
4. Marketing: Personalized marketing
5. Marketing: Recommendation engines
-----------------------------------------
6. Claims prediction


make a small twist from stat to ML/DL
- example 想一下有什麼例子概念是一樣的，但是小小的轉變一下就可以變很厲害 搜集資料？ lemonade?
- 模型方面



- Deep Learning’s Killer App for Finance? [Article](https://aldousbirchall.com/2017/03/25/deep-learnings-killer-app/)





------------------

#### AI in Insurance

[Back to top](#contents)

* Insurance 2030—The impact of AI on the future of insurance [note](https://github.com/yingpublic/RMI-AI/blob/master/review/industry/Insurance%202030_The%20impact%20of%20AI%20on%20the%20future%20of%20insurance.md)

* Potential AI value in Insurance Supply Chain (by McKinsey 2017) [report starting p.30](https://www2.deloitte.com/content/dam/Deloitte/xe/Documents/financial-services/Artificial-Intelligence-in-Insurance.pdf)
<img src="https://github.com/yingpublic/RMI-AI/blob/master/ref_image/Potential_AI_Insurance_supply_chain.png" width="900">
<img src="https://github.com/yingpublic/RMI-AI/blob/master/ref_image/Potential_AI_Insurance_supply_chain_2.png" width="900">

* Potential Applications of ML/AI in Insurance
<img src="https://github.com/yingpublic/RMI-AI/blob/master/ref_image/Potential_ml_on_insurance.png" width="800">
Ref: Institute for SOA Faculty: Practical Application of Machine Learning Within Actuarial Work by Modelling, Analytics and Insights in Data working party

* ML/DL in terms of different insurance
<img src="https://github.com/yingpublic/RMI-AI/blob/master/ref_image/ML_in_4diff_insurance.png" width="800">

SOA: 2019Jan: [Machine-Learning Methods for Insurance Applications-A Survey](https://www.soa.org/resources/research-reports/2019/machine-learning-methods/)
* Machine-Learning Methods for Insurance Applications
* Group Long-Term Disability Jupyter File
* Long-Term Care Jupyter File
* [Group Long-Term Disability Data Set Comparison](file:///Users/Yu-Ying/Downloads/group-ltd-data-set.html)
* Long-Term Care Data Set Comparison





[ratemaking]
- 作者有Bengio!!: Statistical Learning Algorithms Applied to Automobile Insurance Ratemaking [paper](https://www.iro.umontreal.ca/~vincentp/Publications/itii.pdf) [note](https://github.com/yingpublic/RMI-AI/blob/master/review/academia/Statistical%20Learning%20Algorithms%20Applied%20to%20Automobile%20Insurance%20Ratemaking.md)
- 2016: Insurance Premium Prediction via Gradient Tree-Boosted Tweedie Compound Poisson Models [paper](https://arxiv.org/pdf/1508.06378.pdf)
- Machine Learning – Applications to Insurance Pricing [article](https://www.luxactuaries.com/machine-learning-applications-insurance-pricing/)
- AXA: Using machine learning for insurance pricing optimization [news](https://cloud.google.com/blog/products/gcp/using-machine-learning-for-insurance-pricing-optimization)


[parameter estimation]
- [ML-unsupervised?] A MACHINE-LEARNING APPROACH TO PARAMETER ESTIMATION [article](https://www.casact.org/pubs/monographs/papers/06-Kunce-Chatterjee.pdf) 



[Claims]
- R/Shiny - Machine Learning for insurance claims [Video](https://www.youtube.com/watch?v=3KNlT3evDkc) [Article](https://www.r-bloggers.com/machine-learning-for-insurance-claims/) [More Shiny](https://www.youtube.com/channel/UC4cF877tXYUa3h3Ou6tcxXA/videos)

[Fraud Detection] Casualty Insurance face lots of fraud.

- From Logistic Regression in SciKit-Learn to Deep Learning with TensorFlow – A fraud detection case study [Blog Part 1](https://ipythonquant.wordpress.com/2018/05/08/from-logistic-regression-in-scikit-learn-to-deep-learning-with-tensorflow-a-fraud-detection-case-study-part-i/) / [Blog Part 2](https://ipythonquant.wordpress.com/2018/05/18/from-logistic-regression-in-scikit-learn-to-deep-learning-with-tensorflow-a-fraud-detection-case-study-part-ii/) / [Github](https://github.com/mgroncki/IPythonScripts/blob/master/LogisticRegression_Part1.ipynb)
- Top 10 Data Science Use Cases in Insurance [Article](https://medium.com/activewizards-machine-learning-company/top-10-data-science-use-cases-in-insurance-8cade8a13ee1)
- 2018.07 AI IN P&C INSURANCE. Pragmatic Approaches for Today, Promise for Tomorrow. [reviews]() [pdf](https://capeanalytics.com/wp-content/uploads/2018/11/SMA-AI-in-PC-Insurance-2018.pdf) 



[loss]
- [GRU] 2018 Actuarial Applications of Deep Learning_Loss Reserving and Beyond [slide](https://ibnr.netlify.com/#29) / [arxiv](https://arxiv.org/pdf/1804.09253.pdf) / [DeepTriangle_github_R](https://github.com/kevinykuo/deeptriangle)

- KPMG: Learning to trust your digital actuary: New technologies can automate loss reserve analysis, providing insurers with more timely data and deeper insights [report](https://assets.kpmg/content/dam/kpmg/pdf/2016/07/learning-to-trust-your-digital-actuary.pdf)


[Actuarial Education]
- Data Analytics in Actuarial Education [slide](file:///Users/Yu-Ying/Downloads/2017-atc-session-11.pdf)

[Company]
- Allianz's 
> bot Allie, an online assistant available 24/7 to answer personal lines customers’ questions. It is also using machine learning to carry out risk assessments and support automated underwriting in the small- to medium-enterprise (SME) space.


[Decentralize Insurance] \
Decentralized Insurance Developer Conference 2017 [Playlist](https://www.youtube.com/playlist?list=PLv_C3XL8vCF4TfX9UKZgA8wWZQuvuqFyO) (Bold is something I'm more interested in.) 
- **Keynote: Decentralized Decision Making** [Video](https://www.youtube.com/watch?v=-j6Esc_Pm_I&index=2&list=PLv_C3XL8vCF4TfX9UKZgA8wWZQuvuqFyO)
- Workshop: How to Develop a Blockchain-based Insurance Solution in a Few Hours [Video](https://www.youtube.com/watch?v=OqlThIN-kC4&index=3&list=PLv_C3XL8vCF4TfX9UKZgA8wWZQuvuqFyO)
- Bringing the True P2P Mutual Back to Insurance [Video](https://www.youtube.com/watch?v=-0kEd9pcllc&index=4&list=PLv_C3XL8vCF4TfX9UKZgA8wWZQuvuqFyO)
- Insurance and Blockchain, Show Me the Code! [Video](https://www.youtube.com/watch?v=7cHvg6KugcE&list=PLv_C3XL8vCF4TfX9UKZgA8wWZQuvuqFyO&index=5)
- **Workshop: Smart Contract Car Insurance in 30 min** [Video](https://www.youtube.com/watch?v=paWuuz8pZQw&list=PLv_C3XL8vCF4TfX9UKZgA8wWZQuvuqFyO&index=7)
- Workshop - How to Build Decentralized Insurance Apps [Video](https://www.youtube.com/watch?v=Wlii-juuuEY&list=PLv_C3XL8vCF4TfX9UKZgA8wWZQuvuqFyO&index=8)
- Fireside Chat - View on Decentralized Insurance From an Insurance VC [Video](https://www.youtube.com/watch?v=tiZYSAWW49w&list=PLv_C3XL8vCF4TfX9UKZgA8wWZQuvuqFyO&index=9)
- Feeding Authentic Data into Blockchain: Insurance Dapps on Steroids [Video](https://www.youtube.com/watch?v=zLJiWL3VS6I&list=PLv_C3XL8vCF4TfX9UKZgA8wWZQuvuqFyO&index=10)
- **A Simple Probability Model For Decentralized Insurance** [Video](https://www.youtube.com/watch?v=NsF0mOvyDp8&list=PLv_C3XL8vCF4TfX9UKZgA8wWZQuvuqFyO&index=11)
- Standardized Protocols For Decentralized Insurance [Video](https://www.youtube.com/watch?v=y3_a7iwWldI&list=PLv_C3XL8vCF4TfX9UKZgA8wWZQuvuqFyO&index=12)
- **The Value Behind Hyperledger** [Video](https://www.youtube.com/watch?v=2OaAeWke7LY&list=PLv_C3XL8vCF4TfX9UKZgA8wWZQuvuqFyO&index=13)
- **Introduction To Machine Learning For Insurance Use Cases** [Video](https://www.youtube.com/watch?v=vq6G7NnWlDQ&list=PLv_C3XL8vCF4TfX9UKZgA8wWZQuvuqFyO&index=14)
- **Fireside Chat: Prediction Markets For Insurance** [Video](https://www.youtube.com/watch?v=dOrLEuD3Arw&list=PLv_C3XL8vCF4TfX9UKZgA8wWZQuvuqFyO&index=15)
- **Blockchain & Insurance | Regulation & Compliance** [Video](https://www.youtube.com/watch?v=Ll-1wS3pcSQ&list=PLv_C3XL8vCF4TfX9UKZgA8wWZQuvuqFyO&index=16)
- Risk Pool Tokens [Video](https://www.youtube.com/watch?v=Rvz2RjlGFl4&list=PLv_C3XL8vCF4TfX9UKZgA8wWZQuvuqFyO&index=17)

Decentralized Insurance Developer Conference 2018 [Playlist](https://www.youtube.com/playlist?list=PLv_C3XL8vCF4rniMwrZtaLTFNzCrGT1FF)


----------


#### Literature review


[Back to top](#contents)

BirdView for Risk Management:
- AI and Machine Learning for Risk Management [paper](https://poseidon01.ssrn.com/delivery.php?ID=382022091086004002100075096118111027029011095077058037071002077109066120104092065024048096036099043030006119122008105071077088040066043048077004064084065086102073002028005026010021068021110005121007093092067120026125084087126065004027024088113107127&EXT=pdf)
- Overview and Practical Application of Machine Learning in Pricing [report](https://www.casact.org/education/spring/2017/presentations/C-24.pdf)
- Accenture(consulting): Validating Machine Learning and AI Models in Financial [report](https://www.accenture.com/t20180427T082714Z__w__/us-en/_acnmedia/Accenture/Conversion-Assets/MainPages/Documents/Global/Accenture-Emerging-Trends-in-the-Validation-of-ML-and-AI-Models.pdf)
- Reinforcement learning in financial markets - a survey [paper](https://www.econstor.eu/bitstream/10419/183139/1/1032172355.pdf)


Survival Analysis:(relatively mature)
- [ML] 2017: Machine Learning for Survival Analysis: A Survey [paper](https://arxiv.org/pdf/1708.04649.pdf)
- [repository](https://github.com/robi56/Survival-Analysis-using-Deep-Learning)
- [DeepSurv package](https://github.com/jaredleekatzman/DeepSurv)
- [SurvivalNet package](https://github.com/CancerDataScience/SurvivalNet)

Claim Frequency 
- [ML+R code] Data Science in Non-Life Insurance Pricing: Predicting Claims Frequencies using Tree-Based Models [thesis](https://www.ethz.ch/content/dam/ethz/special-interest/math/imsf-dam/documents/walter-saxer-preis/ma-zoechbauer.pdf) / [note](https://github.com/yingpublic/RMI-AI/blob/master/review/academia/Data%20Science%20in%20Non-Life%20Insurance%20Pricing:%20Predicting%20Claims%20Frequencies%20using%20Tree-Based%20Models.md) / [slide](https://people.math.ethz.ch/~wueth/Talks/2017_Geneva.pdf)


Car Insurance
- [CNN] SOA_2018: Applying Image Recognition to Insurance_driver behavior assessment [paper](https://www.soa.org/Files/resources/.../applying-image-recognition.pdf) 
- [CNN] IBM_2017: DarNet: A Deep Learning Solution for Distracted Driving Detection [paper](http://cs.brown.edu/~tab/papers/middleware17.pdf)
- [CNN] Using Convolutional Neural Networks to Perform Classification on State Farm Insurance Driver Images [paper](http://cs229.stanford.edu/proj2016spr/report/004.pdf)



Market Risk Manegement:
- [LSTM+stacked autoencoder] 2017: A deep learning framework for financial time series using stacked autoencoders and long-short term memory [paper](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5510866/)
- [GANs] Using Bidirectional Generative Adversarial Networks to estimate Value-at-Risk for Market Risk Management [Medium](https://towardsdatascience.com/using-bidirectional-generative-adversarial-networks-to-estimate-value-at-risk-for-market-risk-c3dffbbde8dd) [Github](https://github.com/hamaadshah/market_risk_gan_keras)
- [GAN] 2005/Two-Step Disentanglement for Financial Data [note](https://github.com/yingpublic/RMI-AI/blob/master/review/academia/Two-Step%20Disentanglement%20for%20Financial%20Data.md) [paper](https://arxiv.org/pdf/1709.00199.pdf)
- [GAN/LSTM/CNN] Stock Market Prediction on High-Frequency Data Using Generative Adversarial Nets [paper](https://www.hindawi.com/journals/mpe/2018/4907423/)
- [RL] RISK-AVERSE DISTRIBUTIONAL REINFORCEMENT LEARNING: a cvar optimization approach [master thesis](https://dspace.cvut.cz/bitstream/handle/10467/76432/F3-DP-2018-Stanko-Silvestr-thesis.pdf)




Mortgage Risk
- [DL] 2015: Deep Learning for Mortgage Risk [paper](https://stanford.app.box.com/s/0iqyz2zt82uvqjb5cn8tskxxe7m0i0zo)

Credit Risk
- [DL] 2018: Credit Risk Analysis Using Machine and Deep Learning Models [paper](https://halshs.archives-ouvertes.fr/halshs-01835164/document)
- [LSTM] 2018: Deep Credit Risk Ranking with LSTM [talk+slide](https://databricks.com/session/productionizing-credit-risk-analytics-with-lstm-tensorspark-a-wells-fargo-case-study) 
- [DL] Credit Card Default Prediction Using TensorFlow (Part-1 Deep Neural Networks) [medium](https://medium.com/@Saadism/credit-card-default-prediction-using-tensorflow-part-1-deep-neural-networks-ef22cfd4d278)
- [ML] 2018: Ensemble Learning or Deep Learning? Application to Default risk analysis. [student's paper in TW data](http://www.econ.kobe-u.ac.jp/RePEc/koe/wpaper/2018/1802.pdf)
- [ML] 2017: ANALYSIS OF FINANCIAL CREDIT RISK USING MACHINE LEARNING [thesis](https://arxiv.org/pdf/1802.05326.pdf)


Risk Attitude
- [2018] Eye-Tracking and Economic Theories of Choice Under Risk [paper](https://cear.gsu.edu/files/2018/12/WP_2018_06_Eye-Tracking-and-Economic-Theories-of-Choice-Under-Risk_2018_1204.pdf)


Option Pricing:
- [LSTM] 2018: Option hedging with Long-Short-Term-Memory Recurrent Neural Networks [Blog]() / [Deep Hedging Ref Paper](https://arxiv.org/abs/1802.03042) / [Github]()
- [RL] 2018 Igor Halperin: Model-Free Option Pricing with Reinforcement Learning [slide](https://cfe.columbia.edu/files/seasieor/industrial-engineering-operations-research/IgorHalperin_Columbia_ML_in_finance_QLBS.pdf) / [coursera](https://www.coursera.org/specializations/machine-learning-reinforcement-finance)
- [RL] 2017 Igor Halperin: QLBS: Q-Learner in the Black-Scholes(-Merton) Worlds [paper](https://arxiv.org/pdf/1712.04609v2.pdf)
- [RL] 2017 Igor Halperin: Inverse Reinforcement Learning for Marketing [paper](https://arxiv.org/pdf/1712.04612v1.pdf)
- [RL] 2018 Igor Halperin: The QLBS Q-Learner Goes NuQLear: Fitted Q Iteration, Inverse RL, and Option Portfolios [paper](https://arxiv.org/pdf/1801.06077v1.pdf)
- [RL] 2018 Igor Halperin: Market Self-Learning of Signals, Impact and Optimal Trading: Invisible Hand Inference with Free Energy (or, How We Learned to Stop Worrying and Love Bounded Rationality) [paper](https://arxiv.org/pdf/1805.06126v1.pdf)
- [RL] 2018: Pricing Options with an Artificial Neural Network: A Reinforcement Learning Approach [thesis w/ simplified python](https://brage.bibsys.no/xmlui/bitstream/handle/11250/2565055/Masteroppgave%20HaakonTrønnes.g.pdf?sequence=1&isAllowed=y) / [note](https://github.com/yingpublic/RMI-AI/blob/master/review/academia/Pricing%20Options%20with%20an%20Artificial%20Neural%20Network:%20A%20Reinforcement%20Learning%20Approach.md)
- [NN] 2018 World Quant Blog: BEYOND BLACK-SCHOLES: A NEW OPTION FOR OPTIONS PRICING [blog](https://www.weareworldquant.com/en/thought-leadership/beyond-black-scholes-a-new-option-for-options-pricing/)
- [DNN] 2018: The Day my Computer Won the Nobel Prize (Neural Network Option Pricing) [medium w/ python](https://medium.com/datadriveninvestor/the-day-my-computer-won-the-nobel-prize-neural-network-option-pricing-d29b4379f1d2)
- [DNN] 2018: Deeply Learning Derivatives [paper](https://arxiv.org/abs/1809.02233) / [note](https://github.com/yingpublic/RMI-AI/blob/master/review/academia/Deeply%20Learning%20Derivatives.md)
- [GNN] 2017: Gated Neural Networks for Option Pricing: Rationality by Design [paper](https://arxiv.org/pdf/1609.07472.pdf) / [note](https://github.com/yingpublic/RMI-AI/blob/master/review/academia/Gated%20Neural%20Networks%20for%20Option%20Pricing:%20Rationality%20by%20Design.md) / [github?](https://github.com/arraystream/fftoptionlib) / [blog](https://www.arraystream.com/2017/05/08/fftoptionlib/)
- [FeedFroward] 2017: Machine Learning in Finance: The Case of Deep Learning for Option Pricing [paper](https://srdas.github.io/Papers/BlackScholesNN.pdf) /  [pythob code](https://srdas.github.io/DLBook/DeepLearningWithPython.html#option-pricing) / [note](https://github.com/yingpublic/RMI-AI/blob/master/review/academia/Machine%20Learning%20in%20Finance:%20The%20Case%20of%20Deep%20Learning%20for%20Option%20Pricing.md)
- [NN] 2012 An Option Pricing Model That Combines Neural Network Approach and Black Scholes Formula
- [ANN] 2013: Option Pricing Using Artificial Neural Networks: An Australian Perspective [dissertation](https://pure.bond.edu.au/ws/portalfiles/portal/18243185/Option_Pricing_Using_Artificial_Neural_Networks.pdf) / [note](https://github.com/yingpublic/RMI-AI/blob/master/review/academia/Option%20Pricing%20Using%20Artificial%20Neural%20Networks:%20An%20Australian%20Perspective.md)

Pricing:
- [DNN] 2018: The Day I Taught My Computer What Duration Is (Neural Network Bond Pricing) [blog w/ code](https://www.linkedin.com/pulse/day-i-taught-my-computer-what-duration-neural-network-jacob-bourne/)
- [ML] Machine Learning Methods to Perform Pricing Optimization. A Comparison with Standard GLMs. [paper](https://www.variancejournal.org/articlespress/articles/Machine-Spedicato.pdf)
- [ML] Tree-based machine learning for insurance pricing. [slide](https://kuleuvencongres.be/eaj2018/documents/presentations/1-roel-henckaerts.pdf)
- [ML] Machine Learning application in non-life pricing. Frequency modelling: an educational case study. [report](https://reacfin.com/en/sites/default/files/documents/20170914%20Machine%20Learning%20applications%20for%20non-life%20pricing.pdf) 
- [ML] Data Analytics for Non-Life Insurance Pricing [paper](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=2870308)
- [ML] Data Science in Non-Life Insurance Pricing. Predicting Claims Frequencies using Tree-Based Models. [Master Thesis](https://www.ethz.ch/content/dam/ethz/special-interest/math/imsf-dam/documents/walter-saxer-preis/ma-zoechbauer.pdf)
- [ML] Overview and practical application of Machine learning in Pricing [report](https://www.casact.org/education/spring/2017/presentations/C-24.pdf) conclusion: domain knowledge win


Portfolio Management
- [RL Model Free] 2017: A Deep Reinforcement Learning Framework for the Financial Portfolio Management Problem (Crypto) [paper](https://arxiv.org/pdf/1706.10059.pdf)
- [RL] 2015: A Comprehensive Survey on Safe Reinforcement Learning [paper](http://www.jmlr.org/papers/volume16/garcia15a/garcia15a.pdf) [note](https://github.com/yingpublic/RMI-AI/blob/master/review/academia/A%20Comprehensive%20Survey%20on%20Safe%20Reinforcement%20Learning.md)
- [RL] 2005/J of AI: Risk-Sensitive Reinforcement Learning Applied to Control under Constraints [paper](https://arxiv.org/pdf/1109.2147.pdf) [note]()
- [RL-deepQ] Portfolio Management using Reinforcement Learning [paper](http://cs229.stanford.edu/proj2016/report/JinElSaawy-PortfolioManagementusingReinforcementLearning-report.pdf) [note]()
- [RL] 1996/ Use Of Neural Network Ensembles for Portfolio Selection and Risk Management


Stock Price Prediction
- [QLearning] Q-Learning-for-Auto-Trading [Siraj's TY](https://www.youtube.com/watch?v=rRssY6FrTvU&feature=youtu.be) / [Siraj's Github](https://github.com/llSourcell/Q-Learning-for-Trading)
- [RL] Q-learning applied to (short-term) stock trading [Siraj YT](https://www.youtube.com/watch?v=05NqKJ0v7EE) / [Siraj's Github](https://github.com/llSourcell/Reinforcement_Learning_for_Stock_Prediction) / [Original Github](https://github.com/edwardhdlu/q-trader)
- [GAN] 2018: Stock Market Prediction on High-Frequency Data Using Generative Adversarial Nets [paper](https://www.hindawi.com/journals/mpe/2018/4907423/)
- [AttentionRNN] 2017: A Dual-Stage Attention-Based Recurrent Neural Network for Time Series Prediction (The Nonlinear autoregressive exogenous (NARX) model) [paper](https://arxiv.org/abs/1704.02971) / [Pytorch example blog](http://chandlerzuo.github.io/blog/2017/11/darnn) / [update Github](https://github.com/Seanny123/da-rnn) / [note]()

- [Multi LSTM] Using multidimensional LSTM neural networks to create a forecast for Bitcoin price [blog](http://www.jakob-aungiers.com/articles/a/Multidimensional-LSTM-Networks-to-Predict-Bitcoin-Price) / [Siraj's Github](https://github.com/llSourcell/Multidimensional-LSTM-BitCoin-Time-Series)
- [LSTM] Bitcoin Prediction beat ARIMA [Siraj's YT](https://www.youtube.com/watch?v=EqWm8A-dRYg&feature=youtu.be) / [Siraj's Github](https://github.com/llSourcell/bitcoin_prediction)
- [CNN] Use Tensorflow to run CNN for predict stock movement [Siraj's Github](https://github.com/llSourcell/Tensorflow-for-stock-prediction)
- [DL] Financial Forecasting using Tensorflow.js [Siraj's YT](https://www.youtube.com/watch?v=5Uw1iSwvHH8) / [Siraj's Github](https://github.com/llSourcell/Financial_Forecasting_with_TensorflowJS)
- [Keras+TF] How to Predict Stock Prices Easily - Intro to Deep Learning [Siraj's YT](https://www.youtube.com/watch?v=ftMq5ps503w&feature=youtu.be) / [Siraj's Github](https://github.com/llSourcell/How-to-Predict-Stock-Prices-Easily-Demo)
- [ML&Sentimental] Stock Market Prediction [Siraj's TY](https://www.youtube.com/watch?v=JuLCL3wCEAk&feature=youtu.be) / [Siraj's Github](https://github.com/llSourcell/Stock_Market_Prediction)
- [Keras] Predicting Stock Prices [Siraj's TY](https://www.youtube.com/watch?v=SSu00IRRraY&feature=youtu.be) / [Siraj's Github](https://github.com/llSourcell/predicting_stock_prices)




Fraud Detection
- Fraud Detection model based on anonymized credit card transactions [Siraj's YT](https://www.youtube.com/watch?v=UNgdIkuVC6g) / [Siraj's Github](https://github.com/llSourcell/AI_for_Financial_Data)
- [One-Class Adversarial Nets for Fraud Detection](https://arxiv.org/pdf/1803.01798.pdf)
- [Detection of Anomalies in Large-Scale
Accounting Data using Deep Autoencoder
Networks](https://arxiv.org/pdf/1709.05254.pdf)
- [Bypass Fraud Detection:
Artificial Intelligence Approach](https://arxiv.org/ftp/arxiv/papers/1711/1711.04627.pdf)
- [Transaction Fraud Detection Using GRU-centered Sandwich-structured Model](https://arxiv.org/ftp/arxiv/papers/1711/1711.01434.pdf)
- [Opinion Fraud Detection via Neural Autoencoder Decision Forest](https://arxiv.org/pdf/1805.03379.pdf)
- [Instance-Level Explanations for Fraud Detection: A Case Study](https://arxiv.org/abs/1806.07129)
- [A Comprehensive Survey of
Data Mining-based Fraud Detection Research](https://arxiv.org/ftp/arxiv/papers/1009/1009.6119.pdf)
- [Streaming Active Learning Strategies for Real-Life Credit Card Fraud Detection: Assessment and Visualization](https://arxiv.org/abs/1804.07481)
- [Sequential Behavioral Data Processing Using Deep Learning and the Markov Transition Field in Online Fraud Detection](https://arxiv.org/abs/1808.05329v1)
- [A Survey of Credit Card Fraud Detection Techniques: Data and Technique Oriented Perspective](https://arxiv.org/abs/1611.06439v1)

Sentimental Analysis
- [TF] Sentiment Analyzer on IMDB movie [Siraj's YT](https://www.youtube.com/watch?v=si8zZHkufRY&feature=youtu.be) / [Siraj's Github](https://github.com/llSourcell/How_to_do_Sentiment_Analysis)
 
 
Optimication/Decision Making
- [RL] Adobe: Risk-averse Decision-making & Control [slide](http://www.cs.unh.edu/~mpetrik/tutorials/risk/riskaverse_rl.pdf)
===
- FinBrain: When Finance Meets AI 2.0. [arxiv](https://arxiv.org/abs/1808.08497v1)
- Deep Learning in Finance. [arxiv](https://arxiv.org/abs/1602.06561v3) - 2018
- Forecasting Economics and Financial Time Series: ARIMA vs. LSTM. [arxiv](https://arxiv.org/abs/1803.06386v1) - 2018
- TSViz: Demystification of Deep Learning Models for Time-Series Analysis. [arxiv](https://arxiv.org/abs/1802.02952v1) - 2018
- Geometric Learning and Filtering in Finance. [arxiv](https://arxiv.org/abs/1710.05829v2) - 2017
- On Feature Reduction using Deep Learning for Trend Prediction in Finance. [arxiv](https://arxiv.org/abs/1704.03205v1) - 2017
- Forecasting Volatility in Indian Stock Market using Artificial Neural Network with Multiple Inputs and Outputs. [arxiv](https://arxiv.org/abs/1604.05008v1) - 2016
- Financial Market Modeling with Quantum Neural Networks. [arxiv](https://arxiv.org/abs/1508.06586v1) - 2015
- Identifying Metaphoric Antonyms in a Corpus Analysis of Finance Articles. [arxiv](https://arxiv.org/abs/1212.3139v2) - 2013
- Good Debt or Bad Debt: Detecting Semantic Orientations in Economic Texts. [arxiv](https://arxiv.org/abs/1307.5336v2) - 2013
- Identifying Metaphor Hierarchies in a Corpus Analysis of Finance Articles. [arxiv](https://arxiv.org/abs/1212.3138v1) - 2012


Credit scoring:

- [Segment-Based Credit Scoring Using Latent Clusters in the Variational Autoencoder](https://arxiv.org/abs/1806.02538v1)
- [Improving a Credit Scoring Model by Incorporating Bank Statement Derived Features](https://arxiv.org/abs/1611.00252v2)
- [Transfer Learning Using Logistic Regression in Credit Scoring](https://arxiv.org/abs/1212.6167v1)

PF:

- [Different but Equal: Comparing User Collaboration with Digital Personal Assistants vs. Teams of Expert Agents](https://arxiv.org/abs/1808.08157v1)
- [PersonaBank: A Corpus of Personal Narratives and Their Story Intention Graphs](https://arxiv.org/abs/1708.09082v1)
- [Intelligent Personal Assistant with Knowledge Navigation](https://arxiv.org/abs/1704.08950v1)

Sentiment Analysis:

- [Deep Learning for Sentiment Analysis : A Survey](https://arxiv.org/abs/1801.07883v2)
- [Financial Aspect-Based Sentiment Analysis using Deep Representations](https://arxiv.org/abs/1808.07931v1)
- [The Evolution of Sentiment Analysis - A Review of Research Topics, Venues, and Top Cited Papers](https://arxiv.org/abs/1612.01556v4)



#### Literature ML Finance focused

[Back to top](#contents)

1. Neurocomputing - Machine learning in finance [link](https://www.sciencedirect.com/journal/neurocomputing/vol/264/suppl/C)
* Stock portfolio selection using learning-to-rank algorithms with news sentiment
* Twitter data models for bank risk contagion
* Bank distress in the news: Describing events through deep learning

2. Advances in Financial Machine Learning [book](https://books.google.com/books?id=v0RKDwAAQBAJ&pg=PT77&lpg=PT77&dq=Neurocomputing+-+Machine+learning+in+finance&source=bl&ots=X0V2K9SMsz&sig=ACfU3U33MJYhIP1AicdPX-bxbDtYbLUWRw&hl=zh-TW&sa=X&ved=2ahUKEwjLyu6EqLDgAhUGPa0KHVKNCMsQ6AEwCnoECAoQAQ#v=onepage&q=Neurocomputing%20-%20Machine%20learning%20in%20finance&f=false)




#### Actuarial Science Program Worldwide

[Back to top](#contents)

1. ETH Zurich / Department of Math / RiskLab Switzerland [Course](http://www.risklab.ch/education/courses.html) 強
2. RiskLab Finland [website](https://risklab.fi/)
3. The School of Risk & Actuarial Studies at UNSW Sydney [Course](https://www.business.unsw.edu.au/degrees-courses/postgraduate) 還好
4. UIUC University of Illinois at Urbana-Champaign, Department of Mathematics, Actuarial Program [Facultyx3](https://math.illinois.edu/research/faculty-research/actuarial-science)
5. GSU CEAR Georgia State University / Center for the Economics Analysis of Risk [Lots of Conference](https://cear.gsu.edu/working-papers/) Department of Risk Management and Insurance 
6. UNSW University of New South Wales, Australia The School of Risk & Actuarial Studies
Focus on AIPAR (Australian Institute for Population Ageing and Research) and the Centre of Excellence in Population Ageing and Research (CEPAR).
7. Wisconsin University of Wisconsin–Madison


The University of Melbourne
Laval University, Canada
The University of Hong Kong
University of Waterloo, Canada
University of Iowa


EBOOK
- 2018 [An Introduction to Computational Risk Management of Equity-Linked Insurance](https://www.readcube.com/articles/10.1201%2F9781315151687?shared_access_token=llN13LeTubXYwWnRseViDcvVM4Hs7mp6nzCJVzl2VoUrNp4f8MGH1nnddg1N7UKIPYjEPrfO6f890wTSQfnuRLKX4x_O7YRYGJCHdJDVbfvWvk3YXr_rFmwzLaVqOuaeAPrZnkDTWbW7LLF6EXnDtE43yPy_Ugl-XKLgmIGatFY%3D)




#### Australia / RiskLab 

PhD Research Projects [link](https://research.csiro.au/risklab/phd-research-projects/)
1. PhD Project: Simulation-based stochastic control for portfolio management
2. PhD Project: Long-term decision making under uncertainty for sustainable life-cycle retirement management
3. PhD Project: Cyber security (analysis and evaluation)
4. **PhD Project: Cyber security (model and product design)**
* Develop a quantitative pricing model for cyber-insurance. 
* Develop a model for determining resource allocations to combat cyber-crime.
5. **PhD Project: Non-Linear Least Square Monte-Carlo Algorithms**
6. PhD Project: Local Volatility Inference through Optimal Transport
7. **PhD Project: Statistical analysis and visualisation of spatially distributed big time series electricity usage data**
* Cognostics methods for electricity usage time series data with spatial and spatio-temporal structure.
* Develop visualisation methods for spatial and spatio-temporal cognostics for spatially distributed big time series.
* Develop inferential methods for spatially distributed large time series electricity usage data. 
8. PhD Project: Statistical analysis of big time series electricity usage data
* Develop scalable method to analyse a large number of time series. 
* Extend the scalable method developed to analyse a large number of time series to work in real-time or near real-time.
9. PhD Project: Optimal retirement age for a sustainable superannuation system
10. **PhD Project: Managing and modeling longevity risk in the 21st century**
11. PhD Project: Alternative stochastic models in Finance
12. PhD Project: Health of an ageing population
13. **PhD Project: Designing a method to hedge European (social) welfare risk**
* The identification and  modelling  of causes of  increased  welfare  costs (retirement costs, unemployment costs, disability costs etc).
* The design of a bond like product that will smooth those costs by transferring some of the risk from individual countries to the issuer of the European bond (e.g. the European central bank).
14. PhD Project: Solving Portfolio Selection Problems under Gaussian Process
15. **PhD Project:  Contribution of real option to sustainable agriculture**
16. **PhD Project:  Conditional Phase – Type Model in Pension and Health Insurance Premium Calculations**
17. **PhD Project:  Real time car insurance for the New Age** [Allianz](https://www.allianz.com.au/car-insurance/news/use-of-telematics-in-vehicles)
18. PhD Project:  Assessing the Real Option Approach for Mining projects
19. **PhD Project:  Pricing in a competitive stochastic insurance market**
20. **PhD Project:  The impact of climate change in pricing reserve in a competitive insurance market**




















RiskLab Finland

RiskLab Toronto

RiskLab Madrid


#### ML DL Finance Conference

[Back to top](#contents)

--

Sponsored by SOA already 50+ years
2018 Actuarial Research Conference [program](https://conference.uwo.ca/arc2018/program_schedule.pdf)

--

Sponsered by UNSW
[2018] 22nd International Congress on Insurance: Mathematics and Economics [Web](https://www.business.unsw.edu.au/Campaigns/IME2018) [program](https://www.business.unsw.edu.au/Campaigns-Site/IME2018/Documents/program-schedule.pdf)


--

[2019/June/Switzerland] Insurance Data Science Conference [Web](https://insurancedatascience.org)
[2018/London] Insurance Data Science Conference [Web](https://insurancedatascience.org/project/london2018/)
[2017/Paris] R in Insurance [Web](https://insurancedatascience.org/project/paris2017/)
[2016/London] R in Insurance [Web](https://insurancedatascience.org/project/london2016/)
[2015/AMSTERDAM] R in Insurance [Web](https://insurancedatascience.org/project/amsterdam2015/)
[2014/London] R in Insurance [Web](https://insurancedatascience.org/project/london2014/)
[2013/London] R in Insurance [Web](https://insurancedatascience.org/project/london2013/)

--

Sponsered by ETH Zurich
[2019/ETH Zurich] Risk Day 2019 [Web]()
[2018/ETH Zurich] Risk Day 2018 [Web](https://www.math.ethz.ch/imsf/events/risk-day/past-risk-days/programme.html#gonon-abstract)
* AI in risk management and risk management in AI [slide](https://www.ethz.ch/content/dam/ethz/special-interest/math/risklab-dam/documents/Risk%20Day/2018/Flueckiger.pdf)
* Hedging derivatives under market frictions using deep learning techniques [slide](https://www.ethz.ch/content/dam/ethz/special-interest/math/risklab-dam/documents/Risk%20Day/2018/Gonon.pdf)
[2017/ETH Zurich] Risk Day 2017 [Web](http://ccfz.ch/events/past-events/ccfz15092017.html)
* Machine learning in mortality modeling [slide](http://www.ccfz.ch/files/deprez.pdf)
[2016/ETH Zurich] Risk Day 2016 [Web](http://ccfz.ch/events/forthcoming-events/ccfz16092016.html)
[2015/ETH Zurich] Risk Day 2015 [Web](http://www.ccfz.ch/events/forthcoming-events/ccfz11092015.html)
* Insurance-Linked Securities [slide](http://www.ccfz.ch/files/5_muraviev.pdf)
* Risk models in practice: The view of a non-mathematician[slide](http://www.ccfz.ch/files/6_giger.pdf)
[2014/ETH Zurich] Risk Day 2014 [Web](http://www.ccfz.ch/events/past-events/ccfz12092014.html)
* 20 years of RiskLab [slide](http://www.ccfz.ch/files/1_embrechts_2.pdf)
[2013/ETH Zurich] Risk Day 2013 [Web]()


-- 

Sponsered by GSU CEAR
GSU CEAR [Archieved Conference](https://cear.gsu.edu/archived-workshops/?wpv_aux_current_post_id=3193&wpv_view_count=11499-TCPID3193&wpv_paged=3#) 好像還好？
* 2019 CEAR/Huebner Summer Risk Institute
* Welfare, Preferences, and Risk: Theory, Behavioural Evidence, and Policy
* Georgia State FinTech Conference 2019
* The Chicago School and Research Related to Organizational and Market Risk, a 50-Year Perspective
* Behavioral and Experimental Public Choice Workshop 2019
* 6th Workshop in Behavioral and Experimental Health Economics
* CEAR/MRIC Behavioral Insurance Workshop 2018

-- 

Sponsered by Columbia
[2018] Machine Learning in Finance Workshop 2018 by The Data Science Institute (DSI) at Columbia University and Bloomberg [Web](https://cfe.columbia.edu/machine-learning-finance-workshop-2018)
* A High Frequency Trade Execution Model for Supervised Learning [slide](https://cfe.columbia.edu/files/seasieor/industrial-engineering-operations-research/MathewDixon_HFT_MM_Columbia_Bloomberg.pdf)
* Big Data's Dirty Secret [slide](https://cfe.columbia.edu/files/seasieor/industrial-engineering-operations-research/HarveyStein_BigDataSecretShort.pdf)

--

Sponsered by Finland RiskLab
Conference run by Finland RiskLab [web](https://risklab.fi/events/)
* 2019 RiskLab/BoF/ESRB Conference on Systemic Risk Analytics
* 2018 RiskLab/BoF/ESRB Conference on Systemic Risk Analytics
* 2018 Special session on Machine Learning and Network Analytics in Finance
* 2017 RiskLab/BoF/ESRB Conference on Systemic Risk Analytics
* 2017 Special session on Machine Learning and Network Analytics in Finance
* Special session on Systemic Financial Risk Analytics
* 2016 RiskLab/BoF/ESRB Conference on Systemic Risk Analytics
* Special session on Systemic Risk Analytics
* Special session on Systemic Risk Analytics
* 2015 RiskLab/BoF/ESRB Conference on Systemic Risk Analytics
* Special session on Systemic Risk Analytics and Macroprudential Policy
Session on Systemic Risk Analytics and Macroprudential Policy

--

International Gerber-Shiu Workshop
Actuarial Research Conference


----------

#### Libraries 

[Back to top](#contents)

- [ml-fraud-detection](https://github.com/georgymh/ml-fraud-detection)
- [watson-banking-chatbot](https://github.com/IBM/watson-banking-chatbot)


![architecture](https://github.com/IBM/watson-banking-chatbot/blob/master/doc/source/images/architecture.png)

- [Deep-Trading](https://github.com/Rachnog/Deep-Trading)
- [Trading-Gym](https://github.com/thedimlebowski/Trading-Gym)
- [gym-trading](https://github.com/hackthemarket/gym-trading)
- [mosquito](https://github.com/miro-ka/mosquito)
- [deep-algotrading](https://github.com/LiamConnell/deep-algotrading)
- [Credit-Card-Fraud-Detection-using-Autoencoders-in-Keras](https://github.com/curiousily/Credit-Card-Fraud-Detection-using-Autoencoders-in-Keras)
- [Fraud-detection-using-deep-learning](https://github.com/aaxwaz/Fraud-detection-using-deep-learning)
- [credit-card-fraud](https://github.com/ellisvalentiner/credit-card-fraud)
- [ml-fraud-detection](https://github.com/georgymh/ml-fraud-detection)

--------------

#### Startups

[Back to top](#contents)



-------------

#### Appendix

[Back to top](#contents)

![AI-in-FinTech-Market-Map-Image3](https://cbi-blog.s3.amazonaws.com/blog/wp-content/uploads/2017/03/AI-in-FinTech-Market-Map-Image3.png)


![Screen-Shot-2018-07-18-at-7.38.18-PM-1024x467](https://s3.amazonaws.com/cbi-research-portal-uploads/2018/07/18193851/Screen-Shot-2018-07-18-at-7.38.18-PM-1024x467.png)



![Artificial-Intelligence-Financial-Industry](https://thefinancialbrand.com/wp-content/uploads/2018/05/Artificial-Intelligence-Financial-Industry.png)
