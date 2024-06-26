---
jupyter:
  jupytext:
    formats: ipynb,md
    text_representation:
      extension: .md
      format_name: markdown
      format_version: '1.3'
      jupytext_version: 1.14.4
  kernelspec:
    display_name: Python 3 (ipykernel)
    language: python
    name: python3
---

<!-- #region tags=["title"] -->
# "Public opinion should be suspended until further report": A Data-Assisted Analysis of International Newspaper Coverage of the Explosion of the USS *Maine* (1898)
<!-- #endregion -->

```python tags=["cover"]
from IPython.display import Image, display
display(Image("./media/cover.jpg"))
```

<!-- #region tags=["contributor"] -->
### Adán Lerma-Mayer [![orcid](https://orcid.org/sites/default/files/images/orcid_16x16.png)](https://orcid.org/0000-0002-8420-2958)
Universidad Nacional Autónoma de México
<!-- #endregion -->

<!-- #region heading_collapsed=true tags=["contributor"] -->
### Ernesto Priani [![orcid](https://orcid.org/sites/default/files/images/orcid_16x16.png)](https://orcid.org/0000-0003-2908-0457)
Universidad Nacional Autónoma de México
<!-- #endregion -->

<!-- #region tags=["contributor"] -->
### Marc Priewe [![orcid](https://orcid.org/sites/default/files/images/orcid_16x16.png)](https://orcid.org/0000-0002-0956-2873)
University of Stuttgart
<!-- #endregion -->

