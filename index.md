---
layout: page
title: The burst of Brexit bubble
---

{% include_relative _includes/styles.html %}
{% include_relative _includes/scripts.html %}

<!--COVER-->
<img src="/img/cover.jpg" class="img-centered" style="width:100%; height=100%;">

> By Kang Fu, Wanting Li, Shanci Li, Runke Zhou

<!--CHAPTER: BACKGROUD-->
<div align="center">
<font size="3"><h1><b>Background</b></h1></font>
</div>

<div align="justify">
<p> Brexit (a portmanteau of "British exit") is the withdrawal of the United Kingdom (UK) from the European Union (EU) at 23:00 GMT on 31 January 2020 (00:00 CET). Actually, the United Kindom considers exiting the EU ever since 2016. After several referendums and negotiations between UK-EU, they finally exit the EU in early January, 2020. And the withdrawl aggrement finally came into force on 31 January 2020. </p>

<p> Shortly afterwards, the post-brexit scenario has raised concerns about regional integration and economic security both in the UK and the EU in recent years. Hereby we look forward to shed some light on these current issues by a full retrospect of Brexit. We'll dive into 95808 quotations talking about the Brexit from 2016 to 2020, summarize characteristics of relevant speakers, extract underlying top topics behind Brexit, and further analyze the attitudes of UK people throughout the whole process.</p>
</div>
&nbsp;

---
<!--CHAPTER: NETWORK-->
&nbsp;

<div align="center">
<font size="+1"><h1><b>Speakers talking about Brexit most frequently</b></h1></font>
</div>


<!--SPEAKER-->
{% include_relative _includes/Speaker.html %}
<div align="justify">
<p>Let's first catch a glimpse of the top 20 speakers talking about Brexit most frequently. Theresa May, Boris Johnson, Nigel Farage……Looks familiar? Bingo, they’re all influential figures politically active over the last decade.</p>
  
<p>Hereafter we focus on the four most frequent speakers, highlighting their positions and relations with Brexit.</p>
</div>

 
<!--BUTTONS-->

<font size="-1"><i>Click on their photos to see their political position. </i></font><br>
<button class="button" onclick="changeContactPeople('Theresa May')"><img src="/img/theresa.jpg" style="width:40%; height=40%;"></button>
<button class="button" onclick="changeContactPeople('Boris Johnson')"><img src="/img/boris.jpg" style="width:40%; height=40%;"></button>
<button class="button" onclick="changeContactPeople('Nigel Farage')"><img src="/img/nigel.jpg" style="width:40%; height=40%;"></button>
<button class="button" onclick="changeContactPeople('Jeremy Corbyn')"><img src="/img/jeremy.jpg" style="width:40%; height=40%;"></button>

<p id="description">
<b>Theresa May</b> : the most frequent speaker.<br><br>   -<i>Prime Minister of the United Kingdom from 2016 to 2019.</i><br>  -<i>Leader of the Conservative Party from 2016 to 2019.</i><br>  <br><i>Being the leader committed to delivering Brexit, Theresa May started her premiership dealing with Brexit and also ended with it. The outcome of Brexit’s referendum was politically binding on Theresa May despite her having campaigned against leaving the EU. Faced with uncertainty and chaos indirectly caused by David Cameron’s miscalculation, Theresa May had been in the whirl of Brexit, grappling with a number of challenges.</i><br>
</p>


&nbsp;
<div align="center">
	<font size="+1"><h1><b>Nationalities of speakers talking about Brexit</b></h1></font>
</div>
<div align="justify"><p>
	It's also very interesting to analyze where speakers talking about the Brexit come from. This gives us information on people from which country cares about the Brexit.
</p></div>
{% include_relative _includes/Nationality.html %}
<div align="justify"><p>
	After visualizing the top 20 nations talking about the Brexit, it is obvious that most of speakers talking about the Brexit came from developed countries in the world, for example, the United Kindom, the United States of America, Australia and so on. As this event, Brexit, was mostly about the European situation, we can observe that most countries in the top 20 nations talking about the Brexit were from the Europe, which shows that people care about the Brexit are mostly from the Europe.
</p></div>


&nbsp;

<div align="center">
	<font size="+1"><h1><b>Distribution of the Gender of speakers talking about Brexit</b></h1></font>
</div>
<div align="justify"><p>
	Now we are going to analyze the gender of speakers talking about the Brexit.
