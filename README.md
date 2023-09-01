# Neural-Netowrk-Mouse-Olfactory-Bulb

Capturing human capabilities within neural networks has been a feat many machine learning scientists have achieved and continue to strive to capture. Primarily this has been through creating new neural networks
that mimic the way humans learn and this has provided fruitful results. Many researchers have further found that by structuring a neural network to smell like a human does, by identifying a chemical compound, the network
itself begins to mimic the neuron mapping of the olfactory cortex (Burton et al., 2022). Provided this context the team wondered what would be the possible outcomes if a neural network was
trained with the input of scans of the olfactory cortex to predict what smells the brain was detecting.

Our senses, such as smell, not only inform us about our environment but also interact with our memory.
This connection means that the context in which we smell something can influence how we perceive it. For instance, someone with a food allergy might perceive the smell of their allergen as toxic, whereas someone 
without the allergy may not. We aim to explore whether there’s a relationship between how our brain identifies toxicity and different smells.


Our team believes that if the model is successful, it could be implemented in the future to better understand various psychological disorders. For instance, conditions like PTSD have begun to focus treatment
developments on targeting specific portions of the brain through Transcranial Magnetic Stimulation (TMS). Neuroscientists analyze where areas of the brain are more active during the onset of a PTSD symptom and
help relieve it by stimulating the area (Mahoney et al., 2020). Our model’s application in this field could aid neuroscientists in uncovering connections between stimuli and their perception in the olfactory cortex.
This insight might reveal links between specific smells and conditions like PTSD symptoms. Identifying and treating affected areas in the olfactory cortex could enhance our understanding of such disorders. 
Additionally, our model holds the potential for addressing other health conditions that require information from the olfactory cortex.

Using PyTorch, this project‘s goal is to gain insights into sensory perception and its correlation with chemical toxicity through the study of the olfactory system in mice. We propose implementing a neural network model that analyzes brain scans
(748 images) of the olfactory bulb in mice. This model will predict the toxicity of chemical odorants by extracting patterns and features from brain scans. The dataset will be utilized
for training, testing, and validation purposes, with 70/15/15 split. The primary model comprises Convolutional Neural Networks (CNNs) and Artificial Neural Networks (ANNs).
The CNN component will extract pertinent features from the brain scans, while the ANN component will classify the toxicity levels of the chemical odorants. Through rigorous
training, the model will accurately predict toxicity levels (binary classification from 0 to 1) based on the input brain scans. After training and hyperparameters search, our model
produces a test accuracy of 64.29% which is higher than 62.5% produced by our selected baseline model, Random Forests. The results obtained from the neural network model will
deepen our understanding of the olfactory system and contribute to advancements in the field of toxicology


## **Sources**
Shawn D Burton, Audrey Brown, Thomas P Eiting, Isaac A Youngstrom, Thomas C Rust, Michael Schmuker, and Matt Wachowiak. 
Mapping odorant sensitivities reveals a sparse but structured representation of olfactory chemical space by sensory input to the mouse olfactory bulb. 
eLife, 11:e80470, jul 2022.

Jason Castro, Travis Gould, Robert Pellegrino, Zhiwei Liang, Liyah Coleman, Famesh Patel, Derek Wallace,
Tanushri Bhatnagar, Joel Mainland, and Richard Gerkin. Pyrfume: A window to the world’s olfactory
data. 09 2022.

Guillaume Hudon, Christophe Guy, and Jacques Hermia. Measurement of odor intensity by an electronic
nose. Journal of the Air & Waste Management Association, 50(10):1750–1758, 2000.

Martin Kavaliers, Klaus-Peter Ossenkopp, and Elena Choleris. Pathogens, odors, and disgust in rodents.
Neurosci Biobehav Rev, 119:281–293, Dec 2020.

J. J. Mahoney, C. A. Hanlon, P. J. Marshalek, A. R. Rezai, and L. Krinke. Transcranial magnetic stimulation, deep brain stimulation, and other forms of neuromodulation for substance use disorders: Review of
modalities and implications for treatment. Journal of the Neurological Sciences, 418:117149, Nov 2020.
doi: 10.1016/j.jns.2020.117149.

F. Pedregosa, G. Varoquaux, A. Gramfort, V. Michel, B. Thirion, O. Grisel, M. Blondel, P. Prettenhofer,
R. Weiss, V. Dubourg, J. Vanderplas, A. Passos, D. Cournapeau, M. Brucher, M. Perrot, and E. Duchesnay.
Scikit-learn: Machine learning in Python. Journal of Machine Learning Research, 12:2825–2830, 2011.

Peter Y Wang, Yi Sun, Richard Axel, L F Abbott, and Guangyu Robert Yang. Evolving the olfactory system
with machine learning. Neuron, 109(23):3879–3892, Dec 2021.

Zhenqin Wu, Bharath Ramsundar, Evan N. Feinberg, Joseph Gomes, Caleb Geniesse, Aneesh S. Pappu, Karl
Leswing, and Vijay Pande. Moleculenet: a benchmark for molecular machine learning. Chem. Sci., 9:
513–530, 2018.

