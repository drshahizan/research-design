# Data Science Project Proposal

## Front Page Cover
<h4 align="center"> TEMPORAL ANALYSIS OF CLIMATIC INFLUENCES ON FOREST FIRE PATTERNS IN PENINSULAR MALAYSIA </h4>

<h4 align="center"> GRACE LING KIAN HWAI </h4>

<h4 align="center"> 2024 </h4>

## Abstract
Major forest fires have a severe environmental impact in Peninsular Malaysia, placing biodiversity, human health, and economic stability at risk. Even though warm weather, relative humidity, wind speed, and precipitation have been previously correlated with fire seasons, very limited research has focused on temporal relationships among these factors and no studies have identified which specific variables drive fire season length in this region. This study aims to characterize the temporal patterns of forest fires in Peninsular Malaysia and determine the climatic variables that govern these patterns. In this study, at least 3 years of historical data on forest fire incidents in combination with climatic variables relevant to forest fires are used. Through the use of statistical analysis and mathematical (and machine learning) models like time series analysis, regression models, the study summaries the climatic drivers of Forest fire (eg. temperature, rainfall, humidity, and etc.). Preliminary results suggest a high correlation of rising temperatures and lower rainfall with an increase in forest fires. This study provides a predictive context specific model to predict the fire risks and how it is changing with the climatic context, which can be helpful for incorporate the same in the forest management or policy making. The next steps of the study will be aimed at the development of these predictive models and at the inclusion of the factors like land use changes and human activities in the study, and at the study of the effects of climate change on forest fires and their dynamics in future. The findings should apply to refining tactics in the fire management realm, refining the possibilities for risk assessment, and a provision of policy recommendations to minimize the negative consequences of forest fires in Peninsular Malaysia.

## Table of Contents
- Abstract
- List of Figures
- List of Tables
- List of Abbreviations
- Appendices
- Chapter 1: Introduction
- Chapter 2: Literature Review/Problem Background
- Chapter 3: Methodology
- Chapter 4: EDA/Initial Results
- Chapter 5: Discussion and Future Work

## List of Figures
(If necessary)

## List of Tables
(If necessary)

## List of Abbreviations
(If necessary)

## Appendices
(Include Gantt Chart here)

## Chapter 1: Introduction
### 1.1 Introduction
Climate change is defined as any long-standing shifts in temperature, both hot and cold, as well as weather patterns in the earth it is common nowadays to refer to it as one of the most emerging phenomena in the natural environment. Starting from the preceding decades, the climate changes occur due to climate events such as volcanic eruptions, fluctuations in the intensity and distribution of solar energy, and changes in the tilt of the earth. However, since the Industrial Revolution era, which has taken several centuries, most activities, particularly the combustion of fuels and negative impacts such as deforestation have greatly Enhanced activities that have promoted the concentration of GHG’s have prompted high rates of climate change. All these anthropogenic activities over the same have led to an improvement in global temperatures, changes in precipitation, as well as the magnitude and frequency of occurrence of extreme weather conditions.

Another aspect of climate change has to do with this article since the occurrence of forest fires is said to become more frequent and intense. Wildfires or more commonly, forest fires refer to those outdoor ignition of vegetation and they are defined as blazing, intensely hot, and have a high rate of spread fires that occur in a vegetative cover such as forests. These fires can be due to natural occurrences for example as can be observed in dry seasons, while others are owned to human uses such as fire clearing and accidental cause of fires. Climate change works hand in hand with forest fires through factors such as high temperatures, low humidity, shorter times between occurrences of rain and longer durations of drought, and changes in winds that enhance the fire-making environment.

Wildfires have been part of the Earth’s history for a long time now and although they are destructive to wildlife and human property, they are vital in several ways to the ecosystem. Many of the fires kindled by the native Americans hundreds of years back cannot be ‘today’s forest fires in terms of their intensity and impacts, which are caused by humans and changes in climate. Turning to historical events, the Great Fire in 1910 took place in the USA, and the Ash Wednesday Bushfires in 1983 – in Australia; all these facts, along with the recent 2019-2020 Australian Bushfire Season testify to the increase in the frequency of fires and consequently, to the need to develop and improve the methods of fire management.

Due to its tropical weather which is known for high humidity and temperature, Peninsular Malaysia experiences a heightened risk of forest fires during dry spells. Forest fires have been an issue in the region for decades with early incidents related to slash-and-burn farming practices, which were initially minor and localized but became more frequent and intense due to urbanization increased along with deforestation and climatic changes. Severe droughts in 1983-1984, El Niño event of 1997-1998 fire season of 2005, plus peatland blazes in Johor & Selangor backdropped concerns about managing such environmental hazards by highlighting the forests' vulnerability when faced with varying climates throughout history.

