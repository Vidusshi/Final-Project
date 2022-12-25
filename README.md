# Digital Methods for Social Sciences - Final Project
## Analysing Reactions to Nancy Pelosi's Taiwan Visit | August 2022 

### INTRODUCTION

On August 2, 2022, Nancy Pelosi - the Speaker of the House of Representatives of the United States - visited Taiwan during a tour of Asia, accompanied by five other Democratic Party members. She did so despite repeated warnings from China and the risk of already strained relations between the United States and China becoming worse. As is already known, Taiwan is a contested island that is constantly at the risk of being ‘reunified’ with the Chinese mainland under the latter’s One China Policy. The visit expectedly came with a serious set of ramifications - the People’s Liberation Army of China deployed a destroyer and guided missile frigate in the waters surrounding Taiwan. In this project, we seek to understand the reactions to the contentious visit by Speaker Pelosi by two primary stakeholders - the media and common public, what impact said event had, and what kind of narratives emerged from it. 


### METHODOLOGY

In order to understand the impact of Speaker Pelosi’s visit and the narratives promoted by different actors, we use different digital methods on two different datasets on the CorText platform. The first is a corpus of media articles on the visit published between 30th July 2022—when debates regarding her potential visit started, to 10th August 2022—a week after the visit itself. The second dataset is a corpus of tweets published in the same period that mention Pelosi’s visit to Taiwan. For each section, we also analyse a smaller corpus of solely Chinese and/or Taiwanese sources to better reflect the nuances of the themes discussed. Each analysis involves the use of digital media analysis techniques such as Demography, Epic Epoch, Topic Modeling, Terms Extraction and Network Mapping scripts.

## SECTION I
 
**Analysis of Media Articles**

In today’s fast-paced world, the readership of printed newspapers has gradually declined. Print media outlets have also adapted to the changing times and increasingly publish articles online as well. Information can now be found in a multitude of ways online, be it through social media networks, official Twitter handles or webpages of online publications. In fact, 72% of EU internet users aged 16-74 read online news sites, newspapers or news magazines. Therefore, the importance of the digital word in shaping views and perceptions has drastically increased, and the delivery of online news has the power to sensationalise information. This is especially evident in the case of our topic, where a short visit—what some might consider to be a blip in the grand scheme of events happening around the world—generated such a magnitude of media coverage. In the days leading to Speaker Pelosi’s visit, worldwide media delivered an hour-by-hour coverage of the events unfolding, both reporting on and feeding the frenzy that people believed could lead to a third world war. Therefore, understanding the narratives propagated by media articles is essential in our analysis of the reactions to the visit.  In this section, we use different digital methods to break down the topics and themes discussed in media articles, how they relate to each other, and understand how the publication sources—the political alignment of the outlets—factor into what information is being promoted. We also analyse a smaller subset of the corpus comprising Chinese and Taiwanese media sources to better understand the reactions and narratives present there.


**Methodology**

The corpus of media articles on the Pelosi visit has been acquired through the Factiva platform. We used the ‘Search Form’ feature of the platform to find articles that mention both “Pelosi” and “Taiwan” in our selected time period of 30th July 2022 - 10th August 2022. We further filter down to only English language articles. While this provides a collection of more than 14,000 publications, several of them are duplicates. We find that several publishers have multiple publications that run identical or highly similar stories, thus distorting the corpus. Moreover, some publications are transcripted versions of video media segments or are wrap-ups of news-sheets that merely mention the Pelosi visit but also cover a much wider range of topics such as the Ukraine War, other regional conflicts, economic and financial reporting, etc. Therefore, to build a curated and relevant corpus, we further filter out distortionary articles that are centred around climate, ukraine, and russia, and do not consider articles that are duplicate or similar. This gives us a corpus of 3,617 relevant articles from a wide range of sources—from Reuters, Dow Jones and CNN to South China Morning Post, China Daily and Taiwan News.

In the following sub-sections, we dissect the corpus by identifying the frequently used terms and sources of publication, and understanding the trends in the contents using Epic Epoch and Demography scripts on CorText. We also break down the topics discussed in the corpus using Topic Modeling and Network Mapping scripts.

### Section I.I : General Corpus

**A. Top sources of publication**

![Screenshot 2022-12-25 at 9 13 18 PM](https://user-images.githubusercontent.com/115983317/209480907-a0c53609-f3e8-40d7-b236-9038ea3479aa.png)

The table above shows the top 20 publishing sources in our media corpus. As evident, there are a variety of sources represented from different countries and of varying political inclinations. CE NoticiasFinancieras is a Latin American publisher run by ContentEngine LLC. There are several western publications present such as Reuters News, Dow Jones, ABC News, Independent Online, etc. There are Asian—especially, Chinese and Taiwanese—publications such as Central News Agency, Taiwan News, Global Times and Xinhua News Agency. Thus, this confirms that our corpus is well-represented for the topic at hand.

**B. Top Terms in the General Corpus**

![Screenshot 2022-12-25 at 9 19 40 PM](https://user-images.githubusercontent.com/115983317/209481022-82ba7055-b31b-403d-a953-473c7499aff2.png)

The table above shows some of the top extracted terms from the corpus after cleaning. As expected, we can see terms like “Taiwan Strait crisis”, “tensions with China” and terms related to military drills and exercises. We also see other indicative terms like “Liberation Army”, “territorial integrity” and mentions of the One China principle. We also have terms from the other end of the spectrum such as “Taiwan independence” and “support Taiwan”. Another group of terms relate to the United States and other government actors such as “Foreign Minister”, “White House”,” President Joe Biden”, “President Tsai Ing-wen”, etc..


**C. Demography and Epic Epoch**

A demography analysis and a bump graph (epic epoch) are presented below in order to study the evolution of term usage over the time period of our study. For this purpose, the list of terms was narrowed down to 23 relevant terms which were indexed back to the general corpus. 

![Screenshot 2022-12-25 at 9 21 55 PM](https://user-images.githubusercontent.com/115983317/209481060-b16c47a8-2be0-4e8c-93de-6f98bfe39be2.png)

Looking at the above trend, we can see that the term “Asia tour” peaked in the start when there were reports of such a tour being undertaken by Nancy Pelosi and while it is still widely discussed, its frequency of mentions declines over time. This is replaced by the mention of “military drills'' and the “median line” as China reacted with military action against Taiwan. Though small, a similar trend can be observed in case of the term “ballistic missile”. We can also see how the mention of “one-China principle” peaks in the middle when China expressed its discontent over the trip as a violation of the principle. As a result of the trip, the discussions around “blockade of Taiwan'' also picked up pace in the middle and died down in the last few days. 

Discussions around the “semiconductor industry” peak in the last part of the study period possibly in reaction to the sanctions imposed and military drills around Taiwan by China that threatened the industry’s trade. Other topics are found to have a consistently medium to low frequency of discussion throughout the study period. 
![Screenshot 2022-12-25 at 9 22 48 PM](https://user-images.githubusercontent.com/115983317/209481070-6aa2ac87-2511-486b-a225-124a2d0f71fd.png)

Moving on to the bump graph as presented below, similar trends can be observed – “Asian tour” is first mentioned with high frequency and then is overtaken by “military drills” and “median line”. Terms like “territorial integrity” and “national sovereignty” also lose importance over time in the corpus. The term “Semiconductor industry”, as observed above, can be seen relatively rising over time and terms like “blockade of Taiwan” and “ballistic missiles” rise in the middle and then lose importance in the discussions over the last few days. 
