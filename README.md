# LLM Agent for meeting workflow automation

An Autonomous agent created using [Langchain](https://python.langchain.com/docs/get_started) and [langchain agents](https://python.langchain.com/docs/modules/agents/) to create project proposals and automate meeting workflow

### [Read the blog!](https://www.ionio.ai/blog/lets-automate-your-meeting-workflow-with-langchain-and-agents-code-included)

## 👀 Sneak peek

![](https://assets-global.website-files.com/62528d398a42420e66390ef9/65dcad8e72447b6c41891851_product_demo.gif)

## 🤔 How it works?

#### 1. Get information about prospect and idea

Agent gets information about a prospect & their idea from internet using perplexity API when a call is booked

#### 2. Find possible solution

It finds possible solution about idea and how to convert that idea in an actual product from internet

#### 3. Create proposal

Creates a professional project proposal from given idea, client information and solution which includes other information like tech stack, timeline, project link etc

#### 4. Convert proposal to sharable document

Saves the project proposal as notion document or word document

## ⚒️ Architecture

![](https://assets-global.website-files.com/62528d398a42420e66390ef9/65dcab8b7d7f1710c7221f84_image4.png)

## 🚀 Getting started

### Prerequisites

- Python and anaconda installed on your machine
- OpenAI api key
- Perplexity api key
- Notion api key

### How to run?

- Clone the repository
- Create a file called `constants.py` in same folder and store all of your api keys like this

```
OPENAI_API_KEY = <key_here>
PERPLEXITY_API_KEY = <key_here>
NOTION_API_KEY = <key_here>
```

- Open any jupyter notebook from repository
- Select your existing python environment or create one using anaconda
- Run the code
