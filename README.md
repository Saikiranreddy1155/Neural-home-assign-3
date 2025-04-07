# Neural-home-assign-3
question1
The code builds a fully connected autoencoder using TensorFlow/Keras to reconstruct MNIST images. It preprocesses the data, defines an encoder (784→32) and decoder (32→784), compiles and trains the model with binary cross-entropy loss, and visualizes original vs. reconstructed images. Users can modify the latent dimension for analysis.
question2
The code implements a denoising autoencoder using TensorFlow/Keras to remove noise from MNIST images. First, it loads and normalizes the dataset before adding Gaussian noise (mean=0, std=0.5) to simulate real-world imperfections. The model architecture consists of an encoder (input: 784 → hidden: 32) and a decoder (hidden: 32 → output: 784), trained with binary cross-entropy loss. During training, the model learns to map noisy inputs to clean outputs. After training, it reconstructs denoised images from noisy test data. The script also visualizes noisy vs. reconstructed images for performance comparison. Denoising autoencoders are practical in fields like medical imaging, where they help remove noise from X-rays or MRIs, improving clarity for diagnosis while preserving essential details.
question3
This Code:
Loads a small text sample and tokenizes characters.
Converts text into sequences of character indices for training.
Defines an LSTM-based RNN model to predict the next character.
Trains the model using categorical cross-entropy loss.
Generates text by sampling characters based on temperature scaling.
Lower temperature (e.g., 0.5) produces more predictable text.
Higher temperature (e.g., 1.5) increases randomness and creativity.
question4
This code:

Loads the IMDB dataset and preprocesses text data by tokenization and padding.

Defines an LSTM-based model for sentiment classification.

Trains the model with binary cross-entropy loss.

Evaluates performance using a confusion matrix and classification report.

The precision-recall tradeoff is crucial because false positives may misrepresent negative reviews, and false negatives can overlook positive feedback, affecting user experience.
