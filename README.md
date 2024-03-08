# Text-To-Emoji-
The project utilizes a recurrent neural network (RNN) architecture, GAN, Diffusion Model specifically Long Short-Term Memory (LSTM), to map text descriptions to emoji characters. It preprocesses the text data using tokenization and padding techniques and then trains the model using a dataset containing text descriptions and corresponding emojis.
README.md:
# Emoji Generator using GAN
This project implements a Generative Adversarial Network (GAN) to generate emoji-like images based on text descriptions.
## Dataset
The dataset consists of a CSV file named `full_emoji.csv` containing emoji descriptions and corresponding unicode characters.
## Installation
Clone the repository to your local machine:
git clone https://github.com/pranav071/emoji-generator.git
## Usage GAN Model
1. **Training the GAN**:
   - Run the `train_gan()` function to train the GAN model.
   - Adjust hyperparameters such as epochs and batch size as needed.

2. **Generating Emoji Images**:
   - Use the trained GAN model to generate emoji-like images based on text descriptions.
input_text = input("Enter text: ")
generated_image = generate_emoji_image(generator, input_text)

## Usage LSTM Model
Prepare Data:
Ensure you have a CSV file containing text descriptions and corresponding emoji characters.
Make sure the CSV file is formatted with columns for text descriptions and emoji characters.
Training:

Run the train_model.py script to train the text-to-emoji conversion model.
Adjust hyperparameters such as epochs and batch size as needed.
Prediction:

Use the text_to_emoji() function in predict.py to convert a text description to an emoji character.
Example usage:
