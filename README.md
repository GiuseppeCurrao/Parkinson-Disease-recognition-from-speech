# Parkinson-Disease-recognition-from-speech

Parkinson’s Disease (PD) is a progressive neurodegenerative disorder that primarily
affects the motor system, resulting in tremors, bradykinesia, rigidity, and postural instability. PD is caused by the degeneration of dopaminergic neurons in the
substantia nigra, leading to a deficiency of dopamine in the brain. While the exact etiology of PD remains elusive, multiple factors such as genetics, environmental
toxins, and oxidative stress are thought to contribute to its development.
The accurate diagnosis of PD poses a significant challenge due to its complex
clinical presentation, overlapping symptoms with other movement disorders, and the
lack of definitive biomarkers. Misdiagnosis rates are particularly high in the early
stages of the disease, which can have significant implications for patient management
and treatment efficacy. Therefore, there is a pressing need for sensitive and specific
diagnostic methods that can aid in early detection and intervention.

Recent studies have highlighted the potential of vocal dysfunction as a diagnostic marker for PD. Vocal abnormalities, including changes in pitch, loudness, and
speech rhythm, have been observed in individuals with PD. Remarkably, these vocal
impairments can manifest several years before the onset of other motor symptoms,
making them valuable indicators for early detection.
Machine learning (ML) techniques, particularly deep learning models, have shown
promise in the analysis of speech patterns for the detection and classification of PD.
These models can extract intricate features from audio recordings and discern subtle
changes in speech patterns that may be indicative of disease progression.
This promising field is leading to the birth of several studies on the matter. 
In some studies is presented an ensemble of convolutional neural networks (CNNs) for the detection
of PD from the voice recordings. Convolutional Neural Networks (CNNs), a type
of deep learning model, have proven successful in various audio-related tasks and
exhibit great potential in PD detection. Other studies focused on an LSTM based
approach. Other promising results were also given by hybrid approaches utilizing
a combination of Resonance based Sparse Signal Decomposition (RSSD) + TimeFrequency (T-F) algorithm to preprocess data before the giving it in input of a CNN. 

Given the here discussed broad state of the art, in this study, it is proposed a2
total of five distinct ML approaches to analyze speech patterns for accurate earlystage PD identification. These different methods will allow a complete analysis of
Machine Learning behaviour in PD diagnosis.
The first approach involves developing a CNN from scratch and feed it directly
with the audio recordings after appropriate signal processing, such as extracting
Mel Spectrograms or Mel-Frequency Cepstral Coefficients (MFCCs). The second
approach utilizes a CNN on a pretrained network, leveraging transfer learning to
benefit from a network’s prior knowledge and expertise.
Then a 1-D CNN was implemented. This is a variant of convolutional neural
networks that operates on one-dimensional signals such as audio waveforms. This
type of network can automatically learn relevant spatiotemporal filters within the
audio signal, enabling an effective representation of discriminative features for PD
diagnosis.
It follows an RNN. The latter is characterized by cyclic connections within its
hidden layer, allowing it to process sequential data such as audio recordings. This
architecture is particularly well-suited for analyzing temporal patterns in the context
of voice and language.
Lastly, the LSTM is a type of RNN that utilizes a long-term memory structure
to handle sequences of data with long-range dependencies. By retaining information
over time, the LSTM can capture complex correlations within the audio recordings
and enhance the classification capability of different vocal conditions.

By comparing the performance of the methods, we aim to determine the most
effective approach for early-stage PD detection.
To conduct our analysis, we will utilize the Italian Parkinson’s Voice and Speech
dataset. The dataset is accessible after logging in through IEEE. Before the creation of the dataset used for this study, a preliminary step of data preprocessing was made to organize in a better way the files.
The comparative analysis of our proposed ML techniques will provide valuable
insights into the efficacy of different approaches for early-stage PD detection.