</p></div>

{% include_relative _includes/Gender.html %}

<!--PIE SENDERS-->
<div id="pie4"></div>
{% include_relative _includes/pie4.html %}

<div align="justify"><p>
	After analyzing the distribution of quotations based on different genders, it's obvious that most speakers pay attention to the Brexit are male. This comforms with the common sense that most people willing to talk about this kind of political event, like the Brexit.
</p></div>


&nbsp;
  
<div align="center">
	<font size="+1"><h1><b>Occupations of speakers talking about Brexit</b></h1></font>
</div>
<div align="justify"><p>
	Let's first have a look at who are the speakers talking about the Brexit most frequently.
</p></div>

{% include_relative _includes/Occupation.html %}

<div align="justify"><p>
	Here you can see the distribution of the number of quotes based on different occupations. The result is obvious that politicians are the kind of people who talks most about the Brexit. This result is not surprising as this event is basically a political event, thus politicians always need to express their opinions to persuade their supporters. Other occupations, for example, journalist, writer, economist and blogger, are also occupations that are highly related with the politics. This explains why these groups of people would like to talk about the Brexit.
</p></div>


&nbsp;
  
<div align="center">
	<font size="+1"><h1><b>Age ranges of speakers talking about Brexit</b></h1></font>
</div>
<div align="justify"><p>
	Let's analyze the distriution of speakers' age ranges who talk about the Brexit.
</p></div>

{% include_relative _includes/Age.html %}
  
<div align="justify"><p>
	Here we can make the conclusion from the above plot that most people caring about the Brexit are in the range between 40 years old to above 70 years old. This can be explained by following two reasons. Firstly, most politicians or people from related fields are in this age range from 40 years old to above 70 years old. What's more, people in this age range are also more concerned about political events than younger people. As you can see, there is a very limited number of quotations come from people youger than 29 years old.
</p></div>

  
&nbsp;
<div align="center">
	<font size="+1"><h1><b>What are people talking about?</b></h1></font>
</div>
&nbsp;
<div align="justify"><p>
  The Brexit was not decided and finished in one moment. It has been last for 4 years. There are numerous issues to discuss and negotiate during the procedure. We are curious about the content of quotations so that we can gain more insight of what the British people care most about Brexit. Here we apply topic detection techniques to get the topic of these quotations. First, we build the tf-idf matrix of the quotations shown in the newspapers and visualize the most frequent ones as below:<p></div> 
&nbsp;
<div align="center">
  <img src="/img/WordClouds_of_Topics.png" class="img-centered" style="width:100%; height=100%;"></div>
&nbsp;
<div align="justify"><p>
  To further analyze the content of the quotations related to the Brexit, we perform the LDA (Latent Dirichlet Allocation) topic detection model. Through the analysis, the model achieves highest coherence when the assigned topic number is 4. The outputs of the algorithm is a distribution among the words in the topic, which means we represent a topic by a distribution of frequent words. This is very useful in recommendation system or information retrieval when we want to calculate the similarity and relation among different quotations. But it can not summarize a topic in a sentence or several meaningful phrases. So we observe the outputs of topic and summarize a topic manually.
</p></div>

<div align="center">
{% include_relative _includes/lda.html %}</div>
  
<div align="justify"><p>
  By sliding to adjust relevance metric and observing the Top-30 most relevant terms inside each topic, we can summarize each topic and analysis the most significant concerns when people talking about Brexit.</p>
  
<p>The first topic covers 29.5% of tokens in the reported quotations. The most meaingful keywords in the topic distribution are: EUR, scotland, northern_ireland, agreement, border, option, soft, extension, priority, discussion, certainty, relationship, withdrawal agreement, farmer, recognise, law, disastrous, transition period. Therefore, we suspect this topic is mainly about the way how Ireland and Scotland would act during the Brexit.</p>
 
<p>The second topic covers 28.4% of tokens and is mainly related to politics. The most meaingful keywords in the topic distribution are: party, election, parliament, labour, leave, tory, boris_johnson, prime_minister, government, referendum, conservative, campaign, british, general election, boris and chance. Therefore, we suspect this topic is about the different attitudes of the all kinds of parties in the UK.</p>
  
<p>The third topic covers 23.6% of tokens. The most meaingful keywords in the topic distribution are: business, market, delay, company, challenge, opportunity, industry, uncertainty, investment, work, london, economy. Therefore, we suspect this topic is mainly the concerns about business and economy after Brexit.</p>
  
