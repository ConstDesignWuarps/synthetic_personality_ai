# synthetic_personality_ai

## 1	Introduction & Context

We are aiming to build a project that targets to consume ai models, while wrapping them in target personalities, using split repositories/containers with selected data on the target personas social media, history, career, and common factors to create a sytethic persona mimicking our persona personality and possible answers.


### 1.1	Steps to Create AI Models Based on Personalities:

This section describes an AI-based personality creation process that not only relies on predefined prompts but also provides the AI model with an inverse approach to build a comprehensive knowledge base for the chosen personality. The AI will consist of different modules representing the persona, goals, and skills, and will limit responses to the persona's range of knowledge. This creates a synthetic experience of the persona, using large language models (LLMs) and transformers for each synthetic persona. The wrap will also leverage sequential chains to allow the synthetic persona to evolve through interaction with the user.




<img width="989" alt="Screenshot 2024-05-26 at 4 41 04 PM" src="https://github.com/miglesia5/synthetic_personality_ai/assets/20667852/3b390841-ff82-4f48-b468-b493a7c7c265">


### 1.1.1	Define the Personality

•	Traits and Behaviors: Outline key traits and behaviors. For example, Chuck Norris would have traits like confidence, toughness, and humor.
•	Goals and Skills: Define the persona's goals and skills. For Chuck Norris, this might include martial arts mastery, acting, and humor.

### 1.1.2	Modular Design 
•	Persona Module: Contains personality traits, behaviors, and typical responses.
•	Goals Module: Defines the persona’s goals and how they might influence responses.
•	Skills Module: Lists the skills the persona possesses and incorporates them into relevant responses.
•	Knowledge Limitation Module: Ensures the AI only responds within the persona’s known range of expertise.
3.1.3	LLMs and Transformers

Fine-tune large language models (like GPT) to embody the persona by training on the collected data.
•	•  Use transformers to handle different aspects of the persona, such as conversational tone, context understanding, and humor generation.


### 1.1.4	Sequential Chains for Evolution

Implement sequential chains to allow the persona to evolve based on interactions. For example, the more the AI interacts with users, the more it learns and refines its responses, staying true to the persona's traits and knowledge.


### 1.1.5	Integration and Interaction

Deploy the AI with the defined modules and ensure it can interact with users in real-time.
Continuously update the knowledge base and fine-tune the model as new data becomes available.

## 2	Sample Implementation

This repository aims to simplified example to illustrate how you might implement such a system: This approach creates a dynamic and evolving AI personality, providing a rich, interactive experience for users. By continuously updating the model with new interactions and data, the AI can maintain an accurate and engaging representation of the chosen persona.
