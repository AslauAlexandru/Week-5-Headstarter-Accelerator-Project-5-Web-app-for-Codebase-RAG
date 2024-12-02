# Week 5 Headstarter Accelerator Project 5 Web app for Codebase RAG
## Statement for this project
## Codebase RAG 

In this project, you will create an AI expert over a codebase using 
Retrieval-Augmented Generation (RAG).

This project involves creating an AI expert over a codebase using 
Retrieval-Augmented Generation (RAG). You'll implement the ability to chat 
with a codebase so you can understand how they work and what can be improved.

This is how the /ai-coding-agent-help command works on Slack: given your query, 
the most relevant code is retrieved from the codebase and used to generate a response 
using an LLM.

For this project, you will learn how to embed the contents of a codebase, 
insert them into a vector database called Pinecone, and then get answers 
to your queries based on the contents of the codebase using LLMs.

The submission for this project is a web app where you can chat with a codebase.

- If you want to build the web app only using Python, see the [Streamlit documentation 
here](https://docs.streamlit.io/develop/tutorials/llms/build-conversational-apps) for a guide on how to build a chatbot.
- If you want to use React and Next.js, see the AI Chatbot template 
on [Vercel here](https://vercel.com/templates/next.js/nextjs-ai-chatbot).

See an example of a web app that does this [here](https://sage.storia.ai/auth) and check out a recording of our 
RAG workshop from before [here](https://app.headstarter.co/content/accelerator/recordings/rag-workshop).

Here are some additional challenges for this project if you are finished early:

- Add support for image uploads when chatting with the codebase - this is called Multimodal RAG.
- I have done this: Add a way to select different codebases to chat with. 
- Add a way to update the Pinecone index when you push any new commits to your repo. This would be done through a webhook that's triggered on each commit, where the codebase is re-embedded and added to Pinecone.
- Add a way to chat with multiple codebases at the same time.

## Resources:

[Code, Full Code for Codebase RAG](https://colab.research.google.com/github/team-headstart/CodebaseRAG/blob/main/Codebase_RAG_Completed.ipynb)

[Link, Example Web App](https://sage.storia.ai/auth)

[Blog, RAG on Codebases Blog](https://blog.lancedb.com/rag-codebase-1/)

[Article, Getting started with Embeddings](https://huggingface.co/blog/getting-started-with-embeddings)

[Link,Embedding Model Leaderboard](https://huggingface.co/spaces/mteb/leaderboard)

[Link, How Greptile does Codebase RAG](https://news.ycombinator.com/item?id=39604961)

[Article,RAG for a Codebase with 10k Repos](https://www.qodo.ai/blog/rag-for-large-scale-code-repos/)

[Paper,How Embeddings are Generated](https://arxiv.org/abs/1301.3781)














