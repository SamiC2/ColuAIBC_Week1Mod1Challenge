# Report on Kore.AI

## Overview and Origin

The company that I have decided to research further is Kore.AI. They are an AI-driven platform specializing in Conversational AI experiences and driving solutions for automating contact centers.

Raj Koneru is the founder of Kore.AI and started it back in April of 2014. He started the company after being inspired by the potential of LLMs in AI to transform user experiences. In his own words in an interview he had with [Yahoo Finance](https://finance.yahoo.com/news/kore-ai-startup-building-conversational-120057028.html?guccounter=1) he said the following:

> With the introduction of GenAI and LLMs, the tech landscape turned out to be very chaotic and uncertain due to rapid advancements." "There were more questions than answers ... but I saw conversational AI and LLMs as an opportunity to innovate."

Their most recent funding has come from FTV Capital, NVIDIA, Vistara Growth, Sweetwater PE, NextEquity, Nicola and Beedie, reaching towards $150 million dollars. The company plans to use this money to further enhance their no-code platform to provide the most robust AI contact center experience for its users.

## Business Activities

Kore.AI is trying to help companies automate their contact centers and improve relations between customers and employees. Their audience are companies with contact centers who have large volumes of traffic to their live agents that want to alleviate said traffic. This market size is wide ranging, as basically any company that has a contact center would be able to automate it with Kore.AI. According to this [Yahoo Finance Article on the Conversational AI Market Forecast](https://finance.yahoo.com/news/conversational-ai-market-forecast-experience-103900663.html), the conversational AI market is projected to grow from $8.45 billion in 2022 to an expected $39.55 billion in 2030. Kore.AI seeks to claim a huge portion of the conversational AI market amongst enterprises. Their main three main NLP related solutions are as follows:

* Offering a robust chatbot and contact center experience with XO
* Utilizing GALE to create Generative AI Agents to empower NLP models
* Employing Search AI, a solution using Generative AI to help with agent assist and solve customer queries faster

According to [Stackshare](https://stackshare.io/kore-ai/kore-ai), the main technologies behind Kore.AI are Node.JS, NGINX, AngularJS, Redis, and RabbitMQ. These technologies are used for developing the Kore.AI platform. They also utilize Elasticsearch and Postman for API integrations while also using Docker and Jenkins for DevOps. As Kore.AI has mentioned in their own [Documentation](https://developer.kore.ai/docs/bots/nlp/llm-integration/), they utilize a few different LLM models from Azure OpenAI, OpenAI, Anthropic, and custom LLMs that the users can integrate with their own APIs.

Kore.AI's main selling point from other companies is that they are offering a no-code solution that is easy for engineers to implement in their systems.  

## Landscape

Kore.AI is in the field of conversational AI. This is about providing AI chatbot solutions that are sophisticated enough to handle user queries and answer them efficiently without having to send them to live agents. The goal is to reduce the load of live agents so that their time can be optimized for more crucial important queries from users, instead of answering small simple-to-find details.

There have been many trends recently in Conversational AI that even I am excited about to see further develop in the future. Most chatbots now are starting to be multilingual as opposed to primarily being in one language in the past. Google for example has its own [DialogFlow](https://cloud.google.com/dialogflow/es/docs/agents-multilingual) that started implementing multilingual agents in its design to handle more varied language queries. Mastering complex conversations is another growing trend in the space as more chatbots are able to handle complex discussions and queries to them. Voice assistant chatbots have also been growing and getting better at recognizing human speech. One point that I had not considered however comes from [Chatbot.Com](https://www.chatbot.com/blog/future-of-conversational-ai/), who talked about how improvements in privacy and ethics is starting to grow in the Conversational AI space. Indeed, in the past when I worked on chatbot solutions, I knew how crucial it was for us to implement DLP tools in our chatbots to prevent PII from releasing into the conversation logs.

There are a few other conversational AI solutions that are offered by multiple companies. The one I personally have the most experience in is Google's DialogFlow. It is very similar to Kore.AI in offering an automated contact center solution, while also allowing for a great deal of flexibility in allowing users to create a more programmatic approach with its GCP integration. GeneSys, Avaamo.AI, and IBM Watsonx Assistant are other examples of converstaional AI solutions that are offered to enterprises seeking to automate their contact centers.  

## Results

Kore.AI's business impact has been quite massive as they have served over 230 million companies globally. One [specific case study](https://info.kore.ai/leading-slovenian-bank-offers-seamless-customer-experience-with-ai-powered-contact-centers) that also goes over their metrics when evaluating solutions involves Nova KBM and how they were able to do the following:

* Improve customer satisfaction rate with the automated chatbots by about 94%
* Reduce chats routed to live agents by about 75%
* Increase chat containment rate by about 65%

These are the main metrics that most conversational AI solutions use to judge the effectiveness of their automation. The metrics they employ involve containment within the chatbot itself and the load of conversations decreased from the live agents. Another metric is how many customers and clients they have helped and optimized.

These are industry standard so Kore.AI is performing just fine. Relative to other companies, [most users from this review site](https://www.gartner.com/reviews/market/enterprise-conversational-ai-platforms/vendor/kore-ai/alternatives) say that Kore.AI performs just as well as competitors while also being easier to implement compared to them.

## Reccomendations

If I were to advise the company, I would suggest that they offer more customizations in their LLM models. Right now they use a great deal of pre-existing models, but they should allow for more flexibility and allow users to implement their own models more seamlessly. I also believe they should add their own proprietary LLM models to stand out from other competitors. It seems that their business model could be easily copied as a simple platform, so offering its own unique LLM could provide some contrast in the conversational AI market. Offering your own robust LLM model while also allowing for more customization involving a little bit of coding would help enterprises that want to fine-tune their own models to fit their business needs without having to rely on pre-existing models. This could capture larger company interest as well. For example, DialogFlow already implements a great deal of flexibility for users to really understand what's going on underneath the hood and to fine-tune their models based on their own business needs. [With their generators](https://cloud.google.com/dialogflow/cx/docs/concept/generative/generators) they are able to offer more flexibility in their CCAI solutions by allowing users to create their own LLM natively inside DialogFlow CX without any external APIs. This allows them to fine-tune it within the platform based on the client's needs. Adding something like this to Kore.AI would help it fare better against its competitiors.

### Resources

1. [Yahoo Finance - Kore.ai, a startup building conversational AI for enterprises, raises $150M](https://finance.yahoo.com/news/kore-ai-startup-building-conversational-120057028.html?guccounter=1)
2. [Yahoo Finance - Conversational AI Market Forecast to Experience 21.3% CAGR till 2030 - Rising Demand for AI-Powered Customer Support and Chatbot Solutions](https://finance.yahoo.com/news/conversational-ai-market-forecast-experience-103900663.html)
3. [Stackshare - on Kore.AI](https://stackshare.io/kore-ai/kore-ai)
4. [Kore.AI LLM Integration Documentation](https://developer.kore.ai/docs/bots/nlp/llm-integration/)
5. [DialogFlow Multi Language Agent Docuemntation](https://cloud.google.com/dialogflow/es/docs/agents-multilingual)
6. [Chatbot.Com Blog on The Future of Conversational AI: Trends for 2024 and Beyond](https://www.chatbot.com/blog/future-of-conversational-ai/)
7. [Kore.AI case study on Nova KBM - Leading Slovenian Bank Offers Complete Customer Self-Service with AI-Powered Contact Centers](https://info.kore.ai/leading-slovenian-bank-offers-seamless-customer-experience-with-ai-powered-contact-centers)
8. [Gartner.com on Competitors and Alternatives to Kore.ai](https://www.gartner.com/reviews/market/enterprise-conversational-ai-platforms/vendor/kore-ai/alternatives)
9. [Google Dialogflow Documentation on Generators](https://cloud.google.com/dialogflow/cx/docs/concept/generative/generators)
