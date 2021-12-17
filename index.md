---
layout: page
title: Brexit
---

{% include_relative _includes/styles.html %}
{% include_relative _includes/scripts.html %}

<!--COVER-->
<img src="/img/cover.jpg" class="img-centered" style="width:100%; height=100%;">

> By Kang Fu, Wanting Li, Shanci Li, Runke Zhou

<!--CHAPTER: BACKGROUD-->
<div align="center">
<font size="+1"><h1><b>Background</b></h1></font>
</div>

<div align="justify">
<p> Brexit (a portmanteau of "British exit") was the withdrawal of the United Kingdom (UK) from the European Union (EU) at 23:00 GMT on 31 January 2020 (00:00 CET). Actually, the United Kindom was considering about exiting the EU ever since 2016. After several referendums and negotiations between UK-EU, they finally exit the EU in early January, 2020. And the withdrawl aggrement finally came into force on 31 January 2020. </p>

<p> Shortly afterwards, the post-brexit scenario has raised concerns about regional integration and economic security both in the UK and the EU in recent years. Hereby we look forward to shedding some light on these current issues by a full retrospect of Brexit. We'll dive into 95808 quotations talking about the Brexit from 2016 to 2020, summarize characteristics of relevant speakers, extract underlying top topics behind Brexit, and further analyze the changing attitudes of speakers throughout the whole process.</p>
</div>
&nbsp;

---
<!--CHAPTER: NETWORK-->
&nbsp;

<div align="center">
<font size="+1"><h1><b>Speakers Talking about the Brexit Most Frequently</b></h1></font>
</div>


<div align="justify"><p>
	Let's first have a look at who are the speakers talking about the Brexit most frequently.
</p></div>

{% include_relative _includes/Speaker.html %}
 
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
	<font size="+1"><h1><b>Nationalities of Speakers Talking about the Brexit Belongs to</b></h1></font>
</div>
<div align="justify"><p>
	It's also very interesting to analyze where do speakers talking about the Brexit come from. This gives us information on people from which country cares about the Brexit.
</p></div>
{% include_relative _includes/Nationality.html %}
<div align="justify"><p>
	After visualizing the top 20 nations talking about the Brexit, it's obvious that most of speakers talking about the Brexit came from dominant countries in the world, for example, the United Kindom, the United States of America, Australia and so on. As this event, Brexit, was mostly about the European situation, we can observe that most countries in the top 20 nations talking about the Brexit were from the Europe, which shows that people care about the Brexit are mostly from the Europe.
</p></div>


&nbsp;

<div align="center">
	<font size="+1"><h1><b>Distribution of the Gender of the Speakers Talking about the Brexit</b></h1></font>
</div>
<div align="justify"><p>
	Now we are going to analyze the gender of speakers talking about the Brexit.
</p></div>
<div align="justify"><p>

{% include_relative _includes/Gender.html %}

<!--PIE SENDERS-->
<div id="pie4"></div>
{% include_relative _includes/pie4.html %}

<div align="justify"><p>
	After analyzing the distribution of quotations based on different genders, it's obvious that most speakers pay attention to the Brexit are male. This comforms with the common sense that most people willing to talk about this kind of political event, like the Brexit.
</p></div>


&nbsp;
  
<div align="center">
	<font size="+1"><h1><b>Occupations of Speakers Talking about the Brexit Belongs to</b></h1></font>
</div>
<div align="justify"><p>
	Let's first have a look at who are the speakers talking about the Brexit most frequently.
</p></div>
<div align="justify"><p>
{% include_relative _includes/Occupation.html %}

<div align="justify"><p>
	Here you can see the distribution of the number of quotes based on different occupations. The result is obvious that politicians are the kind of people who talks most about the Brexit. This result is not surprising as this event is basically a political event, thus politicians always need to express their opinions to persuade their supporters. Other occupations, for example, journalist, writer, economist and blogger, are also occupations that are highly related with the politics. This explains why these groups of people would like to talk about the Brexit.
