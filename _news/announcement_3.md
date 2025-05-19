---
layout: post
title: Analysing Company Layoffs in the Technology Sector using SQL
date: 2025-05-19 12:00:00-0400
inline: false
related_posts: false
---

I recently completed a short introductory course for Structured Query Language (SQL) Programming, called <a href="https://youtu.be/HXV3zeQKqGY?si=pBLtVr-Z_IVKe44_">SQL Tutorial - Full Database Course for Beginners</a>. The course was developed by Mike Dane from the Giraffe Academy. To cement what I have learned from the course, I have decided to begin working on a project that uses SQL to analyse a dataset that tracks layoffs that have taken place in companies within the technology sector. 

---

On 11 March 2020, the <a href="https://www.who.int/europe/emergencies/situations/covid-19">World Health Organisation</a> declared that the coronavirus disease is a pandemic. As a result, state leaders around the world made urgent calls to increase state spending on healthcare in their countries, and to enforce social distancing practices to curb the spread of the disease. These calls, however, were not without their disadvantages on the world economy. With the restriction on economic activities, countries saw a decrease in consumer spending and the global demand for exports, and an increase to private and public debt levels [1, 5]. On 14 April 2020, Gopinath [2] reported that due to the global lockdown, advanced economies, emerging markets and developing economies were all in recession. The last time this happened was in 1929, when the Great Depression took place.

Various sectors of the economy were negatively affected by the pandemic. In South Africa, it was noted that the sectors that were especially affected included construction, retail and hospitality [5]. However, this was not the case for the technology sector. The lockdown meant that large numbers of people would resort to digital tools more and more for work, entertainment and shopping. By late 2020, technology companies responded to the growing demand for digital tools by escalating recruitment efforts; only for that to all change in 2022 [3].

Initially, the majority of the layoffs were seen in technology start-ups, but by late 2022 larger technology companies, like Meta and Twitter (now called X), followed suit [3]. Reports of layoffs in this sector continue until today [4]. The <a href="https://www.hirist.tech/blog/tech-layoffs-2024-it-layoffs-meaning-reason-labour-law-more/">HiristBlog</a> lists some of the key reasons following these layoffs as follows:
<ul>
    <li><b>Economic slowdown:</b> Layoffs are used in companies as a response to periods of economic uncertainty, increased inflation and interest rates, decreased company revenue and profits, or a banking crisis;</li>
    <li><b>Increased use of AI:</b> Many companies today are investing in AI to replace certain functions that would have previously been performed by humans, to reduce company expenditure in the long run;</li>
    <li><b>Dealing with pandemic over-staffing:</b> Now on the other side of the lockdown, with many people returning to in-person engagements, the demand for digital tools is decreasing. Layoffs are used to deal with the over-staffing that occurred in techology companies during the pandemic;</li>
    <li><b>Satisfaction of investors:</b> Layoffs are used to minimise company expenditure with the goal of satisfying investor expectations for profitability; and</li>
    <li><b>Shift in focus:</b> The rate of innovation is slowing down, relative to the last few decades, with many large technology companies having already corned their share of the market. These companies are now opting to shift their focus from innovation to increasing efficiency and profitability.</li>
</ul>

The goal of this project is to use Structured Query Language (SQL) Programming to analyse a dataset that tracks layoffs that have taken place in companies within the technology sector, and to discover valuable insights regarding this unfortunate event.

The dataset used in this project contains a collection companies in the technology sector that have been reported to have conducted layoffs between 11 March 2020 and 12 March 2025, along with details about the location of the companies' headquarters, the countries where the layoffs took place, the industries that the companies serve, as well as the number of people who were reported to have been laid off. It is worth noting that the dataset is not without its share of issues. Therefore, a significant portion of this project will be dedicated to performing data cleaning to ensure integrity of the insights put forward from the analysis. 

#### References
<ol>
    <li>World Bank. Chapter 1: The Economic Impacts of the COVID-19 Crisis. <i>In World Development Report 2022: Finance for an Equitable Recovery</i>, pages 49–77. World Bank, 2022.</li>
    <li>Gita Gopinath. The Great Lockdown: Worst Economic Downturn Since the Great Depression. <a href="https://www.imf.org/en/Blogs/Articles/2020/04/14/blog-weo-the-great-lockdown-worst-economic-downturn-since-the-great-depression">https://www.imf.org/en/Blogs/Articles/2020/04/14/blog-weo-the-great-lockdown-worst-economic-downturn-since-the-great-depression</a>, April 2020. Accessed: May 13, 2025</li>
    <li>Anna Helhoski. Tech Layoffs in 2025. <a href="https://www.nerdwallet.com/article/finance/tech-layoffs">https://www.nerdwallet.com/article/finance/tech-layoffs</a>, May 2025. Accessed: May 13, 2025</li>
    <li>Roger Lee. <a href="https://layoffs.fyi">https://layoffs.fyi</a>, n.d. Accessed: May 13, 2025</li>
    <li>National Treasury, Republic of South Africa. Chapter 3: The COVID-19 Shock and the Revised Economic Outlook. <i>2020 Supplementary Budget Review</i>, pages 21-28. National Treasury, 2020.</li>
</ol>