In the past, forest fires were thought of as entirely natural events and efforts to combat them focused mainly on suppression rather than prevention. As time went on, attitudes shifted toward acknowledging the ecological significance of fire in forest management. Consequently, prescribed burns became a popular tool for maintaining healthy forests during the mid-20th century. Recent developments in data collection and analytical techniques have allowed us to gain a deeper understanding of how climate variables interact with wildfires. This improved knowledge has spurred more proactive strategies for managing these hazards effectively. Modern technologies such as remote sensing, GIS systems, and machine learning technology are now essential components that play an active role in predicting  and addressing wildfire outbreaks within our precious national landscapes today.’

Forest fires in Peninsular Malaysia pose a significant threat to biodiversity, human health, and the economy. However, despite being aware of climatic factors' influence on forest fire occurrences in this region, research focusing specifically on temporal patterns and climate influences has been limited. Addressing this problem is crucial due to various reasons. Environmentally speaking, habitat destruction caused by fires leads to loss of biodiversity as well as degradation of soil quality. Public health also faces severe risks with smoke inhalation from burning pollutants causing respiratory issues while economically; the tourism sector gets negatively affected along with considerable timber resource damage. Mitigating these impacts through effective fire management strategies promotes sustainable development but there's still much work needed considering how dangerous uncontrolled forest burns can be (as evidenced by recent events like those seen in Australia or Amazon). Therefore predictive models are necessary for dealing proactively against such incidents rather than reacting late afterward!

This project aims to explore the impact of climate on forest fires in Peninsular Malaysia. The central research question that will be pursued is how climatic variables affect temporal patterns regarding these incidents. To address this inquiry, we intend to achieve several objectives such as collecting a comprehensive dataset relating to historical forest fire occurrences and relevant climatic data spanning over recent decades while analyzing any apparent trends or distinctive temporal characteristics observed. Furthermore, our goals include quantifying the relationship between these phenomena more accurately and developing predictive models for identifying possible risk factors based on prevailing weather conditions leading up to such scenarios' emergence; ultimately aiding us with appropriate recommendations towards achieving better management strategies as preventive measures against future calamities effectively.

This study concentrates on Peninsular Malaysia and spans at least 5 years to analyze various climatic factors, including temperature, rainfall, humidity, and wind speed. However, historical data may contain inaccuracies or gaps in information while the exclusion of East Malaysia is due to varying ecological conditions. The anticipated results are predictive models aimed at evaluating forest fire hazards within this region.

Studies conducted in multiple regions have investigated the correlation between forest fires and climatic factors; however, research specific to Peninsular Malaysia is scarce. Past investigations commonly suffered from incomplete data sets and lacked advanced analytical techniques. This study intends to close these gaps by employing machine learning along with time series analysis for forecasting fire hazards, and ascertaining instances of wildfires and climatic indicators within Peninsular Malaysia. The aim is not just to bridge those gaps but also to produce an informative contribution towards environmental management while improving our understanding regarding alterations observed in fruitfulness combustion incidents against changes in climate conditions.

### 1.2 Problem Background
With climate change exacerbating the situation, forest fires have become a significant environmental and socio-economic concern in various regions such as Peninsular Malaysia. These wildfires pose severe threats to both biodiversity and human well-being while also affecting economic stability. Given the frequent occurrence of intense bushfires linked to global warming, prolonged droughts along with other climatic factors necessitate further research into their root causes and trends for more effective fire management strategies aimed at mitigating ecological damage besides safeguarding public health and financial assets.

Numerous studies have investigated the correlation between forest fires and climatic variables in various regions. For example, the study by Turco et al.'s in 2012 on the title "Climate Change and Forest Fires in the Mediterranean Basin: How Will Fire Weather Change?" examined how climate change affects fire weather patterns in that region. The researchers found statistical evidence suggesting that increased temperatures combined with reduced precipitation significantly heightens fire risk. Refer to Flannigan et al.'s in 2005, report titled "Impact of Climate Change on Forest Fire Regimes in Canada," which focused specifically on Canadian forests' changing frequency or severity due to altered temperature levels as well as precipitation characteristics by reviewing historical data alongside using modern-day models. Likewise, Balshi et al's study from 2009 about Modeling impacts of Climate Variability vary for wildfire activity within Alaska’s boreal habitat employed dynamic vegetation modeling techniques aimed at predicting future scenarios dependent upon climate variations over periods allowed them to draw concluding remarks indicating an anticipated increase regarding both burning area size along with frequency becoming more common throughout these environments impacted under such conditions subjected themselves too long periods exposed directly towards continually shifting climates regularly redefining functioning biome therein rest. Therefore, research into regional-specific management plans is necessary to curb this trend effectively while considering critical climatic factors during operational strategies concerning active natural resources usage across all areas eventually affected despite differing special nuances tied uniquely together making each place variably distinct depending solely depended wholly apartence varying aspects inherent therewithin innate controls overriding current paradigms based around assumptions existing previously without further analysis ever involved itself before acceptance occurred unquestioningly adopted standard methods applied uniformly everywhere regardless individual needs adapting contextual style accordingly required duly noting environmental changes detected forthwith absolute care knowledge remain paramount importance always forefront mind guarantee safe use forevermore available societal demands authority directives codification implemented universally otherwise highly negative outcomes logical consequence faced immediately after instituting practices override emotional concerns policymakers continue deferring until unavoidable disaster strikes governments act expeditiously protect citizens' welfare.

