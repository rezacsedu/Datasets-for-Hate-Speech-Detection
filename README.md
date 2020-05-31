## Introduction
In this *repository*, we pretent to organize the information of datasets that have been used for hate speech detection or related concepts such as *ciberbullying*, *abusive language*, *online harassment*, among others, to make it easier for researches to obtain datasets.

Even when there are several social media platforms to get data from, the construction of a balanced labeled dataset is a costly task in time and effort and it is still a problem for the researchers in the area. Although most of the below listed datasets are not explicitly available, some of them can be obtained from the authors, if requested. 


## Datasets from Related Literature
### English Language

|  No|           Datasets                    (Link to paper)          |          Objects          |             Size             |                                                   Available                                                    |                                                Labels                                                 |
| :----:| :--------------------------: | :-----------------------: | :--------------------------: | :------------------------------------------------------------------------------------------------------------: | :----------------------------------------------------------------------------------------------------: |
|1|     [Dinakar et al., 2011](https://ie.technion.ac.il/~roiri/papers/3841-16937-1-PB.pdf)     |     YouTube Comments      |             6000             |                                                       -                                                         |                                 Sexuality, Race, Culture, Intelligence                                  |
|2|    [Dadvar and Jong, 2012](https://ris.utwente.nl/ws/portalfiles/portal/5512243/DIR12_reviewed04.pdf)     |       Myspace Posts       |             2200             |                                                       -                                                      |                                         Bullying, Non Bullying                                         |
|3|      [Huang et al., 2014](https://wp.comminfo.rutgers.edu/vsingh/wp-content/uploads/sites/110/2016/10/p3-huang-1.pdf)      |          Tweets           |             4865             |                                                       -                                                       |                                         Bullying, Non Bullying                                         |
|4|  [Hosseinmardi et al., 2015](https://www.cs.colorado.edu/~rhan/Papers/socinfo2015_labeled.pdf)   | Instagram Media Sessions  |             998              |                                                       -                                                          |                                         bullying, Non bullying                                         |
|5|    [Waseem and Hovy, 2016](https://www.aclweb.org/anthology/N16-2013.pdf)     |          Tweets           |            16914             |                             [Download](https://github.com/zeerakw/hatespeech)                             |                                             Racist, Sexist, Either                                          |
|6|         [Waseem, 2016](https://www.aclweb.org/anthology/W16-5618.pdf)         |          Tweets           |             6909             |                             [Download](https://github.com/zeerakw/hatespeech)                             |                                      Racist, Sexist, Either,Both                                       |
|7|     [Nobata et al., 2016](http://www.yichang-cs.com/yahoo/WWW16_Abusivedetection.pdf)      |      Yahoo Comments       |             2000             |                                                       -                                                       |                                             Abusive, Clean                                             |
|8|    [Chatzakou et al., 2017](https://arxiv.org/abs/1702.06877)    |       Twitter Users       |             9484             |                                                       -                                                       |                                       Aggressor, Bully, Spammer                                        |
|9|    [Davidson et al., 2017](https://arxiv.org/pdf/1703.04009.pdf)     |          Tweets           |            24802            | [Download](https://github.com/t-davidson/hate-speech-and-offensive-language/blob/master/data/labeled_data.csv)    |                                    hate\_speech, offensive, neither                                    |
|10|     [Golbeck et al., 2017](http://www.cs.umd.edu/~golbeck/papers/trolling.pdf)     |          Tweets           |            35000             |                                                       -                                                       |                                       Harassing, Non Harassing                                        |
|11|      [Wulczyn et al. 2017](http://papers.www2017.com.au.s3-website-ap-southeast-2.amazonaws.com/proceedings/p1391.pd)   |     Wikipedia Comments     |             100000             |                                                       [Download](figshare.com/articles/Wikipedia_Detox_Data/4054689t)                                                        |                                   Personal Attacks
|12| [Tahmasbi and Rastegari, 2018](https://dl.acm.org/doi/10.1145/3290838) |          Tweets           |            12837            |                                                       -                                                       |                                         Bullying, Non Bullying                                         |
|13|    [Anzovino et al., 2018](https://link.springer.com/chapter/10.1007/978-3-319-91947-8_6)     |          Tweets           |             4454             |                                                       -                                                       | Discredit, Stereotype, Objectification, Sexual_Harassment, Threats of Violence, Dominance, Dearailingy |
|14|     [Founta et al., 2018](https://datalab.csd.auth.gr/wp-content/uploads/publications/17909-77948-1-PB.pdf)      |          Tweets           |            80000             |          [Download](https://dataverse.mpi-sws.org/dataset.xhtml?persistentId=doi:10.5072/FK2/ZDTEMN)          |                                      Hate Speech, Offensive, None                                      |
|15|     [Gibert et al., 2018](https://www.aclweb.org/anthology/W18-5102.pdf)      | Sentences from Stormfront |            10568             |                       [Download](https://github.com/aitor-garcia-p/hate-speech-dataset)                       |                                 Hate Speech, Non Hate Speech                                      |
|16|       [SemEval19, 2019](https://www.aclweb.org/anthology/S19-2007.pdf)        |          Tweets           |             9000             |                                                       [Request Link](http://hatespeech.di.unito.it/hateval.html)                                                       |                                          Hate speech, Non Hate Speech                                      |
|17|      [OLID 2019](https://www.aclweb.org/anthology/N19-1144.pdf)    |     Tweets     |             14100             |                                                       [Download](https://competitions.codalab.org/competitions/20011#participate)                                                        |                Offensive, Non Offensive

### Spanish 

|  No|           Datasets                    (Link to paper)          |          Objects          |             Size             |                                                   Available                                                    |                                                Labels                                                 |
| :----:| :--------------------------: | :-----------------------: | :--------------------------: | :------------------------------------------------------------------------------------------------------------: | :----------------------------------------------------------------------------------------------------: |
|1|      [IberEval 2018](http://ceur-ws.org/Vol-2150/overview-AMI.pdf)    |     Tweets     |             4138            |                                                        [Download](https://amiibereval2018.wordpress.com/important-dates/data/)                                                        |        Misogeny (5 cathegories), Not Misogeny 
|2|      [MEX-A3T](http://ceur-ws.org/Vol-2150/overview-mex-a3t.pdf)    |     Tweets     |             11,000            |                                                        [Download](https://mexa3t.wixsite.com/home/aggressive-detection-track)                                                        |        Aggressive (5 cathegories), Not Aggressive 
|3|       [SemEval19, 2019](https://www.aclweb.org/anthology/S19-2007.pdf)        |          Tweets           |             4500        |     [Request Link](http://hatespeech.di.unito.it/hateval.html)  |        Hate Speech, Non Hate Speech 
|4|      [Pereira et al., 2019](https://www.mdpi.com/1424-8220/19/21/4654)    |     Tweets     |             6000             |                                                        [Download](https://zenodo.org/record/2592149#.XmuNJahKg2w)                                                        |        Hate Speech, Non Hate Speech 



### Other languages

|  No|           Datasets                    (Link to paper)          |          Objects          |             Size             |                                                   Available                                                    |   Language    |                                                 Labels                                                 |
| :----:| :--------------------------: | :-----------------------: | :--------------------------: | :------------------------------------------------------------------------------------------------------------: | :-----------: | :----------------------------------------------------------------------------------------------------: |
|1|       [Hee et al., 2015](https://www.aclweb.org/anthology/R15-1086.pdf)       |       Ask.fm Posts        |            85485             |                                                       -                                                       |     Dutch     |       Threat-Blackmail, Sexual-talk, Insult, Curse-Exclusion, Defense, Defamation-Encouragement        |
|2|    [Papegnies et al., 2017](https://arxiv.org/abs/1708.01060)    |      Game Chat Logs       |             2779             |                                                       -                                                       |    French     |                                          Abusive, Non Abusive                                          |
|3|   [Sanguinetti et al., 2018](https://www.aclweb.org/anthology/L18-1443.pdf)   |          Tweets           |             6000             |                            [Download](https://github.com/msang/hate-speech-corpus)                            |    Italian    |                                     Hate Speech, Non Hate Speech                                     |
|4|     [Sirihattasak et al., 2018](https://biblio.ugent.be/publication/8562716/file/8562719.pdf)     |          Tweets           |            3,300             |                                                      Yes                                                       |     Thai      |                                            Toxic, Non Toxic                                            |
|5|      [Bohra et al., 2018](https://www.aclweb.org/anthology/W18-1105/)      |          Tweets           |             4575             |                                                      Yes                                                       | Hindi-English |                                     Hate Speech, Non Hate Speech                                      |
|6|     [Sanguinetti et al., 2018](https://www.aclweb.org/anthology/L18-1443.pdf)      |          Tweets           |            6929             |          [Download](https://github.com/msang/hate-speech-corpus)          |    Italian    |                                      Hate Speech, Non Hate Speech                             |
|7|     [Albadi et al., 2018](https://ieeexplore.ieee.org/document/8508247)      | Tweets |            6136             |                       [Download](https://github.com/nuhaalbadi/Arabic_hatespeech)                       |    Arabic    |                                      Hate Speech, Non Hate Speech                                      |
|8|     [L-HSAB, 2019](https://www.aclweb.org/anthology/W19-3512/)     |     Tweets     |             5846             |                                                       [Download](https://github.com/Hala-Mulki/L-HSAB-First-Arabic-Levantine-HateSpeech-Dataset)                                                        |    Arabic    |                                 Normal, Abuse, Hate Speech
|9|      [Fortuna et al., 2019](https://www.aclweb.org/anthology/W19-3510.pdf)    |     Tweets     |              5668             |                                                        [Download](https://github.com/paulafortuna/Portuguese-Hate-Speech-Dataset)                                                        |    Portuguese    |      Hate Speech (81 categories), Non Hate Speech  
|10|      [Ousidhoum et al., 2019](https://arxiv.org/pdf/1908.11049.pdf)    |     Tweets     |              3353             |                                                        [Download](https://github.com/HKUST-KnowComp/MLMA_hate_speech)                                                        |    Arabic    |      Hate Speech, Non Hate Speech  


<!-- 
## References
1. [Maria Anzovino, Elisabetta Fersini, and Paolo Rosso. “Automatic Identification and Classification of Misogynistic Language on Twitter.” In:International Conference on Applications of Natural Language to Information Systems. Springer.2018, pp. 57–64.](https://link.springer.com/chapter/10.1007/978-3-319-91947-8_6)
2. [Valerio Basile, Cristina Bosco, Viviana Patti, Manuela Sanguinetti, Elisabetta Fersini, Debora Nozza, Francisco Rangel,and Paolo Rosso. SemEval-2019 Task 5: Multilingual Detection of Hate Speech Against Immigrants and Women in Twitter.](https://www.aclweb.org/anthology/S19-2007.pdf)
3. [Aditya Bohra, Deepanshu Vijay, Vinay Singh, Syed SarfarazAkhtar, and Manish Shrivastava. “A Dataset of Hindi-English Code-Mixed Social Media Text for Hate Speech Detection.” In:Proceedings of the Second Workshop on Computational Modeling of People’s Opinions, Personality, and Emotions in Social Media. 2018, pp. 36–41.](https://www.aclweb.org/anthology/W18-1105/)
4. [Despoina Chatzakou, Nicolas Kourtellis, Jeremy Blackburn,Emiliano De Cristofaro, Gianluca Stringhini, and AthenaVakali. “Mean Birds: Detecting Aggression and Bullying onTwitter.” In:Proceedings of the 2017 ACM on Web Science Conference, WebSci 2017, Troy, NY, USA, June 25 - 28, 2017.2017, pp. 13–22.](https://arxiv.org/abs/1702.06877)
5. [Maral Dadvar, de FMG Jong, Roeland Ordelman, and Dolf Tri-eschnigg. “Improved cyberbullying detection using gender information.” In:Proceedings of the Twelfth Dutch-Belgian Information Retrieval Workshop (DIR 2012). University of Ghent.2012.](https://ris.utwente.nl/ws/portalfiles/portal/5512243/DIR12_reviewed04.pdf)
6. Maral Dadvar and Franciska de Jong. “Cyberbullying detection: a step toward a safer internet yard.” In:Proceedingsof the 21st World Wide Web Conference, WWW 2012, Lyon,France, April 16-20, 2012 (Companion Volume). 2012, pp. 121–126.
7. [Thomas Davidson, Dana Warmsley, Michael W. Macy, andIngmar Weber. “Automated Hate Speech Detection and theProblem of Offensive Language.” In:Proceedings of the Eleventh International Conference on Web and Social Media, ICWSM2017, Montréal, Québec, Canada, May 15-18, 2017.AAAI Press,2017, pp. 512–515.](https://arxiv.org/pdf/1703.04009.pdf)
8. [Karthik Dinakar, Roi Reichart, and Henry Lieberman. “Modeling the Detection of Textual Cyberbullying.” In:The Social Mobile Web, Papers from the 2011 ICWSM Workshop,Barcelona, Catalonia, Spain, July 21, 2011. 2011.](https://ie.technion.ac.il/~roiri/papers/3841-16937-1-PB.pdf)
9. [Antigoni-Maria Founta, Constantinos Djouvas, DespoinaChatzakou,  Ilias  Leontiadis,  Jeremy  Blackburn,  Gianluca Stringhini, Athena Vakali, Michael Sirivianos, and Nicolas Kourtellis. “Large Scale Crowdsourcing and Characterization of Twitter Abusive Behavior.” In:Proceedings of the Twelfth International Conference on Web and Social Media, ICWSM 2018,Stanford, California, USA, June 25-28, 2018. 2018, pp. 491–500.](https://datalab.csd.auth.gr/wp-content/uploads/publications/17909-77948-1-PB.pdf)
10. [Ona de Gibert, Naiara Perez, Aitor García-Pablos, Montse Cuadros. Hate Speech Dataset from a White Supremacy Forum” Proceedings of the Second Workshop on Abusive Language Online (ALW2), pages 11–20 Brussels, Belgium, October 31, 2018](https://www.aclweb.org/anthology/W18-5102.pdf)
11. [Jennifer Golbeck, Zahra Ashktorab, Rashad O Banjo, Alexandra Berlinger, Siddharth Bhagwan, Cody Buntain, Paul Cheaka-los, Alicia A Geller, Quint Gergory, Rajesh Kumar Gnanasekaran et al. “A large labeled corpus for online harassment research.” In:Proceedings of the 2017 ACM on Web Science Conference.ACM. 2017, pp. 229–233.](http://www.cs.umd.edu/~golbeck/papers/trolling.pdf)
12. [Cynthia Van Hee, Els Lefever, Ben Verhoeven, Julie Mennes, Bart Desmet, Guy De Pauw, Walter Daelemans, and Véronique Hoste. “Detection and Fine-Grained Classification of Cyberbullying Events.” In:Recent Advances in Natural Language Processing, RANLP 2015, 7-9 September, 2015, Hissar, Bulgaria.2015, pp. 672–680](https://www.aclweb.org/anthology/R15-1086.pdf)
13. [Homa Hosseinmardi, Sabrina Arredondo Mattson, Rahat IbnRafiq, Richard Han, Qin Lv, and Shivakant Mishra. “Analyzing labeled cyberbullying incidents on the Instagram social network.” In:International Conference on Social Informatics.Springer. 2015, pp. 49–66](https://www.cs.colorado.edu/~rhan/Papers/socinfo2015_labeled.pdf)
14. [Sugan Sirihattasak, Mamoru Komachi, Hiroshi Ishikawa. "Annotation and Classification of Toxicity for Thai Twitter" In:TA-COS2018–2nd Workshop on Text Analytics for Cybersecurity and Online Safety, collocated with LREC 2018, 11th edition of the Language Resources and Evaluation Conference. European Language Resources Association (ELRA). 2018.](https://biblio.ugent.be/publication/8562716/file/8562719.pdf)
15. [Hala Mulki, Hatem Haddad, Chedi Bechikh Ali, and Halima Alshabani. L-hsab: A levantine twitter dataset for hate speech and abusive language.  In Proceedings of the Third Workshop on Abusive Language Online, pp. 111–118, 2019.](https://www.aclweb.org/anthology/W19-3512.pdf)
16. [Chikashi Nobata, Joel Tetreault, Achint Thomas , Yashar Mehdad, Yi Chang. "Abusive Language Detection in Online User Content"  International World Wide Web Conference Committee (IW3C2), WWW 2016](http://www.yichang-cs.com/yahoo/WWW16_Abusivedetection.pdf)
17. [Etienne Papegnies, Vincent Labatut, Richard Dufour, andGeorges Linares. “Graph-based Features for Automatic Online Abuse Detection.” In:International Conference on Statistical Language and Speech Processing. Springer. 2017, pp. 70–81.](https://arxiv.org/abs/1708.01060)
18. [Manuela Sanguinetti, Fabio Poletto, Cristina Bosco, VivianaPatti, and Marco Stranisci. “An Italian Twitter Corpus of Hate Speech against Immigrants.” In:Proceedings of the 11th Conference on Language Resources and Evaluation (LREC2018),May 2018, Miyazaki, Japan. 2018, pp. 2798–2895.](https://www.aclweb.org/anthology/L18-1443.pdf)
19. [Nargess Tahmasbi and Elham Rastegari. “A Socio-contextual Approach in Automated Detection of Cyberbullying.” In:Proceedings of the 51st Hawaii International Conference on System Sciences. 2018.](https://dl.acm.org/doi/10.1145/3290838)
20. [Zeerak Waseem. “Are you a racist or am i seeing things? annotator influence on hate speech detection on twitter.” In:Proceedings of the first workshop on NLP and computationalsocial science. 2016, pp. 138–142.](https://www.aclweb.org/anthology/W16-5618.pdf)
21. [Zeerak Waseem and Dirk Hovy. “Hateful Symbols or Hateful People? Predictive Features for Hate Speech Detection on Twitter.” In:Proceedings of the Student Research Workshop, SRW@HLT-NAACL 2016, The 2016 Conference of the North merican Chapter of the Association for Computational Lin-guistics: Human Language Technologies, San Diego California,USA, June 12-17, 2016. 2016, pp. 88–93.](https://www.aclweb.org/anthology/N16-2013.pdf)
22. [Ellery Wulczyn, Nithum Thain, and Lucas Dixon. "Ex machina:  Personal attacks seen at scale." In Proceedings of the 26th International Conference on World Wide Web, pp. 1391–1399. International World Wide Web Conferences Steering Committee, 2017.](http://papers.www2017.com.au.s3-website-ap-southeast-2.amazonaws.com/proceedings/p1391.pdf)
23. [Marcos Zampieri, Shervin Malmasi, Preslav Nakov, Sara Rosenthal, Noura Farra, and Ritesh Kumar. “Predicting the Type and Target of Offensive Posts in Social Media.” In:Pro-ceedings of NAACL. 2019](https://www.aclweb.org/anthology/N19-1144.pdf)
24. [Juan Carlos Pereira-Kohatsu, Lara Quijano Sánchez, Federico Liberatore, and Miguel Camacho-Collados. “Detecting and Monitoring Hate Speech in Twitter.” In:Sensors19.21 (2019),p. 4654.](https://www.mdpi.com/1424-8220/19/21/4654)