# Dev Log — Week of 11/03/25

## ✅ Projects 

This week, my ticket focused on expanding the RC Learning Tool’s chatbot analytics integration. I began developing a function that collects student analytical data (topics, strengths, weaknesses, and skill level) gathered from the chatbot and formats it as JSON. The goal is to feed this structured data into our prompt composer, allowing the chatbot to fine-tune and tailor its responses to each student based on contextual insights.
I’m still actively working through this implementation and mapping out how my function interfaces with the overall chatbot pipeline — specifically how data flows from analytics collection to the prompt composition layer.

Outside of that, I also continued working on NeetCode problems related to heaps. Through that process, I started to feel that while JavaScript can handle these data structures, they’re more intuitive to work with in Python, so I’m considering redoing some past problems in Python to strengthen my understanding and flexibility.

## 🧠 Learnings

Gained a deeper appreciation of how analytical data can be used to personalize AI model responses through structured context.

Realized that Python’s data structure accessibility (especially with heaps and priority queues) could improve my problem-solving workflow compared to JavaScript.

Started connecting more dots on how chatbot pipelines integrate multiple layers (analytics, prompt composition, and response generation).

## 🚧 Blockers / Challenges

My main blocker right now is getting a clearer understanding of how the chatbot’s overall flow operates — from the data collection phase to the final prompt output. I plan to sync with other engineers on the team to clarify these connections and ensure the updates I make to the prompt composer align with the existing system design.