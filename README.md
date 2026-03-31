# Animal-Colour-Path

Abstract
Colouration is often useful for distinguishing between closely related species, or
between sexes of a given species. Nevertheless, sometimes colouration is so complex
or non-descript to a human viewer that it cannot be used for delimitation. In
this article, we propose the use of a Deep Learning (DL) algorithm to discriminate
colour patterns of individuals belonging to different species, populations or sexes
that are not discriminable by humans. Namely, we test the effectiveness of DL at
distinguishing (i) between two species of the amphibian urodele Salamandrina,
S. perspicillata and S. terdigitata (Sp vs St), (ii) between two populations of S. perspicillata
based on ventral colour pattern (AdC vs SM), and between (iii) two populations (MB vs SB) and (iv) sexes (F vs M) of
the painted turtle Chrysemys picta based on plastron colouration. The classification
algorithm performs well at distinguishing Salamandrina species (96.8% of the test
set), and C. picta sexes (83.9%) and populations (76.7%), but has a lower performance
on distinguishing populations of S. perspicillata (66.7%). Thus, DL is able
to detect colour pattern differences between biological groups when humans cannot
reliably distinguish them, representing a new way to examine animal colouration
when it is highly variable or has only subtle differences among individuals,
although DL does not output how patterns are similar or different. However, finding
that colour differences occur can represent the first step of a longer analytical
workflow based on possible explanatory hypotheses, or can allow researchers to
save time in the opposite case.

![Confusion_Matrices](https://github.com/user-attachments/assets/87bb9a3f-2079-4146-9440-e0c533b646ea)


for full paper, please read:
https://zslpublications.onlinelibrary.wiley.com/doi/abs/10.1111/jzo.70096
for models and datasets, go to:
https://huggingface.co/MANDRACHE-Lab