<p>The forth topic covers 18.5% of tokens. The most meaingful keywords in the topic distribution are: uncertainty, risk, economy, impact, market, concern, economic, growth, cost, trade, pound, price, business, rise, demand, chaos, worry, sterling. Therefore, we suspect this topic is mainly the concerns about chaos  after Brexit. </p></div>
&nbsp;

<p>
<b>External resource</b>:</p>
<p>For Ireland, the main discussion is on the <b>soft or the hard border</b> with the EU. The impact of Brexit on the Irish border and its adjacent polities involves changes in trade, customs, immigration checks, local economies, services, recognition of qualifications, medical cooperation, and other matters, now that it is the only external EU land border between the United Kingdom and the European Union. After the UK Parliament voted to leave the European Union, all parties said that they want to <b>avoid a hard border</b> in Ireland, due particularly to the border's historically sensitive nature. Border issues were <b>one of three areas of focused negotiation</b> in the Withdrawal Agreement. Following the United Kingdom's exit from the European Union on 31 January 2020, this border is also the frontier between the EU and an external country. The Northern Ireland Protocol of the Brexit withdrawal agreement commits the UK and the EU to maintaining an open border in Ireland, so that (in many respects) the de facto frontier is the Irish Sea border between the two islands. This requires the continued application of the Common Travel Area as well as free trade of goods (including electricity) between Ireland and Northern Ireland. The latter requires the UK to follow EU law in Northern Ireland with respect to these areas, with jurisdiction of the European Court of Justice in the interpretation of the law.</p>
  
<p>For Scotland, after the Brexit referendum, the Scottish Government – led by the Scottish National Party (SNP) – planned another <b>independence referendum</b> because Scotland voted to remain in the EU while England and Wales voted to leave. It had suggested this before the Brexit referendum. The First Minister of Scotland, Nicola Sturgeon, requested a referendum be held before the UK's withdrawal, but the British Prime Minister rejected this timing.At the referendum in 2014,  <b>55% of voters had decided to remain in the UK</b>, but the referendum on Britain's withdrawal from the EU was held in 2016, with <b>62% of Scottish voters against it</b>. In 2017, if Northern Ireland remained associated with the EU – for example, by remaining in the Customs Union, some analysts argued Scotland would also insist on special treatment. However, in the event, the only part of the United Kingdom which received unique treatment was Northern Ireland.
  
</p></div>


&nbsp;
  
  <div align="center">
	<font size="+1"><h1><b>Do UK people regret Brexit?</b></h1></font>
</div>
<div align="justify"><p>
	Brexit has been a truth since 2020. We have come up with an interesting question: do they regret to make the decision of Brexit? We will investigate if there is a altitude shift between 2016 and 2020. Sentiment analysis has been applied to the quotations from UK people using pretrained model. The output is binary including positive and negative about Brexit.
</p></div>
<div align="justify"><p>
{% include_relative _includes/quotation_number.html %}
{% include_relative _includes/quotation_with_sentiment.html %}
{% include_relative _includes/quotation_percentage.html %}</div>
<div align="justify">
<p>At the start of 2016, the number of overall quotations about brexit is very small. Additionally, the altitude of UK people to Brexit is mainly negative. However, there is <b>steep increase number of quotations</b> about Brexit from May to June. The reason is that the UK held a referendum on whether to leave the European Union on 23 June. 52% of voters voted to leave. This is the start point of Brexit. At that time, the percentage of the positive quotations has also increased to over 40%, but still less than negative quotations.</p>
  
<p>After three months, the number of quotation decreases to the level before the Brexit, but it suddenly increase to more than 500 in November. On December, the House of Commons voted 461 to 89 in favour of Theresa May's plan to trigger Article 50 by the end of March 2017.</p>

<p><b>The quotation number is going up since the start of 2017 and reach peak on June 2017</b>. On March 2017, a letter from Theresa May was handed to President of the European Council Donald Tusk to invoke Article 50, starting a two-year process with the UK due to leave the EU on 29 March 2019. Brexit negotiations commenced on 19 June. This also resulted in heated discussion on newspapers. The number of quotations reached the largest during 2017 period. We have noticed that the altitude of UK people toward Brexit fluctuated during this year, but the negative quotation dominates.</p>

