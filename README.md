Project title: Sri Lanka presidential Election 2019 - Sample Opinion Poll Analysis
Research Question: The main purpose of this study is to conduct a public opinion poll on the 2019 presidential election and provide statistical analysis using the collected data. And also identify the burning problems of the society which we are currently facing.
Introduction:
The next Sri Lankan Presidential election will be held on 16th November 2019 and 35 candidates filed nominations for this presidential election. Even though there have 35 candidates only a few of them actively involved with the campaign. The former Defense Secretary Gotabhaya Rajapaksa from the Sri Lanka Podujana Peramuna (SLPP) is one of the front-runner. Another strong contender is Sajith Premadasa, the housing minister in the current government. 
Here we use the following questionnaire to collect data.
https://github.com/randikacse/sl_presidential_election_analyze/blob/master/questionnaire/Sri%20Lanka%20presidential%20Election%202019%20-%20Sample%20Opinion%20Poll.pdf

In this questionnaire, we have collected the people’s opinions about the upcoming presidential election, candidates, burning social problems like questions. Apart from that we also collected classification demographic information such as age group, gender, race, religion, education level, economic level, etc.
To collect samples we have used an online survey method as well as face to face interviews. When we are doing the face to face interview we try to pick a random sample. But since part of the survey was conducted online and not with a random sample(because of only 25.5% population have internet access), the findings presented below cannot be generalized to Sri Lanka. Initially, we expected to collect around 300 random samples, but due to time and resources limitations, we ended up with 206 samples.
 
Results and analysis:
To analyze the collected data we have used R Studio. Using the libraries available in the R we were able to get the following results.
Since this election is one of the major election in the country, the majority of responders willing to use their votes. 
According to the results 89% willing to use their vote in this election.





If the Presidential election is to be held tomorrow, the majority of respondents (70.7%) believe that Gotabhaya Rajapaksa from the SLPP would win. Only 9.4% believe that Sajith Premadasa would win.









Even though more than 70% believe Gotabhaya Rajapaksa from the SLPP would win, only 50.3% gave their preference for Gotabhaya Rajapaksa.

Also, most of the youngsters (18-30 age group) prefer to give their vote for Gotabhaya Rajapaksa.

In the questionnaire, we were given a list of issues affecting the country at present and were asked to select which issue they thought should be the main concern. 48.1% selected corruption and economic growth while 33.7% selected the National security, 3.9% selected living cost.



Even with the recent terrorist attack in the country, the majority of responders selected the economic growth as the major concern. 


The majority of the youngsters (18-30 age group) also have similar concerns about social issues.






According to the last election preference majority voted for Maithreepla Sirisena.









Different classifications by demographic information

Voter by Religion






Conclusion:
According to the above findings, the most burning issue is corruption and low economic growth. the next concern is National security. Therefore the key focus of the campaigns should goto reduce corruption and increase economic growth.

Discussion: 
In this survey, we were not able to collect a truly random sample of the country due to time and resources limitations. Therefore we cannot map this result to Sri Lanka to predict the true outcome of the election. To overcome this issue we expect to conduct more door to door interviews and also hope to use a telephonic survey method to collect samples. Apart from that, in the questionnaire, we keep location fields(electoral district and polling division) as open textbox fields. Therefore some people enter the same name in different ways (due to spelling mistakes, different languages). Therefore it takes extra effort to clean that data. As a solution, we plan to use dropdown like closed input field in next time.

