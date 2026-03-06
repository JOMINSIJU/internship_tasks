# TASK 1
# Text Summarization Tool using NLP

## Overview

This project implements a **Text Summarization Tool** using Natural Language Processing (NLP) techniques in Python. The tool automatically generates a shorter version of a long text while preserving the important information and key ideas.

## Objective

To build a system that can analyze large blocks of text and produce a concise summary using NLP techniques.

## Technologies Used

* Python
* Natural Language Processing (NLP)
* NLTK (Natural Language Toolkit)
* Jupyter Notebook

## Features

* Sentence tokenization
* Stopword removal
* Word frequency analysis
* Automatic summary generation

## How It Works

1. The input text is provided by the user.
2. The text is divided into sentences using **sentence tokenization**.
3. Common words (stopwords) are removed.
4. Word frequencies are calculated to determine important words.
5. Sentences with higher scores are selected to generate the final summary.

## Example

### Input Text

```text
Artificial Intelligence is transforming industries across the world. 
It is being used in healthcare, education, finance, and transportation 
to improve efficiency and decision making.
```

### Generated Summary

```text
Artificial Intelligence is transforming industries across the world 
and improving efficiency in multiple sectors.
```

## Project Files

* `text_summarization.ipynb` – Notebook containing the implementation and examples.

## Result

The system successfully generates concise summaries from longer texts using NLP techniques.



# TASK 2
# Speech Recognition System

## Overview

This project implements a **Speech Recognition System** that converts spoken audio into text using Python. The system captures audio through a microphone or audio file and transcribes it into readable text using a pre-trained speech recognition model.

## Objective

To build a basic speech-to-text application capable of transcribing short audio clips using Python libraries.

## Technologies Used

* Python
* SpeechRecognition Library
* PyAudio
* Google Speech Recognition API

## Features

* Converts speech into text
* Supports microphone input
* Supports audio file transcription
* Simple and easy-to-use implementation

## How It Works

1. The system captures audio from the microphone or an audio file.
2. The audio signal is processed using the **SpeechRecognition** library.
3. A pre-trained speech recognition model analyzes the speech patterns.
4. The spoken words are converted into text and displayed as output.

## Example Output

```text
Speak something...
You said: Hello how are you
```

## Project Files

* `speech.py` – Python script for speech recognition.
* `requirements.txt` – Required Python libraries.

## Result

The system successfully transcribes spoken words into text, demonstrating the basic working of a speech-to-text system.




# TASK 3
# Neural Style Transfer

## Overview

This project implements **Neural Style Transfer**, a deep learning technique that combines the **content of one image** with the **artistic style of another image** to create a new stylized image. The model extracts the structure of the content image and applies the visual patterns of the style image.

## Objective

To demonstrate how neural networks can apply artistic styles to photographs using Python and deep learning libraries.

## Technologies Used

* Python
* PyTorch
* Torchvision
* PIL (Python Imaging Library)
* Matplotlib

## How It Works

1. A **content image** (photograph) and a **style image** (painting or artwork) are loaded.
2. Both images are converted into tensors using image transformations.
3. The style patterns and textures from the style image are blended with the structure of the content image.
4. The model generates a **new stylized output image**.

## Project Files

* `neural_style_transfer.ipynb` – Jupyter notebook containing the implementation.
* `content.jpg` – Input photograph.
* `style.jpg` – Image containing artistic style.
* `output.jpg` – Generated stylized image.

## Example Workflow

Content Image → Style Image → Stylized Output

The output image preserves the main structure of the content image while adopting the artistic style of the style image.

## Output

The notebook displays:

* Content Image
* Style Image
* Generated Styled Image


# TASK 4
# Generative Text Model

## Overview

This project demonstrates a **Generative Text Model** using a pre-trained **GPT-2 model** from the HuggingFace Transformers library. The model generates coherent paragraphs of text based on user-provided prompts.

## Objective

To implement a text generation system capable of producing meaningful paragraphs from a given topic or prompt.

## Technologies Used

* Python
* HuggingFace Transformers
* PyTorch
* Jupyter Notebook

## How It Works

1. A pre-trained GPT-2 model is loaded using the Transformers library.
2. The user provides a **prompt or topic**.
3. The model processes the prompt and predicts the next sequence of words.
4. The system generates a **coherent paragraph related to the prompt**.

## Example Prompt

```
The future of space exploration
```

## Example Generated Output

```
The future of space exploration will depend on advances in technology,
international collaboration, and sustainable space missions. Scientists
are working on new propulsion systems and exploring ways to establish
human presence on other planets.
```

## Project Files

* `generative_text_model.ipynb` – Notebook containing the implementation and demonstrations.

## Result

The notebook demonstrates how a generative language model can produce paragraphs of text based on different prompts.
