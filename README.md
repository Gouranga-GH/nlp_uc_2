
# NLP Text Classification & Semi-Rule Based Chatbot Project

## Problem Statement

This project is divided into two distinct parts:

### Part I: Multi-Label Text Classification
The task is to build a **multi-label text classifier** for predicting several attributes of an author based on their blog post. The project uses a **real-world dataset**, consisting of over **600,000 posts from 19,320 bloggers**, gathered from a popular blogging platform. The goal is to create a model that predicts certain characteristics of the blogger (such as age and gender) based solely on the text of their blog.

### Part II: Semi-Rule Based NLP Chatbot
The second part focuses on building an **interactive chatbot** to handle generic customer support queries. The chatbot must provide relevant answers to simple queries from a predefined corpus or escalate more complex questions to a human agent. The objective is to automate the resolution of common customer issues, ensuring that users get quick and efficient responses.

## Objectives

### Part I: Multi-Label Text Classification
- **Domain**: Digital content management.
- **Objective**: Build a classifier that predicts the following labels for blog posts:
  - **Age group**: Categorized into teens (13-17), twenties (23-27), and thirties (33-47).
  - **Gender**: Male or female.
  - **Other features**: Industry and astrological sign (though these may be missing for some users).
  
The task requires the following steps:
1. **Data import** and analysis.
2. **Data preprocessing**, including:
   - Removing unwanted characters, spaces, and stop words.
   - Converting text to lowercase.
   - Merging and transforming target labels.
   - Splitting the dataset into train and test sets.
   - Applying text vectorization techniques.
3. **Model design**, training, tuning, and testing to identify the best classifier.
4. **Evaluation** of the model using classification reports.
5. **Display predictions**: Output true vs. predicted labels for five random blog entries.

### Part II: Semi-Rule Based NLP Chatbot
- **Domain**: Customer support automation.
- **Objective**: Create a Python-based chatbot that automates responses to frequently asked support questions, including:
   - **Start a chat session** with greetings and prompt the user for their query.
   - **Process dynamic text-based queries** and provide relevant answers from the pre-defined corpus.
   - **Handle complex requests** by escalating them to a human agent.
   - **Chat session loop**: Continue the conversation until the user requests to end it.

## Dataset Description

### Part I: Blog Authorship Corpus
- The dataset consists of **681,288 blog posts** from 19,320 bloggers collected in August 2004.
- Each blog is tagged with features such as **age, gender, industry**, and **astrological sign**.
- Bloggers fall into three age groups: teens (13-17), twenties (23-27), and thirties (33-47), with an equal gender distribution in each group.
- The dataset is available [here](https://www.kaggle.com/rtatman/blog-authorship-corpus).

### Part II: Customer Support Corpus
- The chatbot uses a predefined **sample corpus** of frequently asked questions and answers.
- The corpus can be expanded based on the task requirements to improve the chatbot's performance.
