# MatrixRepresenationInAudioSimilarity
A simple approach to analyze audio signals in the form of mp3 files of songs by representing them as matrices, with each row representing a different frequency component and each column representing a short time segment of the audio signal.

By applying singular value decomposition (SVD) to these matrices, it is possible to reduce the dimensionality of the data by focusing on the most important frequency components, represented by the singular value vectors.

These singular value vectors are then compared using similarity metrics of cosine similarity, Euclidean distance and Manhattan distance to determine how similar the two audio signals are.

This approach can be useful for various applications, such as audio classification, music recommendation, and audio similarity analysis.
