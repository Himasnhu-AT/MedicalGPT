# MedicalGPT - AI Generative Models for Medical Queries

## Introduction

Welcome to the MedicalGPT project's README. Here, we'll introduce you to our AI generative models designed to assist in answering medical queries. Our initiative includes three distinct models, each contributing to the goal of providing medical-related answers. Please keep in mind that our models' usage and answer quality are currently limited due to dataset constraints and resource availability.


##
## Custom Model

### How It Works

Our custom language model, a vital component of the MedicalGPT endeavor, has been crafted using the PyTorch framework. Drawing inspiration from the GPT architecture, this model excels at generating text that revolves around the realm of medicine. By employing cross-entropy loss during training, it learns to predict the next token in a sequence based on the preceding ones.

### Usage

1. **Installation**: Begin by installing the necessary libraries, including PyTorch.
2. **Dataset Preparation**: Procure medical training data that takes into account the current limitations of our dataset.
3. **Hyperparameter Adjustment**: Tailor the model's hyperparameters according to your preferences and available resources.
4. **Training Process**: Train the model using the provided training loop.
5. **Text Generation**: Leverage the `generate` function to generate medical text.
6. **Recognizing Constraints**: It's essential to remember that our model's capabilities are influenced by the constraints of both the dataset and available resources.

### Model-Working update
Currently trained on `10 M parameters` and working to increase it to `35 M parameters`. The model on 10 M parameter gave result but the sentence formation was inaccurate.


##
## LLAMA2 Trained Model

### How It Works

Our LLAMA2 trained model is a fine-tuned version optimized for generating medical text. Part of the MedicalGPT project, this model employs an architecture akin to GPT and is fine-tuned on medical data. While it strives to answer medical queries effectively, the model's performance is influenced by the limitations of our dataset.

#### Image explaining how it works: 
![Working LLAMA](https://github.com/Himasnhu-AT/MedicalGPT/blob/main/Working-llama.png)

### Usage

1. **Model Loading**: Load the pre-trained LLAMA2 model provided by the MedicalGPT project.
2. **Chatbot Construction**: Construct a specialized chatbot tailored for medical queries.
3. **Retrieval QA Chain**: Utilize a Retrieval QA chain to process and respond to user queries.
4. **User Interaction**: Engage in meaningful interactions with users, offering medical insights.
5. **Acknowledging Constraints**: It's crucial to keep in mind that our model's ability to provide accurate medical answers is constrained by dataset limitations.

### Model-Working Update:
Built beta version. Here's how it responded: 
> BOT: Hi, Welcome to Medical GPT. What is your query?
 
> USER: Alpha-fetoprotein test

> BOT: The Alpha-fetoprotein (AFP) test can be used to screen for certain birth defects, including Down syndrome, in a developing fetus. The test measures the level of AFP in the mother's blood and can detect low levels of this protein, which may indicate a higher risk of birth defects. However, it is important to note that the test is not 100% accurate and may not detect all cases of Down syndrome or other birth defects. Additionally, the test cannot determine the severity of any birth defects or the likelihood of them being life-threatening.
>
> Sources: [Document(page_content='Purpose\nAlpha-fetoprotein is a substance produced by the', metadata={'source': 'data/71763-gale-encyclopedia-of-medicine.-vol.-1.-2nd-ed.pdf', 'page': 140}), Document(page_content='alpha fetoprotein screen can be done through a simpleblood test in the doctor’s office between the 16th and18th week of gestation. It tells the odds that their childwill have a severe congenital anomaly. The test works bymeasuring the level of alpha fetoprotein, a substance pro-duced by a fetus with birth defects. Low levels of alphafetoprotein in the mother’s blood may indicate Down’sSyndrome. In that case, the next step for most couples isamniocentesis because the alpha fetoprotein test can', metadata={'source': 'data/71763-gale-encyclopedia-of-medicine.-vol.-1.-2nd-ed.pdf', 'page': 233})]


##
## Falcon Model

### How It Works

The Falcon model, a valuable addition to MedicalGPT, has undergone fine-tuning on a Falcon LLM with 7B parameters. It's trained with the aim of assisting with medical text generation. However, it's important to understand that the model operates within the boundaries set by resource limitations and the quality of our dataset.

### Usage

1. **Environment Setup**: Ensure your environment is prepared and the necessary dependencies are installed.
2. **Model and Tokenizer Loading**: Load the Falcon model and tokenizer, both optimized for generating medical text.
3. **Data Preparation**: Curate training data that falls within the medical domain.
4. **Fine-Tuning Process**: Fine-tune the Falcon model to excel in medical text generation.
5. **Text Generation**: Use the model to generate medical text based on user queries.
6. **Working within Constraints**: Keep in mind that the model's output is influenced by the dataset's quality and the resource limitations.

## Project Outlook

The MedicalGPT project's core mission is to enhance medical query responses through AI generative models. It's important to acknowledge that our models' potential is currently constrained due to the inherent limitations of the dataset and the available resources.

We're committed to continuous improvement and are dedicated to regularly updating our models to provide better results. We're excited to showcase our progress during the Yash Technologies hackathon, where our models will undergo further enhancement. Additionally, we're exploring the possibility of open-sourcing the codebase after receiving permissions from Yash Technologies.
