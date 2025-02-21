---
layout: default
title: Data Conversion
parent: Methods
grand_parent: Case Study
nav_order: 3
---

<!-- 
This page is an example lesson template.
Add, edit, or remove any content below for the workshop in question. -->

<!-- Putting a {: .no_toc} above a header removes it from the table of contents -->

{: .no_toc}  

# Data Conversion

To sonify the data from our discourse analysis, we first needed to convert the words into numerical values. We returned to the Excel spreadsheet where we had been tracking the language used to describe data breaches as crises. This included terms related to victims, perpetrators, the breach itself, and the implicated company or organization. We then assessed each category separately to create a scoring framework.  

## Scoring Framework

We came up with this [Scoring Framework](../data/SCORING%20FRAMEWORK.pdf) informed by the insights generated through the discourse analysis. 

<b> Perpetrators </b> refers to the intensity of language used to describe those responsible for a data breach. Our research shows that this language varies in intensity, with the term "hacker" evolving over time to become shorthand for an unauthorized and compromising breach.

- 0 =	Unknown 
- 1	= Neutral language  
- 2	= Demonstrates Intent (fraudster, fisher) 
- 3	= HACKER (clear cut, trope) 
- 4	= More criminal intent than the more generalized use of hacker 
- 5	= Larger nefarious criminality, more organized, identified group or individual 

<b> Company </b> tracks whether a company was explicitly named. Since the breaches we studied affected mid-to-large-sized organizations, it was crucial to monitor when and how these companies or organizations were mentioned in sources. We assigned a score of 2 when a company was named, knowing this would result in a higher-pitched sound, making these rare instances more noticeable.  

<b> Company (named or not) </b>

- 1 =	Not named (No) 
- 2	= Named (Yes) 

<b> Breach </b> measures the intensity of language and expressions used to describe data breach events. In the mid to late 2000s, language was more passive and inconsistent. However, as discussions about breaches stabilized, the language became more consistent and intense, particularly for large breaches or those involving sensitive data. The intensity of the language used in these descriptions scored higher on the scale. 

<b> Breach (intensity of the language used to describe the breach) </b> 
- 0	= Unknown
- 1	= Passive language (exposed, unprotected, revealed) 
- 2	= Leaking (accessed directly) 
- 3	= Breach 
- 4	= Major breach 
- 5	= Catastrophe 

<b> Data </b> indicates the sensitivity of the information compromised in a data breach. We created a scale based on our observations during the discourse analysis to measure sensitivity. Our goal was to see how the sensitivity of the data correlated with other factors, such as perpetrators and the nature of the breach. 

<b> Data (sensitivity of data) </b> 
- 0	= Unknown 
- 1	= Public already 
- 2	= Sensitive
- 3	= Very sensitive 

<b> Risk </b> evaluates the language used to describe the risk to individuals affected by the data breach, such as compromised consumer accounts. We consistently recorded instances where the language was intense, even when the actual risk was not yet known. In these cases, we assigned mid-range scores to reflect the intensity of the language and expressions used. 

<b> Risk (The specific language used to describe the risk) </b>
- 0 =	Unknown 
- 1 =	Low Risk (describes a possible or projected risk; the data is already publicly available) 
- 2	= Medium risk (a known risk is identified; language is intense, but the risk is unknown) 
- 3	= High risk (immediate concern and impact; a concrete risk is named) 

<b> Risk to company </b> records whether a risk to the company was mentioned. This was important for understanding the broader context of the data breach as a security crisis. Like the "Company Named" variable, we assigned a score of 2 when the risk to a company was mentioned. This creates a higher-pitched sound, making these instances more noticeable.

<b> Risk to Company </b>
- 1 =	No 
- 2 =	Yes 

Although the <b> size </b> variable is not included in the framework since it was already recorded numerically in the Excel spreadsheet, it was used in the sonification process to represent the number of accounts compromised in each data breach. If a source did not provide this information, we entered a '0' value in the spreadsheet. Interestingly, this only occurred in one case, the Twitch breach in 2021. Unlike other cases that reported the number of accounts compromised, the Twitch breach focused on the amount of data leaked (1000GB). We aimed to track the size of the data breach to understand how it related to other variables.
