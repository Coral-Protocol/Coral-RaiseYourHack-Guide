# Coral Raise Your Hack Guide

## About Raise Your Hack 💻
This is your chance to push boundaries, solve real-world challenges, and create impact at the official hackathon of the [RAISE Summit 2025](https://www.raisesummit.com/) at one of Paris's most iconic venues: Le Carrousel du Louvre. RAISE Summit 2025 is a premier event convening the brightest minds across industries to accelerate innovation and drive the future of entrepreneurship, AI, and technology.

## About Coral Protocol 🪸

The [Coral Protocol](https://www.coralprotocol.org/) is an initiative to create an open, standardized infrastructure for AI agent coordination. It builds on the MCP framework to enable multiple AI agents to work together collaboratively, addressing the limitation of isolated AI systems that lack mechanisms for interconnected workflows. The Coral Protocol focuses on:

- Agent Collaboration: Allowing AI agents to communicate, share tasks, and coordinate in a structured way.

- Messaging Layer: Providing a system for agents to exchange messages, similar to human messaging platforms, with features like threads and mentions.

- Scalability and Openness: Designing an extensible, open-source solution that can support a wide range of AI applications, from customer support to project management.

We released the [Coral Server](https://github.com/Coral-Protocol/coral-server) as an open-source MCP server to serve as the backbone for this vision. The server acts as a messaging hub where AI agents can register, communicate via threads, and coordinate tasks by mentioning each other. The protocol aims to foster a community-driven ecosystem, encouraging developers to experiment, contribute, and build collaborative AI systems.

## About the Tracks 🎯

Coral Protocol is encouraged for teams interested in multi-agent systems, allowing them to integrate open-source agents from any framework. With its thread-based agent architecture, Coral enables scalable and predictable multi-agent interactions, making it a powerful tool for innovative applications. Build on one of the below tracks using Coral Protocol.

### Qualcomm Track

🧠 Edge AI Consumer Utility Application

<details>

Build a powerful, AI-driven utility app for everyday users—right at the edge.
In this track, you'll will develop a consumer-facing utility application that runs entirely on-device using the Snapdragon X Elite platform. The challenge is to harness the power of Edge AI to create a tool that is both useful and accessible to a broad audience—without relying on cloud connectivity.

🔍 What We’re Looking For:

• Consumer-Oriented: The app should appeal to a wide range of users and offer clear, everyday value.
• Utility-Focused: It must help users accomplish a task—whether it's organizing, creating, assisting, or enhancing their experience.
• Edge AI-Powered: The core functionality should include a probabilistic AI component (e.g., computer vision, audio processing, or generative AI) that runs locally in a resource-constrained environment.
• Cross-Platform: While the app targets Snapdragon X Elite, it should be compatible with Windows, macOS, and Linux.
• Developer-Ready: Submissions should include a GitHub repository with setup and run instructions. A polished consumer UI is not required—focus on functionality and innovation.

🛠️ Tech Flexibility:

• Use any programming language or framework.
• Combine multiple AI modalities (CV, audio, Gen AI) as needed.
• No internet connection should be required for core functionality.

Qualcomm will directly ship the Copilot+ PC with the Snapdragon® X Elite (loaner devices) to selected participants and collect them at the conclusion of the hackathon.

The hardware will be shipped on June 30th with next-day delivery.

</details>

### Prosus Track

🤖 Design an Agent-Powered E-Commerce App

<details>

Create an e-commerce application that uses AI agents to let users perform one or more of the following tasks:

•  Food ordering: Restaurant discovery, menu browsing, order placement
•  Travel Booking: Flight searches, hotel reservations, itinerary planning
•  Product Marketplace: New and second-hand item purchases

Your app should build a reusable user profile based on in-app conversations. This profile will help personalize experiences across different activities and should be stored as a knowledge graph.

Bonus Challenges:
•  Build a voice-first user interface
•  Support multimodal input for richer user interactions
•  Store the user profile as a knowledge graph

To Succeed in This Challenge:
• Focus on core functionality – show live, working features (live demo, not just slides!)
• Use pre-trained models and APIs to save time
• Keep your code modular and simple for easier debugging

Judges Will Focus On:
• Technical Execution – Does the MVP work reliably?
• AI Integration – How creatively and effectively is AI used?
• Originality & Impact – How novel is the idea, and does it solve a real-world problem?
• Agentic Capabilities – How useful, stable, and advanced are the agent-powered features?

⚠️ We encourage participants to explore a variety of technologies for this challenge, including: 
• SERP API
• Tavily
• Twilio
All of which offer free tiers for testing.

</details>

### Vultr Track

🧠 Agentic Workflows for the Future of Work

<details>

Build a Web-Based Enterprise Agent Deployed on Vultr

In this track, you'll design and develop a web-based AI agent purpose-built to support enterprise teams—from marketing to sales, operations, and beyond. Your mission: create a smart, agentic tool that simplifies, accelerates, or transforms workflows for today’s (and tomorrow’s) knowledge workers. The core app should be deployed on Vultr infrastructure and optimized for real-world business use cases.

🔍 What We’re Looking For:
• Enterprise-Ready: Your agent should address pain points or opportunities within marketing, sales, customer success, HR, or other enterprise functions.

• Agentic & Autonomous: Move beyond simple prompts. Build workflows where the agent can reason, plan, and act with minimal human input. Think multi-step tasks, decision trees, and feedback loops.

• Future-of-Work Focused: Help teams save time, make smarter decisions, or enhance collaboration—through the lens of what future employee experience could look like.

• Web-Based & Deployed on Vultr: The app must be a deployable web app running on Vultr. You can use any stack, language, or framework, but it should be cloud-hosted and publicly accessible (Vultr credits will be provided).

• Scalable Tooling: We encourage—but don’t require—use of technologies like vector databases, model context protocol (MCP), or other modular, scalable AI components.

🛠️ Tech Flexibility:
• Use any programming language or framework.
• Use open-source LLMs, retrieval-augmented generation. (Also available via Vultr Serverless Inference)

📦 Developer Expectations:
• Include a GitHub repo with setup instructions, agent capabilities, and a sample use case demo.
• Deploy on Vultr (we’ll provide credits and assistance).
• Show how your app solves a real problem in an enterprise context.

Each team leader of the Vultr Track will receive a coupon code to claim $250 in free credits on Vultr by signing up as a regular customer.

</details>

## Coral Example Usage

Checkout: [How to Build a Multi-Agent System with Awesome Open Source Agents using Coral Protocol](https://github.com/Coral-Protocol/existing-agent-sessions-tutorial-private-temp) to get started on building on Coral.

Set-up as per the given instructions and choose below agents.

### Qualcomm Track: Personal Finance Advisor

- A comprehensive personal finance advisor system that  to provides secure, intelligent, and privacy-preserving financial management through natural language interaction using Coral Monzo Agent.
- The Monzo Agent enables users to safely access and analyze their Monzo banking data using a local LLM, ensuring sensitive information never leaves their device. By integrating with Monzo’s official API and customized toolkits, the system supports conversational account balance checks, transaction history queries, and personalized financial advice.
- Agents: [Interface Agent](https://github.com/Coral-Protocol/Coral-Interface-Agent) | [Monzo Agent](https://github.com/Coral-Protocol/Coral-Monzo-Agent)
- How to run:

<details>

1. Follow the steps in [How to Build a Multi-Agent System with Awesome Open Source Agents using Coral Protocol](https://github.com/Coral-Protocol/existing-agent-sessions-tutorial-private-temp)

2. Pull the docker image

```bash
docker pull coralprotocol/coral-repounderstanding
```

3. Update the config by updating the "application.yml" file

```bash
applications:
  - id: "app"
    name: "Default Application"
    description: "Default application for testing"
    privacyKeys:
      - "default-key"
      - "public"
      - "priv"

registry:
  repounderstanding:
    options:
      - name: "OPENAI_API_KEY"
        type: "string"
        description: "OpenAI API Key"
      - name: "GITHUB_ACCESS_TOKEN"
        type: "string"
        description: "GitHub Access Token"

    runtime:
      type: "docker"
      environment:
        - name: "API_KEY"
          from: "OPENAI_API_KEY"
        - name: "GITHUB_ACCESS_TOKEN"
          from: "GITHUB_ACCESS_TOKEN"
      image: "coralprotocol/coral-repounderstanding:latest"

  deepresearch:
    options:
      - name: "OPENAI_API_KEY"
        type: "string"
        description: "OpenAI API Key"
      - name: "LINKUP_API_KEY"
        type: "string"
        description: "LinkUp API Key. Get from https://linkup.so/"

    runtime:
      type: "docker"
      environment:
        - name: "API_KEY"
          from: "OPENAI_API_KEY"
      image: "coralprotocol/coral-opendeepresearch:latest"

  interface:
    options:
      - name: "OPENAI_API_KEY"
        type: "string"
        description: "OpenAI API Key"
      - name: "HUMAN_RESPONSE"
        type: "string"
        description: "Human response to be used in the interface agent"

    runtime:
      type: "docker"
      image: "coralprotocol/coral-interface-agent:latest"
      environment:
        - name: "API_KEY"
          from: "OPENAI_API_KEY"
        - name: "HUMAN_RESPONSE"
          from: "HUMAN_RESPONSE"
```
</details>

### Prosus Track: Restaurant Agentic System Webapp

This project is a comprehensive restaurant voice agent system that combines [Interface Agent](https://github.com/Coral-Protocol/Coral-Interface-Agent) and [Restaurant Voice Agent](https://github.com/Coral-Protocol/Restaurant-Voice-Agent) to connect via coral protocol to provide an intelligent conversational experience for restaurant interactions.

### Vultr Track: How to setup Coral on Vultr

1. Sign up on Vultr and know more by looking into the [product documentation](https://docs.vultr.com/products)

2. Choose and host an instance as per your system requirements

![Vultr Instance](images/vultr-instance.png)

3. SSH into the instance (check IP) and enter the password of your instance

```bash
ssh root@95.179.233.169
```

4. Clone your system/ agent repository on the server and run

## Example 

