---
layout: default
title: Sonification
parent: Methods
grand_parent: Case Study
nav_order: 4
---

<!-- 
This page is an example lesson template.
Add, edit, or remove any content below for the workshop in question. -->

<!-- Putting a {: .no_toc} above a header removes it from the table of contents -->

{: .no_toc}  
# Sonification

Once we had a scoring framework in place, we followed it to code the data in the Excel spreadsheet. This [Case Conversion file](../data/Case%20Conversion.xlsx) documents how language and expressions were converted into numerical values using the scoring framework.  

We then removed the discourse analysis data from the spreadsheet, keeping only the numerical values. The result was the [Data Breaches Sonification Data spreadsheet](../data/Data%20Breaches%20Sonification%20Data.xlsx) used to create the sonifications in TwoTone.  

## Demos

### EXAMPLE 1 
<audio controls preload="auto" style="width: 100%">
  <source src="../data/audio/EXAMPLE 1.mp3" type="audio/mpeg">
[Download audio here.](../data/audio/EXAMPLE 1.mp3)
</audio>

<iframe height="416" width="100%" allowfullscreen frameborder=0 src="https://echo360.ca/media/7bec0dd1-12e6-40b3-bd52-46aa260cd55f/public"></iframe>
[View original here.](https://echo360.ca/media/7bec0dd1-12e6-40b3-bd52-46aa260cd55f/public)

Example 1 is the default output in TwoTwo. As documented in the [Example 1 Code Book](../data/EXAMPLE%201%20CODE%20BOOK.pdf), the default for any data set uploaded into TwoTwo is C major with diverse instrumentation, a duration of 4:47, and a tempo (BPM) of 60. Loading the [Data Breaches Sonification Data spreadsheet](../data/Data%20Breaches%20Sonification%20Data.xlsx) into TwoTone will generate an identical sonification without manipulating any variables.  

A significant amount of time was spent playing around with TwoTone. The program's constraints can feel limiting initially, especially with the finite selection of instruments. A prime frustration was that early experiments produced very conventional musical compositions. 

The examples below were created while I was becoming familiar with TwoTone. Listening even to snippets of each will make audible the ways I adapted to the constraints of the application. 

<b>Test 1</b> 
<audio controls preload="auto" style="width: 100%">
  <source src="../data/audio/Test 1.mp3" type="audio/mpeg">
[Download audio here.](../data/audio/Test 1.mp3)
</audio> 
Out of the four, this is by far the most conventional composition. It is created this in C major and used diverse instruments to represent each variable. 


<b>Test 2</b> 
<audio controls preload="auto" style="width: 100%">
  <source src="../data/audio/Test 2.mp3" type="audio/mpeg">
[Download audio here.](../data/audio/Test 2.mp3)
</audio> 
This example charts the experimentation with different tempos and major and minor keys, with an emphasis on experimenting with the different ways of manipulating the instruments and observing which of the instruments could produce intense sounds. 

<b>Test 3</b> 
<audio controls preload="auto" style="width: 100%">
  <source src="../data/audio/Test 3.mp3" type="audio/mpeg">
[Download audio here.](../data/audio/Test 3.mp3)
</audio> 
Example three was a turning point in the process. This version is in D minor and there is significant experimentation happening with distorting the instruments. It also uses double bass on core variables like breach and perpetrators, which I transported to example 2. 

<b>Test 4</b> 
<audio controls preload="auto" style="width: 100%">
  <source src="../data/audio/Test 4.mp3" type="audio/mpeg">
[Download audio here.](../data/audio/Test 4.mp3)
</audio> 
This example documents the full extent of attempting to stretch the limits of the instruments in TwoTone. To produce the distortion and droning sound, the track tempo was experimented with. The harp and trumpet were set to a tempo of 12x. These were important discoveries imported into examples 2 and 3. 

It was through experimenting with TwoTone that I learned how to work within the constraints of the application. Notably, understanding the limitations of the application led to important insights for how to manipulate the instruments to produce different sounds to map the data onto, the outcomes of which are discussed in examples 2 and 3.  

Further, experimentation enabled me to develop and refine a process. For example, very early on, I was not devising a code book for the sonification. However, it became apparent that the process was more important than the output, and rather than producing only one sonification that could encompass the project, it was appropriate to the experimentation to create a few examples to demonstrate the possibilities for sound data.  

### EXAMPLE 2
After months of experimenting with the data set in TwoTone, I decided the next step was to choose a key to work within. After careful consideration, I chose D minor. The notes in the D minor scale are D, E, F, G, A, Bb, C, and D. Traditionally, D minor is used to express melancholy, introspection, anxiety, uncertainty, despondence and similar states and emotional intensities.  

Before the 20th century, associating musical keys with specific emotional or qualitative characteristics was a common practice. This understanding was part of the shared cultural experience among those who created, performed, and listened to music. For instance, when composers like Mozart, Beethoven, or Schubert wrote a piece in Ab major, known as the ‘key of the grave’, it was expected that many in their audience would recognize this association as well (Steblin, 1983).  

The tonality of D minor in classical music is frequently linked with somber, melancholic, or even dark “humors” (Steblin, 1983). This can be used to convey a sense of tragedy or sorrow, while in rock and pop music, D minor has been used to create emotional intensity. The Beatles’ Come Together (1969), Phil Collins’ In the Air Tonight (1981), New Order’s Blue Monday (1983), Wham!’s Careless Whisper (1984), Sade’s Smooth Operator (1984), Beastie Boys’ Root Down (1994), Radiohead’s I Might Be Wrong (2001), Beyonce’s Crazy in Love (2003), and Drake’s Hotline Bling (2015) are all in the key of D minor. 

In the context of sonifying data, this historical practice of key association can be leveraged to enhance the emotional and qualitative impact of the auditory representation. By carefully selecting musical keys that align with the desired emotional response, data sonification can become a more powerful and intuitive tool for conveying complex information. In this example, D minor was an appropriate choice for the data set because it could augment and potentially distort the themes and observations to emerge from the discourse analysis. We observed many tensions in how data breaches were framed as crises and concluded that D minor could offer a heightened perception of the tensions, intensities and harmonies in the dataset. 

As a first step, I considered which data would be assigned to which key and sound/instrument and why, how to represent linear and nonlinear data, and whether to stay within or defy certain conventions. I decided immediately to remove the ‘Year’ and ‘Date’ fields after the dataset was imported into TwoTone as I was not particularly interested in having this temporal data represented in the sonification least in part because the data was already sorted chronologically to chart changes over time. Removing these two fields allowed me to focus on the core narratives and themes that emerged through the discourse analysis.  

With example 2, I chose a limited number of instruments to work with, specifically the trumpet, harp and double bass. Based on my previous experiments as documented in examples 1 to 4, I wanted to continue to manipulate some of the instruments to produce distortions. For example, setting the track tempo to 12x for the trumpet and harp resulted in a droning sound. I isolated the ‘perpetrators’ and ‘breach’ variables as the core narratives. Both are represented as a double base in D minor with a 2-octave range. The primary difference is that the perpetrators track has a tempo of 2x and the breach track has a tempo of 3x to produce variation and tension between the two. Together, the tracks produce the following: 
<audio controls preload="auto" style="width: 100%">
  <source src="../data/audio/EX 2 Core Melodies.mp3" type="audio/mpeg">
[Download audio here.](../data/audio/EX 2 Core Melodies.mp3)
</audio> 

‘Perpetrators’ and ‘breach’ anchored the sonification and produced a melody to assist with mapping the other variables to an instrument, key, scale, octave and tempo. I chose from the outset not to use arpeggios to diminish ornamentation. These were some of the initial decisions made to assist with structuring the sonification.  

Below, is a detailed explanation of the reasoning behind the choices made for specific tracks. Following this section is the complete sonification 

#### EXAMPLE 2.1 SIZE

<iframe height="416" width="100%" allowfullscreen frameborder=0 src="https://echo360.ca/media/09b5053c-4c7f-4989-909f-b735c5219e6d/public"></iframe>
[View original here.](https://echo360.ca/media/09b5053c-4c7f-4989-909f-b735c5219e6d/public)

The trumpet is at 12x tempo to represent <b> size</b>. At 12x, the trumpet produces a persistent low droning and changes to a higher pitch to represent large data breaches without the sound being too overbearing. 

#### EXAMPLE 2.2 PERPETRATORS

<iframe height="416" width="100%" allowfullscreen frameborder=0 src="https://echo360.ca/media/c3734466-fe29-47e8-b59a-f20629e1fb1a/public"></iframe>
[View original here.](https://echo360.ca/media/c3734466-fe29-47e8-b59a-f20629e1fb1a/public)

Because the <b> perpetrators </b> and breach were the anchor narratives of the sonification, the double bass was chosen to represent these. Along with the drums, the bass is typically the instrument that provides the backbone to a composition. However, here, this relatively quiet instrument was applied to amplify a melody instead. The track uses 2 octaves to augment the pitch or the range of ways in which language is used to describe perpetrators without it overly dominating in the sonification. 

#### EXAMPLE 2.3 COMPANY NAMED
<iframe height="416" width="100%" allowfullscreen frameborder=0 src="https://echo360.ca/media/9cd8eff1-ea93-4ac6-954c-cb84de17b29c/public"></iframe>
[View original here.](https://echo360.ca/media/9cd8eff1-ea93-4ac6-954c-cb84de17b29c/public)

The harp at 12x tempo represents the variable <b> company named</b>. At this tempo, the harp produces a machine-like sound. At a lower pitch it sounds like drilling and at a higher pitch it sounds like hammering. It is set within a 1 octave range to augment the binary coding (yes or no) we used in the scoring framework. The constant droning in the background sonifies the dearth in corporate accountability in news stories. 

#### EXAMPLE 2.4 BREACH
<iframe height="416" width="100%" allowfullscreen frameborder=0 src="https://echo360.ca/media/d86a8a30-cde6-49d4-b85c-0a9837b96266/public"></iframe>
[View original here.](https://echo360.ca/media/d86a8a30-cde6-49d4-b85c-0a9837b96266/public)

As the companion narrative to the perpetrators track, <b> breach </b> is represented as a double base in D minor with a 2-octave range. While the perpetrators track is a 2x tempo, the breach track uses a 3x tempo to differentiate it from the perpetrators track and to differentiate between the two tracks. Like the perpetrators track, it is set within 2 octaves to augment the variation in the levels of intensity used to describe the breach. 

#### EXAMPLE 2.5 DATA
<iframe height="416" width="100%" allowfullscreen frameborder=0 src="https://echo360.ca/media/39068e39-a5d0-46b0-92a3-1b32ef4f565f/public"></iframe>
[View original here.](https://echo360.ca/media/39068e39-a5d0-46b0-92a3-1b32ef4f565f/public)

<b> Data </b> is represented as a double bass in A minor with a 1 octave range and 2x tempo. These presets were chosen to produce the backbone to the sonification. The track is marked by noticeable sections of the same pitch with discernable variations. The data variable is the track that provides the backbone to the sonification, much like the way so many facets of contemporary life is characterized by, and through, data. 

#### EXAMPLE 2.6 RISK
<iframe height="416" width="100%" allowfullscreen frameborder=0 src="https://echo360.ca/media/c1e38d35-374f-46b8-981c-1e7d2f3b0954/public"></iframe>
[View original here.](https://echo360.ca/media/c1e38d35-374f-46b8-981c-1e7d2f3b0954/public)

Like size, <b> risk </b> is represented as a trumpet at 12x tempo, but it is in E minor key. The trumpet was chosen for how it can augment the variability in how risk is represented in the research data. Further, because we understand risks and crises like data breaches as not exceptional to but rather an outcome of datafication, the persistent droning of the risk variable throughout is reflective of this. 

#### EXAMPLE 2.7 COMPANY RISK
<iframe height="416" width="100%" allowfullscreen frameborder=0 src="https://echo360.ca/media/e8bc35e1-42c3-440e-9b7d-312179c09630/public"></iframe>
[View original here.](https://echo360.ca/media/e8bc35e1-42c3-440e-9b7d-312179c09630/public)

As the companion narrative to company named, <b> company risk </b> is represented by a harp at 12x tempo but in F minor to complement and differentiate it from company named. Although this variable has more variation than company named, it is still relatively monotonous. In turn, those few sections sonifying a documented risk to a company are discernable.  

#### Example 2 Sonification  
<audio controls preload="auto" style="width: 100%">
  <source src="../data/audio/EXAMPLE 2.mp3" type="audio/mpeg">
[Download audio here.](../data/audio/EXAMPLE 2.mp3)
</audio> 

<iframe height="416" width="100%" allowfullscreen frameborder=0 src="https://echo360.ca/media/8a25a769-9af4-4245-927e-40e6896d5220/public"></iframe>
[View original here.](https://echo360.ca/media/8a25a769-9af4-4245-927e-40e6896d5220/public)

- [Example 2 Code Book](../data/EXAMPLE%202%20CODE%20BOOK.pdf)

Example 2 leans into a notable distortion of nearly all sounds that could be recognized as traditional instruments, amplifying their effects to levels commonly heard in experimental genres such as PC music, industrial, or noise rock. This distortion is a deliberate effort to push the limits of the technology, resulting in the creation of new sounds that aim to put listeners in unexpected affective states. The deliberate distortion and amplification of the synthesized instrument sounds suggest the often overwhelming and disruptive nature of data breaches, while the contrast with occasional ‘pop out’ sonic moments can be understood as a representation of a sudden shift in how language was used to describe breach events, which often coincided with particular cultural or geopolitical moments in the West.  

### EXAMPLE 3 

Example 3 was derived by using example 2 as the starting point. Only some of the tracks have been altered to observe the subtle changes between examples 2 and 3. If the instruments in the tracks constituting the melodies changed, what would the effect be?  

Perpetrators and breach remained the anchoring narratives to which risk was added. Rather than use the double bass to represent the core narratives, I chose the trumpet at 12x. As previously noted, at this tempo, the trumpet produces a droning sound. The perpetrators and breach tracks are both in D minor with a 1 octave range. The only difference between the tracks is that the perpetrators track is set at a 12 x tempo and the breach track is set at a 6x tempo to differentiate the two tracks slightly. The risk track was not altered from example 2 and is represented again by a trumpet at 12x tempo in E minor.  Together, the tracks produce the following: <a href="https://mcmasteru365-my.sharepoint.com/:u:/g/personal/zeffiroa_mcmaster_ca/Eb70HA7j70RIrbXHWdC0HT8B9xNUaTGMHCK1wiKrN4YL1g?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D&e=IJZN9j" target="_blank" rel="noopener noreferrer"> EXAMPLE 3 CORE MELODIES </a> 

I wanted to experiment with distorting the key melodies to consider how the framing of data breaches as security crises are also distorted and shaped by the social, political and historical contexts in which these events circulate.  

Below, is a detailed explanation of the reasoning behind the choices made for specific tracks. Following this section is the complete sonification. 

#### EXAMPLE 3.1 SIZE
<iframe height="416" width="100%" allowfullscreen frameborder=0 src="https://echo360.ca/media/66bb8ec2-805d-49c0-9ab2-80c0d4b83ebf/public"></iframe>
[View original here.](https://echo360.ca/media/66bb8ec2-805d-49c0-9ab2-80c0d4b83ebf/public)

In this version, <b> size </b> is represented by the double bass at 12x tempo. At this speed, the double base produces a persistent drone with some subtle changes in pitch with the most distinctive changes occurring when large data breaches are sonified. It is set at 1 octave so that the changes in size are noticeable yet subtle. In conjunction with the harp used for company named and company risk, a lazer-like sound is produced. 

#### EXAMPLE 3.2 PERPETRATORS
<iframe height="416" width="100%" allowfullscreen frameborder=0 src="https://echo360.ca/media/6621dfbb-591d-4e35-8e56-555bd4c194e7/public"></iframe>
[View original here.](https://echo360.ca/media/6621dfbb-591d-4e35-8e56-555bd4c194e7/public)

Example 2 represented <b> perpetrators </b> with the bass guitar at a 2x tempo. In this example, the trumpet at a 12x tempo is used, producing a layered and rougher sound, which picks up the fluctuations in the intensity of language used to describe individuals and groups held accountable for data breaches. Along with breaches and risk, this track forms the anchor melody of the sonification. 

#### EXAMPLE 3.3 COMPANY NAMED
<iframe height="416" width="100%" allowfullscreen frameborder=0 src="https://echo360.ca/media/ca3c542b-aa10-4afe-a642-c0aac8e0ed52/public"></iframe>
[View original here.](https://echo360.ca/media/ca3c542b-aa10-4afe-a642-c0aac8e0ed52/public)

The harp at 12x tempo represents the variable <b> company named</b>. At this tempo, the harp produces a machine-like sound. I chose to work within a 1 octave range to represent the binary coding (yes or no) we used in the scoring framework. The constant droning in the background sonifies the rarity of companies being held responsible. In this version, it elicited a meditativeness that I did not pick out in example 2.3. 

#### EXAMPLE 3.4 BREACH
<iframe height="416" width="100%" allowfullscreen frameborder=0 src="https://echo360.ca/media/746174b9-927b-4aba-80ca-71bcf2dfefb2/public"></iframe>
[View original here.](https://echo360.ca/media/746174b9-927b-4aba-80ca-71bcf2dfefb2/public)

In example 2, the <b> breach </b> variable was represented by the bass guitar at 3x tempo. Because it is one of three variables with perpetrators and risk constituting the core melody, breach is also represented by the trumpet in D minor like perpetrators but at 6x instead of 12x to stress more of the melody and to differentiate slightly from the perpetrators track and allow it to stand out, which is appropriate given the project’s focus on data breaches. 

#### EXAMPLE 3.5 DATA
<iframe height="416" width="100%" allowfullscreen frameborder=0 src="https://echo360.ca/media/624c5079-ed49-4344-b03b-6907ba3d5a78/public"></iframe>
[View original here.](https://echo360.ca/media/624c5079-ed49-4344-b03b-6907ba3d5a78/public)

<b> Data </b> is represented as a double bass in A minor with a 1 octave range and 2x tempo. These presets were chosen to produce the backbone to the sonification. The track is marked by noticeable sections of the same pitch with discernable variations. It was important to keep the data variable as the anchor to the sonification as a way of reinforcing how so many facets of contemporary life are characterized by, and through, data. 

#### EXAMPLE 3.6 RISK
<iframe height="416" width="100%" allowfullscreen frameborder=0 src="https://echo360.ca/media/f0804576-9678-4057-b31d-d8a99611f3d7/public"></iframe>
[View original here.](https://echo360.ca/media/f0804576-9678-4057-b31d-d8a99611f3d7/public)

<b> Risk </b> is still represented as a trumpet at 12x tempo in E minor key. In this version, risk is paired with perpetrators and breach to observe how tensions and resolves compare across the three narratives. It is set at 1 octave so as not to dominate. Risk was paired with perpetrators and breach to listen to it not as exceptional but rather as new norm stemming from datafication. What do these variables sound like together? 

#### EXAMPLE 3.7 COMPANY RISK
<iframe height="416" width="100%" allowfullscreen frameborder=0 src="https://echo360.ca/media/84ecbc20-4fd2-49c2-8f23-7e855843b9cf/public"></iframe>
[View original here.](https://echo360.ca/media/84ecbc20-4fd2-49c2-8f23-7e855843b9cf/public)

<b> Company risk </b> is represented again by a harp at 12x tempo in F minor, but it is set at an octave higher than example 2.7 to augment the droning. In turn, the few data points representing when a risk to the company was noted stand out. 

#### Example 3 Sonification 

<audio controls preload="auto" style="width: 100%">
  <source src="../data/audio/EXAMPLE 3.mp3" type="audio/mpeg">
[Download audio here.](../data/audio/EXAMPLE 3.mp3)
</audio> 

<iframe height="416" width="100%" allowfullscreen frameborder=0 src="https://echo360.ca/media/ca021117-cc6a-4247-ae97-0b22624fffb1/public"></iframe>
[View original here.](https://echo360.ca/media/ca021117-cc6a-4247-ae97-0b22624fffb1/public)

- [Example 3 Code Book](../data/EXAMPLE%203%20CODE%20BOOK.pdf)

This example features a foreboding, march-like rhythm reminiscent of Bernard Hermann's film soundtracks. The rhythmic foundation emulates archetypal compositional techniques that convey tension, particularly through pizzicato on cello or bass (Karlin et al., 2004, p. 94). Iconic soundtracks like “Psycho” (1960) and “Jaws” (1975), for example, used this technique innovatively. The surrounding instrumentation fills the sonic space around this rhythmic foundation, as different voices emerge unpredictably to create a shifting and uneasy soundscape; listeners may here dissonant 'trumpet' voices that disrupt the drone-like melodic lines, highlighting the track's use of contrapuntal and polytonal qualities (Karlin et al., 2004, p. 233). These elements aim to add layers of complexity and dimensionality that is distinct to that afforded by aural comprehension and which visual data often omits. 
 
Our interpretation suggests this example emphasizes "breach fatigue," with the sounds described above symbolizing the relentless, organized nature of cyber threats. The march-like rhythm reflects the systematic approach of cyber attackers, while dissonant interruptions and clashing polytonal elements represent the chaos and unpredictability of breaches, as well as the varied and sometimes disjointed responses to them. At a higher level, this sonification may evoke a heightened sense of both urgency and murkiness, mirroring the multifaceted and complex nature of cybersecurity discussions. 

