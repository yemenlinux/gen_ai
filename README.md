# gen_ai
Generative AI example

This example show how to use prompt engineering to generate Arabic text using gpt-3.5-turbo model.

## Installation
First, install miniconda3 from [here](https://docs.conda.io/projects/miniconda/en/latest/).

Clone this repository:
```bash
    git clone https://github.com/yemenlinux/gen_ai.git

    cd gen_ai
```

Then, create a new conda environment and install the required packages:
```bash
    conda env create --name ai4beg --file environment.yml
```

Get your OpenAI API key from [here](https://openai.com/).

save your API key in an environment variable:
```bash
    export OPENAI_API_KEY=<your key>
```

Or use python-dotenv to load your API key from a file named .env:
```bash
    pip install python-dotenv
```

To load your API key from a file named .env:
```bash
    from dotenv import load_dotenv
    load_dotenv()
```

## Usage the notebook
```bash
    conda activate ai4beg
    jupyter-lab
```

Then open the notebook named gen_ai_Arabic.ipynb

## Credits
This example is based on the following resources:

[Generative AI for beginners](https://github.com/yemenlinux/generative-ai-for-beginners).