### 1.3 Problem Statement
While climatic factors are widely recognized as crucial in determining forest fire occurrences worldwide, there is a dearth of research specifically examining the temporal patterns and influences of climate on forest fires in Peninsular Malaysia. Prior studies have been hampered by incomplete data sets and inadequate analytical methods tailored to this region's distinct ecological and meteorological conditions. This gap presents significant challenges for formulating effective strategies to manage forest fires within the country, posing risks to biodiversity, human health, economy while presenting obstacles towards policy-making decisions regarding management practices that can provide resiliency against future wildfires. As such it becomes imperative that this void be filled with increased research efforts aimed at developing better knowledge upon which policies may rest when making choices about managing these events before they occur.

### 1.4 Research Questions
1.	How have forest fire occurrences in Peninsular Malaysia varied over the past two decades?
2.	Are there specific months or seasons with higher incidences of forest fires?
3.	Are there specific regions within Peninsular Malaysia that are more prone to forest fires?
4.	How do geographical features (e.g., elevation, land cover) interact with climatic variables to influence forest fire patterns?

### 1.5 Objectives of the Research
To answer this research question, the following specific objectives are set:
1.	To compile a comprehensive dataset of forest fire occurrences and relevant climatic variables in Peninsular Malaysia over the past few decades.
2.	To analyze the temporal trends and patterns of forest fire occurrences and identify the relationship between climatic variables and forest fire occurrences.
3.	To develop predictive models for forest fire risk based on climatic conditions.

### 1.6 Scope of the Study
The scope of this project includes:
1.	The study will utilize the dataset provided by the collaborator where the dataset is obtained from Global Remote Sensing Data from Google Earth Engine (GEE).
2.	The analysis will cover at least 5 years to capture long-term trends and patterns.
3.	Key climatic variables such as temperature, rainfall, and humidity will be examined for their influence on forest fire patterns. 
4.	The study will focus exclusively on Peninsular Malaysia, excluding East Malaysia due to different climatic and ecological conditions.
5.	The research will use historical data that is currently obtainable, although it may have some constraints regarding precision and comprehensiveness. 
6.	Statistical and machine learning tools will be used for data analysis and model development.

### 1.7 Assumptions
The following assumptions are made for this research:
1.	Historical data on forest fire occurrences and climatic variables are sufficiently accurate and complete for analysis.
2.	Climatic variables are the primary drivers of forest fire patterns, with other factors (e.g., human activities) considered as secondary influences.
3.	The relationships identified between climatic variables and forest fire patterns are consistent over the study period.

### 1.8 Significance of the Research
The significance of this study lies in its ability to shed light on the impact of climate on forest fire occurrences in Peninsular Malaysia. The results could potentially enhance fire risk forecasting, leading to improved firefighting strategies. Ultimately, the project aims to contribute towards sustainable management practices for forests and safeguard both natural habitats and human settlements within Peninsular Malaysia. 

### 1.9 Structure of the Thesis
The present thesis consists of seven distinct chapters, with each chapter adopting a comprehensive and systematic approach towards answering the research question at hand - namely, how do climatic variables impact the temporal patterns observed in forest fires within Peninsular Malaysia? Below is an overview of how these different chapters are structured.

### Chapter 1: Introduction

The opening of the article commences with introducing the focal research inquiry and elucidating its importance in comprehending how climatic factors affect forest fires. It imparts imperative contextual details on climate change and forest fires, underscoring their worldwide and local repercussions, especially within Peninsular Malaysia. The section delineates the study's intentions, extent, presumptions, and significance to lay down a foundation for further exploration. Additionally, it provides a concise summary of methodologies utilized such as data acquisition procedures alongside analytical tools employed during modeling techniques at length before concluding this segment.

### Chapter 2: Literature Review/Problem Background

In this chapter, the literature and research pertinent to the field are reviewed. The aim is to create a framework for the current project by discussing the historical context as well as how understanding climate change and forest fires have evolved both globally and specifically in Peninsular Malaysia. Various key studies are analyzed with emphasis on their methodologies, findings, and limitations. Additionally, gaps in existing research are identified which emphasizes that there exists an urgent need for in-depth study focused solely on investigating region-specific ecological conditions given its unique climatic characteristics within that area.

### Chapter 3: Research Methodology

