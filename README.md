# Digital Methods for Social Sciences - Final Project
## Analysing Reactions to Nancy Pelosi's Taiwan Visit | August 2022 

### Table of Contents

<a href="https://vidusshi.github.io/Final-Project/#introduction"> Introduction </a>

<a href="https://vidusshi.github.io/Final-Project/#methodology"> Methodology </a>

<a href="https://vidusshi.github.io/Final-Project/#section-i"> Section I: Analysis of Media Articles </a>

<a href="https://vidusshi.github.io/Final-Project/#section-ii--general-corpus"> Section I.I: General Corpus </a>

<a href="https://vidusshi.github.io/Final-Project/#section-iii--chinese-and-taiwanese-corpus"> Section I.II: Chinese and Taiwanese Corpus </a>

<a href="https://vidusshi.github.io/Final-Project/#section-iiii--observations-and-inferences"> Section I.III: Observations and Inferences </a>

<a href="https://vidusshi.github.io/Final-Project/#section-iii--general-twitter-corpus"> Section II: Twitter Analysis </a>

<a href="https://vidusshi.github.io/Final-Project/#section-iii--general-twitter-corpus"> Section II.I: General Twitter Corpus </a>

<a href="https://vidusshi.github.io/Final-Project/#section-iiii--china-corpus-for-twitter"> Section II.II : China Corpus for Twitter </a>

<a href="https://vidusshi.github.io/Final-Project/#conclusion"> Section II.II : Conclusion </a>






### INTRODUCTION

On August 2, 2022, Nancy Pelosi - the Speaker of the House of Representatives of the United States - visited Taiwan during a tour of Asia, accompanied by five other Democratic Party members. She did so despite repeated warnings from China and the risk of already strained relations between the United States and China becoming worse. As is already known, Taiwan is a contested island that is constantly at the risk of being ‘reunified’ with the Chinese mainland under the latter’s One China Policy. The visit expectedly came with a serious set of ramifications - the People’s Liberation Army of China deployed a destroyer and guided missile frigate in the waters surrounding Taiwan. In this project, we seek to understand the reactions to the contentious visit by Speaker Pelosi by two primary stakeholders - the media and common public, what impact said event had, and what kind of narratives emerged from it. 


### METHODOLOGY

In order to understand the impact of Speaker Pelosi’s visit and the narratives promoted by different actors, we use different digital methods on two different datasets on the CorText platform. The first is a corpus of media articles on the visit published between 30th July 2022—when debates regarding her potential visit started, to 10th August 2022—a week after the visit itself. The second dataset is a corpus of tweets published in the same period that mention Pelosi’s visit to Taiwan. For each section, we also analyse a smaller corpus of solely Chinese and/or Taiwanese sources to better reflect the nuances of the themes discussed. Each analysis involves the use of digital media analysis techniques such as Demography, Epic Epoch, Topic Modeling, Terms Extraction and Network Mapping scripts.

## SECTION I: Analysis of Media Articles
 
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

Moving on to the bump graph as presented above, similar trends can be observed – “Asian tour” is first mentioned with high frequency and then is overtaken by “military drills” and “median line”. Terms like “territorial integrity” and “national sovereignty” also lose importance over time in the corpus. The term “Semiconductor industry”, as observed above, can be seen relatively rising over time and terms like “blockade of Taiwan” and “ballistic missiles” rise in the middle and then lose importance in the discussions over the last few days. 

**D. General Corpus: Topic Modelling**

Different discussions, actions, and reactions surrounded the US house speaker’s trip to Taiwan that shaped the core discussions in the media. With the help of Topic Modelling, we aim to identify and briefly analyse how and to what degree these different themes were presented in the press, both western and Chinese and Taiwanese press. This is done by conducting two analyses – one for the general corpus and one for the Chinese and Taiwanese Corpus.