<!-- #region tags=["copyright"] -->
 [![cc-by-nc-nd](https://licensebuttons.net/l/by-nc-nd/4.0/88x31.png)](https://creativecommons.org/licenses/by-nc-nd/4.0/) 
© Adán Lerma-Mayer - Ernesto Priani - Marc Priewe. Published by De Gruyter in cooperation with the University of Luxembourg Centre for Contemporary and Digital History. This is an Open Access article distributed under the terms of the [Creative Commons Attribution License CC-BY-NC-ND](https://creativecommons.org/licenses/by-nc-nd/4.0/)

<!-- #endregion -->

<!-- #region tags=["title"] -->
## Abstract
<!-- #endregion -->

<!-- #region tags=["abstract"] -->
In this paper, we investigate the first week of international newspaper coverage about the explosion of the armored cruiser USS *Maine* in Havana harbor on February 15, 1898. This event, in part, triggered the Spanish American War, which marked a changing of the imperial guards in the Western Hemisphere at the end of the nineteenth century. Using a selection of digitized newspapers from seven countries and employing statistical methods of quantitative analysis as well as close reading approaches, we take a new and comparative look at the initial coverage of the event from various national perspectives. Our research into the available newspaper data shows how information that arrived via news agencies and other newspapers during the first week after the event was molded into reports that added and reflected different biases concerning the explosion for specific national and regional audiences.
<!-- #endregion -->

<!-- #region tags=["keywords"] -->
digital history, transnational journalism studies, opinion-making in newspapers, Spanish American War.
<!-- #endregion -->

## Introduction


On April 19, 1898, the United States Congress recognized the independence of Cuba and authorized President William McKinley in a joint resolution to remove Spanish armed forces from the island. The ensuing war with Spain over its remaining colonies in the Western Hemisphere, which lasted only a few months, would propel the United States to a center-stage position in the concert of imperial powers at the time. Before this epochal decision in the spring of 1898, the United States had remained officially neutral in the recent resurgences of Cuban military resistance against Spanish colonial oppression, yet increasingly engaged in various ways and degrees in the conflict. Aside from sending contraband weapons to Cuban rebels and engaging in secret diplomacy with Spain, it was especially the incessant reporting in American newspapers about the cruelties and atrocities of Spanish colonial rule that helped the cause of *Cuba Libre* by creating an enemy-image that would later aid in justifying war.


Some historians have argued that the press played a central role in the decision of the United States government to enter into war with Spain by providing the necessary propaganda to gin up support for sending American men off to the battlefield (<cite data-cite="6095605/SBVQYHFC"></cite>, 264-67, <cite data-cite="6095605/3K5NG55P"></cite>, 201, <cite data-cite="6095605/6TXMVZNM"></cite>, 8). The present study aims to shed further light on the newspaper reporting preceding the decision of the United States to engage militarily in Cuba and other Spanish colonies by studying a collection of digitized newspaper articles from the United States, Spain, Mexico, Germany, the United Kingdom, the Netherlands, and Finland that report on what is generally seen as the pivotal event on the road to the Spanish-American war: the sinking of the USS *Maine* in the island’s capital harbor.


At least since the mid-1890s, parts of the American press had been instrumental in generating enthusiasm for expansionism beyond the nation's territorial boundaries on the heels of *Manifest Destiny*. The emerging yellow press, especially, took up the cause of spreading the narrative of American virtue, duty, and superiority that ultimately justified and demanded military interventions. William Randolph Hearst's *New York Journal* and Joseph Pulitzer's *New York World* were the center of the sensational press and significantly influenced political decisions of the time. Yellow journalism in the United States was geared to the masses regarding content, language, appearance, and price. Instead of newspaper reports that aimed at objectivity and sobriety, yellow journalism engaged in lavish and extravagant stories with attention-grabbing, large headlines that catered to the interests and financial means of the rising working-class readership, especially  in New York City. Unlike their traditional competitors, yellow papers also paid staff of journalists, writers, and illustrators of national acclaim to produce fabricated or exaggerated stories packaged as news that would attract readers' attention (<cite data-cite="6095605/TE5IANE9"></cite>, 28-54; <cite data-cite="6095605/ZX5QAL9Y"></cite>, 16). The growing conflict between Cuban rebels and Spanish troops partly spurred the rise of yellow journalism in the United States, a topic that New York papers had picked up almost daily since 1895. Relying on the familiar narrative of an underdog seeking liberation from an evil colonial ruler, and often consisting of "harrowing tales of women victims of Spanish cruelty" (<cite data-cite="6095605/ZX5QAL9Y"></cite>, 93), most of the reports printed in the yellow press showed islanders as victims and the Spanish colonial government as brutal perpetrators of discrimination, oppression, and violence. Rumors and biased reports by the Cuban *junta*, a pro-independence organization in New York with close geographic and ideological proximity to the nearby yellow press, often fueled topics and stories at the time (<cite data-cite="6095605/6APGTG5J"></cite>, 14, <cite data-cite="6095605/46XUDA7Z"></cite>, 28, <cite data-cite="6095605/QNF6PJQD"></cite>, 12-14, <cite data-cite="6095605/8KWJRM5V"></cite>, 36-37). William Hearst is mainly credited for using his sensationalistic newspaper to create a pro-war public sentiment, at least since 1897, in order to generate profit and to cement his role in the Spanish-American War, which he went so far as to call the "Journal's war" (cited in <cite data-cite="6095605/SBVQYHFC"></cite> 266). The imminent war in Cuba energized the competition between Hearst and Pulitzer, in which one not only tried to outdo the other with the latest scoop, but they accused the other paper of slow or false reporting. Both papers also rallied for war in response to the explosion of the *Maine* almost immediately, with Hearst's Journal leading the call to arms (<cite data-cite="6095605/P97L8XTZ"></cite>, 65-70).


Nevertheless, the exact role of the press in causing the United States to enter into war with Spain is still debated among historians, not least because yellow journalism did not spread widely or evenly across the country (<cite data-cite="6095605/ZX5QAL9Y"></cite>, 19, 443, <cite data-cite="6095605/46XUDA7Z"></cite>, 62, 72). It is safe to assume that American newspapers aided in the rally-around-the-flag effect, an outburst of public sentiment and agreement with the goals of the wartime nation; however, this was not the sole motivator for McKinley to opt for military intervention in Cuba (<cite data-cite="6095605/R48SEVSY"></cite>, 24, <cite data-cite="6095605/6DQ7MKZ3"></cite>, 150). Historians have persistently disagreed over what caused the United States to begin a war with Spain over Cuba, including the role of the press (<cite data-cite="6095605/WND9IA2U"></cite>, <cite data-cite="6095605/ZX5QAL9Y"></cite>, cf. <cite data-cite="6095605/H3L2CQG4"></cite>, <cite data-cite="6095605/HNWNC6RC"></cite>, 378-454).
Upon closer inspection of the records, historians have provided a more nuanced picture, one that refutes the claim that the yellow press was mainly, if not solely, responsible for driving the United States into war with Spain. George Auxier's research has shown, for instance, that Midwestern newspapers, while maintaining a firm sense of patriotism, were more cautious in calling for war with Spain and quite suspicious of the arrogant nationalism, or jingoism, displayed by the leading New York papers (<cite data-cite="6095605/8B7QHMNB"></cite>). <cite data-cite="6095605/6DQ7MKZ3"></cite>, in a similar vein, write: "The dividing line between the Yellow Press of the East and the middle-of-the-road press in the Midwest was quite noticeable in the coverage of the sinking of the U.S. armored cruiser *Maine* in Havana harbor. While the New York press howled for war, the Minnesota press urged caution and contemplation" (129), and the Kansas press reported similarly (<cite data-cite="6095605/TXZGKNJI"></cite>). Moreover, as Piero Gleijeses has shown, opposition to the war was quite prominent in (public) opinions expressed in nationwide editorials and in the more general reporting on the events that led up to the war. Not all newspapers subscribed to and re-printed news from Hearst and Pulitzer. Many relied on the more restrained and "conservative" reports sold and circulated by the Associated Press (A.P.) or on a combination of several news services (<cite data-cite="6095605/TE5IANE9"></cite>, 6-7, <cite data-cite="6095605/ZX5QAL9Y"></cite>, 131).


The year 1898 had begun with violent riots in Havana that received comprehensive coverage in the United States and caused growing concerns over human rights and the protection of American economic interests. As one result, President McKinley sent one of the most modern ships in the navy fleet, the armored cruiser *Maine*, painted in white, on a "friendly" visit from Key West to Havana on January 24. Diplomatic tensions between Spain and the United States mounted when news broke on February 9 that a letter by Spanish diplomat Dupuy De Lome had been intercepted by the Cuban *junta* and published by the New York yellow press in which he denigrated McKinley as weak and cowardly (<cite data-cite="6095605/TE5IANE9"></cite>, 92-97). Less than a week later, on February 15, 1898, at 9:40 pm, the *Maine* exploded in Havana harbor, killing 266 men, amounting to two-thirds of its crew. Given the already existing public animosities toward Spain expressed in many newspapers of the day, it was no coincidence that for many observers, the culprit under whose behest or at least auspices the explosion had taken place was Spain (<cite data-cite="6095605/46XUDA7Z"></cite>, 62, <cite data-cite="6095605/CHKZZDP8"></cite>, 170).


On March 28, 1898, an official investigation by U.S. experts concluded that the sinking of the cruiser had been caused externally by a mine, yet no person or group was made responsible. The wreck of the *Maine* has since been examined numerous times to find the cause of the sinking. While the first report in 1898 (confirmed in 1911) claimed that an external mine was responsible, a re-examination undertaken in 1976 had found the cause to be internal, due to negligence, or by mere accident. In an extensive computer-aided simulation of the available data, *National Geographic Magazine* concluded in 1999 that both causes were possible without providing sufficient evidence for either claim (<cite data-cite="6095605/FD8IKH5J"></cite>). In the newspapers studied for this project, no account blames the explosion explicitly on the Cuban *Junta*, which could have had an interest in causing the United States to (finally) intervene on the island and free its people from Spanish colonialism. Although rumors about various possible acts of conspiracy were circulating in the yellow papers shortly after the explosion, opinion leaders did not discuss them as viable causes. Also, in our corpus, there are no references to the conspiracy theory, first traceable in print in Tiburcio P. Castañeda's 1925 book *La explosión del *Maine* y la guerra de los Estados Unidos con España*, that "war hawks" in the U.S. government, especially Assistant Secretary of the Navy, Theodore Roosevelt, "conceal[ed] the real cause of the disaster from the American public in order to proceed to war and the conquest of the Philippines" (<cite data-cite="6095605/X6AY9XQ3"></cite>, 205).


For our case study, we relied on 1,627 newspaper articles published in seven countries during the first week after the explosion of the *Maine*. In order to extract usable data from the digital newspaper archives available to us, we used several search terms related to the event. We then applied text mining tools and topic-based annotations to compare newspaper reporting on this specific historical event more granularly than previously possible. Since our corpus was based on digitized newspapers from various national archives, we were able to detect different trends compared to research methods that rely primarily on interpreting editorials from a comparatively small selection of newspapers housed in libraries or archives. Our scalable reading approach consisted of a combination of a bird's-eye and a microscopic view of documents (international newspapers) that represent a specific historical event (the explosion of the *Maine*), allowing us to study the attitudes of the press beyond the borders of the American Northeast and its yellow press subsidiaries and the Midwestern papers (<cite data-cite="6095605/NFAZA7VR"></cite>, <cite data-cite="6095605/IDTJU3HD"></cite>, <cite data-cite="6095605/EU8XH2UE"></cite>). This reading approach to digitized newspapers employs close and distant reading methods, enabling one to assess how newspapers reflected and helped mold public opinion in the Western Hemisphere and Europe during the spring of 1898. What we see unfold in the data is how expansionist and anti-expansionist movements found expression in newspaper reporting following the sinking of the *Maine* in virtually all of the countries studied. These two factions quarreled vociferously over the right path of the country in international affairs, especially in the United States. Taking on a remaining, although declining, imperial power such as Spain and potentially having to step in as colonists themselves caused both unease and excitement among American politicians, the broader public, and the media. However, the events in Cuba, Washington, and Madrid were also closely monitored by traditional and aspiring imperial powers, among them (and with varying efforts and degrees) Great Britain, Germany, the Netherlands, and even Cuba's neighbor Mexico (<cite data-cite="6095605/4BGQ3G5T"></cite>).


We aim to generate further insight into newspaper reporting in these countries by asking the following guiding questions: How did different newspapers in different countries react to the emerging shifts in imperial powers in the Americas that the *Maine* incident seemed to signal? To what extent was this event seen as a sign of war by newspapers in countries with varying interests in a possible conflict between the United States and Spain over Cuba? In addressing these questions, we seek to test a common hypothesis in historical research on the Spanish-American War, namely that "during the latter part of February, the newspapers seemed to be led gradually to the conclusion that war was inevitable" (<cite data-cite="6095605/TE5IANE9"></cite>, 105). While *the World, the Journal*, and their yellow press subsidiaries in the United States did, in fact, pronounce Spain guilty almost immediately, our research shows a more nuanced reaction by the American as well as by the international press in the first week after the sinking of the *Maine*. In the following, we will first outline the selection of primary source material and the methods chosen and developed for the analysis. This includes an assessment of the obstacles we encountered, such as the selection of newspapers in the collection of digitized documents or OCR errors contained in the available data. Then, we provide our reading reports of the press coverage in seven countries involved in the ensuing conflict between Spain and the U.S. to varying degrees. These reports are enhanced by a comparative analysis of opinion-making in the chosen national newspapers based on the data generated from our working corpus. This scalable reading approach is consistently informed by secondary literature on the conflict and the roles and functions that newspapers played at the time.

<!-- #region tags=["hermeneutics"] -->
## Digging into Data: Corpora and Methods
<!-- #endregion -->

<!-- #region tags=["hermeneutics"] -->
Our exploration of nineteenth-century news reporting was based on a collection of digitized newspapers, which was assembled and clustered by an international research group working on *Oceanic Exchanges: Tracing Global Information Networks in Historical Newspaper Repositories, 1840-1914* (2017-2020). This collection presents opportunities and challenges for scholars researching how newspapers mediated past events to a broader public. On the one hand, the publicly funded digital holdings allow unprecedented access to primary materials housed in archives that had often been too far apart to consult in person. On the other hand, the state and quality of newspaper digitization projects in different countries vary significantly, for instance, concerning the quality of Optical Character Recognition (OCR), the extent of metadata inclusion, or the use of article separation when displaying and downloading individual articles (cf. <cite data-cite="6095605/784EF7FS"></cite>). Moreover, while some national archives (Finland, the Netherlands, and Australia, for instance) offer all of their available historical newspapers as digital facsimiles, other collections are based on selection criteria that are not always transparent for users, resulting, for instance, in a lack of data from Cuba, from Vienna in the German-language archives or from late-nineteenth-century yellow press newspapers in the corpus of *Chronicling America*. These and other shortcomings in the quality and quantity of the data can potentially lead to skewed results and force researchers to proceed with caution when analyzing and interpreting digitized newspapers as data (cf. <cite data-cite="6095605/MS9GS47Z"></cite>).

<!-- #endregion -->

<!-- #region tags=["hermeneutics"] -->
We employed data-assisted methods to further explore our corpus. As Miguel Escobar explains, scholars can employ data to transform our view of a question or problem with a data-assisted method. It is, in essence, a strategy of defamiliarization from the text in order to generate new perspectives on it. In our case, we took a scalable reading approach that combines traditional close reading practices borrowed from Literary Studies and History with data-assisted, "distant reading" (<cite data-cite="6095605/BW8UK5UU"></cite>) approaches that have gained prominence in Digital Humanities research in recent years. We understand "close reading" to refer to the detailed analysis of individual newspaper items read by human beings and the manual annotation and interpretation of data provided by information technology. Distant reading is "a condition of knowledge" because while it offers a bird's-eye perspective on large data sets that would be impossible to read by a single human being, distant reading also "allows us to focus on units that are much smaller than the text" (<cite data-cite="6095605/BW8UK5UU"></cite>, 57), such as specific words and subjects in a heap of news data. This approach enables us to contrast and enrich data processing results with the assumptions we have formed while reading the news reports and the scholarly literature on the *Maine* case.
<!-- #endregion -->

<!-- #region tags=["hermeneutics"] -->
We gathered our subcorpus of newspaper articles on the explosion from the larger corpus made available through the Oceanic Exchanges research consortium. In order to keep the data manageable and to ensure that the bulk of reporting that we aimed to compare references the same event, we decided to search for articles published between February 16 and 23, 1898, the time between the explosion and the day when Congress appropriated 50 million dollars to prepare for war with Spain. We later decided to add data for the same time frame from the Spanish newspaper collection provided through the *Hemeroteca Digital de Biblioteca Nacional de España*, because Spain was a central protagonist in the controversy around the explosion of the USS *Maine* and the ensuing war and was thus vital for a meaningful investigation of international newspaper coverage of a single event. We also separated the German-language newspapers geographically into those from Germany and Austria-Hungary according to their respective national borders at the time of publication. However, because we only had a statistically insignificant number of articles from Austria-Hungary, and since we lacked access to digitized newspapers from Vienna at the time of conducting our research, we decided to refrain from studying news reporting from this area for the time being.
<!-- #endregion -->

<!-- #region tags=["hermeneutics"] -->
Since "Maine" is an ambiguous word, we had to use additional keywords that would help refine our search. Given that we were dealing with a multilingual corpus, we had to vary concepts and spellings found in the papers. For example, "USS Maine, "Kruiser," in German and Dutch "räjähdys", in Finnish, "Havana" or "Habana",  "Espanja" or "España", "Explosion" or "explosión" were used as search terms in order to arrive at our corpus of newspaper articles. Our extensive and multiple keyword searches resulted in 1,627 stories published on the explosion of the *Maine* during the first week after the event (see [table 1](#anchor-table-1)).
<!-- #endregion -->

```python tags=["hermeneutics", "table-1", "anchor-table-1"]
import pandas as pd


df_table1 = pd.read_csv("https://raw.githubusercontent.com/jdh-observer/aADj3Ljjqti2/main/script/corpus.csv", na_filter=False)
caption_content_1 = 'table 1: Working Corpus "The Explosion of the USS *Maine*, February 16-23, 1898" (excerpt). https://github.com/jdh-observer/aADj3Ljjqti2/blob/main/script/Full%20Corpus.xlsx'
#df_table1


display(df_table1.style.set_properties(**{'text-align': 'left'}), metadata={ "jdh":{"object":{"source":[ "Working Corpus 'The Explosion of the USS *Maine*, February 16-23, 1898' (excerpt).","https://github.com/jdh-observer/aADj3Ljjqti2/blob/main/script/Full%20Corpus.xlsx"]}}})


```

<!-- #region tags=["hermeneutics"] -->
As shown in [figure 1](#anchor-figure-1), 67.8% of articles during the explosion's first week of reporting came from the United States, 11.1% from Spain, and the remaining 22.6% from the rest of the countries. The imbalance in news coverage can be explained by the relevance of the news to the main actors in the conflict–the United States and Spain–and by the higher number of newspapers published and circulated in the United States at the time. This also implies that the results must be understood within this context of over-representation and frequency of reporting, rather than merely by total numbers.
<!-- #endregion -->

```python caption="Piechart" jdh={"module": "object", "object": {"source": ["figure 1: Distribution of absolute frequencies by country on news reports on the *Maine*'s explosion"], "type": "image"}} tags=["hermeneutics", "figure-1", "anchor-figure-1"] widefigure=true

import pandas as pd
import plotly.express as px

df = pd.read_csv("https://raw.githubusercontent.com/jdh-observer/aADj3Ljjqti2/main/script/Figure%202.csv")
metadata={
    "jdh":{
        "module": "object",
        "object": {
          "type": "image",
           "source": [
            "figure 1: Distribution of absolute frequencies by country on news reports on the *Maine*'s explosion"

          ]
        }
    }
}
fig = px.pie(df, names = "Country",
             values ="No. of newstories",
             title="Distribution of absolute frequencies by country on news reports on the *Maine*'s explosion",
             labels = {"names" :["Spain","USA","Germany","Mexico","Finland","UK","Netherlands"]})
fig.update_traces(textposition='inside', textinfo='percent+label')
fig.show()



```

<!-- #region tags=["hermeneutics"] -->
When it comes to the reliability of the data, perhaps the most relevant aspect of our corpus is the difference in the quality of the OCR that we obtained from each national collection, which directly affects the analysis process (<cite data-cite="6095605/EV79DXBF"></cite>). As libraries and archives often follow different digitization processes, the final quality of the data varies. Differences in scanning practices, the software used, the quality of the originals, and the editorial decisions over how to present the scanned newspapers as images and texts determine what users see as a digital copy of an old newspaper on their computer screen. This was significant for our study because of the differences in OCR quality, especially between the U.S. and Spanish newspaper data. The library cleaned the latter, meaning that the automatically extracted OCR was not used but instead underwent a subsequent improvement process to make it accessible to human eyes and machine-readable simultaneously. The data from the United States (and Great Britain) did not undergo this clean-up; hence, users only have access to the data resulting from the automatic extraction, which includes everything on the printed page, without separating news stories and columns or automatic OCR correction. The quality of the newspaper data provided by other national archives varies similarly. We had not foreseen such a lack of uniformity in the data made available by the archives and the subsequent  problems posed by the diverging quality of the OCR of the most substantial part of our corpus, the collection of newspapers from the United States. In order to carry out our analysis, we decided to reduce the "noise" of the U.S. data through an automatic process that mainly eliminated most of the information contained in the OCR that did not correspond to the explosion of the *Maine*. This was done by filtering chunks of surrounding text (windows of words to the right and to the left) where “USS Maine” or "Havana" were mentioned. The second decision was to refrain from a manual clean-up of the data and, instead, to keep the remaining files "raw," accepting that the data disparity reflects the complex digitization decisions and processes in each country. Overall, the cleaning activities by institutions and our research led to a usable corpus of articles, with an OCR quality of "approximately 60-85%" (<cite data-cite="6095605/784EF7FS"></cite>, 7).


<!-- #endregion -->

<!-- #region tags=["hermeneutics"] -->
In order to understand the attitudes towards the sinking of the *Maine* conveyed in international newspapers in February of 1898, we combined our reading reports of selected articles with information from secondary literature and with interpretation drawn from a computational analysis that used text mining and topic-based annotations. It quickly became apparent that the discussions in the international press centered primarily around the cause of the ship's sinking: Was it an internal accident or a deliberate attempt? During the time frame chosen for our study (02/16-02/23/1898), newspapers worldwide began to speculate about the cause of the explosion, citing or paraphrasing the opinions of experts, politicians, members of the military, and other newspapers. Whenever an article leaned toward spontaneous combustion in the ship's coal bunkers as an explanation, it implied an opinion that the explosion was the result of an accident (and thus the fault of the U.S.), and conversely, whenever an article leaned toward a torpedo's explosion being the explanation, it implied an opinion that the explosion was the result of an attack (and thus the fault of Spain). What was clear to virtually all observers at the time was that, if the United States were to blame Spain for the sinking, it would take this opportunity to begin a military intervention in Cuba. Hence, we also sought to understand how the media reported statements from specific actors involved in the aftermath of the sinking in order to study how newspapers attempted to sway public opinion in favor of the accident or deliberate explosion hypotheses. We hence selected “opinion,” drawn from the telegram sent by Captain Sigsbee, as a search term for our working corpus to identify the stances on the reasons behind the explosion conveyed in the papers: an attack, an accident or to suspend opinion. The search obtained 1,724 hits, and 200-character width window contexts were automatically extracted and divided by country of origin.  

<!-- #endregion -->

```python tags=["hermeneutics", "figure-2"]
from IPython.display import Image
metadata={
    "jdh": {
        "module": "object",
        "object": {
            "type":"image",
            "source": [
                "Script to extract textual information around a searchable term"
            ]
        }
    }
}
display(Image("media/Get context.png"), metadata=metadata)
```

<!-- #region tags=["hermeneutics"] -->
From these, we identified seven categories of actors or speakers in the aftermath of the incident: Captain Sigsbee, the survivors of the *Maine*, experts on ships and explosions, journalists, politicians, military personnel other than the ship's crew, and unknown or unidentified speakers within the extracted contexts. Herman and Chomsky have pointed out in *Manufacturing Consent* that "the mass media are drawn into a symbiotic relationship with powerful sources of information by economic necessity and reciprocity of interest" as "they cannot afford to have reporters at all places" and "taking information from sources that may be presumed credible reduces investigative expense" (<cite data-cite="6095605/GUDUZYMP"></cite>, 18). This is also true for our case study on parts of the international press at the end of the nineteenth century. The reported voices followed the same pattern as in the modern media: official sources, highly reputable unofficial sources, and a body of experts that functioned as a filter for the news deemed fit to print. 		

<!-- #endregion -->

<!-- #region tags=["hermeneutics"] -->
Next, using manual annotations, we assigned the expressed opinions to a position on the sinking (i.e., we classified the meaning of the opinion as either promoting an accidental explosion, suggesting a deliberate attack, or calling for a suspension of all opinion until further investigations).
<!-- #endregion -->

```python mpriewe={"figure": {"caption": "figure 3: Finland", "label": "figure 3: Finland"}} tags=["hermeneutics", "table-2", "anchor-table-2"]
import pandas as pd

df_table2 = pd.read_csv("https://raw.githubusercontent.com/jdh-observer/aADj3Ljjqti2/main/script/Finland.csv", na_filter=False)

display(df_table2.head(5).style.set_properties(**{'text-align':'left'}), metadata={ "jdh":{"object":{"source":["Manual annotations of „opinion“ contexts in the Finnish Press. https://github.com/jdh-observer/aADj3Ljjqti2/blob/main/script/Full%20Corpus.xlsx" ]}}})
```

```python tags=["hermeneutics", "table-3"]
import pandas as pd


df_table3 = pd.read_csv("https://raw.githubusercontent.com/jdh-observer/aADj3Ljjqti2/main/script/Germany.csv", na_filter=False)
display(df_table3.head(5).style.set_properties(**{'text-align':'left'}), metadata={"jdh":{"object":{"source": ["Manual annotations of „opinion“ contexts in the German Press. https://github.com/jdh-observer/aADj3Ljjqti2/blob/main/script/Full%20Corpus.xlsx"]}}})
```

```python tags=["hermeneutics", "table-4"]
import pandas as pd


df_table4 = pd.read_csv("https://raw.githubusercontent.com/jdh-observer/aADj3Ljjqti2/main/script/Mexico.csv", na_filter=False)
display(df_table4.head(5).style.set_properties(**{'text-align':'left'}), metadata={"jdh":{"object":{"source": ["Manual annotations of „opinion“ contexts in the Mexican Press. https://github.com/jdh-observer/aADj3Ljjqti2/blob/main/script/Full%20Corpus.xlsx"]}}})
```

```python tags=["hermeneutics", "table-5"]
import pandas as pd


df_table5 = pd.read_csv("https://raw.githubusercontent.com/jdh-observer/aADj3Ljjqti2/main/script/Netherlands.csv", na_filter=False)
display(df_table5.head(5).style.set_properties(**{'text-align':'left'}), metadata={"jdh":{"object":{"source": ["Manual annotations of „opinion“ contexts in the Dutch Press. https://github.com/jdh-observer/aADj3Ljjqti2/blob/main/script/Full%20Corpus.xlsx"]}}})
```

```python tags=["hermeneutics", "table-6"]
import pandas as pd


df_table6 = pd.read_csv("https://raw.githubusercontent.com/jdh-observer/aADj3Ljjqti2/main/script/Spain.csv", na_filter=False)
display(df_table6.head(5).style.set_properties(**{'text-align':'left'}), metadata={"jdh":{"object":{"source": ["Manual annotations of „opinion“ contexts in the Spanish Press. https://github.com/jdh-observer/aADj3Ljjqti2/blob/main/script/Full%20Corpus.xlsx"]}}})
```

```python tags=["hermeneutics", "table-7"]
import pandas as pd


df_table7 = pd.read_csv("https://raw.githubusercontent.com/jdh-observer/aADj3Ljjqti2/main/script/UK.csv", na_filter=False)
display(df_table7.head(5).style.set_properties(**{'text-align':'left'}), metadata={"jdh":{"object":{"source": ["Manual annotations of „opinion“ contexts in the British Press. https://github.com/jdh-observer/aADj3Ljjqti2/blob/main/script/Full%20Corpus.xlsx"]}}})
```

```python tags=["hermeneutics", "table-8"]
import pandas as pd


df_table8 = pd.read_csv("https://raw.githubusercontent.com/jdh-observer/aADj3Ljjqti2/main/script/USA.csv", na_filter=False)
display(df_table8.head(5).style.set_properties(**{'text-align':'left'}), metadata={"jdh":{"object":{"source": ["Manual annotations of „opinion“ contexts in the U.S.-American Press. https://github.com/jdh-observer/aADj3Ljjqti2/blob/main/script/Full%20Corpus.xlsx"]}}})
```

<!-- #region tags=["hermeneutics"] -->
 After discarding hits that were illegible (due to OCR errors), obviously out-of-context, or when the speaker's position was unclear, the final corpus of 671 (58% of the original hits) was placed in a matrix showing the possible combination of actor and stance on whether the explosion was an accident or an attack (as can be seen in [table 2 to 8](#anchor-table-2)). Then, we verified 10% of each other's annotations to ensure a homogeneous interpretation of the data. This close reading of the final "opinion" corpus enabled us to obtain a nuanced picture of how newspapers portrayed certain opinions and voices that were ultimately connected to the question of war and peace. Based on the available digitized newspapers from the United States and other countries, we argue that the opinions on the cause of the sinking and, hence, on the necessity of war are more widely distributed and diverse than previous research has indicated.
<!-- #endregion -->

## International Press Reactions to the Explosion of the *Maine*


Between February 16 and 23, 1898, the international media scene in our corpus remained undecided about the cause of the *Maine*'s sinking, with a slight overall leaning towards the accident hypothesis. All national presses re-printed Captain Sigsbee's words of caution from February 16, calling for the suspension of opinion until further investigations took place ([figure 3](#anchor-figure-3)).


Regarding the frequency of the word "opinion" in relation to the number of stories about the *Maine* in our working corpus as a whole, newspapers from the United States and Mexico printed the item more than once per article, while the British and Spanish papers used this word 95% and 73%, respectively. The rest of the European countries (Finland, Germany, Netherlands) employed the term "opinion" significantly less.  

```python caption="Barchart" jdh={"module": "object", "object": {"source": ["figure 3: Distribution of opinions voiced about the *Maine*\u2019s explosion by country"], "type": "image"}} tags=["figure-3", "anchor-figure-3"] widefigure=true
import pandas as pd
import plotly.express as px

df = pd.read_csv("https://raw.githubusercontent.com/mpriewe/repo_article_maine/main/script/Figure%203.csv")
fig = px.histogram(df, x=["Finland","Germany","Mexico", "Netherlands","Spain","UK","USA"],
                   y=["Suspend Opinion", "Accident", "Attack"],
                   barnorm= "percent",
                   title="Distribution of opinions voiced about the *Maine*’s explosion by country",
                   labels={"x": ""})
fig.update_layout(yaxis_title="", legend_title="")
fig.update_yaxes(ticksuffix="%")
fig.update_xaxes(ticktext=["Finland","Germany","Mexico", "Netherlands","Spain","UK","USA"],
                 tickvals=["Finland","Germany","Mexico", "Netherlands","Spain","UK","USA"])
fig.show(metadata={"jdh": {"object": {"source": ["Distribution of opinions voiced about the *Maine*’s explosion by country"]}}})

```

Most countries clearly expressed many unknown speakers’ opinions, which we could not identify from the context. In addition, the graphs were normalized to the number of helpful “opinion” hits in the final corpus. It did not include all undecided data. With this normalization, we were able to observe comparable trends per country.


Concerning the question of accident or intent, most newspapers studied in our project referenced the opinions of military personnel and politicians, followed by experts (e.g., engineers), survivors of the *Maine*, and other journalists. When taking a closer look at the voices that called the sinking a deliberate attack ([figure 4](#anchor-figure-4)), it is interesting to note that in Mexico and the U.K., this position was mostly held by politicians, whereas in the U.S., a broader range of actors argued in favor of the attack hypothesis.

```python caption="Barchart" jdh={"module": "object", "object": {"source": ["figure 4: Distribution of speakers leaning towards attack hypothesis by country"], "type": "image"}} tags=["figure-4", "anchor-figure-4"] widefigure=true
import pandas as pd
import plotly.express as px

df = pd.read_csv("https://raw.githubusercontent.com/mpriewe/repo_article_maine/main/script/Figure%204.csv")
fig=px.histogram(df, x=["Finland","Germany","Mexico", "Netherlands","Spain","UK","USA"], y = ["Experts","Journalists","Military Personnel","Politicians","Sigsbee","Survivors","Unknow Speaker"],barnorm = "fraction",title="Distribution of speakers leaning towards attack hypothesis by country",labels={
    "x":""
})
fig.update_layout(    
yaxis_title="",
legend_title="")
fig.update_xaxes (
ticktext= ["Finland","Germany","Mexico", "Netherlands","Spain","UK","USA"],
tickvals= ["Finland","Germany","Mexico", "Netherlands","Spain","UK","USA"])
fig.show(metadata={ "jdh":{"object":{"source":[ "Distribution of speakers leaning towards attack hypothesis by country" ]}}})
```

The United States data are also indicative of a higher diversity of voices and opinion-shapers than in other countries represented in our corpus. In Finland, by contrast, only experts claimed that the sinking was due to an attack, and in the Netherlands, the voices of journalists calling the incident an attack seemed unusually high. When reading the actual newspaper articles, it becomes clear that Dutch papers re-printed the belligerent voices in the New York yellow press, which then appeared in our data as voices of journalists. In contrast to other countries, Dutch newspapers referenced no expert opinions but appeared to lean strongly towards the attack theory compared to other European papers because of the citations by American journalists who claimed that it was an attack and that Spain was behind it.



It is not only insightful to learn who said what about the event, but also which voices were not represented in the press. Concerning the attack theory, only the American press referenced military personnel and survivors. Similarly, with regard to “suspend opinion,” only survivors, a few experts, and journalists were quoted. The accident position was also barely mentioned by journalists and Captain Sigsbee. Nonetheless, this is the hypothesis with the highest number of voices overall. In contrast, more speakers sided with the accident hypothesis than the attack theory, i.e., there was a higher degree of a plurality of points of view among those who considered the explosion to be due to an accident. Experts supported the accident theory in every country except the Netherlands and the U.K., where politicians and military personnel mostly voiced this opinion ([figure 5](#anchor-figure-5)).


As can also be deduced from the data, the Finnish press relied more on expert assessments of the explosion and leaned towards the accident hypothesis more strongly than any other national press in our corpus. It is difficult to determine whether the most balanced and least biased reporting was due to Finish strivings for neutrality, with no stakes in who controls Cuba and the Western Hemisphere, or whether it reflected Russian political (and imperial) interests, given that in 1898 Finland was still officially a Grand Duchy in the Russian Empire.

```python caption="Barchart" jdh={"module": "object", "object": {"source": ["figure 5: Distribution of speakers leaning towards accident hypothesis by country"], "type": "image"}} tags=["figure-5", "anchor-figure-5"] widefigure=true
import pandas as pd
import plotly.express as px

df = pd.read_csv("https://raw.githubusercontent.com/mpriewe/repo_article_maine/main/script/Figure%205.csv")
fig=px.histogram(df,x=["Finland","Germany","Mexico", "Netherlands","Spain","UK","USA"], y = ["Experts","Journalists","Military Personnel","Politicians","Sigsbee","Survivors","Unknow Speaker"],barnorm = "percent",title="Distribution of speakers leaning towards accident hypothesis by country",labels={
    "x":""
})
fig.update_layout(    
yaxis_title="",
legend_title="Speakers")
fig.update_yaxes (ticksuffix="%")
fig.update_xaxes (
ticktext= ["Finland","Germany","Mexico", "Netherlands","Spain","UK","USA"],
tickvals= ["Finland","Germany","Mexico", "Netherlands","Spain","UK","USA"])
fig.show(metadata={ "jdh":{"object":{"source":[ "Distribution of speakers leaning towards accident hypothesis by country" ]}}})
```

### Spain


Our data-assisted comparison shows that pro-accident voices were featured less prominently in Spain's press than in any other national corpus. This was likely due to Spanish officials seeking to avoid further escalation of diplomatic tensions in the wake of the DeLome affair in early February 1898 by suggesting that the explosion may have been due to American negligence or even intent. We also find that experts, survivors, and military personnel identified the explosion as an accident in Spain. Upon closer inspection, Spanish newspapers such as *El Heraldo*, *La Epoca*, and *El Siglo Futuro* produced an evening edition on February 16 with information regarding the intensely reported rumors during the day about the destruction of the *Maine* in Havana. *El Día*, for example, reported:


>El Maine, el acorazado norteamerticano que fue al puerto de la Habana a hacernos una visita de amistad, ha sido completamente destruido por la explosión de sus calderas y depósito de pólvora. La noticia que anticipó Fabra ha circulado con gran rapidez, produciendo la natural sensación. Los telegramas oficiales que se han recibido en los ministerios de la Guerra y Marina, y las transmitidas por el corresponsal de El Imparcial en la Habana a este periódico dan cuenta detallada de la catástrofe.


>“The *Maine*, the North American battleship that went to the port of Havana to pay us a friendly visit, has been completely destroyed by the explosion of its boilers and gunpowder deposit. The news that Fabra anticipated has circulated very quickly, producing the natural sensation. The official telegrams that have been received by the War and Navy ministries, and those transmitted by the correspondent of *El Imparcial* in Havana to this newspaper give a detailed account of the catastrophe.” (google.translate)


It was an important day for the Spanish press since the previous year had turned events in Cuba into front-page news (<cite data-cite="6095605/XKPZYPDG"></cite>, 231). Similar to the United States, for the Spanish press, the conflict in Cuba led to a significant growth in sales (<cite data-cite="6095605/KH3UHVCH"></cite>, 41). Access to information from Cuba made newspapers such as *El Imparcial*, the most influential newspaper at the time in Spain, *El Heraldo*, an evening newspaper that was also very popular, and *La Correspondencia Militar*, an army newspaper, essential reading. These newspapers relied on correspondents in Havana, Key West, and New York. Another important and exclusive source of information for the Spanish press were the FABRA agency cables, a predecessor of the EFE news agency, which also had correspondents in Havana and other cities. That meant that significant proportions of information circulating in Spain during the crisis caused by the explosion of the *Maine* were first-hand  products of the work of correspondents and news agencies.



On February 17, news of the *Maine* occupied the front page of the entire morning press in Spain. Newspapers highlighted two particular reports on that day: a telegram from General Blanco to the government of Spain in which he affirms that it was an accident and the telegram by Captain Sigsbee requesting the authorities of his country to suspend their opinion until further investigation. From the beginning, the press stuck to the accident thesis and aimed to praise the Spanish navy's noble intervention in rescuing the wounded and the dead bodies. *La Correspondencia Militar*, for instance, made an extensive, informative display of the accident, describing in detail what happened and the subsequent mobilization for the rescue of sailors of the *Maine*. *El Imparcial*, in turn, narrated through the pen of its correspondent the previous days’ events and detailed two hypotheses of how the accident could have occurred inside the ship.


The press reviewed the event in the context of existing political tensions with the United States. With a few exceptions like *El Socialista* and *El Nuevo Régimen*, the Spanish press was ultranationalist (<cite data-cite="6095605/XKPZYPDG"></cite>, 237) and very soon pro-war (<cite data-cite="6095605/Z8D4MCP8"></cite>, 89). *El Correo Militar* noted, for instance, that the accident should not produce conflict with the U.S. while detailing demonstrations in New York against Spain. *El Día* was the only Spanish paper to allude to the torpedo thesis but did so in the context of warning that the U.S. probably wanted to take advantage of the incident (i.e., use it as a *casus belli*). Very much in the tone of preventing the United States from taking advantage of the accident in its favor, *La Epoca* wrote:


>De todas suertes, bien hará el Gobierno español en apercibirse contra posibles injusticias, y por eso nos parecen oportunos sus deseos de depurar pronto y por entero los hechos, para desvanecer al momento cuantas dudas pudieran surgir en este caso.


>“By all luck, the Spanish Government will do well to warn itself against possible injustices, and for this reason its desire to purge the facts soon and completely, to dispel at the moment any doubts that may arise in this case, seem appropriate.” (google.translate)


On February 18, newspapers highlighted that the dominant opinion of politicians in Washington, D.C. was that it was an accident. Several Spanish newspapers reviewed the American press and emphasized its generally moderate tone. However, papers with their correspondents, particularly *El Heraldo* and *El Imparcial*, stressed the attack hypothesis. These same newspapers and *La Correspondencia Militar* took up the issue of the formation of an investigation commission and indicated their fear that it would serve to support the attack hypothesis. Many Spanish papers also reported what their colleagues in France, England, and Germany had published on the *Maine*.



The people voiced in the Spanish newspapers were predominantly military personnel (22.4%), followed by politicians (17.8%), experts (15.9%), and Sigsbee (12.1%). One might have predicted that Spanish papers would rush to blame an internal cause, but this would have led to further diplomatic tensions between Spain and the U.S. in light of the already existing ones. Rather than presenting a mirror-image to the jingoistic yellow press in New York (which was re-printed or paraphrased widely in other national newspaper corpora) that sought to direct blame to the U.S., Spanish newspapers, by and large, took Sigsbee's call to "suspend opinion" (44.8%) quite seriously and, like no other national press in our corpus, exercised restraint and moderation in shaping public and published opinion, at least during the initial phase after the explosion (<cite data-cite="6095605/Z8D4MCP8"></cite>, 88-89).


On February 19, Spanish newspapers began to refer to reports from Cuba that there were no dead fish in the harbor of Havana, indicating that a torpedo could not have destroyed the *Maine* and that, therefore, it must have been an accident. Toward the end of the news cycle that we studied, the "no dead fish in the water" news item spread from Spain to various Dutch, (regional) American, Mexican, and German newspapers. On February 20, 1898, stories on the investigation commission, the arrival of divers, including those sent by the *World* and the *Herald*, and the tensions over the authorization to inspect the wreck's hull by the Spanish colonial government or the American Consul dominated the Spanish press. Another piece of news was the Spanish Council of Ministers meeting and the diplomatic exchange with Washington. Through its correspondents, *El Imparcial* dedicated its main article to the session in the United States Senate and to the participation of Senator Mason, who maintained the theory of a direct attack. The report also referenced the existence of a group of jingoes who sought war and, in the following days, became the object of attention in the Spanish media, intending to discredit them.


*El Correo Militar* exemplified a typical editorial change in the views of the Spanish press, which claimed different positions on different days. In the following example, it can be seen that the newspapers’ first shift (one day’s edition) argued that the explosion was an accident, while in the second shift (the next day’s edition), the same paper claimed it was an attack:


>En la cuestión con los Estados Unidos, ya se sabe: Turno par: (el de ayer. Véanse EL Imparcial, etc.) <Todo va perfectamente. El Gobierno de Washington y la prensa sensata han convencido á las gentes de allá a un accidente casual. No irán más buques norteamericanos á Cuba. Para investigar las causas de la catástrofe, procederán de acuerdo las comisiones española y americana. Se debe confiar en que todo termine satisfactoriamente.> Turno impar: (el de hoy. Véanse los susodichos periódicos) <El espíritu más belicoso domina entre los yankees. La idea de que lo del Maine fue intencionado cunde entre las masas. La convicción general es que viene la guerra. El Gobierno de Washington prepara más buques y dispone tropas. Se aproximan graves sucesos.>


>“On the question with the United States, it is already known: One day: (yesterday's. See El Impartial, etc.) <Everything is going perfectly. The Government of Washington and the sensible press have convinced the people there to a chance accident. No more American ships will go to Cuba. To investigate the causes of the catastrophe, the Spanish and American commissions will proceed in agreement. It must be trusted that everything ends satisfactorily.> The odd day: (Today's. See the aforementioned newspapers) <The most bellicose spirit dominates among the Yankees. The idea that the *Maine* thing was intentional is spreading among the masses. The general conviction is that war is coming. The Government of Washington prepares more ships and has troops. Serious events are coming.>” (google.translate)



In the days following, the press consistently alternated between certainty that it was an accident and how Americans were more inclined to believe in the attack hypothesis. A vital news focus was the report of what the North American and European press wrote and the pending investigation of the causes of the explosion. Between this moment and the end of March, the Spanish press started to talk seriously about an imminent war (<cite data-cite="6095605/Z8D4MCP8"></cite>, 89).



### United States of America


Newspapers from the United States often referenced politicians (17.3%), military personnel (16.8%), and Sigsbee (16.1%). By and large, 40.9% of American newspapers leaned toward a deliberate attack as the cause of the explosion. 30.7% of the opinions leaned toward an accident, while 28.4% asked readers to suspend their opinion. Our data also indicates that the American press and public relied on and emphasized what Captain Sigsbee had to say on the cause of the events in Havana harbor (24.3%). That about two-thirds of the American press initially hesitated to blame Spain for the loss of the *Maine* was primarily due to the reprints of Sigsbee's note of caution following the explosion that "public opinion should be suspended until further report." The first telegram Sigsbee sent to the Secretary of the Navy read: "Maine blown up in Havana harbor at nine forty tonight and destroyed. Many wounded and doubtless more killed and drowned. Wounded and others on board Spanish man-of-war and Ward Line streamer. Send light house tenders from Key West for crew and the few pieces of equipment above water. No one has clothing other than that upon him. Public opinion should be suspended until further report. All officers believed to be saved. Jenkins and Merritt not yet accounted for" (cited in <cite data-cite="6095605/ZX5QAL9Y"></cite>, 117-18).


After the loss of the *Maine*, the American public (or at least the press) was so anxious to learn more about Sigsbee's opinion on the cause of the explosion that rumors spread widely and quickly. One news item that repeatedly appeared in our data set is that Sigsbee sent a secret telegram to the Secretary of the Navy in which he blamed a torpedo, based on the observation of an eight-inch hole in the wreck of the *Maine*. The New York yellow press "published a cablegram allegedly sent by Captain Sigsbee to the Secretary of the navy in which the commander stated that he knew the explosion was not an accident. Supposedly, the assistant secretary of the navy, Theodore Roosevelt, concurred with Sigsbee's conclusions. There was only one problem with the story: the communication was a fabrication" (<cite data-cite="6095605/6DQ7MKZ3"></cite>, 148, cf. <cite data-cite="6095605/P97L8XTZ"></cite>, 65). We were able to trace this "fake news" in the press by checking and counting the contexts in which the words "Sigsbee" and "opinion" occur in our corpus. Some papers printed the fabricated "attack telegram" by the Captain of the *Maine* as news, whereas others marked it as a rumor. Our data show that the fabricated Sigsbee telegram circulated almost exclusively in the United States, constituting about 20% of the articles that mention "Sigsbee" and "opinion."



 Journalists and the public, in general, reacted to the sinking of the armored cruiser in Havana harbor with a relatively clear sense that this event could lead to war between the United States and Spain, depending on the cause of the explosion. As has been well-documented, the yellow press reacted in horror and disgust in the morning editions on February 16, 1898. Next to an illustration of an exploding battleship anchored over a mine in Havana harbor, Hearst's *Journal* reported: "The Warship *Maine* was Split in Two by an Enemy's Infernal Machine," leaving no room for the possibility of an accident on board the ship. Ivan Musicant and other historians and commentators have assumed that an inflammatory press picked up the battle cry "Remember the *Maine* . To Hell With Spain!" which resonated with a newspaper-reading public that had already developed sympathy with the Cubans who were fighting against a cruel Spanish colonial regime, especially after 1895, through increasingly one-sided press reporting (<cite data-cite="6095605/4YQQCH7A"></cite>). According to this historiographic narrative, after the *Maine* incident, American public sentiment rose in revenge against Spain, and as a result, relations between the two countries quickly soured, and tensions increased continuously. Joseph Wisan, in his study of New York journalism from 1895 to 1898, has also argued that the press played a significant role in preparing the ground for military intervention in Cuba and thus for war with Spain (<cite data-cite="6095605/8KWJRM5V"></cite>). Siding clearly with the efforts of the Cuban revolutionaries (although still undecided about the island's political future), parts of the New York yellow press framed the explosion of the *Maine* as a deliberate attack and called for war almost immediately (<cite data-cite="6095605/8KWJRM5V"></cite>, 34, <cite data-cite="6095605/ZX5QAL9Y"></cite>, 122-23). This was not the first time that the yellow press had done so. Given the biased and sensationalist reporting on the Cuban situation in previous years, the call for war fit neatly into an already established discourse in which Spain was the antagonist, the Cubans were oppressed people fighting against monarchical misrule, and the United States the potential hero that could step in either under the banner of "revenge" or "humanitarian aid," while securing its economic, political, and strategic interests in the region and globally. The *Journal* and other papers that engaged in sensationalist reporting saw the sinking of the *Maine* as yet another indication of the inevitability of a regime change in Cuba and increased publication numbers, page numbers, and expenses for generating news. Wisan explains: "During the week beginning February 17, the *Journal* devoted an average daily space of 8½ pages to the *Maine* – news, editorials, and pictures. It sent the yachts *Buccaneer* and *Anita* and the tug *Echo* to Havana and massed at the Cuban capital its group of special correspondents [...]. It offered a reward of fifty thousand dollars" (<cite data-cite="6095605/8KWJRM5V"></cite>, 390) for finding the perpetrator of the explosion, thereby denying that the incident could have been accidental. The yellow press repeatedly proved that it cared little for truthful accounts of reality. As if the investigation on the *Maine*'s wreck did not matter, the *Journal* declared that a mine had caused the explosion on the day divers were to inspect the site (<cite data-cite="6095605/ZX5QAL9Y"></cite>, 124).





It is often overlooked, however, that the two leading New York yellow papers did not initially agree on the causes and consequences of the destruction of the *Maine* and reacted quite differently to the event. While the *Journal* had wanted war with Spain, was in favor of the independence of Cuba for a while, and considered the explosion to be the proverbial straw that broke the camel's back, the *World* reacted with more restraint when it came to blaming Spain and calling for military intervention (<cite data-cite="6095605/8KWJRM5V"></cite>, 393-94). Other New York papers, especially those critical of the jingoism expressed by the sensationalist press, sought to separate the *Maine* incident from an intervention into Cuba. By and large, the *Sun*, the *Evening Post*, the *Tribune*, and the *Times* accepted the accident theory and, to varying degrees, denounced the warmongering of parts of the American press (<cite data-cite="6095605/8KWJRM5V"></cite>, 396-99). In line with historians who emphasize the role of the (American) press in McKinley's decision to declare war on Spain, Wisan concludes that "though the destruction of the *Maine* did not plunge the nation into immediate war, it created a situation from which escape without war was well-nigh impossible" (<cite data-cite="6095605/8KWJRM5V"></cite>, 400). This assumption is only partly true. Wisan's deep dive into New York journalism at the end of the nineteenth century offers essential insights into a media landscape that was highly relevant and visible as can be seen by the amount of coverage of the New York press as American press in European papers at the time. However, other studies of American journalism at the time indicate a much broader and varied spectrum of reporting than the scene in New York studied by Wisan. While the yellow and traditional New York presses still held particular importance, not least because of its international reception and citation, Harold J. Sylwester, George Auxier, and others have shown the diversity of opinions on the prospect of war and, significantly, the hostility of many Midwestern newspaper editors towards the sensationalist and increasingly powerful yellow press in New York, whose circulation and hence political capital was increasing steadily.


The *Indianapolis Journal* was a typical Midwestern paper that exemplified the more cautious and restrained position that part of the American press took after the destruction of the *Maine*. For instance, their reporting on what was known about the explosion on February 18, 1898, is comparatively objective and leveled, without engaging in sensationalism or jingoism. There is no sense of information suppression. The paper attempts to identify various rumors, and the reporting includes several sources, opinions, and angles on the situation in Havana, Washington, and Madrid that were available three days after the explosion.

```python description="The *Indianapolis Journal*, February 18, 1898; digital facsimile, front page." tags=["figure-6"]
from IPython.display import IFrame

src = 'https://chroniclingamerica.loc.gov/data/batches/in_bradlaugh_ver02/data/sn82015679/0041566574A/1898021801/0483.pdf'
metadata={
    "jdh":{
        "module": "object",
        "object": {
            "type": "image",
            "source": [
                "figure 6: The *Indianapolis Journal*, February 18, 1898; digital facsimile, front page."
            ]
        }
    }
}
display(IFrame(src, width=1000, height=550), metadata=metadata)
```

It is particularly interesting to note how this regional paper, as with most dailies published in the United States during the late nineteenth century, included the reception by the foreign press, which newspapers received through the growing international cable system that facilitated a more rapid exchange of information. For instance, the *Indianapolis Journal*, featuring foreign reactions to the sinking of the *Maine* quite prominently on pages one and two, wrote about the British press reaction: "The provincial morning newspapers make comment [sic!] similar in tone to those of the London morning, and the London afternoon newspapers devote much space to the disaster" (*Indianapolis Journal*, February 18, 1898, p.2). This illustrates how well-connected the American press was at the time and how well-regarded the United States' international reputation was, especially in Europe, indicating where national support of European countries in a possible conflict between the United States and Spain might fall.




Similar to the diversification of opinions in American newspapers, the reactions to the *Maine*'s sinking from non-Spanish newspaper offices in European countries were also far from unanimous. Despite various ideological and regional differences, most conservative editorials in Europe had been rather critical of U.S. military interventions since the Mexican-American War (1846-1848) and hence tended to side with Spain in the emerging conflict with the United States; whereas liberal and progressive/socialist voices in the press tended to be more pro-American (<cite data-cite="6095605/BLSHWQQ2"></cite>, 84, <cite data-cite="6095605/9BE9UPNJ"></cite>, <cite data-cite="6095605/E3FNKKMA"></cite>). In most European countries, the reactions to the explosion reflected the political direction of the respective paper, which, similar to the newspaper scene in the United States, was affiliated with a particular political movement, faith, or economic sector. While one can detect transnational similarities between how certain political interest groups in different European countries reacted to the news about the *Maine*, specific national perspectives on the ensuing conflict are recognizable in the digitized newspaper data collected for this study.


### Great Britain


The U.K. was the only major power in Europe that sided openly with the United States. The newspapers from the British Isles included in our corpus provided extensive reporting on the events surrounding the events in Havana harbor. Overall, the first reports in the British press printed details that came from various telegrams from the United States, Spain, mainland Europe, and Cuba (including Sigsbee's note of caution) as well as from American newspapers and special correspondents in various locations.  Several newspapers referenced the New York yellow press, e.g., the London-based *Daily News* blamed Spain solely. Other newspapers, such as the *Glasgow Herald*, emphasized the "Bravery of Spanish Seamen" (February 17, 1898) who came to aid the American sailors after the explosion. Furthermore, some newspapers compared the sinking of the *Maine* to similar events that had occurred in British naval history to relate the severity to their readers. In the first few days after the incident, the British press leaned on the side of the accident hypothesis, mainly because the ship did not sink immediately, while also stating that the cause of the explosion needed further investigation. Sigsbee was the most often quoted voice concerning the cause of the explosion (22.2%), followed by military personnel (13.9%) and experts (11.1%). These actors generally asked the public to suspend opinion (61.1%), and some voices leaned towards an accident (27.8%). British papers also expressed a general concern about the necessity and inevitability of war between the U.S. and Spain in the first days after the explosion.


In the following days, reports became longer and attempts to convey the human tragedy of the explosion increased. Articles on how politicians in Washington and Captain Sigsbee tried to quell rushed calls for war with Spain also appeared in numerous papers. Furthermore the British press amplified the sympathy expressed by Cubans and Spaniards for the loss of lives and materials and the respect that was given to the dead American soldiers. The subtext underlying this reporting was that the explosion did not constitute an intentional act of war but rather a tragic accident. On February 18, the *Daily News* claimed that all signs pointed in the direction of an accident and that the American press was initially quite actively engaged in suppressing calls for war with Spain.


On February 19, the news cycle shifted towards various condolences and the funeral for the lost sailors. In addition, the British press began to report extensively on the Spanish plan to send the battleship *Vizcaya* to New York City on a "friendly" visit, which was considered a sign of increasing tension between the United States and Spain. Also, on the day of the funeral, there were first reports about a torpedo hole in the wreck of the *Maine* in newspapers in the U.S. British readers further learned that the American public was increasingly convinced that war was coming, as was indicated by reports of an increase of young American men signing up for military service.


The following news week (starting Monday, February 21) began with British papers relaying the latest information on the *Maine* incident, including the selection of divers investigating the cause and the different hypotheses (accident vs. design) discussed in political and media circles in the United States. The reporting was now integrated into other international news, even though the imminent danger of war was voiced and caution was called for repeatedly. Shifting away from the accident hypothesis, the British press began to present increasing evidence for the torpedo theory and to report on the attendant shift toward war in American public opinion: "The belief most widely held by the outside public is that the ship was blown up by a mine." (*Glasgow Herald*, February 21, 1898).


Overall, the British press proved comparatively well-informed about political developments and the media discourse in the United States (and to a lesser extent in Spain). Our data indicate that their access to various cable and news services as well as to the leading New York and Washington newspapers, yellow and more traditional, was extensive, and hence allowed them to present their readers with the latest news on the events occurring during and after the explosion of the *Maine*. The amount of detailed information about the event that readers in the U.K. received differed significantly from that in other European countries, primarily due to news censorship in countries such as Germany and Austria-Hungary.



### Germany


German newspapers relied almost exclusively on A.P. sources through London, Washington, and New York in addition to some reports from Cuba and Madrid immediately following the explosion. While initial reports after the sinking of the *Maine* remained uncertain about its cause, German newspapers soon concluded that it had to have originated internally and, therefore, was not caused by Spain. In addition, most of the editorials rejected U.S. military interventions on legal and moral grounds. Commentators first mourned the loss of a fine cruiser and then quickly criticized how the American yellow press employed the incident to fan the flames of war (<cite data-cite="6095605/E3FNKKMA"></cite>, 76-78). Instead of siding with Spain, the German press propagated a neutral stance while failing to report on Germany's own imperial ambitions  in the conflict between Spain and the United States (<cite data-cite="6095605/E3FNKKMA"></cite>, 83, <cite data-cite="6095605/6KQ8G8UC"></cite>, 144-48, <cite data-cite="6095605/CAHH74FZ"></cite>).


Although the German press purported to stay neutral, our data show a clear tendency towards the accident hypothesis and towards amplifying Sigsbee's note of caution. Newspapers in Germany re-printed Captain Sigsbee’s call to "suspend opinion" more frequently than any other nation in our corpus. It is also interesting to note that they relied far less on expert opinions or those of politicians but rather on those by Sigsbee (21.4%) and survivors (35.7%). In addition, no other group of papers available to us from different countries seemed as interested in the opinions of eyewitnesses as the German one. This reliance on survivor testimony and the high frequency of re-printing Sigsbee’s call to suspend judgment tied in with a comparatively strong leaning towards the accident hypothesis (50%) in the digitized German newspapers.


Most of the initial German newspaper reports attributed the explosion to an internal combustion in the bunkers of the *Maine*. The editorial section of an article on the explosion in the *Neue Hamburger Zeitung* was unusually clear about the (unconfirmed) *Schadenfreude* among Spanish circles in Havana and Madrid about the loss of an American warship. On February 18, most German newspapers stressed the message of condolence sent by the German Emperor, and the sampled data indicates that most papers expressed the opinion that the explosion could only have originated inside the *Maine*. The *Hamburger Anzeiger* reported on the torpedo hypothesis that had been gaining traction in Washington and New York and added that if this were proven accurate, then war between the United States and Spain would be inevitable. The *Berliner Tageblatt* declared the discovery of the *Maine*'s wreck hole, which could only be attributed to a torpedo hitting the ship, as a rumor. According to this Berlin newspaper, most first-hand accounts by surviving soldiers agreed that the explosion was caused internally. On February 19, German newspapers reported on the funeral and again on how eagerly German officials had expressed their condolences to various members of the U.S. government. In hindsight, it is clear that the German press served as a mouthpiece for seemingly noble official acts while being largely silent on the issue of German involvement in a possible Spanish-American war.



On February 21, many papers discussed the two explanatory approaches and discarded the torpedo hypothesis because of the lack of dead fish in Havana harbor that would naturally occur when a torpedo or mine detonates. In addition, German papers provided information on the imminent “friendly” visit of the *Vizcaya* to New York and the debate about who would lead and participate in the official investigation of the wreck. On February 22, the *Hamburger Nachrichten* again discussed various aspects of accident and design theories, landing clearly on the side of the former. Most German papers cited the leading New York papers, including the *Times*, the *Journal*, the *Herald*, and the *World*, when they reported on how the event was seen in the American press and, by extension, the American public. The *Berliner Tageblatt* proved especially critical of the "jingo press" that made its readers believe that a (Spanish/Cuban) torpedo was responsible for the sinking of the *Maine*, with war being the only option for the U.S. to avenge this humiliating act.



### The Netherlands


The Dutch press also picked up the topic of the *Maine* on February 17 by re-printing telegraphic reports on the explosion itself and the number of missing sailors known at the time. The *Algemeen Handelsblad* from Amsterdam, one of the first papers in the Netherlands to report on the event, speculated that the explosion was internally caused (and not by a torpedo) because the cruiser did not sink immediately, an opinion that was echoed and repeated in other Dutch papers. In the following days, the reports on the *Maine* became more elaborate, although they still relied on telegrams relaying basic information about the event. On February 18, the *Algemeen Handelsblad* and other Dutch papers attempted to absolve Spain from actively pursuing the bombing of the *Maine* by pointing out how the Spanish navy and colonial government came to help the survivors of the American ship. On February 19, the peak day of reporting, most newspapers reported on a Reuter's telegram about an 8-inch hole discovered near the keel of the *Maine*, indicating the possibility that the ship was sunk intentionally by a torpedo or an underwater mine placed and operated on behalf of Spain. In contrast to other national presses, however, this information was not marked as a rumor but as fact. Rather than solely relying on telegraphic reports, editors and journalists now also included what newspapers in the United States, especially the *Journal* and *Herald*, featured in their reporting. Many Dutch papers considered the jingoistic New York yellow press, with its early amplification of the torpedo theory, as an expression of American public opinion beginning to become more bellicose. As stated above, the re-printing of news items from American yellow papers is why a comparatively high number of voices of journalists in the Dutch press leaned towards the attack hypothesis.

```python description="Digital facsimile of Rotterdamsch Nieuwsblad, February 19, 1898" tags=["figure-7"]
from IPython.display import IFrame

src='https://resolver.kb.nl/resolve?urn=ddd:010177239:mpeg21:pdf'
metadata={
    "jdh":{
        "module": "object",
        "object": {
            "type": "image",
            "source": [
                "figure 7: *Rotterdamsch Nieuwsblad*, February 19, 1898; digital facsimile. "
            ]
        }
    }
}
display(IFrame(src, width=1000, height=550), metadata=metadata)
```

Such rather detailed articles appeared mostly in metropolitan papers from Amsterdam, Den Haag, and Rotterdam, whereas most regional papers (e.g., the *Venloosche Courant*) only reported on the explosion on February 19, 1898. Beginning on February 20, Dutch news on the *Maine* became shorter and less frequent as they focused mainly on the explosion's aftermath, such as the number of casualties or the pending investigation of the wreck, rather than on the possible cause. Overall, as Bootsma concludes, "[d]espite the ideological diversity of the Dutch press, most papers fitted into the almost general European pattern (British newspapers excepted) of condemning the American intervention in Cuba" (<cite data-cite="6095605/9BE9UPNJ"></cite>, 40). In the first week after the sinking, Dutch papers did not rely on survivor or expert testimony at all, which is in stark contrast to German-language reporting and other national presses at the time. Military personnel (27.8%) and journalists (16.7%) were the most vocal actors in the press, while Sigsbee and politicians appeared less prominently (11.1% each). In addition, our data support Bootsma’s ideological diversity assumption in the Dutch press by an almost even distribution of published opinions that favored an accident (46.7%) and those that claimed it was a deliberate attack (40%).


### Finland


Our newspaper corpus on the *Maine* exposes various details about the Finnish press and the transatlantic dissemination of knowledge. The news appeared first in Helsinki and from there spread to smaller cities and towns. Although the number of newspapers written in Finnish was higher, the Swedish-language press, especially *Hufvudstadsbladet*, was the first to publish extensive reports about the explosion. Moreover, *Hufvudstadsbladet* appeared to dominate the internal dissemination of knowledge about the explosion because various newspapers referred to the reports published in this newspaper. In addition, the explosion of the *Maine* is a telling example of how the transmission of knowledge operated concerning an occurrence that took place far removed from, yet linked to, Finland. The efficient reporting of the event indicated that the Finnish people saw it as relevant and exciting news.  Moreover, the Finnish press also discovered a national connection with the case, as they began to speculate that Arthur Brofeldt, a Finnish citizen who had emigrated to the United States, was serving on the ship as Chief Gunner’s Mate and died during the explosion. In addition, and in contrast to other countries, Finnish newspapers mainly relied on expert testimony (60%). Sigsbee's note of caution is not mentioned at all. Nonetheless, most papers argued it was an accident (81.3%), which is a significantly higher number than in any other national press sampled for this study.


### Mexico


The Mexican news coverage showed both idiosyncrasies and similarities with other national presses. For instance, it differed from others in the fluidity and fast communication between continents. The reception of telegrams in Mexican news offices generated a lot of political confrontations that were in part fed by the clear and comparatively open stances of newspapers that covered the story. At the end of the nineteenth century, Mexico City was well-connected to the conduits of global information flows. Due to its geographic location and a recent push to extend telegraph lines in the Western Hemisphere, Mexico was connected to Havana and Jamaica via a submarine cable and landlines to the United States. The emerging confrontation between the U.S. and Spain over hegemony in the Americas accelerated the telegraphic line's expansion in Mexico, which was part of a more extensive network of communication than, for example, that which existed in Germany, a country that relied primarily on Anglo-American news sources. Another interesting point in this context is that in the last decade of the nineteenth century, the press in Mexico was made up of a range of newspapers that represented not only the interests of various national or political groups but also those of foreign communities living in Mexico, notably the Spanish and the North American (<cite data-cite="6095605/7Z2NPNMZ"></cite>, 258).


Overall, the opinions voiced in the Mexican press tended towards an accident (50%), while voices asking for suspension of opinion (26.1%) and those claiming an attack (23.9%) made up the rest. Mexican newspapers represented a comparatively balanced number of voices, especially Sigsbee (16.7%), politicians (15.6%), military personnel (13.3%), and experts (16.7%). Interestingly, we find both positions (accident and attack) distributed almost equally among the politicians whose opinions were printed. The rest were unanimous voices in favor of the accident hypothesis. In the case of Sigsbee's opinion, we found evidence of the circulation of the fabricated telegram showing the connection of some of the Mexican papers with the news sources in the United States.


In the days following the explosion of the *Maine*, the Mexican press featured opposing versions concerning its cause. For instance, *El Correo Español* published its anti-American stance in its editorials bluntly and openly by favoring the accident hypothesis. Yet, different accounts about what happened came from New York, whose press broadly and quickly concluded that it was a targeted Spanish attack from Cuban soil. Soon, Mexican newspapers were filled with rumors and arguments for and against the two positions.

```python description="The *Mexican Herald*, February 17, 1898; digital facsimile, front page." tags=["figure-8"]
from IPython.display import IFrame

src='https://hndm.iib.unam.mx/consulta/resultados/visualizar/558a33207d1ed64f16908db9?resultado=14&tipo=pagina&intPagina=1&palabras=Maine#bajar'
metadata={
    "jdh": {
        "module":"object",
        "object": {
            "type":"image",
            "source": [
                "figure 8: The *Mexican Herald*, February 17, 1898; digital facsimile, front page."
            ]
        }
    }
}
display(IFrame(src, width=1000, height=550), metadata=metadata)
```

In addition, more details about the tribulation, the *Maine*'s physical characteristics, and the time of service, among other aspects, were published. Many articles referenced Captain Sigsbee's statements to the press and the confrontation between his version of the facts before and after the explosion. Mexican newspapers consistently offered competing explanations about the explosion, both official ones and those from the case's investigative group, who reported on how Spanish authorities had intercepted Captain Sigsbee's communications to and from the United States. There was also quite a bit of concern in the Mexican press because Spain had initially refused to allow American divers and experts to enter Havana harbor to inspect the *Maine*'s wreck. The newspapers also included satirical and mocking columns, usually on the margin of the official news. The Mexican press, influenced by the French and Spanish press, published opinion pieces like those in *Croniquillas* (a diminutive for chronicle), defined as gloss of a fact, of an event, that not only informs but judges and values (<cite data-cite="6095605/E44KKNDN"></cite>, 146). Professional literary writers usually wrote these in a flexible style to show their point of view and their ingenuity.


During this study's investigation period, those who sympathized with Spain tended to be more active in the press than those who favored the American side. For instance, several prose pieces, poems, and songs dedicated to Spain appeared in the Mexican press. Many of these literary texts also displayed a sense of *Schadenfreude* at seeing the *Maine* sunk. Other newspapers publicly sanctioned some positions, and the *Correo Español* was asked to retract what they had published.



>“If I was to speak frankly, of course I’ve felt the deaths
>from the explosion, but I don’t think is wrong that the Maine went down.
>This lost for someone with so much money is nothing.
>Is like picking a hair from a pig.” (*Continente Americano*, February 20, 1898)


Notably, these two publications, under the title "Thoughts from *El Correo Español* about the *Maine* disaster," aroused the publication of protest stories because of the "outrageous" demonstration of Spanish "nobility." Newspapers, such as *Continente Americano*, edited in Mexico City, published a story on February 20, 1898, in which it explained that they refused to print some texts coming from Spain because of their high content of "rude language" and lamented the "vengeful spirit" of the received telegrams. *La Voz* and *El Imparcial* also published their opinions about the distasteful and inconvenient publication from the Spanish press. In response, *El Correo Español* published the following:


>*El Mundo y El Imparcial*,
>Que muestran su amor a España
>Cuantas veces se presenta
>La ocasión para alabarla,
>Con el asunto del “Maine”
>han dejado bien sentada
>su reputación de …. Sables,
>por no usar otra palabra.
>Su información es tan sólo
>De Cayo Hueso y de Tampa,
>Y por lo mismo insurrecta,
>Y por lo mismo muy mala.
>Hora es ya que se comprima
>la prensa subvencionada;
>hora es ya que se presente
>noblemente y cara á cara,
>para que todos sepamos
>si es ó no amiga de España.
>Porque nunca ha sido noble
>valerse de malas mañas,
>como hace todos los días
>la prensa subvencionada.


>“*The World* and *The Imparcial*,
>Who show their love to Spain
>How many times does it show up?
>The occasion to praise her,
>With the matter of the "*Maine*"
>they have left well seated
>its reputation for... sabers,
>not to use another word.
>Your information is only
>From Key West and from Tampa,
>And for the same insurgent,
>And for the same very bad.
>Time it is already compressed
>the subsidized press;
>time is now for it to show up
>nobly and face to face,
>so we all know
>whether or not she is a friend of Spain.
>Because she has never been noble
>make use of bad habits,
>like she does every day
>the subsidized press.” (google.translate)


American newspapers in Mexico, including those that tried to portray neutrality, refrained from publishing these literary forms when covering the events. However, one can easily detect an increase in opinion pieces about the diplomatic crisis that were in favor of American hegemony in the region and that argued for the need for the U.S. to intervene on the island as it saw fit, without authorization from Spain.


## Conclusion: Remember the *Maine*?


Although largely forgotten in public education and imagination, the Spanish-American war played an essential role in changing the imperial guards in the Western Hemisphere. After a brief war of only four months, the United States had not only acquired control over Puerto Rico, Hawaii, Guam, the Philippines, and Cuba but had also asserted its role as the regional superpower and as a new and aspiring player on the international scene. The explosion of the *Maine* on February 15, 1898, is seen by historians as the point of no return on the imperial path for the U.S. While war sentiment was still relatively low immediately after the explosion, voices calling for armed intervention in Cuba grew in numbers and strength consistently during the spring of 1898. In light of a public geared up for military intervention in part by a warmongering yellow press and driven by political and economic interests, President McKinley decided to take the United States to war with Spain over its remaining holdings in the Western Hemisphere. In the months following the declaration of war against Spain, the American press reflected and amplified public opinion in the United States that was increasingly in favor of military intervention. By January 1898, the press and the public had sympathized with the cause of Cuban independence, yet there was relatively strong disagreement over the right course of intervening in the conflict on the island. This sentiment began to shift towards war only after the sinking of the *Maine*, which remained an important reference point in the international press, especially in American papers, in the two months leading up to the outbreak of war. After the time window analyzed in this article (February 16-23, 1898), the slogan "Remember the *Maine*, (to hell with Spain)!" began to circulate throughout U.S. newspapers and was often cited and commented on in various international papers. This call for mobilization intensified, especially after the investigative committee's report was published on March 28, 1898, which attributed the cause of the explosion to a mine while remaining silent on who placed it. By the time Spain and the United States declared war on each other (on April 19 and 25, respectively), the American press was by and large behind the national cause of freeing Cuba and securing American interests in the region (<cite data-cite="6095605/ZX5QAL9Y"></cite>, 145-46).


Our data-assisted approach to studying international reactions to a seminal event illustrates how national presses used specific authorities (e.g., military members, survivors, or politicians) to present certain opinions that served varying interest groups. When we look at how actors and their opinions on the incident are represented in newspaper data, we get a clearer sense of how the print media shaped and reflected public opinion about the sinking of the *Maine* across the countries studied. We can conclude that except for the yellow press in the United States, there was no immediate call for war in the U.S. or the international press by politicians or experts, primarily because of Captain Sigsbee's note of caution that circulated in almost all the newspapers in all countries. Another relevant conclusion is that the press shaped local public opinion by the voices it reproduced and how often they were frequented. Notoriously, the U.S. press reported on both the attack and accident hypotheses through a plurality of speakers. In Spain's case, the attack position came from reports from politicians in the United States or the reaction of Spanish politicians to what was said in Washington, as well as reports on what was circulating in the American press. By contrast, the possibility of it being an accident came from experts, military personnel, and survivors. The relative uniformity of the sources used for the U.S. case contrasts with the multiple voices used in the Spanish, and it shows how uniformity among those who supported the attack hypothesis skewed the information in favor of the accident hypothesis. With regard to countries with less interest in the conflict between Spain and the United States over Cuba, the sources tend to be less confident, with the extreme case being Finland, whose newspapers relied exclusively on experts. This may reflect different causes in each country, from the informative interest at the local level of the event to some political bias, to local journalistic practices and access to international news.


Our analysis of international news coverage of a particular historical event presents several advantages over more conventional research methods while also being prone to limitations. Previous research projects have often relied on scholars spending time in physical archives, which was often necessarily limited to a single country or even a specific region or city. The increasing availability of digitized newspapers and information technology allows greater access to material previously only available in print and tools that can further help historical research in addition to already existing methods. While there are still many obstacles for scholars engaging with digital newspaper archives–ranging from a lack of access to specific papers owned by profit-oriented institutions to challenges involved in the computational processing of newspapers as data–the new access to historical information facilitated by newspaper archives and other data providers has generated new opportunities for research in the Humanities, yet always constrained by the library’s selection and digitalization methods and policies. The hybrid methods employed in the present research project, albeit still limited in the degree of automation and flexibility, have enabled the recognition of outliers and patterns in the data that would otherwise have been impossible or at least very difficult to detect. In addition, the transnational cooperation of scholars from various Humanities and Computational disciplines to study journalistic representations of an event with global repercussions has facilitated the inclusion of diverse viewpoints and approaches.


Finally, the present study has offered insights into the self-referential nature of the international press system at the end of the nineteenth century. With our scalable method employed in studying newspaper data from that period, we were able to illustrate how certain newspapers paid attention to what happened in other countries through their newspapers, how they reacted to specific events of international scope, and how these were perceived at home and abroad. In doing so, many newspapers created and built upon already existing enemy and ally images; their gauging of public opinion in other countries in and through newspapers played a crucial role in foreign policy-making, as the case of the United States, and the willingness of its national community at the time to engage in military conflict, makes particularly clear.



### Acknowledgments


The authors would like to thank Seyda Akkaya, Ryan Cordell, Laura Martínez Domínguez, Jana Keck, Otto Latva, Laura Angélica López Méndez, Fabiola Delfín Martínez, Jamie Parker, Miriam Peña Pimentel, Rocío Castellanos Rueda, Iván Vladimir Meza Ruiz, Isabel Galina Russell, David Smith, and Ximena Gutiérrez Vásques for their help in preparing this article.

<!-- #region tags=["hidden"] -->
<div class="cite2c-biblio"></div>
<!-- #endregion -->
