---
layout: default
title: Lesson 2 - Working with Raw Data
nav_order: 2
parent: Lessons
---

{: .no_toc}  
# Lesson 2 - Working with Raw Data

A small description about the lesson.

<details markdown="block" class="toc">
  <summary>
    Table of Contents
  </summary>
  {: .text-delta }
- TOC
{:toc}
</details>

## Lesson Objectives
- A learning objective.
- Second learning objective.
- Another learning objective.


## Rendering Data Usable for Sonification in Two-Tone: A Multi-Step Process  

First we needed to consider what narrative elements we wanted to bring out in the data. 

For our use-case we: 

- Engaged in critical discourse analysis to understand the intricacies of our sources. 
- Focused on words and phrases that contained ideological associations. 
- Assigned a numerical “scoring framework” to the terms we isolated  
- Organized these terms in their respective rows/column assignment  

Remember: The goal is to understand the broader context in which your topic exists and how it is perceived and discussed in various circles. This will look slightly different for each use case, ours is only an example to give you an idea of how qualitative work can be translated into quantitative terms for the purposes of using this tool.  

<em> Note: There are many tools like tone.js and ChucK that allow you to transform qualitative data without using this process, but they require previous knowledge in coding to use. </em> 

You can also opt to track quantitative data points where possible, including:  
- Number of breaches that year 
- Amount of data compromised per breach 
- Source of the breach (e.g., hacking, human error, crypto extortion). 

Next you need to clean or <b> prepare your data: </b> 

Ensure that there are no missing values or outliers that could distort the sonification such as missing dates, non-responses in survey data, entry errors, or measurement errors. 

<b> Side Bar: A Note on Handling Anomalies in Data: </b> When dealing with outliers, consider using statistical methods like the Interquartile Range (IQR) – a method of understanding the spread of data points by focusing on its <b> central </b> portion – to identify and manage them. While this was not relevant to our case, there are some established processes for achieving this, including: 
- For missing data, techniques such as mean imputation, where missing values are replaced with the mean of that variable, or;  
- More sophisticated approaches like k-nearest neighbors (KNN) imputation – a technique that uses an algorithm to fill in missing pieces of data by imputing missing databased on the value of that data’s nearest neighbours – can be employed.  
- It's crucial to understand the nature of your data to choose the most appropriate method. 

<b> Normalize: </b> Scale your data so that the values fit within a range suitable for sonification, e.g., frequency ranges. For this process we developed a <b> Scoring Framework: </b> 

1) The scoring framework was developed by analyzing the data's distribution and identifying a suitable scaling method. We used Min-Max normalization to transform the data, ensuring that all values fell within our desired frequency range, thus making the sonification process more coherent and interpretable. 
2) In our example, we decided to transform each category of data into values based on a 0-5, 0-3, or 1-3 scale by analyzing the levels of intensity each category of data held. For example, when analyzing the intensity of language in a category like our data breach “Perpetrators,” we considered the levels of violence possible within the language we found. “0” represented an unknown perpetrator, while “1” indicated the language used to describe the perpetrator was neutral, “3” was average (in our case “hacker”), and “5” indicated a more organized or nefarious level of violence. For categories that represented a yes or no answer, we relied on a 1-2 framework (i.e., “was there a risk to the company?”, with “1” indicating “No” and “2” indicating “yes”). And for categories that did not require as large of a scale, we went with a 0-3 framework (i.e, “sensitivity of data” leaked, with “0” indicating unknown, “1” indicating public data, “2” indicating sensitive data, and “3” indicating very sensitive data).   
3) When developing your scoring framework, consider how you might group data into values with patterns that will stand out to your listener. For example, are there particular categories of data that you want to draw more attention to? Consider using a larger scoring framework (i.e., 0-5), which will provide more nuance and variation in your sonification than a smaller scale (i.e., 1-2).  
4) Regardless of the framework you develop, <em> consistency </em> is key. If you have multiple researchers scaling the data, make sure everyone is on the same page with how they are transforming the data into values for sonification. We recommend developing the scoring framework and going through a few examples together to ensure a consistent approach.  
a) You may also want to use <a href="https://dovetail.com/research/intercoder-reliability/" target="_blank" rel="noopener noreferrer">intercoder reliability formulas</a> to ensure that your data coding process is relatable and consistent. These formulas measure the agreement between different coders who classify, rate, or categorize the same dataset. Common formulas include Cohen's Kappa, which adjusts for agreement occurring by chance; Krippendorff's Alpha, suitable for any number of coders and different types of data; and Fleiss' Kappa, designed for evaluating agreement among three or more coders. 


## Key Points / Summary

- Remind the student about what they just learned.
- You can also note down any key information to keep in mind.

## Additional Resources (optional)

- Here, you can list some additional resources the student can access to learn more about this lesson.
