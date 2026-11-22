# Build AI Agents in Teams [Ignite 2026 Lab]

## Overview

Most agentic interactions take place in a one-to-one chat. In this lab, you will create an agent that primarily works in collaborative spaces like group chats and channels in Microsoft Teams. Today you'll create an agent that achieves the following:

- Read channel conversations and summarize threads.
- Pull live data from an external contract management system through MCP.
- Post shared Adaptive Cards that the whole channel can update.
- Send targeted messages to the person who took an action on an adaptive card.

We'll build this agent in a real Microsoft 365 Enterprise tenant with an Azure OpenAI key. You'll leave this lab with a fully functional collaborative agent you can reuse to help create your own Teams agent. This agent was built using the Teams SDK. The Teams SDK is available in TypeScript, .NET, and Python.

---

## Lab Breakdown

This lab is divided into 7 exercises:

### Exercise 0: Build your First Agent & Connect AI Resources

- Bootstrap your new agent
- Open your agent code
- Configure your Azure OpenAI LLM key
- Run the agent in Agents Playground

### Exercise 1: Bring Your Agent to Teams

- Set up a development tunnel
- Create a Teams app registration
- Sideload it in 1:1 chat
- Test streaming

### Exercise 2: Enable Collaboration

- Update RSC permissions
- Add the agent to a channel
- Test @mentions, thread reading, and summaries

### Exercise 3: Connect Tools via MCP

- Integrate contract management via MCP

### Exercise 4: Create Shared Checklists

- Generate a five-point checklist from conversation context
- Post the checklist as an Adaptive Card
- Sync updates across channel members

### Exercise 5: Send Targeted Notifications

- Notify users when checklist items are updated via private targeted messages

### Exercise 6: Render HTML Widgets

- Display a summary of current contracts in the system as HTML widgets

---

> **Note:** This lab is written in TypeScript. No prior knowledge is needed.

> **Help:** **If you are stuck in any part of the lab, please raise your hand to ask a proctor for help.**

---

## Exercises

| Exercise | Title |
| --- | --- |
| Exercise 0 | [Build your First Agent & Connect AI Resources](.instructions/Exercise-0.md) |
| Exercise 1 | [Bring Your Agent to Microsoft Teams](.instructions/Exercise-1.md) |
| Exercise 2 | [Enable Collaboration](.instructions/Exercise-2.md) |
| Exercise 3 | [Connect the Agent to External Tools](.instructions/Exercise-3.md) |
| Exercise 4 | [Generate Interactive Adaptive Cards](.instructions/Exercise-4.md) |
| Exercise 5 | [Send Targeted Messages from Adaptive Card Interactions](.instructions/Exercise-5.md) |
| Exercise 6 | [Render HTML Widgets](.instructions/Exercise-6.md) |

---

## Conclusion and Key Takeaways

- Built a **Microsoft Teams agent** that evolved from a local prototype into a collaborative teammate capable of working directly within Teams conversations.

- Configured an **Azure OpenAI** LLM resource on **Microsoft Foundry** and integrated the resource into your agent.

- Used the **Teams CLI** and **Dev Tunnel** to create, configure, sideload, and test the agent in Microsoft Teams.

- Used **Socket Mode** to connect your agent to Teams during development.

- Enabled collaboration through **Resource-Specific Consent (RSC)** permissions, allowing the agent to participate in channels, read conversation threads, respond to @mentions, and generate contextual summaries and next steps.

- Connected the agent to an external **Contract Management System using MCP**, enabling it to retrieve contract information and create new contract records from natural-language requests.

- Implemented **Adaptive Cards** that transform conversation context into a shared five-item checklist that multiple channel members can interact with and update in real time.

- Explored how Adaptive Card events are orchestrated, rendered, and synchronized across users.

- Added **Targeted Messaging**, enabling the agent to acknowledge individual users' card interactions privately without notifying other channel members.

- Added an **HTML widget**, enabling the agent to send an HTML document that Teams renders in a sandboxed iframe inside a chat message.

---