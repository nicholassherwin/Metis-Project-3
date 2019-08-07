# Metis-Project-3
In this study, we will be reading in a UCI dataset that includes descriptions of hypothetical samples corresponding to 23 species of gilled mushrooms in the Agaricus and Lepiota Family Mushroom drawn from The Audubon Society Field Guide to North American Mushrooms (1981). Each species is identified as definitely edible, definitely poisonous, or of unknown edibility and not recommended. This latter class was combined with the poisonous one. The Guide clearly states that there is no simple rule for determining the edibility of a mushroom; no rule like "leaflets three, let it be'' for Poisonous Oak and Ivy.

We will be utilizing a number of supervised machine learning models to determine which mushrooms are poisonous and which are edible. To this end we will be using accuracy as our classification metric. To eat a mushroom that is poisonous can spell certain death in many cases, so we want to be ABSOLUTELY sure the mushroom we have identified is indeed edible.

Once we have modelled the data, we will be taking a look at which features are most important to either class so if we were out in the wild searching for mushrooms, we know what to look for first.

In addition to our ML models, we will be building a Deep Learning image classifier to augment the work we have done. The image classifier will utilize transfer learning (the Inception V3 model) in one instance and a custom built convolutional neural network for another. The results will be compared and documented within. 
