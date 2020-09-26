# Opinions

## 1999 - Present  

Data from 1999 to present was gotten from Wikipedia.  

These are the annotated opinions from the Supreme Court. Data in ./raw_wiki_data
represents the data from [these](https://en.wikipedia.org/wiki/Lists_of_United_States_Supreme_Court_cases#By_term_(since_1999))
Wikipedia pages. ./parsed_wiki_data is that data converted into a simpler format
and ./parsed_wiki_data_simpler is the same, only with a simpler breakdown of opinions.
The breakdown is as follows:  
1 - Favorable:  
 - partjoinmajority
 - majority
 - joinplurality
 - partjoinplurality
 - joinmajority
 - plurality
 - concurrence
 - partjoinconcurrence
 - joinconcurrence
 - concurrencewithoutopinion

2 - Unfavorable:  
 - dissentwithoutopinion
 - dissent
 - joindissent
 - partjoindissent


3 - Other:  
 - didnotparticipate

4 - Unclear, requires other explanation:
 - partjoinconcurrencedissent
 - joinconcurrencedissent
 - concurrencedissent
 - concurrencedissentwithoutopinion  

 It is therefore possible for items to be in 1 and 4, in which case they will be
 settled as favorable, or 2 and 4, in which case they'll be settled as
 unfavorable. It is, however, impossible for items to be 1 and 2.

Additional stats can be found in ./additional_stats.  

 ## Before 1999
