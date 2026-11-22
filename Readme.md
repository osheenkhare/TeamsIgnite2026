# Build AI Agents in Teams [Ignite 2026 Lab]

## Overview

Most agentic interactions take place in a one-to-one chat. In this lab, you will create an agent that primarily works in collaborative spaces like group chats and channels in Microsoft Teams. Today you'll create an agent that achieves the following:

- Host your agent locally, connect it to Microsoft Teams using `socket` mode.
- Stream Messages in both one-to-one chats and collaborative spaces.
- Read channel conversations, pass it as context to the agent, and summarize threads.
- Pull live data from an external contract management system through MCP.
- Perform actions on external tools through MCP integration.
- Post shared Adaptive Cards that the whole channel can update.
- Send targeted messages to the person who took an action on an adaptive card.
- Post HTML widgets in the channel to display dynamic content.

We'll build this agent in a real Microsoft 365 Enterprise tenant with an Azure OpenAI key. You'll leave this lab with a fully functional collaborative agent you can reuse to help create your own Teams agent. This agent was built using the Teams SDK. The Teams SDK is available in TypeScript, .NET, and Python.


## Lab Breakdown

This lab is divided into 7 exercises:

| Exercise | Title |
| --- | --- |
| Exercise 0 | [Build your First Agent & Connect AI Resources](.instructions/Exercise-0.md) |
| Exercise 1 | [Bring Your Agent to Microsoft Teams](.instructions/Exercise-1.md) |
| Exercise 2 | [Enable Collaboration](.instructions/Exercise-2.md) |
| Exercise 3 | [Connect the Agent to External Tools](.instructions/Exercise-3.md) |
| Exercise 4 | [Generate Interactive Adaptive Cards](.instructions/Exercise-4.md) |
| Exercise 5 | [Send Targeted Messages from Adaptive Card Interactions](.instructions/Exercise-5.md) |
| Exercise 6 | [Render HTML Widgets](.instructions/Exercise-6.md) |

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

## Prerequisites

- A Microsoft 365 Enterprise tenant with appropriate permissions to create and manage Teams apps.
- An Azure subscription with permission to create and manage Azure OpenAI resources.
- Node.js and npm installed on your development machine.
- The Teams CLI installed and configured. Refer: [Teams CLI](https://www.npmjs.com/package/@microsoft/teams.cli)
- Basic familiarity with TypeScript, although no prior experience is required for this lab.