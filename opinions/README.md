# Opinions

## 1999 - Present  

Data from 1999 to present was gotten from Wikipedia.  

These are the annotated opinions from the Supreme Court. Data in ./raw_wiki_data
represents the data from [these](https://en.wikipedia.org/wiki/Lists_of_United_States_Supreme_Court_cases#By_term_(since_1999))
Wikipedia pages. ./parsed_wiki_data is that data converted into a simpler format
and ./parsed_wiki_data_simpler is the same, only with a simpler breakdown of opinions.
The breakdown is as follows:   

A - Favorable:  
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

B - Unfavorable:  
 - dissentwithoutopinion
 - dissent
 - joindissent
 - partjoindissent

C - Other:  
 - didnotparticipate

D - Unclear, requires other explanation:
 - partjoinconcurrencedissent
 - joinconcurrencedissent
 - concurrencedissent
 - concurrencedissentwithoutopinion  

Due to the Supreme Court allowing for the jurors to agree with or dissent to parts
of the case, ./full_opinion_list.txt has all of the combinations found in
./parsed_wiki_data, and the value assigned to each. This adhered to the following
rule: the presence of A OR B resulted in 1 or 2. The presence of both ((A AND B) or D)
resulted ambiguous (3), and the presence of C meant did not rule (4).

Additional stats can be found in ./additional_stats.  

 ## Before 1999
