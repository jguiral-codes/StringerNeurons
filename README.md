# StringerNeurons
# Mixed representations in V1 neurons (Stringer dataset)
Pod: Wistful Wolves 

Group: Neuronas Stringer

### Team members:

[Adrián Alemán-Zapata](https://github.com/Aleman-Z)

Julián Guiral

# Abstract
Mixed representations is the phenomenon in which motor information is encoded and integrated with sensory state variables, creating a multidimensional representation of experiences in the same neuronal population (Stringer, C. et al., 2019). We ask if the combined motor and sensory information during a mice visual-stimuli task improves the accuracy of a predictive model describing the population activity of V1 cortex neurons compared to models trained with the individual motor or sensory variables. This comparison could provide us with insights about the mixed representation phenomenon during different conditions. We hypothesize that the prediction of the V1 cortex population spontaneous activity should improve with a model trained with both motor and sensory variables. On the contrary, the prediction of activity during visual stimuli tasks should benefit less from such a model and instead, improve by using a model trained with only sensory information. Therefore, we expect the visual stimulus to modify the performance of models trained with combined sensory and motor information. To investigate this hypothesis we trained an encoding model with sensory, motor and their combined  information, under the absence and presence of visual stimuli, and during periods of high and low motion. We found that models trained with combined information improved the prediction of both spontaneous activity and the activity during visual stimuli. An exception was the prediction of Non-motor neurons during the Stimulus condition, which best model only required Angle information.  Thus, our results partially confirm the proposed hypothesis, and highlight how mxed-representations is a frequently occurring phenomenon for most neurons during most conditions. The low variability and simplicity of the angle and the running speed data represents a limitation of this study. Another limitation was the lack of standardization of the data between spontaneous and stimuli datasets. We consider that a future direction would be to make use of a more homogeneous and richer version of the dataset. Including real images instead of gradings of different angles during the stimulation, as well as the use of more detailed measures of the mice behavior, would allow training more complex models which would give further insights to the mixed representation phenomenon in V1 cortex neurons. 

# Methods and results
For methods and results please check the following colab notebooks, each pertaining to either the Stimulation or Spontaneous condition:

- [Stringer_stimulation_models.ipynb](https://github.com/Aleman-Z/StringerNeurons/blob/main/Stringer_stimulation_models.ipynb) 
- [Stringer_spontaneous_models.ipynb](https://github.com/Aleman-Z/StringerNeurons/blob/main/Stringer_spontaneous_models.ipynb)

For an attempt using neuronal networks:
- [Neural_network_Stringer_stimulation_models.ipynb](https://github.com/Aleman-Z/StringerNeurons/blob/main/Neural_network_Stringer_stimulation_models.ipynb)

# Conclusions

- Neurons active during High-motion period showed higher mixed representations. 
- Prediction improved with combined sensory+motor features as inputs, except for non-motor neurons.  
- Lack of stimulus in spontaneous condition led to worse prediction.
- Common neurons (Low-motion) during spontaneous condition potentially a signature of resting-state replay.

# Final presentation
The slides of our final presentation can be consulted [here](https://github.com/Aleman-Z/StringerNeurons/blob/main/Project_mixed_representations.pdf). 

# Acknowledgements
José Rey Lopez (TA) for advice and comments. 
