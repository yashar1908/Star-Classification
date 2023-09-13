# Star-Classification

Dataset link - https://www.kaggle.com/datasets/deepu1109/star-dataset?datasetId=391127&sortBy=voteCount

Dataset Info:
This is a dataset consisting of several features of stars.

Some of them are:

<ul>
<li>Absolute Temperature (in K)</li>
<li>Relative Luminosity (L/Lo)</li>
<li>Relative Radius (R/Ro)</li>
<li>Absolute Magnitude (Mv)</li>
<li>Star Color (white,Red,Blue,Yellow,yellow-orange etc)</li>
<li>Spectral Class (O,B,A,F,G,K,,M)</li>
<li>Star Type **(Red Dwarf, Brown Dwarf, White Dwarf, Main Sequence , SuperGiants, HyperGiants)** </li>
</ul>
Lo = 3.828 x 10^26 Watts (Avg Luminosity of Sun)<br>
Ro = 6.9551 x 10^8 m (Avg Radius of Sun)

Purpose:
The purpose of making the dataset is to prove that the stars follows a certain graph in the celestial Space ,
specifically called Hertzsprung-Russell Diagram or simply HR-Diagram
so that we can classify stars by plotting its features based on that graph.

![image](https://github.com/yashar1908/Star-Classification/assets/73465642/b57d3126-c0c9-463c-9396-6aeee4bfe4c2)

Implemented K-nearest neighbors and Random Forest Classifier on the given dataset to classify the stars according to their types.
