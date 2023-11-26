# Artificial Intelligence

Artificial intelligence (AI) refers to computer systems capable of performing complex tasks that historically only a human could do, such as reasoning, making decisions, or solving problems.

The concept of AI first emerged in the 1950s, but ideas about intelligent machines date back much further in human history, with mechanical automatons and imagined humanoid robots appearing in ancient myths and fiction. 

The modern field of AI was largely sparked by Alan Turing's 1950 paper "Computing Machinery and Intelligence". In it, he poses the pivotal question: "Can machines think?" To evaluate whether machines can exhibit intelligent behavior, he devised the now famous Turing Test.

![Turing test](https://upload.wikimedia.org/wikipedia/commons/5/55/Turing_test_diagram.png)

While no AI has fully passed the complex Turing Test yet, systems have come close recently. Thanks to rapid advances in the field over the past 20 years, AI and machine learning now power many everyday technologies and tools that would have seemed like science fiction just a decade ago.

## A Brief History of AI

![Alt text](image.png)

### Pre-Computer AI Concepts 

Ideas about developing artificial beings with intelligence date back many centuries. Notable examples include:

- **1200s**: Accounts of mechanical automatons able to sing, play instruments, or perform other lifelike actions. 
- **1818**: Mary Shelley's Frankenstein explores the idea of artificially created life.
- **1950s**: As computing advanced, scientists start formally studying how to achieve artificial intelligence.

### Founding of AI as a Discipline

Key events in establishing AI as a scientific discipline include:

- **1950s**: Term "artificial intelligence" coined; Neural network concepts developed.   
- **1956**: First academic AI conference held at Dartmouth College.
- **1997**: IBM's Deep Blue defeats world chess champion, demonstrating AI progress.   

### AI Winter and Resurgence   

- **1974-1980s**: Disappointing early progress led to reduced funding and interest, known as the "AI winter".    
- **1980s**: Expert systems and knowledge bases created for more specialized AI applications.   
- **1990s**: Machine learning techniques helped AI progress beyond rule-based systems.
- **1997**: Deep Blue's chess victory regains interest in general AI goals.

### AI Revolution Powered by Machine Learning

Rapid advancement of AI since 2000 is largely driven by machine learning and deep neural networks, enabled by growth in data and computing power.

- **2001**: Machine learning helps Google Search users correct their spelling.
![Google search spell correct](https://storage.googleapis.com/gweb-uniblog-publish-prod/original_images/gobbledygook.gif)
- **2011**: IBM Watson's Jeopardy! win highlights improvements in natural language processing. 
- **2016**: AlphaGo program becomes first to defeat top human professional player in complex game of Go.
- **2019**: Natural language understanding helps Google to search better.
 ![Alt text](image-1.png)
- **2020**: Protein-folding algorithms and large language models take major leaps forward.
- **2020**: OpenAI introduces GPT-3 model.
- **2022**: OpenAI launches ChatGPT.
- **2023**: Google launches Google BARD.

The pace of AI capabilities continues to accelerate.

## Current and Future Applications

AI and machine learning are now embedded in many common consumer products and services:

- Smartphone assistants like Siri, Alexa and Google Assistant
- Image recognition and organisation in apps like Google Photos  
- Predictive text typing suggestions  
- Recommender systems providing personalised suggestions
- Self-driving and driver assistance car technologies
- Disease risk screening and medical diagnosis support 

In the coming decades, AI could replicate more complex creative and contextual human skills previously thought impossible:

- Natural conversational ability 
- Producing original art, music, literature  
- Advanced strategic planning and decision making  
- High-level physical dexterity and movement 

Ethical considerations around data, bias, transparency, and impact on jobs and society will be crucial in guiding the continued advancement of AI technologies.


# Machine Learning and AI Models

There are three main types of machine learning models:

## Supervised Learning

In supervised learning, models are trained on labelled datasets that contain inputs and desired outputs. For example:

- Image classification models are trained on images labelled with the object classes they depict (e.g. apples and bananas). Given new images, the models can predict these labels.

![supervised model](https://neurospace.io/blog/2020/08/what-is-supervised-learning/images/what-is-supervised-learning.png)


Supervised learning requires collecting and labelling large training datasets, which can be expensive and time-consuming. However, performance is often strong after sufficient training data is provided.

## Unsupervised Learning 

Unsupervised learning models analyse unlabelled input data to find patterns and structure. Some examples include:

- Clustering algorithms group data points (e.g., apples, pears and strawberries) based on detected similarities. This can reveal categories within datasets.

![Alt text](image-2.png)

- Anomaly detection identifies outliers that are significantly different from the norm. 

- Association rule learning finds interesting relationships between variables.

Unsupervised learning derives insights directly from data distributions without needing labelling, reducing data demands. But performance metrics can be harder to define.

## Reinforcement Learning

In reinforcement learning agents interact dynamically with environments, receiving rewards or penalties for actions to learn behaviours that maximise cumulative reward. For instance:

- Robot dogs taught to walk properly through trial-and-error reinforcement of stable gaits.

    ![Alt text](image-3.png)

- Game-playing algorithms that learn winning strategies based on scores.

Reinforcement learning enables very responsive adaptation but requires carefully engineering reward functions.

These three model types are integral to machine learning, with a vast array of models designed for diverse tasks. While exploring various models is beyond this text's scope, the focus here is on a unique machine learning architecture: neural networks.

## Neural Networks
A neural network is a type of machine learning model loosely inspired by biological neural networks in the human brain. They are designed to recognize patterns and features in data.

![Alt text](image-4.png)

At a very basic level, they consist of the following components:

**Inputs**
- Data such as images, text or sound samples get fed into the model
- Each input gets assigned to one of the initial **nodes**

**Nodes**
- Also called neurons or units
- Organised in layers - usually an input layer, one or more hidden layers, and an   output layer
- Each node assigns a weight to its input, performs a calculation on it and passes the value to connected nodes
- Think of a node receiving multiple inputs, assessing their importance, and communicating its assessment to other neurons deeper in the network

**Connections**
- Direct connections between the output of nodes in one layer to the input of nodes in the next layer
- Enable information and weighted values to be passed along for further processing steps

**Outputs**
- The end result showing what the neural network has predicted based on all the calculations stepped through each layer of connections
- Output could be a classification, a prediction, recommendation or other inferred pattern in the data

The strengths of connections between nodes and the node weight values are optimized during model training to improve accuracy on sample data. The trained model can then be applied to new unseen data.

Various neural network types cater to specific tasks, such as vision, numerical processing, and language understanding. In this context, we will provide a brief overview of a large language model (LLM).

### Large Language Model (LLM)
Large language models are a type of AI system that are trained on massive amounts of text data to predict probable next words when given a few words to start with. For example, if you type "The car drove into the..." the model will generate plausible continuations like "drive way" or "parking lot". 

![Alt text](image-5.png)

These models consist of billions of interlinked neural network parameters optimized through exposure to diverse examples of text structures. Thanks to their huge scale and smart architectures capturing complex language patterns, they can now write surprisingly human-like text given a prompt, power new applications like chatbots, and even reason about concepts they were never explicitly trained on. While impressive, they do have limitations in fully understanding context or factual knowledge without further progress. But large language models represent a major recent advance in AI's ability to not just process but dynamically generate natural language.

#### Popular LLMs
There are proprietary and open-sourced LLMs. Here is a list of popular one.

1. ChatGPT (https://chat.openai.com/)
2. Google Bard (https://bard.google.com/chat)
3. Claude AI (https://claude.ai/chat/)
4. LLAMA2 (https://ai.meta.com/llama/)

# References

- What is Artificial Intellience? Click [here](https://www.ibm.com/topics/artificial-intelligence) to access. (Accessed: 23rd Nov 2023)
- What Is Artificial Intelligence? Definition, Uses, and Types. Click [here](https://www.coursera.org/articles/what-is-artificial-intelligence) to access it. (Accessed: 23rd Nov 2023)
- AI is closer than ever to passing the Turing test for ‘intelligence’. What happens when it does? Click [here](https://theconversation.com/ai-is-closer-than-ever-to-passing-the-turing-test-for-intelligence-what-happens-when-it-does-214721) to access it. (Accessed: 23rd Nov 2023)
- History of Artificial Intelligence. Click [here](https://qbi.uq.edu.au/brain/intelligent-machines/history-artificial-intelligence) to access. (Accessed: 23rd Nov 2023)
- Turing, A. M. (1950). Computing Machinery and Intelligence. Mind, 49, 433-460. https://doi.org/10.1093/mind/LIX.236.433  

- McCorduck, P. (2004). Machines Who Think (2nd ed.). Natick, MA: A. K. Peters, Ltd.