</p></div>
<div align="justify"><p>


&nbsp;
  
<div align="center">
	<font size="+1"><h1><b>Age Ranges of Speakers Talking about the Brexit Belongs to</b></h1></font>
</div>
<div align="justify"><p>
	Let's analyze the distriution of speakers' age ranges who talk about the Brexit.
</p></div>
<div align="justify"><p>
{% include_relative _includes/Age.html %}
  
<div align="justify"><p>
	Here we can make the conclusion from the above plot that most people caring about the Brexit are in the range between 40 years old to above 70 years old. This can be explained by following two reasons. Firstly, most politicians or people from related fields are in this age range from 40 years old to above 70 years old. What's more, people in this age range are also more concerned about political events than younger people. As you can see, there is a very limited number of quotations come from people youger than 29 years old.
</p></div>
<div align="justify"><p>
  
&nbsp;
<div align="center">
	<font size="+1"><h1><b>What are people talking about?</b></h1></font>
</div>
<div align="justify"><p>
  First, we build the tf-idf matrix of the quotations shown in the newspapers and visualize the most frequent ones as below: 
<div align="center">
  <img src="/img/WordClouds_of_Topics.png" class="img-centered" style="width:100%; height=100%;">
  
</div>
<div align="justify"><p>
  To further analyze the content of the quotations related to the Brexit, here we perform the LDA (Latent Dirichlet Allocation) topic detection model. Through the analysis, the model achieves highest coherence when the assigned topic number is 4. Here is the distribution of the top 4 topic:
</p></div>

<div align="center">
{% include_relative _includes/lda.html %} 
  
<div align="justify"><p>
  By sliding to adjust relevance metric and observing the Top-30 most relevant terms inside each topic, we can summarize each topic and analysis the most significant concerns when people talking about Brexit. </p>
  
<p>The first topic covers 29.5% of tokens in the reported quotations. The most meaingful keywords in the topic distribution are: EUR, scotland, northern_ireland, agreement, border, option, soft, extension, priority, discussion, certainty, relationship, withdrawal agreement, farmer, recognise, law, disastrous, transition period. Therefore, we suspect this topic is mainly about the way how Ireland and Scotland would act during the Brexit.</p>
 
<p>The second topic covers 28.4% of tokens and is mainly related to politics. The most meaingful keywords in the topic distribution are: party, election, parliament, labour, leave, tory, boris_johnson, prime_minister, government, referendum, conservative, campaign, british, general election, boris and chance. Therefore, we suspect this topic is about the different attitudes of the all kinds of parties in the UK.</p>
  
<p>The third topic covers 23.6% of tokens. The most meaingful keywords in the topic distribution are: business, market, delay, company, challenge, opportunity, industry, uncertainty, investment, work, london, economy. Therefore, we suspect this topic is mainly the concerns about business and economy after Brexit.</p>
  
<p>The forth topic covers 18.5% of tokens. The most meaingful keywords in the topic distribution are: uncertainty, risk, economy, impact, market, concern, economic, growth, cost, trade, pound, price, business, rise, demand, chaos, worry, sterling. Therefore, we suspect this topic is mainly the concerns about chaos  after Brexit. </p><p> </p><p>
<b>External resource</b>:</p>
<p>For Ireland, the main discussion is on the soft or the hard border with the EU. The impact of Brexit on the Irish border and its adjacent polities involves changes in trade, customs, immigration checks, local economies, services, recognition of qualifications, medical cooperation, and other matters, now that it is the only external EU land border between the United Kingdom and the European Union. After the UK Parliament voted to leave the European Union, all parties said that they want to avoid a hard border in Ireland, due particularly to the border's historically sensitive nature. Border issues were one of three areas of focused negotiation in the Withdrawal Agreement. Following the United Kingdom's exit from the European Union on 31 January 2020, this border is also the frontier between the EU and an external country. The Northern Ireland Protocol of the Brexit withdrawal agreement commits the UK and the EU to maintaining an open border in Ireland, so that (in many respects) the de facto frontier is the Irish Sea border between the two islands. This requires the continued application of the Common Travel Area as well as free trade of goods (including electricity) between Ireland and Northern Ireland. The latter requires the UK to follow EU law in Northern Ireland with respect to these areas, with jurisdiction of the European Court of Justice in the interpretation of the law.</p>
  