<p><b>There is a noticeable rising volatility from April 2018 to May 2019</b>. Meanwhile, the negative quotations are steadily increase during this period. The background event is House of Commons passed the "Leaving the European Union Act", which was passed by the House of Lords in May and signed by the Queen of UK in June. According to the Act, the United Kingdom would withdraw from the European Union at 23:00 on March 29, 2019. The Brexit withdrawal agreement was published on 14 November. After the United Kingdom and the European Union reached a draft Brexit agreement, it caused strong dissatisfaction among opponents. The Brexit Minister Dominic Raab, who had been in office for only four months, resigned on the grounds of dissatisfaction with the draft. The Minister of Work and Pensions, Esther McVeigh, and two other deputy ministerial officials also resigned. Dominic Raab issued a statement saying that he cannot support the draft Brexit agreement "without conscience." He criticized the content of the draft regarding the resolution of the Irish border issue and the continued presence of the United Kingdom in the EU Customs Union. He believed that this would not allow the United Kingdom to truly leave the European Union.</p>

<p>From the graph, we can see that <b>the number of quotation between January 2019 and May 2019 is going up and down</b>. The reason behind it is the first and second meaningful vote are held on the Withdrawal Agreement in the UK House of Commons. The UK government are both defeated. Therefore, Theresa May requested the EU extend the Article 50 period until 30 June 2019. After that, the UK cannot pass Withdrawal Agreement. Theresa May announced that she would resign as Conservative Party leader, effective 7 June, due to being unable to get her Brexit plans through parliament and several votes of no confidence. </p>

<p>On 23 July, Theresa May officially resigned and Boris Johnson accepted the Queen's invitation to form a new government and became Prime Minister of the United Kingdom, the third since the referendum. <b>There is a small rise since July 2019. A noticeable increase in positive quotation from December 2019</b>.The general election held on 12 December. Boris Johnson was invited to form his second government by The Queen, beginning his second term and allowing Brexit to be completed. The Withdrawal Agreement passed its second reading in the House of Commons in a 358–234 vote and it ban the government to extend the Brexit transition period.</p>

<p>On 31 January 2020, at 11 p.m. GMT the United Kingdom withdrawed from the European Union at the deadline set for its departure by the Article 50 extension agreed between the UK and the EU in October 2019, and transitional arrangements began for the period ending on 31 December 2020.</p>
 
<p> From the graph, <b>the negative also dominate the most time from 2016 to 2020</b>. That can also verify that the result of referendum in 2016 is totally unexpected. The Brexit lasts almost 4 years and such a long time can reflect that Brexit received great pressure from the opponents. Most people are actually negative about Brexit, but the leader of government insists on this unprecedented event.</p>
</div>
 
 
&nbsp;

---
<!--CHAPTER: CONCLUSITON-->
&nbsp;

<div align="center">
<font size="+1"><h1><b>Conclusion</b></h1></font>
</div>

<div align="justify">
By analyzing quotations related to the Brexit, we conclude that: <br>

<ul>
- Most of speakers talk about the Brexit came from dominant countries in the world, for example, the United Kindom, the United States of America, Australia and so on.<br>
- Most speakers pay attention to the Brexit are male.<br>
- Politicians are the kind of people that talks most about the Brexit. Other dominant occupations that talks about the Brexit are also highly related to the politics, such as journalist, writer, economist and blogger. <br>
- Most of speakers talk about the Brexit are in the age range from 40 years old to above 70 years old.<br>
- Most of speakers are talking about the political, economic issues and the potential chaos with the Brexit. The Irish boder and the independence referendum of Scotland are two of the main focus during the procedure.<br>
- The sentiment analysis shows most quotations from UK people are negative, meaning that the UK people are regretful to leave the EU. Although the positive quotation rate increase in some specific period, the negative quotation dominates. <br>
</ul>

  <p> The above findings make us think about that Brexit is an international event and most countries in the world will be affected to this event. However, after researching the quotations during this period, the truth may be surprising. Brexit may not reflect all the UK people expectation. The main motivatation is from the leaders of the government. If we go back to 2016 and hold a second referendum, the result may be that more than 50% people will choose to stay in EU. </p>
</div>


&nbsp;

---
<!--CHAPTER: AUTHOR-->
&nbsp;

The research is made by:   
<center><a href="https://github.com/epfl-ada/ada-2021-project-skrw"><b><font size="+2">skrw</font></b></a></center>

