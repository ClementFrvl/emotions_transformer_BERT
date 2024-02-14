# Emotion prediction using a finetuned BERT model

The project uses the Emotions dataset on Kaggle (https://www.kaggle.com/datasets/nelgiriyewithana/emotions).
The goal of this project is to predict the emotion of a given text, in a many to one fashion.
To achieve it I finetuned a BERT model and achieved 0.94 F1 Score with 30 minutes of training.

## Setup

Instructions on setting up the project environment.

### Prerequisites

- Python 3.x
- pip
- virtualenv (optional)

### Installation

```bash
# Clone the repository
git clone https://github.com/ClementFrvl/emotions_transformer_BERT
cd your-project-directory

# (Optional) Create a virtual environment
python -m venv env
source env/bin/activate  # On Windows use `env\Scripts\activate`

# Install dependencies
pip install -r requirements.txt
```

### Weights & Biases Setup

If you lanch the training cell, you'll be prompted for a wandb API key. 
You can get one from this website: [Wandb website]https://wandb.ai/home (free)

Follow the prompts to log in to wandb with your API key.

## Usage

You can run the cells and train the model yourseilf, and download the finetuned model and use it directly without training

## Contributing

If you would like to contribute to this project, please fork the repository and submit a pull request with your proposed changes. Be sure to follow the project's coding standards and update any documentation as necessary.

## License

This project is licensed under the Apache License

## Contact

Clement Florval [LinkedIn]https://www.linkedin.com/in/clement-florval/