<p>For Scotland, after the Brexit referendum, the Scottish Government – led by the Scottish National Party (SNP) – planned another independence referendum because Scotland voted to remain in the EU while England and Wales voted to leave. It had suggested this before the Brexit referendum. The First Minister of Scotland, Nicola Sturgeon, requested a referendum be held before the UK's withdrawal, but the British Prime Minister rejected this timing. At the referendum in 2014, 55% of voters had decided to remain in the UK, but the referendum on Britain's withdrawal from the EU was held in 2016, with 62% of Scottish voters against it. In 2017, if Northern Ireland remained associated with the EU – for example, by remaining in the Customs Union, some analysts argued Scotland would also insist on special treatment. However, in the event, the only part of the United Kingdom which received unique treatment was Northern Ireland. On 21 March 2018, the Scottish Parliament passed the Scottish Continuity Bill. This was passed by stalling negotiations between the Scottish Government and the British Government on where powers within devolved policy areas should lie after Brexit. The Act allows for all devolved policy areas to remain within the remit of the Scottish Parliament and reduces the executive power upon exit day that the UK Withdrawal Bill provides for Ministers of the Crown. The bill was referred to the Supreme Court, which found that it could not come into force as the European Union (Withdrawal) Act 2018, which received royal assent between the Scottish Parliament passing its bill and the Supreme Court's judgement, designated itself under Schedule 4 of the Scotland Act 1998 as unamendable by the Scottish Parliament. The bill has therefore not received royal assent
  
</p></div>
<div align="justify"><p>



&nbsp;
  
  <div align="center">
	<font size="+1"><h1><b>Are UK people Regret to Brexit</b></h1></font>
</div>
<div align="justify"><p>
	Brexit has been a truth since 2020. We have come up with an interesting question: do they regret to make the decision of Brexit? We will investigate if there is a altitude shift between 2016 and 2020. Sentiment analysis has been applied to the quotations from UK people using pretrained model. The output is binary including positive and negative about Brexit.
</p></div>
<div align="justify"><p>
{% include_relative _includes/quotation_number.html %}
{% include_relative _includes/quotation_with_sentiment.html %}
{% include_relative _includes/quotation_percetage.html %} 
<div align="justify">
<p>At the start of 2016, the number of overall quotations about brexit is very small. Additionally, the altitude of UK people to Brexit is mainly negative. However, there is steep increase number of quotations about Brexit from May to June. The reason is that the UK holds a referendum on whether to leave the European Union on 23 June. 52% of voters vote to leave. This is the start point of Brexit. At that time, the percentage of the positive quotations has also increased to over 40%, but still less than negative quotations.</p>
  
<p>After three months, the number of quotation decreases to the level before the Brexit, but it suddenly increase to more than 500 in November. On November, in the Miller case, the High Court ruled against the Secretary of State for Exiting the European Union on the question of whether notice could be given under Article 50 of the Treaty on European Union using the Royal prerogative. On December, the House of Commons votes 461 to 89 in favour of Theresa May's plan to trigger Article 50 by the end of March 2017.</p>

<p>The quotation number is going up since the start of 2017 and reach peak on June 2017. On March 2017, a letter from Theresa May was handed to President of the European Council Donald Tusk to invoke Article 50, starting a two-year process with the UK due to leave the EU on 29 March 2019. Brexit negotiations commenced on 19 June. This also resulted in heated discussion on newspapers. The number of quotations reached the largest during 2017 period. We have noticed that the altitude of UK people toward Brexit fluctuated during this year, but the negative quotation dominates.</p>