In the study, the methodology chapter delineates a framework for the data science project life cycle and how it was employed. It expounds on where climatic and forest fire data were sourced from, as well as illustrates the approaches used to collect such information. Also explored are measures taken in the pre-processing of collected data - cleaning up errors; and conducting transformations - so that they can be analyzed efficiently through feature engineering methods. Aiming at maintaining accountability, this all-encompassing account securities replicability of research procedures utilized herein.

### Chapter 4: Exploratory Data Analysis (EDA)

In this chapter, the primary emphasis is on Exploratory Data Analysis (EDA), which commences with visualizations and descriptive statistics to comprehend and investigate data. Diagnostic analytics also known as initial observations from EDA are addressed along with executing feature engineering for building influential features meant for modeling purposes. Additionally, various predictive modeling methodologies utilized in assessing forest fire jeopardy grounded upon weather-related factors are explained while further examining probable prescriptive analytic alternatives tailored towards recommending effective management tactics against fires.

### Chapter 5: Model Development

In the chapter on model development, readers will explore the various steps and experiments undertaken to create predictive models. The accuracy and reliability of these models are thoroughly assessed using appropriate metrics. Furthermore, this section delves into creating a results dashboard that aids decision-making through effective visual communication emphasizing storytelling techniques as essential for sharing findings effectively.

### Chapter 6: Results and Discussion/Interpretation

In this chapter, the study's outcomes are showcased. The data processing and analysis pipeline used in case applicable is described with visualizations and tables that simplify the discoveries made by providing a precise interpretation of results relative to the problem background and research objectives identified in Chapter 1. Additionally, implications for forest fire management policies have also been highlighted along with comparing it with existing studies emphasizing its contributions as well as differences discovered from other works conducted before. 

### Chapter 7: Conclusion

The final chapter aims to summarize the pivotal discoveries of the study while highlighting its contributions to the area of focus. It also reflects on both achievements and constraints faced during project implementation, providing conclusive remarks along with suggesting avenues for future research or improvements. Notably, it emphasizes that there is a continual need for effective management and understanding regarding forest fires within climate change contexts by offering actionable recommendations accordingly.

The sequential arrangement of the chapters ensures a coherent progression of concepts, resulting in an extensive grasp of the research issue and its remedies. Such architecture is purposed to furnish lucid guidance for undertaking the study proficiently; ultimately leading towards valuable findings and feasible suggestions.

### 1.10 Summary
The primary focus of this thesis is to examine the impact of climatic variables on forest fires' temporal patterns in Peninsular Malaysia, a critical issue that has been exacerbated by climate change with substantial environmental and socio-economic consequences. The problem statement emphasizes the inadequacy of specific research on this subject within the region, characterized often by incomplete data and insufficient analytical techniques. Essentially, what influence do these variables have? This led us to develop predictive models for fire risk assessment while creating dashboard tools capable of visualizing outcomes- all geared towards supporting crucial decision-making processes. By compiling an exhaustive collection dataset leveraging advanced analytical methods intended explicitly for backing up ecological nuances unique to Malaysia; we aim to bridge contemporary research gaps  in comprehending how forest fires operate concerning natural warming trends affecting tropical rainforest eco-spaces around our planet today. Ultimately, this exploration's essence pertains additional importance given its potential illumination impacts exacerbating wildfire risks from global heating are significant not just environmentally but also socio-politically influential. Relevant stakeholders can yield valuable insights via such studies enhancing strategies aimed at managing wildfires effectively under unfavorable contexts related chiefly due damaging human activities as well as having negative overshadowing detriments operative through climate shifts occurring unbowed. We hope overall gains aid better conservation approaches across affected areas dictated here ultimately benefiting both society-at-large guidelines govern management practices over time framed decisions necessary going forward safeguard continuity amidst known fallouts emanating bad policies or ineffective strategies employed previously.


## Chapter 2: Literature Review/Problem Background
(Review of relevant literature and research)

## Chapter 3: Methodology
### Data Science Project Life Cycle
(Description of the life cycle followed)

### Data Sources and Collection Methods
(How and where the data was sourced)

### Data Pre-processing
(Cleaning, transformation, and feature engineering steps)

## Chapter 4: EDA/Initial Results
### Case 1: Primary Data
#### Exploratory Data Analysis (EDA)
- Visualizations
- Descriptive statistics
- Initial insights
- Feature engineering

### Case 2: Secondary Data
#### Exploratory Data Analysis (EDA)
- Visualizations
- Descriptive statistics
- Initial insights
- Feature engineering

#### Machine Learning (Initial Result)
(Description of initial machine learning results)

## Chapter 5: Discussion and Future Work
### Interpretation of Results
(Interpretation in the context of the research question)

### Implications of Findings
(Discussion on the implications)

### Comparison to Previous Research
(If applicable)
