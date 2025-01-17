# Blog-generation-using-LLama-2

## Overview
This project is a blog generation app that leverages the Llama 2 language model for creating blog content based on user inputs. The app allows users to specify the topic, number of words, and intended audience (e.g., researchers, data scientists, or general audiences) for tailored blog generation.

 ### Features
1. Interactive UI built using Streamlit.
2. Integrates Llama 2 model via the CTransformers library for fast inference.
3. Customizable inputs for:
 • Blog topic
 • Number of words
 • Target audience

### Setup Instructions
Prerequisites:

1. Python 3.8 or later.
2. A system with sufficient memory and a compatible GPU (optional but recommended for faster inference).
3. Llama 2 model file: Ensure you have downloaded the model binary file (llama-2-7b-chat.ggmlv3.q8_0.bin) and placed it in the appropriate directory.

### Installation
1. Clone the repository:
   ```
   git clone https://github.com/yourusername/blog-generation-llama2.git
   cd blog-generation-llama2
   ```
2. Install the required Python packages:

   ```
   pip install -r requirements.txt
   ```
3. Place the Llama 2 model in the models/ directory:
   ```
   mkdir models
   mv /path/to/llama-2-7b-chat.ggmlv3.q8_0.bin models/
   ```

  ### Usage
  1. Enter a blog topic in the Blog Topic input field.
  2. Specify:
    Number of Words: Desired word count for the blog.
    Writing the Blog For: Select the target audience (e.g., Researchers, Data Scientists, or Common People).
    Click Generate.
    View the generated blog content directly in the app after few minutes.
 