![Screenshot 2022-12-25 at 9 24 35 PM](https://user-images.githubusercontent.com/115983317/209481117-2042330e-6e12-42f5-a732-ddf147b4a6ce.png)

For both the corpuses, 10 key topics were identified using CorText that were presented as an intertopic distance map. Under each of these 10 topics, the frequency of the 30 most relevant words in relation to the overall term frequency in the corpus was presented in a bar chart. For ease of presentation, the different topics were given titles based on the main theme represented by the 30 most relevant terms under it. A brief comparison between the findings from the two analyses is presented at the end of this section.
 
Out of the 10 topics, most of the identified topics were meaningful in providing an insight into our research question. Ranked in order of their frequencies, a summary table of the topics in the general corpus and their frequencies are presented below.

![Screenshot 2022-12-25 at 9 25 43 PM](https://user-images.githubusercontent.com/115983317/209481135-4deaabd9-defd-45b0-88be-187fa13c5982.png)

Starting with the most frequently discussed topic in the corpus (17.60% of tokens), as expected, discussions around “Defence” took the centre stage as a reaction to Nancy Pelosi’s visit. Under topic 4, terms like “drill”, “exercise”, “force”, “launch”, “missile”, “plane”, etc. were discussed heavily. Sparked by the visit, China “conducted” military “drills” and “missile” strikes as a way to display its disapproval of Taiwan welcoming the US officials. In addition to missile strikes across Taiwan, Chinese navy “ships” and military “aircrafts” were also reported to have crossed the Taiwan “Strait”. Therefore, given the extreme escalation of tension in the region, discussions around defence as a retaliatory measure and message to Taiwan and the USA evidently dominated the media and press. Not only did these measures impact the regions and countries that were directly involved, but also other countries through changing trade routes and fears of further escalation of tensions into war.

![Screenshot 2022-12-25 at 9 26 49 PM](https://user-images.githubusercontent.com/115983317/209481154-ea1528fe-6f94-4ae6-b058-66d4a7807a4d.png)

The second most frequent topic (Topic 8 – Unrelated, 13.40% of tokens) does not provide us with information relevant to the analysis as it includes general verbs and other unrelated combinations of words. We therefore skip to the third most frequent topic (13.20% of tokens) that revolves around the theme of “US-China Relations”. Words like “government”, “Beijing”, “Washington”, “Taipei”, “president”, “delegation”, “policy”, “tension”, etc. point towards foreign “policy” and “political” discussions surrounding the “trip” that related to the existing US-China-Taiwan “tense” relations. Multiple statements were made citing the capitals of the three countries and including those by the respective country leaders. Several “warnings” were issued by China’s “foreign” ministry as it perceived the trip to be a threat to their “territory”.

![Screenshot 2022-12-25 at 9 27 19 PM](https://user-images.githubusercontent.com/115983317/209481159-9a365e4b-1422-405f-8297-4aa1a26408eb.png)

The fourth most frequent top can be titled as “Markets and Economy” (12.70% of tokens). This topic covers reactions of the market and the economy to rising US-China geopolitical “tensions”. “Investors” were said to have lost confidence in the Taiwan “markets” that depend heavily on peace and stability across the Taiwan Strait. The “Tuesday’s reports” on the possible visit were enough to affect investor “expectations” that led to the Taiwan “stock market” plunging. Both, the expectations of the visit and the actual visit affected investor confidence and trade. Words like “tension”, “investor”, “stock”, “market”, “price”, “trade”, etc. confirm the relationship between geopolitical peace and market stability in the region.

![Screenshot 2022-12-25 at 9 27 51 PM](https://user-images.githubusercontent.com/115983317/209481170-7309127b-bb3a-4ddb-952e-55aaeac234e1.png)

Fifth in line is the topic “China Principle” (11.90% of tokens) revolving around the “one-China principle”, described as “the political foundation of the diplomatic relations between China and the world”. China’s “foreign” ministry published multiple warnings against the US interfering in China’s “internal affairs” and inappropriately promoting Taiwan “independence” separatist forces. China saw the trip as a serious violation of the “one-China principle” that threatened to undermine “peace” and “stability” in the region, and cautioned against necessary measures to defend “national sovereignty” and “territorial” integrity. This topic provides a background to the US-China and China-Taiwan relations that formed the basis of tensions and criticism against Pelosi’s trip.

![Screenshot 2022-12-25 at 9 28 12 PM](https://user-images.githubusercontent.com/115983317/209481175-db4e7c5e-b9e7-4fa3-bdaf-42ff7249e7f2.png)

The sixth most discussed topic revolves around the general discussion around Pelosi’s Asia tour with a few specific indications towards the Taiwan trip. Words like “delegation”, “Asia”, “trip”, “meet”, “plan”, “official'', etc., point towards general mentions of the trip. While words like “tension”, “peace”, “affair”, “human”, etc., may be understood as pointing towards the Taiwan trip that was seen as a warning against China’s “human” rights violations and China invading Taiwan. During the trip, the US Speaker met with “human” rights and pro-democracy activists from China, Taiwan, and Hong Kong.

![Screenshot 2022-12-25 at 9 28 39 PM](https://user-images.githubusercontent.com/115983317/209481181-f45906ba-a132-4d86-b42a-61428e1181a6.png)

The next topic can be titled as “Manufacturing & Supply” (Topic 3, 9.60% of tokens). Taiwan has secured a significant position in the American and Chinese tech “supply” chains, pushing Taiwan in the middle of the US-China trade war and the rising tensions. This topic focuses on the dependence of the world on Taiwan-produced advanced chips with Taiwan being home to “TSMC”, the world’s largest contract chipmaker and supplier to major “tech” “companies”. This topic can also be associated with the US proposed Chip 4 alliance that aims to reduce reliance on China-made “chips”. Hence, this topic covers the discussions around the US-China trade war and the possibility of disruptions in global supply chains due to rising tensions.

![Screenshot 2022-12-25 at 9 29 03 PM](https://user-images.githubusercontent.com/115983317/209481193-be6244b6-6f66-45e4-87c1-898f721f2fd3.png)

Complementing this Topics 3 and 10 10 is Topic 5 (4.50% of tokens) that highlights the US diplomatic relations with “South Korea” and “Japan”. Topic 5 can be associated with not only South Korea and Japan being US allies but also with their close proximity to Taiwan and how tensions affected trade in the region. This topic points towards how the rising tensions between US and China opened discussions around other military (“nuclear”) issues surrounding China and US allies. It also touches over discussions around the Chip 4 alliance that aims to include the US, South Korea, Japan, and Taiwan.

![Screenshot 2022-12-25 at 9 29 30 PM](https://user-images.githubusercontent.com/115983317/209481206-9b8d3a60-72ac-4ab7-ad69-18989c28896d.png)

Coming to the last relevant topic (Topic 7, 3.80% of tokens), the themes revolve around terms related to economy and “Trade”. In response to Pelosi’s trip to Taiwan despite multiple warnings from China, China imposed blockades on the island and conducted military drills along the Taiwan Strait that had negative implications on trade. China is Taiwan’s biggest trading partner and therefore used trade sanctions as a way to exert pressure on the island. China “suspended imports” of citrus “fruits” and “fish products” from Taiwan and also “banned” the export of natural “sand” to Taiwan.

![Screenshot 2022-12-25 at 9 29 53 PM](https://user-images.githubusercontent.com/115983317/209481214-fee7d65c-4f25-464c-a175-b5ac15893e72.png)

The last topic, Topic 6 (2.80% of tokens) gives a wide range of terms that indicate “Media” references like “user”, “twitter”, “social”, “media”, “post”, “website”, “netizens”, etc., that points towards discussions around the trip on social media platforms and also statements made by country officials. While this may not directly relate to our research question, it does show that the event attracted both social media and press attention.

![Screenshot 2022-12-25 at 9 24 35 PM](https://user-images.githubusercontent.com/115983317/209481117-2042330e-6e12-42f5-a732-ddf147b4a6ce.png)

![Screenshot 2022-12-25 at 9 30 28 PM](https://user-images.githubusercontent.com/115983317/209481226-083328f8-9a90-4155-9373-695e12e9d76e.png) 

Overall, we can see that a few key topics surrounded the discussions around Nancy Pelosi’s trip. To further supplement the analysis, an intertopic distance map is provided for a better understanding of the “distance” between the 10 identified topics based on their positions on the map. The discussion was dominated by themes of diplomatic relations, trade, and defence; where the topic of US-China relations can be seen to be closely placed to that of defence and the general discussion around the Asia tour in the intertopic distance map.

**E. General Corpus: Network Mapping**

Using the CorText Network Mapping Script, we aim to identify the main topics of discussion in our media articles corpus, and to establish a network in their usage. This would help us understand the different themes of discussions around our topic, and how subtopics are clustered and related to each other. To further understand the origin of these themes, we add the third variable of publication source to the network map.

In the first section, we consider a homogeneous network map generated based on the whole media articles corpus and curated terms list. For this purpose, top 300 terms were extracted, cleaned and indexed back into the corpus using Terms Extraction and Corpus Terms Indexer scripts respectively. In the map, we present 150 nodes with edges proximity measure distribution set as distributional and an added third variable to tag clusters based on publication name (with tagging specificity measure set as chi-square).

![Picture1](https://user-images.githubusercontent.com/115983317/209481268-70325e46-ab7e-4a1c-bc8b-645a39d8c678.png)

At first glance, we can see that there are three large concentrated clusters and three relatively smaller ones. Since node sizes are scaled by their weight—or importance—we can see that some prominent terms are “Taiwan strait crisis”, “military drills”, “military exercises”, “territorial integrity”, “Taiwan independence”, etc.. Connected to these, we see several clustered nodes along similar topics. We now consider each cluster individually to understand their theme and if the publication sources justify and explain the contents.

![Screenshot 2022-12-25 at 9 33 04 PM](https://user-images.githubusercontent.com/115983317/209481278-460e030e-49ad-4d96-a3fb-9b69d48b749e.png)

![Screenshot 2022-12-25 at 9 33 59 PM](https://user-images.githubusercontent.com/115983317/209481294-8e8f09e6-0a7d-4b72-b9ea-3e12a7056255.png)

Based on the first cluster, we can infer that it relates to the theme of military activities surrounding the Pelosi visit. “Taiwan Strait crisis” is the most prominent node, along with others related to military drills and exercises, “ballistic missiles”,  “Liberation Army”, “South China Sea”, “Defense Ministry”  and “USS Ronald Reagan”. These findings are in line with the facts of the event itself. Prior to Pelosi’s visit, the Chinese government had issued several statements dissuading the same and warned of severe military action. As the visit went ahead as planned, the Chinese Liberation Army launched extensive military drills in the Taiwan Strait—essentially, creating a “blockade of Taiwan”—using their vast arsenal of ballistic missiles, aircrafts and fighter jets. The region became a hotbed of military activity as the United States also deployed its warship USS Ronald Reagen to monitor the situation. These events were followed and reported by state and non-state media outlets in all parts of the world. From the top publication sources listed for the cluster, we see a range of political stances represented. Taiwan News is an English language newspaper in Taiwan that is strongly associated with the Taiwanese identity and opposes Chinese unification. CNN is a western—USA—based multimedia corporation. Central News Agency, on the other hand, is a government-controlled agency that receives significant funding from the Republic of China. Since the detailed reporting of military activities had been done by media outlets across the board irrespective of their political inclination, these findings are justified.

![Screenshot 2022-12-25 at 9 34 37 PM](https://user-images.githubusercontent.com/115983317/209481301-4203c62e-6e2a-4237-a0f0-0a3cc19fccd7.png)

![Screenshot 2022-12-25 at 9 34 56 PM](https://user-images.githubusercontent.com/115983317/209481308-e0db8f33-4846-45fb-8f28-4cafd7410a06.png)

In the second cluster, we can see that some prominent terms are “Taiwan independence”, “territorial integrity” and “one-China principle”. These, along with terms such as “internal affairs”, “national sovereignty”, “peace and stability” and “serious violation”, indicates that this cluster can be interpreted to be on Chinese policy or stance with respect to the event of Pelosi’s visit. It is a well-known and now-accepted fact that the Chinese Communist Party has a “One China” policy and considers Taiwan to be an integral part of its territory. Therefore, any interference from foreign parties, especially the United States, is considered to be an infringement on its territorial integrity and national sovereignty. Inside Taiwan, however, there is a significant separatist movement that often receives support from the West. Therefore, we also see related terms in the cluster such as “United Nations”, “international community”, “separatist forces” and “Taiwan independence”. The publication outlets listed for the cluster are Xinhua News Agency and Global Times. The Xinhua News Agency is the official state news agency of People’s Republic of China and is thus owned by the Chinese Communist Party. Global Times is a daily newspaper also aligned with the Chinese Communist Party and known for its Chinese ultra-nationalist perspective. Given that this cluster primarily talks about China’s stance on the Pelosi visit and its implications, this result is justified.

![Screenshot 2022-12-25 at 9 35 32 PM](https://user-images.githubusercontent.com/115983317/209481322-d9a41cea-102a-4c43-b191-fbe51d747493.png)

![Screenshot 2022-12-25 at 9 35 58 PM](https://user-images.githubusercontent.com/115983317/209481335-ded91d88-0204-4640-b50e-b3309a0e261c.png)

In this cluster, the most prominent nodes are “House Speaker”, “visit Taiwan”, “White House” and “President Joe Biden”. Some other nodes related to these are “President Tsai Ing-wen”, “autocracy and democracy” , “support Taiwan”, “Tiananmen Square”, “Taiwan Relations Act” and “china threat”. Based on these, we can infer that this cluster relates to the narrative from primarily the United States. While many in the United States had been weary of Pelosi’s visit to Taiwan, the official stance of the United States on Taiwan historically has been in support of its democratic development—as opposed to China’s autocratic regime. This combined with the rising tensions between the United States and China, justifies the presence of terms such as “vibrant democracy” and “unwavering commitment” and “Asian giant”. The publication sources listed for the cluster are all typically western-origin—ABC News, Dow Jones and CNN. Therefore, the pro-west theme of the cluster is justified.

![Screenshot 2022-12-25 at 9 36 27 PM](https://user-images.githubusercontent.com/115983317/209481352-40e4cf17-8576-42e5-b095-8376dd7d88f7.png)

![Screenshot 2022-12-25 at 9 36 47 PM](https://user-images.githubusercontent.com/115983317/209481361-2bdc02f0-d909-4e5d-a416-8a32f7aba134.png)

This cluster could relate to the discussions on the possible impact of the visit on the world economy. The prominent nodes are “Hong Kong”, “Speaker of the House of Representatives”, “tensions with China”, “US-China tensions”, “Federal Reserve”, “oil prices”, “stock market”, etc. As the events around the visit unfolded and tensions mounted, there were discussions about the economic impact of the worsening relations between US-China and the blockade on Taiwan. Notably, China had imposed export bans on Taiwan and warned of possible sanctions on the West as well. The publication sources listed for the cluster are western outlets, possibly focused on financial reporting as well—Reuters News, Dow Jones and Investor’s Business Daily. 

![Screenshot 2022-12-25 at 9 37 12 PM](https://user-images.githubusercontent.com/115983317/209481371-a017daee-5f6a-4bf1-9e8c-c5b8be654000.png)

![Screenshot 2022-12-25 at 9 37 37 PM](https://user-images.githubusercontent.com/115983317/209481379-07f866f1-a6f1-4fc4-9b7d-1dd3cb00ae17.png)

There are two smaller clusters related to the larger themes explored above. The first, linked to the ‘China policy’ cluster, mentions “people of taiwan”—linked to the “Taiwan question”— “taiwan affairs office” and “export of natural sand”. Notably, with the escalation of tension, China had banned export of natural sand to Taiwan, an essential commodity for the latter country. Natural sand is required in the chip production process, of which Taiwan is a global exporter. The publication sources are regional—Taipei Times, which is a progressive paper in Taiwan, and People’s Daily, which is aligned with the Chinese Communist Party.

![Screenshot 2022-12-25 at 9 38 06 PM](https://user-images.githubusercontent.com/115983317/209481389-b64626ea-0748-4909-8bed-aa78c3f89d79.png)

![Screenshot 2022-12-25 at 9 38 22 PM](https://user-images.githubusercontent.com/115983317/209481395-b6f91e31-4156-4141-90c6-af32f831588b.png)

The second smaller cluster is linked to the previously explored ‘military activities’ cluster. It consists of nodes such as “foreign minister”, “south korea”, “north korea” and “regional security”. This could possibly stem from the impact of military activity on the southeast asian region in terms of security and trade. In line with the contents, the publication sources are primarily South Korean—Yonhap English News, Korea JoongAng Daily and KBS World News.

## Section I.II : Chinese and Taiwanese Corpus

Since our analysis uses only English language articles, there is an over-representation of Western-origin media articles in our corpus. However, given that this event happened in Asia and that the countries of the region—especially Taiwan and China—were also directly involved, it is important to better understand their reactions to the visit. To that end, we analyse a subset of the corpus that comprises English media articles by popular publishers in China and Taiwan—Taiwan News, China Daily, South China Morning Post and Xinhua, each of which have multiple media publications. This would allow us to delve deeper into the themes discussed at the other end of the spectrum by Chinese and Taiwanese media. This sub-section comprises Topic Modelling and Network Mapping of the Chinese and Taiwanese corpus.

**A. Chinese and Taiwanese Corpus: Topic Modelling**

![Screenshot 2022-12-25 at 9 39 49 PM](https://user-images.githubusercontent.com/115983317/209481419-33be3601-9918-4243-aa9e-defcc53733ec.png)

Since our general corpus is more representative of western media, we analysed a smaller corpus that consists of press articles specifically from China and Taiwan, with China dominating the same. Topics surrounding the discussion in the Chinese and Taiwanese media are found to be similar to those in the general corpus, however, the frequency of the topics differed between the two. The top 10 frequent topics along with their frequencies and illustrative terms is given below.

![Screenshot 2022-12-25 at 9 40 23 PM](https://user-images.githubusercontent.com/115983317/209481430-79608b73-d949-467f-a4e5-86e573694c86.png)

Briefly comparing topics across the two corpuses, we can see that unsurprisingly, the Chinese and Taiwanese media corpus (dominated by China) mentions the one-China principle more frequently than the general corpus and is the most frequent topic under this corpus (18.80% of tokens). Similar to the general corpus, terms surrounding the theme of defence were also found to be frequently discussed.
 
Another observation is that markets, manufacturing, and sanctions comprised three different topics under the general corpus. However, under the China and Taiwan corpus it is clubbed under Topic 3 titled “Trade & Manufacturing”, the fourth most frequent topic (10.80%). Overall, discussions under this corpus were found to be dominated by themes of diplomatic relations, international affairs, and retaliatory measures. This is possible due to China’s focus on presenting the trip as a violation of the one-China principle that threatened the global order and went against agreed upon terms. The relatively higher mention of such themes directs towards China’s attempt at making the US and the world aware of the consequences of such actions.


**B. Chinese and Taiwanese Corpus: Network Mapping**

In this section, we consider a homogeneous network map generated based on the corpus of select Chinese and Taiwanese media articles and a curated terms list. For this purpose, top 200 terms were extracted, cleaned and indexed back into the corpus using Terms Extraction and Corpus Terms Indexer scripts respectively. In the map, we present 120 nodes with edges proximity measure distribution set as distributional and an added third variable to tag clusters based on publication name (with tagging specificity measure set as raw).

![Picture2](https://user-images.githubusercontent.com/115983317/209481456-d60b209b-5487-41fe-8f13-c074d62715cb.png)

From the network map generated, we can see that there are two large clusters and four relatively smaller ones. The most prominent nodes across them are “one-China principle”, “territorial integrity”, “Taiwan question”, “median line”, “Liberation Army” and “Taiwan independence”. At first glance, the terms are quite similar to what have been explored previously. Now, we consider each cluster individually to identify the themes explored by different publications.

![Screenshot 2022-12-25 at 9 41 52 PM](https://user-images.githubusercontent.com/115983317/209481466-646b19f9-a1fe-4194-88b5-d680ccdc4cb8.png)

![Screenshot 2022-12-25 at 9 42 12 PM](https://user-images.githubusercontent.com/115983317/209481481-b1610441-6e4f-4252-8452-e1f6a5f5e18a.png)

The first cluster, again, seems to be on the theme of Chinese policy and stance on the issue. Other than “one-China policy” and “territorial integrity”, other important nodes are “Taiwan question”, “internal affairs”, “national sovereignty”,”peace and stability”, “international relations” and “disregard of China”. This can be interpreted as an extension of the Chinese policy cluster explored in the larger corpus. The narrative seems to be that “world peace” is contingent on Taiwan’s existence as an “inalienable part of China”, and the actions of Speaker Pelosi—and by extension, the United States—is considered to be a “major political provocation”. The publication sources of these terms are all known pro-Chinese government media outlets, Xinhua—the official state news agency of People’s Republic of China, and China Daily.

![Screenshot 2022-12-25 at 9 42 37 PM](https://user-images.githubusercontent.com/115983317/209481488-b360bf34-c5d6-46b5-a28d-4427d325d866.png)

![Screenshot 2022-12-25 at 9 42 57 PM](https://user-images.githubusercontent.com/115983317/209481495-74888f7f-20c4-482a-a8f3-e5b908cee4ef.png)

The second cluster can be inferred to be about military activities related to the event. We can see that the most prominent nodes are “median line”, “live-fire drills”, “Liberation Army”, related to others such as “Eastern Theater Command”—one of the command centres of the PLA, “war games”, “Taiwanese defence ministry” and “self-ruled island”. The publisher sources include both Taiwan News—that is pro-Taiwan independence, and South China Morning Post—which is owned by the Alibaba Group and considered to be a promoter of China’s soft power abroad. Therefore, the detailed coverage of China’s military activities around Taiwan is justified.

![Screenshot 2022-12-25 at 9 43 27 PM](https://user-images.githubusercontent.com/115983317/209481507-fd8f08dc-645b-4ea5-9b53-0d9e2ff75b6a.png)

![Screenshot 2022-12-25 at 9 44 00 PM](https://user-images.githubusercontent.com/115983317/209481519-30611983-6bdd-4c77-9ad6-3a9e78bc7465.png)

Interestingly, in the clusters presented above, we can see some more representation of Taiwanese media. Prominent nodes include “Taiwan independence”, “democratic progressive party”—which is the Taiwanese nationalist party, “mainland China”. Another important connection established here is between “semiconductor”, “mainland China” and “natural sand”. As explained previously, natural sand exported from China to Taiwan is essential for its semiconductor and thus chip manufacturing industry. Taiwanese chips are exported to all parts of the world, including South Korea, Japan and the United States.

## Section I.III : Observations and Inferences

From topic modelling, the following observations can be made about the themes discussed:
- Discussions within both the corpuses revolved around similar topics with only the differing frequencies of said topics providing us with insights into the different focal points (topics). 
- Defence and military action were widely discussed across the two corpusses followed by themes surrounding trade, manufacturing, and international relations. 
- In the China-Taiwan corpus, it is observed that diplomatic relations and international relations are widely discussed, potentially as a result of China highlighting that the trip was in violation of the one-China principle which would threaten peace and stability in the region. 
- The results were as expected – the general corpus focussed on defence, trade, and manufacturing while the China-Taiwan corpus focussed on China policies and diplomatic ties. 

From the network maps, the following observations can be made about narratives identified:
- ‘Military activities’ cluster that focuses on military exercises and manoeuvres carried out by the parties involved, especially China. The coverage of these events was provided by worldwide media.
- ‘Chinese policy’ cluster that expounds on the stance of the People’s Republic of China on the “Taiwan question”—its One China policy and disapproval of foreign interference in what it considers to be internal affairs. This narrative was primarily propagated by Chinese state-owned media outlets.
- ‘Western narrative’ cluster, mostly based in the United States, that talks about its support to Taiwan and democracy over the perils of authoritarianism. As expected, this is primarily published by popular western publishers.
- The corpus of Chinese and Taiwanese media articles shows a Taiwanese cluster of key political figures and institutions, and establishes a trade-related link between China-Taiwan and the rest of the world.


# Section II: Twitter Analysis 

**Data Collection**

Data for the corpus was extracted from Twitter using Google Collab. All English language Tweets with the search query “Pelosi OR Taiwan” between the dates July 30, 2022 and August 10, 2022 were collected using the mentioned software. The rationale behind these dates is that the former marks a couple of days before Nancy Pelosi visited Taiwan (August 2) and the latter marks about a week after the visit. It is during this period that social media discussed the issue most. Furthermore, we are aware that collecting only English language Tweets comes with its limitation of not covering important vernacular Tweets, especially from China. Given this, we also perform an analysis of Tweets that reflect the official Chinese opinion on the issue in the following section. The present section is limited to an analysis of a more general and global take on the visit. 

## Section II.I : General Twitter Corpus

**A. Top Locations**

![Screenshot 2022-12-25 at 9 47 30 PM](https://user-images.githubusercontent.com/115983317/209481580-144538a2-40ca-474f-9648-5d2178a1a5ec.png)

The table above shows which countries Tweeted most about Nancy Pelosi’s visit to Taiwan. Since several locations were in the form of cities, districts, or states, the data was cleaned to mention only countries. Certain redundant locations like “Earth”, “Worldwide”, and “Global”, however, still exist. This is a limitation of the corpus. We can see that the United States has talked most about it, more than thrice the second highest country - India. This is unsurprising given first that the visit directly concerns the country’s Speaker of the House of Representatives and second, that the United States has historically had highly strained relations with China. This visit thus sends a strong message to China regarding the United States’ unequivocal support for Taiwan against Chinese threats of integration with the mainland. It may appear strange that China and Taiwan are only the fifth and seventh highest countries to Tweet about Pelosi’s visit because it directly concerns them. However, as stated in the preceding paragraph, since these are English Tweets, they do not accurately reflect the importance of the issue in the aforementioned countries. Further, that Taiwan is a geographically small area with merely around 20 million inhabitants could also explain its relatively lower position in the table above. 

Another interesting fact to note is that India features rather high in the list despite the event not directly affecting its inhabitants. One explanation for this could be that India - much like the United States - has had strained diplomatic relations with China and is frequently talked about online by the Indian public and media alike. Another could be that India is among the most populous countries in the world; it is but natural that several Tweets are sent from there. The United Kingdom’s Twitter interest (third in the list of countries) in the event could be because of similar issues faced by Hong Kong, which is a former British colony. 

**B. Top Terms**

![Screenshot 2022-12-25 at 9 48 21 PM](https://user-images.githubusercontent.com/115983317/209481602-0a0c6149-8dc4-4ae0-8423-23b7a5f9477f.png)

The table above shows the 20 most frequently used terms in the Twitter corpus. The initial list of terms was cleaned before extracting this list so as to eliminate redundant and meaningless terms as well as club terms that mean the same thing (for example, “tensions with China” and “China tensions”. They can be categorised into certain groups:
a. Objective description of or details regarding the visit - this includes terms like “Asia tour” and “Pelosi visits Taiwan” which does not reveal much by way of how countries or individuals reacted to it 
b. Important stakeholders associated with the event - this includes terms such as “Xi Jinping”, “President Tsai Ing-win”, “People’s Liberation Army”, “Taiwan and China”, and “President Joe Biden” 
c. Discussion around the joint military exercises organised by Beijing around Taiwan as a response to the visit - terms like “fighter jets”, “military exercises”, “military drills” and “threats” are included in this category 
d. Description of the relations between China and Taiwan - “warnings from China”, “support Taiwan”, “one-China principle”, “China tensions”, “Taiwan and China”, and “threats”

Having said this, it must be conceded that the table above does not reveal a significant amount about the political leanings of users or about how exactly they perceive Pelosi’s visit barring words like “support Taiwan” which betrays a clear anti-China sentiment. A major chunk of terms are neutral in nature.

**C. Network Mapping**

**Hashtag-Hashtag Map**

![Picture3](https://user-images.githubusercontent.com/115983317/209481623-02683913-c6b4-4e10-bd69-2a3fb18be733.png)

The following homogeneous network map was made by extracting hashtags used from each Tweet using Cortext Manager tools and then entering them as the first and second variable for the map. 75 nodes were considered given that any more would lead to overcrowding and therefore incoherent data. 

At the outset, it is clear that the map has no central cluster around which other nodes revolve. It is a rather disparate map in that sense but has coherent clusters nevertheless. The two biggest clusters are light green one on the top left and blue one on the bottom right. The former concerns neutral hashtags that describe the Pelosi visit such as #PelosiVisitToTaiwan and #PelosiTaiwan. However, there are some hashtags that are politically charged and indicate some strong opinions such as #TaiwanIsNotChina.  Interestingly, one of the hashtags describes the visit itself as a “crisis”. The latter is concerned with the stakeholders, countries and other actors involved directly or indirectly with the visit like #PLA, #CCP, #Pelosi, and #Taiwanese. While the orange cluster concerns topics related to news, the yellow one can be ignored given that it comprises terms unrelated to the event. 


**Terms-Terms Map With Locations Superimposed**


![Picture4](https://user-images.githubusercontent.com/115983317/209481637-511f7b7e-e36e-4097-856d-50df757be1a2.png)


This map represents a homogeneous network of terms used in the Twitter corpus post cleaning them up to remove redundant terms and club terms with similar meanings. A third variable of the location of users was superimposed onto the map to get a sense of how different countries reacted to the visit. 

At first glance, it is evident that there are three connected networks while the other three are disparate. It is however difficult to tell which are the prominent clusters and which are the secondary ones. The dark green cluster comprises a mixture of terms associated with the visit like the stakeholders involved, its consequences, China-Taiwan relations and so on. The light green cluster on the right is about military concerns following Pelosi’s visit (terms like “aircraft carriers”, “navy deploys” and “military operations”. As already mentioned, China conducted military exercises as an expression of its disagreement with the visit. The red cluster on the top covers issues pertaining to relations between China and Taiwan such as “one-China principle”, “Taiwan independence” and “territorial integrity”. The orange cluster at the bottom also talks about the consequences of the visit evidenced by terms like “Chines fires missiles”, “military drills” and so on. The blue cluster on the left covers the American perspective. Terms like “war with China”, “Biden admin”, and “White House” indicate this. The top left-most cluster covers Taiwan’s perspective and expresses support for its cause. 

As for the locations of users Tweeting about the visit, we can see that besides Taiwan and China, it is primarily users from the United States, India, and other Asian countries like Japan, Malaysia, the Philippines, Hong Kong, Pakistan and so on. 


## Section II.II : China Corpus for Twitter

**Data Collection**

The data of China twitter corpus were collected through Google Colab. In 2009, Twitter was blocked from being used in mainland China due to the Chinese government’s suspicions that rioters used this platform to organise chaos. China also considers that since there are many western platforms that collect and have access to its users’ media account, blocking access to Twitter, Facebook, and other social media apps is a matter of national security. In light of these events, the already ongoing internet censorship also known as The Great Firewall of China strengthened its chains around the western internet. Despite restricting access to most of the popular western platforms, China has created its own social media ecosystem, therefore few chinese netizens access western social platforms because of the troublesome nature, even though the feasibility is guaranteed with VPN. The existing Chinese accounts on Twitter, apart from scattered regular Chinese netizens, are mainly official English accounts of institutions as well as representative personnel, such as national and provincial governments, academic and intellectual institutions, and media civil societies who engage in international affairs. Therefore, this corpus mainly reflects an official opinion of China, because the collection of data is mainly based on accounts of authoritative figures. 

The corpus is made up of 36 accounts, which can be categorised into the following three types: 1) Chinese government (e.g. @MFA_China, the official account of the MFA office of spokesperson) and government officials (e.g. @ SpokespersonCHN, Assistant Minister of Foreign Affairs, Foreign Ministry Spokesperson, Director General of MFA PRC); 2) media (e.g. @XHNews, China state-affiliated public media) and journalist (e.g. @HuXijin_GT, Global Times commentator); 3) civil society (e.g. @ChinaUSFocus, A China-US Exchange Foundation initiative to promote exclusive dialogue). Because of the limited sources of account and for more comprehensive data, the search query is altered into “Pelosi OR Taiwan”, as any account mentioned above with a tweet mentioning either one of the terms from July 30th to august 10th 2022 expressed opinions concerning this political event. 
 
**A. Top Terms**

![Screenshot 2022-12-25 at 9 54 01 PM](https://user-images.githubusercontent.com/115983317/209481703-ceed7d49-7022-4094-9f10-6f6751f0400c.png)

Top 20 terms generated from China corpus and general corpus shared striking differences despite some similarities. An overlap is seen in the following terms, which signify a heated concern from both China and the world. A first overlap is the term “Taiwan visit” and its various forms, which describe this political event. A second overlap is seen among military terms such as “military exercises'', “military drills”, “PLA” (People's Liberation Army). The 2022 Chinese military exercises around Taiwan were a series of military exercises encircling Taiwan. They initially began on 4 August, after Pelosi’s departure, involved live-fire drills, air sorties, naval deployments, and ballistic missile launches by the PLA. China announced an end to the exercises on 10 August, but reserved regular patrols in the Taiwan Strait. 

A third overlap concerns the political ideology, including terms of “Taiwan strait” and “one-China principle”. The meaning of Taiwan strait extends beyond geography, because the perception towards the strait is one of the fundamental elements defining whether Taiwan is a part of China.  The Taiwan Strait ranges in width from about 70 nautical miles at its narrowest and 220 nautical miles at its widest. According to UNCLOS and Chinese laws, the waters of the Taiwan Strait, extending from both shores toward the middle of the Strait, are divided into several zones including internal waters, territorial sea, contiguous zone, and the Exclusive Economic Zone. China MFA constantly repeats in domestic and international conferences that Taiwan is an inalienable part of China’s territory and China has sovereignty, sovereign rights and jurisdiction over the Taiwan Strait. The One China principle or One China policy is opposed to the idea that there are two states holding the name "China", as well as the idea that China and Taiwan form two separate countries. The refers to a United States policy of strategic ambiguity regarding Taiwan.In a 1972 joint communiqué with the PRC, the United States "acknowledges that all Chinese on either side of the Taiwan Strait maintain there is but one China and that Taiwan is a part of China" and "does not challenge that position." It reaffirms the U.S. interest in a peaceful settlement of the Taiwan question. One China principle between mainland and Taiwan dates back to the “1992 Consensus”: both the People's Republic of China (PRC) and the Republic of China (ROC) had agreed that there is one "China", but disagreed on whether "China" is represented by the PRC or ROC, with each rooting for their own party. From the PRC perspective, Taiwan is an inalienable part of China’s territory, and the Government of the PRC is the sole legal government representing the whole of China. This is at the heart of the one-China principle and also a universal consensus of the international community and a basic norm in international relations, which has been clearly recognized by United Nations General Assembly Resolution 2758 of 1971.

However, the top terms in China corpus also display huge differences from the general ones. Two more military terms appear, which are the “Eastern Theater Command '' and “joint combat exercises”. Eastern Theater Command is one of the five theatre commands of the PLA, whose jurisdiction includes Fujian province (which faces Taiwan across the strait) and the Strait of Taiwan. In response to the visit, the Eastern Theater Command conducted joint ground, air, and naval exercises, which are perceived as the next military term, joint combat exercises. The Chinese perceive the drills as a combat, because to the there is only one sovereign state under the name China, with the PRC serving as the sole legitimate government of that China, and Taiwan is a part of China, and China retaliate because the provocative visit of Pelosi is a serious violation of the provisions of the three China-U.S. joint communiqués. This sentiment can also be seen in sentimental terms like “provocation”, “strong opposition”, and “strong protest”. 

Another set of terms include political ideologies, like “Taiwan question”, “territorial integrity”, and “Taiwan independence”. China has precise diction on all Taiwan-related topics. They are worded as “Taiwan question” not “Taiwan issue”. According to Cambridge Dictionary, issue means “a subject or problem that people are thinking and talking about”, which does not yield consensus yet. China insisted that Taiwan is not a controversy, not an “issue”, but already had reached agreement in the international community. The earliest references to this effect are to be found, among others, in Seaboard Geographic Gazetteer compiled in the year 230 by Shen Ying of the State of Wu during the Three Kingdoms Period. The royal court of the Sui Dynasty had on three occasions sent troops to Taiwan, called Liuqiu at that time. Starting from the Song and Yuan dynasties, the imperial central governments of China all set up administrative bodies to exercise jurisdiction over Penghu and Taiwan. In 1662, General Zheng Chenggong led an expedition and expelled Dutch colonialism from the island for around 40 years. Subsequently, the Qing court gradually set up more administrative bodies in Taiwan. In 1684, a Taiwan prefecture administration was set up under the jurisdiction of Fujian Province. In 1885, Taiwan's status was upgraded and it became the 20th province of China. At its 26th session in October 1971, the United Nations General Assembly adopted Resolution 2758, which undertook "to restore all its rights to the People's Republic of China and to recognize the representatives of its Government as the only legitimate representatives of China to the United Nations, and to expel forthwith the representatives of Chiang Kai-shek from the place which they unlawfully occupy at the United Nations and in all the organisations related to it". This resolution settled once and for all the political, legal and procedural issues of China's representation in the UN, and it covered the whole country, including Taiwan. Therefore, for the PRC, Taiwan is not an “issue” but only a “question” raised by certain foreign countries for various intentions. 

Apart from the terms “Chinese mainland” and “Chinese people”, another set of terms include governmental agencies like “Taiwan Affairs Office” and “Chinese Foreign Ministry”, as well as authoritative figures like “Minister Wang Yi” and “Spokesperson Hua Chunying”. The Taiwan Affairs Office of the State Council is an administrative agency under the State Council of Mainland China. It is responsible for setting and implementing guidelines and policies related to Taiwan, as stipulated by the Central Committee of the Chinese Communist Party and the State Council itself. Its work also includes preparations for negotiations and agreements with Taiwan authorities and coordination in mail, transport and trade across the Taiwan Strait and so on. Hua Chunying is a Chinese official and former diplomat serving as spokesperson for the MFA since 2012 and as the Assistant Minister of Foreign Affairs since 2021. Hua was the fifth spokeswoman and 27th spokesperson since the position was established in the ministry in 1983. She constantly uses social media like Twitter for comments.

**B. Evolution of Terms: Demography and Epic Epoch**

![Screenshot 2022-12-25 at 9 58 06 PM](https://user-images.githubusercontent.com/115983317/209481790-b4607e6a-7c5f-46d7-a3cf-0fe60d6c55f5.png)

![Screenshot 2022-12-25 at 9 58 22 PM](https://user-images.githubusercontent.com/115983317/209481798-5cdbb3c9-1391-4d58-811c-4cf51030af93.png)

The two graphs well illustrate how terms evolve during the ten days. The first day of the visit, China’s first response was deterrence with the mentioning of PLA. The second day is a major discussion on the possibility and feasibility of the visit. The third day, the discussion becomes more ideological, by mentioning the Taiwan strait for proof of One China, Chinese people for sentimental attachment, and provocation for being the just side of this political farce. The day of the visit, the Chinese minister of MFA marked the top term by strongly condemning the doings of Pelosi. The following two days after the visit, “Eastern Theater Command” is the top term because of the retaliatory drills initiated by China. 

**C. Network Mapping**

![Picture5](https://user-images.githubusercontent.com/115983317/209482097-217b6534-46d4-4cb4-81f4-881fe0c04d42.jpg)

![Picture6](https://user-images.githubusercontent.com/115983317/209482113-bd795de7-4143-453b-a760-3937f7967bb3.jpg)

![Picture7](https://user-images.githubusercontent.com/115983317/209482115-189f6d24-4eed-4304-a3fe-1f16cdc8a6fd.jpg)


The map presents a homogeneous network mapping of 100 terms of the China corpus, with user name as the third variable. The biggest and most central cluster in green is termed “provocation & Taiwan question”, and all other clusters revolve around this one. This cluster involves mainly terms that are political, diplomatic, and ideological. Provocation implies that this visit is highly provocative to the Chinese people, with America’s intent ignorance on the 1972 joint communiqué. This cluster is highly political with the presence of multiple foreign affairs entities and diplomats (e.g., Chinese MFA, Minister Ma Zhaoxu), who are responsible to make an official statement on the visit. The topic they centre on is the Taiwan question and One-China principle, that the USA is playing the “Taiwan Card” to manoeuvre Chinese politics and its power in the Asia-Pacific. These terms are mainly utilised by diplomatic personnel like Zhang Heqing. This cluster is also the most long-lasting one, which has gone through the whole period.  

To the right of the cluster of diplomacy and politics is the yellow cluster in the military. The two clusters are associated with the term “Taiwan strait”, which has both geographical and political implications. Major nodes in this cluster involve “Eastern Theater Command” and PLA, the directing entity and the agents of all the military terms around them, including “joint military operations” and “waters and airspace”. Compared to the former one in green, this cluster of terms were mainly published by state-affiliated media, including CNN international. This reveals a tendency that China prefers to declare military drills by entities rather than by diplomats. This can establish a more severe and solemn atmosphere, and also avoid personal troubles towards diplomats. This cluster is also a long lasting cluster until the penultimate day.

The blue cluster at the bottom of the green cluster are the clusters that focus on Taiwan authorities, Taiwan independence, dialogue between mainland China and Taiwan, and possible punishment. Because the PRC refuses to recognize Taiwan as a country, the diction of terms can differ from the general corpus (e.g. Taiwan authorities vs. Taiwan government, Leader Tsai Ing-wen vs. President Tsai Ing-wen). Some “external forces” and “separatists” are major reasons for “Taiwan independence”. The dialogue between mainland and China is conducted mainly by the Taiwan Affairs Office, and this entity is also relevant to retaliatory interventions like “punishment on organisations” and on the “export of natural sand”. However, this cluster only lasted for the beginning days. After Pelosi’s visit, this political difficulty has gone beyond Mainland-Taiwan relations but rather China-US relations. The governing entities are therefore upgraded to the MFA or State Council, therefore the discussion on the dialogue with Taiwan has stopped and changed into reactions to the USA.

**D.	Topic Modelling**
 
In order to understand the topics emerging in the china corpus, a topic modelling was done. The results of the analysis are visualised in an intertopic distance map where the position of each topic reflects its distances to other topics, while the individual topic’s size is determined by its marginal topic distribution. Moreover, a bar chart shows the top-30 most relevant terms for each single topic, setting the estimated term frequency within the selected topic into relation with the overall term frequency in the corpus.

![Picture8](https://user-images.githubusercontent.com/115983317/209481934-eb5c836e-6584-49bc-be66-059017c82f72.png)

The most frequent Topic 1 (29.7% of tokens) can be titled “China’s reactions to Pelosi visit”. This topic directly discusses her presence in Taiwan and her identity as house speaker. China’s reactions involved entities like MFA and personnel like Minister Wang and Spokesperson Hua. This topic mainly addresses how China reacted to the sudden visit. An example of this would be a tweet by Hua Chunying (@SpokespersonCHN), who commented that “When the House Speaker, being the third-highest ranking figure in the US government, flies on US military aircraft and makes a provocative visit to the Taiwan region, it is by no means an unofficial action” (like count: 11332). This is the Chinese government trying to decipher the purpose of the visit by the house speaker, in order to make future actions.

![9](https://user-images.githubusercontent.com/115983317/209481967-560c058e-7a63-4929-a52c-b3d2370168d7.png)

The second most frequent, Topic 4 (24.5% of tokens), can be titled “Taiwan question”. As addressed earlier, China does not perceive Taiwan as an issue with controversies. The one-China policy is one of the fundamental policies in China, and this topic addresses this from political and historical perspectives. The Taiwan question and the pressure on “Taiwan independence” are from both external forces and internal separatists. Another example from spokesperson Hua would be “History and reality have proved time and again that the one-China principle is what underpins stability across the Taiwan Strait (like count:3333). Chinese on both sides of the Taiwan Straits carried out a prolonged, unremitting struggle against foreign invasion and occupation of Taiwan. In the late 15th century Western colonialists started to grab and conquer colonies in a big way. Japan launched a war of aggression against China in l894. In the ensuing year, as a result of defeat the Qing government was forced to sign the Treaty of Shimonoseki, ceding Taiwan to Japan. In 1937 the Chinese people threw themselves into an all-out war of resistance against Japanese aggression. After eight years of gruelling war against Japanese aggression the Chinese people won final victory and recovered the lost territory of Taiwan in 1945. 

![10](https://user-images.githubusercontent.com/115983317/209481978-6b56316e-f668-4b3c-8c65-4d0161837567.png)

The third most frequent topic, Topic 2 (18.9% of tokens), concerns the military drills. Terms like drill, Eastern Command Theater, army, water, combat appear in this topic. An example would be “PLA will conduct important military exercises and training activities including live-fire drills in six regions surrounding the Taiwan island from Thursday to Sunday” (like count:3966) released by Global Times.

### CONCLUSION

The media corpus, as expected, provides a balanced and holistic view of the topic at hand. Our analysis revealed nearly all the topics and themes one would expect to find when analysing the reactions to the Pelosi visit. The general corpus showed a wide range of narratives—from military activity discussions to the narratives propagated by China and the United States respectively. Since the source of media publications is vast, the topics covered also discussed trade relations, industries and impact on supply chains,  geopolitical impact on other countries, etc.. However, on analysing the subset of Chinese and Taiwanese media publications, we see that the topics discussed primarily revolve around China’s One China policy, the apparent infringement on its national sovereignty and the military actions it carried out in response. This too was expected as the corpus primarily comprised Chinese government-aligned publications. Thus, our analysis proves how important a role media outlets have in shaping news. The publication sources covered in our analysis have varying origins, political alignments and sources of funding, all of which play an essential part in the kind of news they promote. As expected, news and narratives found in Chinese media publications is quite different from that of media publications in the Western world. 

The result from our Twitter analysis, however, has been different. Contrary to what one would expect, the general Twitter corpus presented mostly neutral views on the topic with a few exceptions in support of Taiwan. The discussions primarily focused on the military activities being carried out, which has also been an important theme in our media corpus analysis. Analysis of the Chinese Twitter corpus, on the other hand, revealed much more polarised views. The narrative was almost solely in support of the One China policy with the added angle of military activities. Given that this corpus comprised official Chinese government actors and state-sponsored news agencies, the findings are justified. Thus, the Twitter analysis also shows how the source of information can polarise news and impact its dissemination.

Across the two corpuses, we see that the reporting of military activities has been a constant theme. Since the events unfolding between the two most influential nations of the world had the potential to impact the global order, peace and stability, its coverage by different media outlets and individuals on Twitter is understandable. The differences in the results of the two corpuses arise in other areas, such as in the range of themes discovered and polarity of contents. Media publications being a formal mode of communication, covers more themes than general Twitter data. Another factor to account for is the dearth of Twitter data from China and Taiwan. Since Twitter is not accessible and/or not preferred in those regions, general tweets on the topic are not as well-represented.

Overall, our analysis has produced coherent and holistic results and successfully presented the different reactions to Speaker Pelosi’s visit to Taiwan.
