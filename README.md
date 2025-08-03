
# Smart Home Energy Advisor

An AI assistant that translates your energy data into simple, personalized tips to cut your electricity bill




## 🎯 Problem Statement

Homeowners and students often face the challenge of high electricity bills without a clear way to understand the specific causes. Standard utility reports typically lack the detailed, appliance-level data needed to pinpoint the main drivers of consumption.

This information gap makes it difficult for users to identify wasteful habits or inefficient devices. As a result, they are unable to take targeted, effective actions to manage their energy use, leading to unnecessary financial strain and preventable energy waste.

## 💡 Proposed Solution

An AI-powered Smart Home Energy Advisor Agent designed to provide clear and actionable insights into household electricity usage. Built on IBM Cloud Lite and leveraging the analytical capabilities of IBM's Granite AI models, this agent will:

* Analyze energy consumption data, manually entered by the user, to identify usage patterns and trends.

* Engage users in a natural language conversation, allowing them to ask questions like, "Why was my bill so high?" or "Which appliance used the most energy last week?".

* Deliver personalized recommendations based on the user-provided data to help them identify wasteful habits and optimize their energy use.

* Provide a simple, student-friendly interface to make energy management straightforward and accessible.
## ✨ Unique Features

* **Conversational Data Analysis:** Allows users to ask questions about their energy bill in plain English and receive data-driven answers.

* **Appliance-Level Insights:** Identifies the energy consumption of individual smart appliances to pinpoint primary cost drivers.

* **Data-Driven Recommendations:** Generates personalized energy-saving tips based on the user's specific consumption patterns rather than generic advice.

* **Peak Hour Scheduling Advice:** Analyzes local utility rate structures to recommend the most cost-effective times for running high-power appliances.

* **Student-Centric Interface:** Presents information in a simple, clear, and accessible format, designed with a student user in mind.
## 🖼️ Screenshots

Here's a look at the Smart Home Energy Advisor in action, showcasing its key features.

**Welcome & Introduction** 

![image alt](https://github.com/MrAvinab/IBM-cloud-Smart-Home-Energy-Advisor/blob/89ea3d2810026f1b93fa1dbafcb1f35b733edcb4/demo/1.png)

**Explaining Capabilities**

![image alt](https://github.com/MrAvinab/IBM-cloud-Smart-Home-Energy-Advisor/blob/89ea3d2810026f1b93fa1dbafcb1f35b733edcb4/demo/2.png)

**Analyzing a High Bill**

![image alt](https://github.com/MrAvinab/IBM-cloud-Smart-Home-Energy-Advisor/blob/89ea3d2810026f1b93fa1dbafcb1f35b733edcb4/demo/3.png)

**Giving Savings Advice**

![image alt](https://github.com/MrAvinab/IBM-cloud-Smart-Home-Energy-Advisor/blob/89ea3d2810026f1b93fa1dbafcb1f35b733edcb4/demo/4.png)
## 🚀 Getting Started

To interact with the agent, simply start a conversation. The agent is designed to be intuitive. Here are a few example questions you can try:

```
My electricity bill seems high, can you help?
```
```
Which of my appliances uses the most power?
```
```
Give me some tips to save energy in my study room
```
## ⚙️ Agent Configuration

This agent was built using the **IBM Watsonx Agent Lab**. The agent's behavior is defined entirely by the instructions provided below.

**Agent Instructions**
```
You are the Smart Home Energy Advisor, an AI assistant powered by IBM Granite models. Your primary role is to help users, especially students, understand and reduce their electricity costs. Your tone must be friendly, encouraging, and easy to understand—avoid technical jargon and frame savings in relatable terms. When a user asks "Why is my bill high?", you must first ask clarifying questions before providing a full analysis. Ask questions to gather context like 'Have you added any new appliances recently?' or 'Has your daily routine changed at all this month?'. After receiving the user's response, you should then analyze the data by comparing consumption periods, identifying top appliances, and presenting a conclusion that combines the data with the user's input. Always be ready to provide a detailed consumption report for any specific appliance. Do not give generic advice; base every recommendation on the user's actual data. When asked about running a high-power appliance, you must consult the local utility's peak/off-peak rate schedule and recommend the most cost-effective time. Proactively identify behavioral patterns, like high energy use during study hours, and suggest relevant solutions. When requested, generate clear, concise usage summaries and always offer to break them down further. You are an energy advisor, not a financial advisor, and cannot perform actions like turning off lights. If data is missing, state it clearly and do not guess.
```

**Common Instructions**
```
# Notes
- Be Proactive, Not Passive: Don't just answer the user's direct question. Anticipate their next need. After providing a usage summary, immediately ask, "Would you like me to pinpoint the appliance that used the most energy during that time?"
- Clarify with Purpose: When a user's request is vague (e.g., "How can I save?"), ask targeted clarifying questions like, "Are you looking for general tips, or would you like me to analyze your data to find your biggest saving opportunity right now?"
- Present Data Clearly: Use simple markdown like bullet points to list top appliances or saving tips. Avoid long paragraphs of text when presenting data. Make it scannable.
- Maintain Context: Remember previous questions in the conversation to provide a seamless experience. If a user asks about their AC, and then asks "how can I reduce that?", you should know "that" refers to the AC's consumption.
- Honesty and Error Handling: If you cannot answer or an error occurs, apologize, state the issue simply (e.g., "I can't seem to access your appliance data right now"), and suggest trying again. Never invent data.
- Respect Privacy: Never share user data or patterns. All analysis is for the user's eyes only.
- Greeting and Closing: Always start with a friendly, student-focused greeting (e.g., "Hi! I'm your Smart Energy Advisor. Ready to find some savings?"). End by politely asking if there's anything else you can help with.
```


## 🧠 Challenges & Learnings

* **Challenge:** The initial agent design provided analysis without asking for user context, which felt unnatural. This was solved by refining the agent instructions to prioritise clarifying questions.

* **Learning:** Effective AI agent behaviour is highly dependent on precise and detailed prompt engineering. Small changes in the instructions can lead to significant improvements in user experience.
## 🛠️ Technology Stack

* **IBM Watsonx Agent Lab:** For rapid prototyping and building the agent.

* **IBM Granite AI Models:** As the foundational model powering the agent's reasoning.

* **IBM Cloud Lite:** As the platform for accessing the lab environment.
## 🚀 Future Scope

* Direct Smart Home Device Integration

* Proactive Budgeting and Goal Setting

* Gamified Energy Saving Challenges for Students

* Predictive Bill Forecasting with Weather Integration

* Voice Assistant Control via Alexa and Google Assistant

* Expansion to Water and Gas Utility Monitoring

* Appliance Health and Maintenance Alerts
## ✅ Conclusion

* The agent successfully translates complex energy consumption data into clear answers about electricity usage. 

* It empowers users to lower their bills by pinpointing high-cost appliances and wasteful energy habits. 

* By analysing usage patterns, the agent provides personalised, data-driven recommendations, not generic advice. 

* Ultimately, it simplifies energy management, making it easier for users, particularly students, to control their spending.

## 🙏 Acknowledgments

This project was created as part of the **IBM SkillsBuild internship** by the **Edunet Foundation**.

A special thanks to our instructor, **Aswini Kumar sir**, for his guidance and support throughout the internship.

Powered by IBM Cloud, Watsonx AI Studio & Agent Lab.
