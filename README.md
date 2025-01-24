Here, we implemented an epileptic seizure prediction algorithm
based on the paper EEG signal classification using PCA, ICA, LDA, and support vector
machines (1) which was published by Subasi and Gursoy in 2010. Starting from the fundamentals, 
we implemented the entire process by ourselves.
This work presents a method for analyzing and classifying Electroencephalogram (EEG) signals to detect
epileptic seizures, which is a critical diagnostic support for neurologists. The study leverages
advanced techniques in signal processing and machine learning. Key steps include:

1. Signal Decomposition: EEG signals are decomposed into frequency sub-bands
using the Discrete Wavelet Transform (DWT), which is particularly suited for analyzing
non-stationary signals.

2. Feature Extraction and Reduction: Statistical features are extracted from these
sub-bands. Dimension reduction techniques such as Principal Component Analysis
(PCA), Independent Component Analysis (ICA), and Linear Discriminant Analysis
(LDA) are applied to streamline the data.

3. Classification with Support Vector Machines (SVM): The extracted features
are classified using SVM into two categories—epileptic and no-epileptic.

The study compares the performance of classifiers built using PCA, ICA, and LDA for
feature extraction and demonstrates that SVM with LDA outperforms the others in terms
of accuracy. This framework has the potential to enhance automated diagnostic systems
for epilepsy, offering a robust approach to EEG signal classification.
The repository includes a detailed account of the procedures we followed, the specific challenges
encountered during the implementation, and the results obtained. Furthermore,
we provide a comprehensive comparison between the outcomes of our re-implementation
and those reported in the original study, offering insights into the reproducibility and
practical applicability of the proposed methods. This work not only validates the original
findings but also highlights areas for potential enhancement in future EEG classification
systems.

[1] A. Subasi and M. Ismail Gursoy, “Eeg signal classification using pca, ica, lda and
support vector machines,” Expert Systems with Applications, vol. 37, no. 12, pp. 8659–
8666, 2010.
