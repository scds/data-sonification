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

Once we had a scoring framework in place, we used it to code the data in the Excel spreadsheet. The [Case Conversion file](../data/Case%20Conversion.xlsx) documents how language and expressions were converted into numerical values according to the scoring framework.  

We then removed the discourse analysis data from the spreadsheet, retaining only the numerical values. This resulted in the [Data Breaches Sonification Data spreadsheet](../data/Data%20Breaches%20Sonification%20Data.xlsx), which we used to create the sonifications in TwoTone.  

## Demos

### EXAMPLE 1 
<audio controls preload="auto" style="width: 100%">
  <source src="../data/audio/EXAMPLE 1.mp3" type="audio/mpeg">
[Download audio here.](../data/audio/EXAMPLE 1.mp3)
</audio>

<iframe height="416" width="100%" allowfullscreen frameborder=0 src="https://echo360.ca/media/7bec0dd1-12e6-40b3-bd52-46aa260cd55f/public"></iframe>
[View original here.](https://echo360.ca/media/7bec0dd1-12e6-40b3-bd52-46aa260cd55f/public)

Example 1 represents the default output in TwoTone. As detailed in the [Example 1 Code Book](../data/EXAMPLE%201%20CODE%20BOOK.pdf), the default settings for any dataset uploaded into TwoTone are C major with diverse instrumentation, a duration of 4:47, and a tempo (BPM) of 60. By loading the [Data Breaches Sonification Data spreadsheet](../data/Data%20Breaches%20Sonification%20Data.xlsx) into TwoTone, you can generate an identical sonification without altering any variables.

A significant amount of time was spent experimenting with TwoTone. The program's constraints can initially feel limiting, particularly due to the finite selection of instruments. A primary frustration was that early experiments resulted in very conventional musical compositions.

The examples below were created as I became familiar with TwoTone. Listening to even brief snippets will make it clear how I adapted to the application's constraints.

<b>Test 1</b> 
<audio controls preload="auto" style="width: 100%">
  <source src="../data/audio/Test 1.mp3" type="audio/mpeg">
[Download audio here.](../data/audio/Test 1.mp3)
</audio> 
Out of the four examples, this one is the most conventional composition. It was created in C major, using a variety of instruments to represent each variable.


<b>Test 2</b> 
<audio controls preload="auto" style="width: 100%">
  <source src="../data/audio/Test 2.mp3" type="audio/mpeg">
[Download audio here.](../data/audio/Test 2.mp3)
</audio> 
This example explores different tempos and both major and minor keys, focusing on experimenting with various ways of manipulating the instruments and identifying which ones could produce intense sounds.

<b>Test 3</b> 
<audio controls preload="auto" style="width: 100%">
  <source src="../data/audio/Test 3.mp3" type="audio/mpeg">
[Download audio here.](../data/audio/Test 3.mp3)
</audio> 
Example three marked a turning point in the process. This version, set in D minor, involves significant experimentation with instrument distortion. It also features double bass for core variables like breach and perpetrators, which I carried over to example 2.

<b>Test 4</b> 
<audio controls preload="auto" style="width: 100%">
  <source src="../data/audio/Test 4.mp3" type="audio/mpeg">
[Download audio here.](../data/audio/Test 4.mp3)
</audio> 
This example showcases the extensive effort to push the limits of the instruments in TwoTone. To create the distortion and droning sound, I experimented with the track tempo, setting the harp and trumpet to a tempo of 12x. These discoveries were crucial and carried over into examples 2 and 3.

By experimenting with TwoTone, I learned to work within the application's constraints. Understanding these limitations provided valuable insights into how to manipulate the instruments to produce different sounds, which are discussed in examples 2 and 3.

Additionally, this experimentation helped me develop and refine a process. Initially, I didn't create a codebook for the sonification, but it became clear that the process was more important than the output. Instead of producing a single sonification to encompass the project, it was more fitting to create several examples to demonstrate the possibilities of sound data.

### EXAMPLE 2
After months of experimenting with the dataset in TwoTone, I decided it was time to choose a key to work within. I selected D minor. The notes in the D minor scale are D, E, F, G, A, Bb, C, and D. Traditionally, D minor is associated with emotions such as melancholy, introspection, anxiety, uncertainty, and despondence.

Before the 20th century, it was common to associate musical keys with specific emotional or qualitative characteristics. This understanding was part of the shared cultural experience among those who created, performed, and listened to music. For example, when composers like Mozart, Beethoven, or Schubert wrote a piece in Ab major, known as the 'key of the grave', many in their audience would recognize this association.[^1]  

The tonality of D minor in classical music is often linked with somber, melancholic, or even dark "humors." It can convey a sense of tragedy or sorrow, while in rock and pop music, D minor has been used to create emotional intensity. Songs like The Beatles’ Come Together (1969), Phil Collins’ In the Air Tonight (1981), New Order’s Blue Monday (1983), Wham!’s Careless Whisper (1984), Sade’s Smooth Operator (1984), Beastie Boys’ Root Down (1994), Radiohead’s I Might Be Wrong (2001), Beyonce’s Crazy in Love (2003), and Drake’s Hotline Bling (2015) are all in the key of D minor. 

In the context of sonifying data, this historical practice of key association can enhance the emotional and qualitative impact of the auditory representation. By carefully selecting musical keys that align with the desired emotional response, data sonification can become a more powerful and intuitive tool for conveying complex information. In this example, D minor was an appropriate choice for the dataset because it could amplify and potentially distort the themes and observations that emerged from the discourse analysis. We observed many tensions in how data breaches were framed as crises and concluded that D minor could offer a heightened perception of these tensions, intensities, and harmonies in the dataset.

As a first step, I considered which data would be assigned to which key and sound/instrument and why, how to represent linear and nonlinear data, and whether to stay within or defy certain conventions. I decided to remove the 'Year' and 'Date' fields after importing the dataset into TwoTone, as I was not particularly interested in having this temporal data represented in the sonification. This allowed me to focus on the core narratives and themes that emerged from the discourse analysis.

For example 2, I chose a limited number of instruments to work with: the trumpet, harp, and double bass. Based on my previous experiments documented in examples 1 to 4, I wanted to continue manipulating some of the instruments to produce distortions. For instance, setting the track tempo to 12x for the trumpet and harp resulted in a droning sound. I isolated the 'perpetrators' and 'breach' variables as the core narratives. Both are represented by double bass in D minor with a 2-octave range. The primary difference is that the perpetrators track has a tempo of 2x, and the breach track has a tempo of 3x to produce variation and tension between the two. Together, the tracks produce the following:
<audio controls preload="auto" style="width: 100%">
  <source src="../data/audio/EX 2 Core Melodies.mp3" type="audio/mpeg">
[Download audio here.](../data/audio/EX 2 Core Melodies.mp3)
</audio> 

'Perpetrators' and 'breach' served as the foundation of the sonification, creating a melody that helped map the other variables to specific instruments, keys, scales, octaves, and tempos. I deliberately avoided using arpeggios to reduce ornamentation. These initial decisions were crucial in structuring the sonification.

Below is a detailed explanation of the reasoning behind the choices made for specific tracks. Following this section is the complete sonification.

#### EXAMPLE 2.1 SIZE

<iframe height="416" width="100%" allowfullscreen frameborder=0 src="https://echo360.ca/media/09b5053c-4c7f-4989-909f-b735c5219e6d/public"></iframe>
[View original here.](https://echo360.ca/media/09b5053c-4c7f-4989-909f-b735c5219e6d/public)

The trumpet is at 12x tempo to represent <b> size</b>. When set to 12x, the trumpet emits a consistent low drone, transitioning to a higher pitch to signify large data breaches without overwhelming the sound.

#### EXAMPLE 2.2 PERPETRATORS

<iframe height="416" width="100%" allowfullscreen frameborder=0 src="https://echo360.ca/media/c3734466-fe29-47e8-b59a-f20629e1fb1a/public"></iframe>
[View original here.](https://echo360.ca/media/c3734466-fe29-47e8-b59a-f20629e1fb1a/public)

Because the <b> perpetrators </b>  and breach were the anchor narratives of the sonification, the double bass was chosen to represent them. While the bass, along with drums, typically provides the backbone of a composition, here, this relatively quiet instrument was used to amplify the melody. The track uses 2 octaves to enhance the pitch or the range of ways language is used to describe perpetrators, without it overly dominating the sonification.

#### EXAMPLE 2.3 COMPANY NAMED
<iframe height="416" width="100%" allowfullscreen frameborder=0 src="https://echo360.ca/media/9cd8eff1-ea93-4ac6-954c-cb84de17b29c/public"></iframe>
[View original here.](https://echo360.ca/media/9cd8eff1-ea93-4ac6-954c-cb84de17b29c/public)

The harp at 12x tempo represents the variable <b> company named</b>. At this speed, the harp produces a machine-like sound, resembling drilling at a lower pitch and hammering at a higher pitch. It is set within a 1-octave range to align with the binary coding (yes or no) used in the scoring framework. The continuous droning in the background highlights the lack of corporate accountability in news stories.

#### EXAMPLE 2.4 BREACH
<iframe height="416" width="100%" allowfullscreen frameborder=0 src="https://echo360.ca/media/d86a8a30-cde6-49d4-b85c-0a9837b96266/public"></iframe>
[View original here.](https://echo360.ca/media/d86a8a30-cde6-49d4-b85c-0a9837b96266/public)

As the companion narrative to the perpetrators track, <b> breach </b> is is represented by a double bass in D minor with a 2-octave range. The breach track is set to a 3x tempo, while the perpetrators track is at 2x tempo, to distinguish between the two. Like the perpetrators track, the breach track is set within 2 octaves to enhance the variation in the levels of intensity used to describe the breach.

#### EXAMPLE 2.5 DATA
<iframe height="416" width="100%" allowfullscreen frameborder=0 src="https://echo360.ca/media/39068e39-a5d0-46b0-92a3-1b32ef4f565f/public"></iframe>
[View original here.](https://echo360.ca/media/39068e39-a5d0-46b0-92a3-1b32ef4f565f/public)

<b> Data </b> is represented by a double bass in A minor with a 1-octave range and a 2x tempo. These settings were chosen to create the backbone of the sonification. The track features noticeable sections of the same pitch with discernible variations. The data variable acts as the backbone of the sonification, reflecting how many aspects of contemporary life are defined by and through data.

#### EXAMPLE 2.6 RISK
<iframe height="416" width="100%" allowfullscreen frameborder=0 src="https://echo360.ca/media/c1e38d35-374f-46b8-981c-1e7d2f3b0954/public"></iframe>
[View original here.](https://echo360.ca/media/c1e38d35-374f-46b8-981c-1e7d2f3b0954/public)

Like size, <b> risk </b> is represented by a trumpet at a 12x tempo, but in the key of E minor. The trumpet was chosen to highlight the variability in how risk is depicted in the research data. Additionally, since risks and crises such as data breaches are understood not as exceptions but as outcomes of datafication, the persistent droning reflects the persistent risk.

#### EXAMPLE 2.7 COMPANY RISK
<iframe height="416" width="100%" allowfullscreen frameborder=0 src="https://echo360.ca/media/e8bc35e1-42c3-440e-9b7d-312179c09630/public"></iframe>
[View original here.](https://echo360.ca/media/e8bc35e1-42c3-440e-9b7d-312179c09630/public)

As the companion narrative to company named, <b> company risk </b> is represented by a harp at a 12x tempo but in F minor to complement and differentiate it from company named. Although this variable has more variation than company named, it remains relatively monotonous. Consequently, the sections that sonify a documented risk to a company are distinct and discernible.

#### Example 2 Sonification  
<audio controls preload="auto" style="width: 100%">
  <source src="../data/audio/EXAMPLE 2.mp3" type="audio/mpeg">
[Download audio here.](../data/audio/EXAMPLE 2.mp3)
</audio> 

<iframe height="416" width="100%" allowfullscreen frameborder=0 src="https://echo360.ca/media/8a25a769-9af4-4245-927e-40e6896d5220/public"></iframe>
[View original here.](https://echo360.ca/media/8a25a769-9af4-4245-927e-40e6896d5220/public)

- [Example 2 Code Book](../data/EXAMPLE%202%20CODE%20BOOK.pdf)

Example 2 intentionally distorts nearly all sounds that could be recognized as traditional instruments, amplifying their effects to levels often heard in experimental genres. This distortion is a deliberate attempt to push the technological boundaries, resulting in new sounds that aim to place listeners in unexpected emotional states. The intentional distortion and amplification of the synthesized instrument sounds reflect the often overwhelming and disruptive nature of data breaches. The occasional 'pop out' sonic moments represent sudden shifts in how language was used to describe breach events, often coinciding with particular cultural or geopolitical moments in the West.

### EXAMPLE 3 

Example 3 was developed by using Example 2 as a starting point, with only some tracks altered to observe the subtle changes between the two examples. How would the effect change if the instruments in the tracks that form the melodies were different?

Perpetrators and breach remained the anchoring narratives, to which risk was added. Instead of using the double bass to represent the core narratives, I chose the trumpet at 12x. As mentioned before, at this tempo, the trumpet produces a droning sound. The perpetrators and breach tracks are both in D minor with a 1-octave range. The only difference between the tracks is that the perpetrators track is set at a 12x tempo, while the breach track is set at a 6x tempo to slightly differentiate them. The risk track was not altered from Example 2 and is again represented by a trumpet at 12x tempo in E minor. Together, the tracks produce the following: <a href="https://mcmasteru365-my.sharepoint.com/:u:/g/personal/zeffiroa_mcmaster_ca/Eb70HA7j70RIrbXHWdC0HT8B9xNUaTGMHCK1wiKrN4YL1g?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D&e=IJZN9j" target="_blank" rel="noopener noreferrer"> EXAMPLE 3 CORE MELODIES </a> 

I wanted to experiment with distorting the key melodies to explore how the framing of data breaches as security crises is also distorted and shaped by the social, political, and historical contexts in which these events occur.

Below is a detailed explanation of the reasoning behind the choices made for specific tracks. Following this section is the complete sonification.

#### EXAMPLE 3.1 SIZE
<iframe height="416" width="100%" allowfullscreen frameborder=0 src="https://echo360.ca/media/66bb8ec2-805d-49c0-9ab2-80c0d4b83ebf/public"></iframe>
[View original here.](https://echo360.ca/media/66bb8ec2-805d-49c0-9ab2-80c0d4b83ebf/public)

In this version, <b> size </b> is represented by the double bass at a 12x tempo. At this speed, the double bass produces a persistent drone with subtle pitch changes, with the most distinctive variations occurring when large data breaches are sonified. It is set at 1 octave so that changes in size are noticeable yet subtle. Combined with the harp used for company named and company risk, this produces a laser-like sound.

#### EXAMPLE 3.2 PERPETRATORS
<iframe height="416" width="100%" allowfullscreen frameborder=0 src="https://echo360.ca/media/6621dfbb-591d-4e35-8e56-555bd4c194e7/public"></iframe>
[View original here.](https://echo360.ca/media/6621dfbb-591d-4e35-8e56-555bd4c194e7/public)

In example 2, <b> perpetrators </b> were represented by the bass guitar at a 2x tempo. In this example, the trumpet at a 12x tempo is used, producing a layered and rougher sound. This captures the fluctuations in the intensity of language used to describe individuals and groups held accountable for data breaches. Along with breaches and risk, this track forms the anchor melody of the sonification.

#### EXAMPLE 3.3 COMPANY NAMED
<iframe height="416" width="100%" allowfullscreen frameborder=0 src="https://echo360.ca/media/ca3c542b-aa10-4afe-a642-c0aac8e0ed52/public"></iframe>
[View original here.](https://echo360.ca/media/ca3c542b-aa10-4afe-a642-c0aac8e0ed52/public)

The harp at 12x tempo represents the variable <b> company named</b>. At this speed, the harp produces a machine-like sound. I chose to work within a 1-octave range to represent the binary coding (yes or no) used in the scoring framework. The continuous droning in the background sonifies the rarity of companies being held accountable. In this version, it evoked a meditative quality that I did not notice in example 2.3.

#### EXAMPLE 3.4 BREACH
<iframe height="416" width="100%" allowfullscreen frameborder=0 src="https://echo360.ca/media/746174b9-927b-4aba-80ca-71bcf2dfefb2/public"></iframe>
[View original here.](https://echo360.ca/media/746174b9-927b-4aba-80ca-71bcf2dfefb2/public)

In example 2, the <b> breach </b> variable was represented by the bass guitar at 3x tempo. Since breach is one of three core melody variables along with perpetrators and risk, it is also represented by the trumpet in D minor, like perpetrators. However, it is set at 6x tempo instead of 12x to emphasize more of the melody and to differentiate it slightly from the perpetrators track, allowing it to stand out—an appropriate choice given the project's focus on data breaches.

#### EXAMPLE 3.5 DATA
<iframe height="416" width="100%" allowfullscreen frameborder=0 src="https://echo360.ca/media/624c5079-ed49-4344-b03b-6907ba3d5a78/public"></iframe>
[View original here.](https://echo360.ca/media/624c5079-ed49-4344-b03b-6907ba3d5a78/public)

<b> Data </b> is represented by a double bass in A minor with a 1-octave range and a 2x tempo. These settings were chosen to create the backbone of the sonification. The track is characterized by noticeable sections of the same pitch with discernible variations. It was crucial to keep the data variable as the anchor of the sonification, reinforcing how many aspects of contemporary life are defined by and through data.

#### EXAMPLE 3.6 RISK
<iframe height="416" width="100%" allowfullscreen frameborder=0 src="https://echo360.ca/media/f0804576-9678-4057-b31d-d8a99611f3d7/public"></iframe>
[View original here.](https://echo360.ca/media/f0804576-9678-4057-b31d-d8a99611f3d7/public)

<b> Risk </b> continues to be represented by a trumpet at a 12x tempo in the key of E minor. In this version, risk is paired with perpetrators and breach to observe how tensions and resolutions compare across the three narratives. It is set within 1 octave to avoid dominating the sonification. Risk was paired with perpetrators and breach to understand it not as an exception but as a new norm resulting from datafication. What do these variables sound like together?

#### EXAMPLE 3.7 COMPANY RISK
<iframe height="416" width="100%" allowfullscreen frameborder=0 src="https://echo360.ca/media/84ecbc20-4fd2-49c2-8f23-7e855843b9cf/public"></iframe>
[View original here.](https://echo360.ca/media/84ecbc20-4fd2-49c2-8f23-7e855843b9cf/public)

<b> Company risk </b> is once again represented by a harp at a 12x tempo in F minor. However, it is set an octave higher than in example 2.7 to enhance the droning effect. This adjustment ensures that the few data points indicating when a risk to the company was noted stand out more prominently.

#### Example 3 Sonification 

<audio controls preload="auto" style="width: 100%">
  <source src="../data/audio/EXAMPLE 3.mp3" type="audio/mpeg">
[Download audio here.](../data/audio/EXAMPLE 3.mp3)
</audio> 

<iframe height="416" width="100%" allowfullscreen frameborder=0 src="https://echo360.ca/media/ca021117-cc6a-4247-ae97-0b22624fffb1/public"></iframe>
[View original here.](https://echo360.ca/media/ca021117-cc6a-4247-ae97-0b22624fffb1/public)

- [Example 3 Code Book](../data/EXAMPLE%203%20CODE%20BOOK.pdf)

This example features a foreboding, march-like rhythm using archetypal compositional techniques to convey tension, particularly through pizzicato on cello or bass[^2] (p. 94). he surrounding instrumentation fills the sonic space around this rhythmic foundation, with different voices emerging unpredictably to create a shifting and uneasy soundscape. Listeners may hear dissonant 'trumpet' voices that disrupt the drone-like melodic lines, highlighting the track's use of contrapuntal and polytonal qualities[^2] (p. 233). These elements aim to add layers of complexity and dimensionality distinct from visual data comprehension.

Our interpretation suggests that this example emphasizes "breach fatigue," with the sounds symbolizing the relentless, organized nature of cyber threats. The march-like rhythm reflects the systematic approach of cyber attackers, while dissonant interruptions and clashing polytonal elements represent the chaos and unpredictability of breaches, as well as the varied and sometimes disjointed responses to them. This sonification may evoke a heightened sense of urgency and murkiness, mirroring the multifaceted and complex nature of cybersecurity discussions.

[^1]: Steblin, R. (1983). A history of key characteristics in the 18th and early 19th centuries. UMI Research Press.

[^2]: Karlin, F., & Wright, R. (2004). On the track: A guide to contemporary film scoring. Taylor & Francis Group.