<p>There is a noticeable rising volatility from April 2018 to May 2019. Meanwhile, the negative quotations are steadily increase during this period. The background event is House of Commons passed the "Leaving the European Union Act", which was passed by the House of Lords in May and signed by the Queen of UK in June. According to the Act, the United Kingdom will withdraw from the European Union at 23:00 on March 29, 2019. The Brexit withdrawal agreement is published on 14 November. After the United Kingdom and the European Union reached a draft Brexit agreement, it caused strong dissatisfaction among opponents. The Brexit Minister Dominic Raab, who had been in office for only four months, resigned on the grounds of dissatisfaction with the draft. The Minister of Work and Pensions, Esther McVeigh, and two other deputy ministerial officials also resigned. Dominic Raab issued a statement saying that he cannot support the draft Brexit agreement "without conscience." He criticized the content of the draft regarding the resolution of the Irish border issue and the continued presence of the United Kingdom in the EU Customs Union. He believed that this would not allow the United Kingdom to truly leave the European Union.</p>

<p>From the graph, we can see that the number of quotation between January 2019 and May 2019 is going up and down. The reason behind it is the first and second meaningful vote are held on the Withdrawal Agreement in the UK House of Commons. The UK government are both defeated. Therefore, Theresa May requests the EU extend the Article 50 period until 30 June 2019. After that, the UK cannot pass Withdrawal Agreement. Theresa May announces that she will resign as Conservative Party leader, effective 7 June, due to being unable to get her Brexit plans through parliament and several votes of no confidence. </p>

<p>On 23 July, Theresa May officially resigns and Boris Johnson accepts the Queen's invitation to form a new government and becomes Prime Minister of the United Kingdom, the third since the referendum. There is a small rise since July 2019. A noticeable increase in positive quotation from December 2019.The general election held on 12 December. The Conservative Party gains a landslide 80-seat majority in parliament. Boris Johnson is invited to form his second government by The Queen, beginning his second term and allowing Brexit to be completed. The Withdrawal Agreement passes its second reading in the House of Commons in a 358–234 vote and it bans the government to extend the Brexit transition period.</p>

<p>On 31 January 2020, at 11 p.m. GMT the United Kingdom withdraws from the European Union at the deadline set for its departure by the Article 50 extension agreed between the UK and the EU in October 2019, and transitional arrangements begin for the period ending on 31 December 2020.</p>
</div>
&nbsp;

<div align="center">
	<font size="+1">____________________</font>
</div>


&nbsp;

---
<!--CHAPTER: CONCLUSITON-->
&nbsp;

<div align="center">
<font size="+1"><h1><b>Conclusion</b></h1></font>
</div>

<div align="justify">
By explorating Hillary Clinton's emails, we conclude that: <br>

<ul>
- Hillary sends professional emails to her colleagues via her personal email account on non-government servers during her tenure as Secretary of State.<br>
- The keywords and topics in Hillary’s emails are associated with the international events.<br>
- The sentiment to other countries shown in her emails can reflect the national strategy of U.S. and may influence bilateral diplomatic relations. <br>
</ul>

<p>The above findings make us think that using personal emails for discussing international affaires may <b>cause severe consequences to the national security and diplomacy.</b></p>

<p>It is almost unimaginable how come a politician at her position can be that inprudent. Her "little" mistake may, in the worst case, <b>cause all people of her country in trouble</b>. The image, not only of Hillary's, but also of "American politicians" in general, is worsened from an outside point of view. </p>

<p><b>Surely that we hope to see a transparent world, but when something is related to confidential information concerning the national security, it should be prudently treated.</b></p>
</div>
<div align="justify"><p>
&nbsp;

---
<!--CHAPTER: AUTHOR-->
&nbsp;

The research is made by:   
<center><a href="https://github.com/epfl-ada/ada-2021-project-skrw"><b><font size="+2">skrw</font></b></a></center>

