# Notes
**Voyant**

* Voyant corpus ID: https://voyant-tools.org/?corpus=34e9791a8b147957f44df998456dab50
* <iframe style='width: 637px; height: 163px;' src='https://voyant-tools.org/tool/Phrases/?query=free&corpus=34e9791a8b147957f44df998456dab50'></ifra
  me>

The above section is interesting because it shows different groups of usage for the word "free":  relating to slavery, press, or passages.

* <iframe style='width: 564px; height: 335px;' src='https://voyant-tools.org/tool/Trends/?stopList=keywords-f0753fd4410091128048053659509d49&query=faddy&query=fad*&query=fad&query=%22new%20toys*%22&query=bear&query=bears&query=craze*&mode=&chartType=line&corpus=48d327dd945f1331190cc3dc30fb560f'></iframe>

I wanted to see if, when newspapers wrote about teddy bears, if they often wrote about them in terms of them being "fads." I figured if this were the case, the same newspapers with peaks in mentioning "bear" or "bears" would have similar (although smaller) peaks in words relating to "fad." This seems to be the case for the San Francisco Call, The Sun, and the Minneapolis Journal. 

**AntConc**

I tried to look at some terms related to humour/wit. The one thing I found was that this may be a good way to locate characters or archtypes. For example, when I searched for "witty" there were many instances of "Witty Eppie, the ale-wife." Maybe seaching for other adjectives would find different characters described this way. 

**TopicModelingTool**

I picked the 13th topic I found and made of graph using the top 10-ranked docs in that topic.

**Topic Modelling in R Studio**

[topic model graph with 20 topics](20_topics_over_time.png)

I tried rerunning the topic modelling asking for 20 topics. The large light green section (wi love ye heart thy thee sae) seems pretty significant, although I can't really tell how what the topic is, other than it is something about love. But how is it different from "love dear i’ll heart fair lady true"?

## Errors
`No such file or directory. No urls found`

https://askubuntu.com/questions/1190692/error-when-using-wget-to-download-a-list-of-urls-in-a-txt-file

* Actually means file not found
  * Type name of file without extension (as appears in directory in powershell)
  * Also probably didn't need to use wget for this exercise, just needed URL list
  
* saving plots in R Studio: make sure dimensions are big enough to show whole plot/legend
