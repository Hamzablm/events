The following are notes from the sessions I attended at the [AWS Summit in Paris](https://aws.amazon.com/fr/events/summits/emea/paris/).

Sessions:
- [[#Explorez l'AI generative multimodale avec Claude 3 sur Amazon Bedrock|Explorez l'AI generative multimodale avec Claude 3 sur Amazon Bedrock]]
- [[#Java ❤️ AWS|Java ❤️ AWS]]
- [[#Le développeur augmenté : utilisez l’IA générative pour accélérer vos développements|Le développeur augmenté : utilisez l’IA générative pour accélérer vos développements]]

## Explorez l'AI generative multimodale avec Claude 3 sur Amazon Bedrock
**by Taha Haoulani, AWS | Paul Devillers, AWS** 

Talk about generative AI service choices on AWS and explain utilizing the newest FM model, Claude 3, on Amazon Bedrock.

![CleanShot 2024-04-05 at 11.17.40@2x.png](images/CleanShot%202024-04-05%20at%2011.17.40@2x.png)

![CleanShot 2024-04-05 at 11.18.03@2x.png](images/CleanShot%202024-04-05%20at%2011.18.03@2x.png)

![CleanShot 2024-04-05 at 11.16.48@2x.png](images/CleanShot%202024-04-05%20at%2011.16.48@2x.png)

Cool stuff about the leading ML models on offer from Amazon Bedrock at the summit. Here's a quick rundown:
- **AI21Labs' Jurassic-2**: Go-to for anything that needs a smart reply or a solid summary. Also, it’s quite the paraphrasing pro.
- **Anthropic’s Claude Models**: Swiss Army knives for AI—tackle anything from vision to translation and possess strong coding capabilities.
- **Cohere's Toolkit**: Text generation and digging into documents to find stuff. Classifying info.
- **Meta's Llama 2**: Text summarisation is just the tip of the iceberg. It's also ready to handle all your Q&A, classification, text completion, and even some code gen tasks.
- **Stability.ai's Creation**: Want impressive images and artworks? This one's your muse.
- **Mistral AI**: Versatile, much like Cohere but with a flavor of its own. Summarization, Q&A, text classification, text completion, and even dabbles in code gen.
- **Amazon Titan**: it’s about synthesizing and searching through both images and text, plus it’s got Q&A features.
![CleanShot 2024-04-05 at 11.18.24@2x.png](images/CleanShot%202024-04-05%20at%2011.18.24@2x.png)

Takeaway: more intelligent AI systems require more investment.
![CleanShot 2024-04-05 at 11.19.13@2x.png](images/CleanShot%202024-04-05%20at%2011.19.13@2x.png)

Each Claude model has its unique strengths and is designed to cater to different use cases:
- **Claude 3 Haiku**: This model is the fastest and most affordable model in the suite. It is designed for speed and is three times faster than its peers for most workloads, processing 21K tokens per second for prompts under 32K tokens. It is ideal for applications that require quick responses and low latency where quick answers are essential
- **Claude 3 Sonnet**: This model balances speed and cost. It is capable of responding to basic questions and requests and has a maximum prompt size of 200k tokens, which is around 150k words or more than 500 pages of material.
- **Claude 3 Opus**: This is the most advanced model in the suite. It achieves superior performance on a range of language and vision tasks when compared with competitive models like gpt 4.
![CleanShot 2024-04-05 at 11.19.25@2x.png](images/CleanShot%202024-04-05%20at%2011.19.25@2x.png)
![CleanShot 2024-04-05 at 11.19.35@2x.png](images/CleanShot%202024-04-05%20at%2011.19.35@2x.png)


Some usages of Claude 3:
![CleanShot 2024-04-05 at 11.20.01@2x.png](images/CleanShot%202024-04-05%20at%2011.20.01@2x.png)
![CleanShot 2024-04-05 at 11.20.12@2x.png](images/CleanShot%202024-04-05%20at%2011.20.12@2x.png)
![CleanShot 2024-04-05 at 11.20.47@2x.png](images/CleanShot%202024-04-05%20at%2011.20.47@2x.png)

Prompt engineering techniques for LLMs like Claude 3
![CleanShot 2024-04-05 at 11.23.01@2x.png](images/CleanShot%202024-04-05%20at%2011.23.01@2x.png)![CleanShot 2024-04-05 at 11.23.40@2x.png](images/CleanShot%202024-04-05%20at%2011.23.40@2x.png)
![CleanShot 2024-04-05 at 11.24.12@2x.png](images/CleanShot%202024-04-05%20at%2011.24.12@2x.png)
![CleanShot 2024-04-05 at 13.02.47@2x.png](images/CleanShot%202024-04-05%20at%2013.02.47@2x.png)
- Explorez différents cas d'utilisation de Claude 3 avec des Notebooks Jupyter (QR code note readable 😐)
- [Implémentation de la demo de génération d'un template CloudFormation à partir d'un schéma d'architecture.](https://github.com/TahaHaoulani/claude3-demo-summit)

![CleanShot 2024-04-05 at 13.03.02@2x 1.png](images/CleanShot%202024-04-05%20at%2013.03.02@2x%201.png)
- [En savoir plus sur Claude d'Anthropic sur Amazon Bedrack](https://github.com/anthropics/anthropic-cookbook)
- [Bibliothèque de prompt d'Anthropic](https://docs.anthropic.com/claude/prompt-library)
- [La famille de modèles Claude 3 - Model Card](https://www-cdn.anthropic.com/de8ba9b01c9ab7cbabf5c33b80b7bbc618857627/Model_Card_Claude_3.pdf)


## Java ❤️ AWS 
![CleanShot 2024-04-05 at 11.32.33@2x.png](images/CleanShot%202024-04-05%20at%2011.32.33@2x.png)

![CleanShot 2024-04-05 at 11.33.18@2x.png](images/CleanShot%202024-04-05%20at%2011.33.18@2x.png)
![CleanShot 2024-04-05 at 11.33.33@2x.png](images/CleanShot%202024-04-05%20at%2011.33.33@2x.png)
![CleanShot 2024-04-05 at 11.33.49@2x.png](images/CleanShot%202024-04-05%20at%2011.33.49@2x.png)

Code Written in Java 8
![CleanShot 2024-04-05 at 11.37.35@2x.png](images/CleanShot%202024-04-05%20at%2011.37.35@2x.png)

![CleanShot 2024-04-05 at 11.37.47@2x.png](images/CleanShot%202024-04-05%20at%2011.37.47@2x.png)

## Le développeur augmenté : utilisez l’IA générative pour accélérer vos développements
![CleanShot 2024-04-05 at 11.38.26@2x.png](images/CleanShot%202024-04-05%20at%2011.38.26@2x.png)
![CleanShot 2024-04-05 at 11.38.38@2x.png](images/CleanShot%202024-04-05%20at%2011.38.38@2x.png)

![CleanShot 2024-04-05 at 11.38.49@2x.png](images/CleanShot%202024-04-05%20at%2011.38.49@2x.png)
![CleanShot 2024-04-05 at 11.39.05@2x.png](images/CleanShot%202024-04-05%20at%2011.39.05@2x.png)

![CleanShot 2024-04-05 at 11.39.33@2x.png](images/CleanShot%202024-04-05%20at%2011.39.33@2x.png)







