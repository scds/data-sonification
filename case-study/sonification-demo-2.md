---
layout: default
title: Sonification Demo 2
parent: Methods
grand_parent: Case Study
nav_order: 5
---

<!-- 
This page is an example lesson template.
Add, edit, or remove any content below for the workshop in question. -->

<!-- Putting a {: .no_toc} above a header removes it from the table of contents -->

{: .no_toc}  
# Sonification Demo 2

<audio controls preload="auto" style="width: 100%">
  <source src="../data/audio/EXAMPLE 2.mp3" type="audio/mpeg">
[Download audio here.](../data/audio/EXAMPLE 2.mp3)
</audio> 

<iframe height="416" width="100%" allowfullscreen frameborder=0 src="https://echo360.ca/media/8a25a769-9af4-4245-927e-40e6896d5220/public"></iframe>
[View original here.](https://echo360.ca/media/8a25a769-9af4-4245-927e-40e6896d5220/public)

- [Example 2 Code Book](../data/EXAMPLE%202%20CODE%20BOOK.pdf)

Example 2 intentionally distorts nearly all sounds that could be recognized as traditional instruments, amplifying their effects to levels often heard in experimental genres. This distortion is a deliberate attempt to push the technological boundaries, resulting in new sounds that aim to place listeners in unexpected emotional states. The intentional distortion and amplification of the synthesized instrument sounds reflect the often overwhelming and disruptive nature of data breaches. The occasional 'pop out' sonic moments represent sudden shifts in how language was used to describe breach events, often coinciding with particular cultural or geopolitical moments in the West.

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

[^1]: Steblin, R. (1983). A history of key characteristics in the 18th and early 19th centuries. UMI Research Press.