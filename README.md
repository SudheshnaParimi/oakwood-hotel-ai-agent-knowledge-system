# oakwood-hotel-ai-agent-knowledge-system
An AI-powered hotel information assistant built using Microsoft Azure AI Foundry. This project demonstrates knowledge base integration, document retrieval, source citations, and accurate responses to guest queries.


🏨 Oakwood Hotel AI Agent – Knowledge System Implementation

📌 Project Overview

This project demonstrates the implementation of an AI-powered hotel information assistant using Microsoft Azure AI Foundry.

The Oakwood Hotel AI Agent is designed to answer guest questions by retrieving relevant information from uploaded hotel documents.

The agent provides accurate responses with source citations, helping guests access information about hotel policies, restaurant services, spa facilities, and local attractions.

🎯 Objective

The main objective of this experiment is to build and test a knowledge retrieval system that enables an AI agent to:

* Retrieve information from uploaded documents.
* Answer hotel-related guest queries.
* Handle complex and multi-topic questions.
* Provide source citations for responses.
* Avoid generating unsupported information.

🛠️ Technologies Used

* Microsoft Azure AI Foundry – AI agent development platform.
* Azure AI Agents – Agent configuration and testing.
* Vector Store – Document storage and retrieval.
* File Search – Knowledge retrieval from uploaded documents.

📂 Knowledge Base Documents

The following documents were uploaded to the agent’s knowledge base:

1. Hotel Policies
2. Restaurant Menus
3. Spa Service List
4. Local Area Guide
5. FAQ Compilation

These documents serve as the primary information sources for the AI agent.

⚙️ Implementation Steps

Step 1: Configure the AI Agent

* Opened Microsoft Azure AI Foundry.
* Navigated to the Agents section.
* Selected the hotel information agent.
* Accessed the Knowledge configuration.

Step 2: Upload Knowledge Documents

* Created a vector store.
* Uploaded the five hotel-related documents.
* Saved the knowledge base configuration.

Step 3: Configure Agent Instructions

Configured the agent with the following instructions:

Search all documents before responding.
Always cite sources using [Source: filename].
Prioritize hotel policies document for rules.
Check menus first for food questions.
Limit answers to information in documents.

Step 4: Test the AI Agent

Tested the agent using different types of guest questions.

Test Case 1: Restaurant Information

Question: What are the restaurant opening hours?

Expected Result: Retrieve relevant information from the restaurant menu document.

Test Case 2: Hotel Policies

Question: Can I check in early?

Expected Result: Retrieve check-in policies from the hotel policies document.

Test Case 3: Multiple Services

Question: What are the restaurant hours, and does the spa require reservations?

Expected Result: Retrieve information from both restaurant and spa documents.

Test Case 4: General Information

Question: Tell me about your hotel services.

Expected Result: Provide relevant information from the knowledge base.

✅ Results

The experiment was completed successfully.

* Knowledge base documents were uploaded successfully.
* The AI agent retrieved relevant information.
* The agent handled different types of guest queries.
* Responses included source citations.
* Multi-topic questions were handled successfully.
* The agent performed as expected during testing.

📚 Key Learnings

Through this experiment, I learned how to:

* Integrate a knowledge base with an AI agent.
* Configure document retrieval using Azure AI Foundry.
* Create effective agent instructions.
* Test AI agents with realistic user queries.
* Improve response reliability through source citations.

🏁 Conclusion

The Oakwood Hotel AI Agent knowledge system was successfully implemented and tested using Microsoft Azure AI Foundry.

The experiment demonstrated how an AI agent can retrieve relevant information from multiple documents and provide accurate, source-supported responses to guest queries.

This project helped me understand the fundamentals of knowledge base integration, retrieval-based AI systems, and AI agent testing.

👩‍💻 Author

Sudheshna Parimi

Course: AI Agent Fundamentals with Azure AI Foundry – Microsoft
