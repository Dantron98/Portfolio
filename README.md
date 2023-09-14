# Alan Troncoso's Portfolio

## Project 1: [Pest Analysis in a Botanical Garden](https://github.com/Dantron98/BotanicalGarden)

The goal of this project is to determine whether the Orthopteran species, labeled as Sp3, is or could be a pest for trees of the Quercus genus, in collaboration with entomologist colleagues.
The database consists of 206 different sighted entomological species and 43 plant species.

I first focused on performing a statistical analysis, which provides valuable information for the interests of my biologist colleagues.
A total of 13,880 individuals were collected, averaging 67.37 individuals collected per species, while the standard deviation of the number of individuals per species is 283.3. This measure indicates that there is considerable variability in species abundance.

![](/images/output.png)

An important finding is that some species may have a significantly higher number of individuals, while others may have a lower presence in the study area.

![](/images/cake_graph.png)

By analyzing the average and standard deviation, the entomologist can identify species that stand out in terms of their abundance or rarity. Those species with several individuals much higher than the average can be considered dominant or important species in the ecosystem. This information is vital for the project our colleagues are working on.

![](/images/quercus_sp.png)

Even though Sp3 is frequently found near Quercus trees and other common species of the tree, to be classified as a pest, it primarily needs to be located on leaves, stems, and branches. However, this was not the case for the most part, as it was found on nearby vegetation.

## Project 2: [Cosmic Ray Classification](https://github.com/Dantron98/pyroot)
A Monte Carlo simulation analysis of astroparticle showers, such as protons, was conducted focusing on the parameters 
Xmax and LogE. 

![](/images/jointplot.png)

These data were transformed into a Data Frame using Pandas, the data were cleaned, and a linear fit was made using Scipy.

![](/images/graf1.png)

A linear relationship was deduced between these two parameters, which is clearer if we plot the energy averages for each Xmax value. The results obtained were used for the development of neural networks.

![](/images/LgE_vs_avgXmax_Po.png)

## Project 3: [Facial Recognition](https://github.com/Dantron98/ReconocimientoFacial/tree/main)

CNN trained for real-time facial recognition of a work team, which was trained using Keras and TensorFlow on the [CelebA](https://www.kaggle.com/datasets/jessicali9530/celeba-dataset) database.

First, a database of images along with another database containing 40 features for each image was used to train a model that could recognize human faces. The output of a CNN was a dense layer with 40 neurons, using RMSprop as the optimizer and Binary Crossentropy as the loss function. Subsequently, the already trained model was loaded to learn to recognize a single face and this time a single output neuron was used. Finally, training was conducted for multiple individuals using Categorical Crossentropy, and OpenCV was employed to load the model in real time and make predictions.



