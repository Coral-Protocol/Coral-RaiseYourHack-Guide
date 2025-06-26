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

## Coral Example Usage 🎮

Checkout: [How to Build a Multi-Agent System with Awesome Open Source Agents using Coral Protocol](https://github.com/Coral-Protocol/existing-agent-sessions-tutorial-private-temp) to get started on building on Coral Protocol, set-up as per the given instructions and choose/ create agents as per your requirement.

### Qualcomm Track: Personal Finance Advisor

- A comprehensive personal finance advisor system that  to provides secure, intelligent, and privacy-preserving financial management through natural language interaction using Coral Monzo Agent.
- The Monzo Agent enables users to safely access and analyze their Monzo banking data using a local LLM, ensuring sensitive information never leaves their device. By integrating with Monzo’s official API and customized toolkits, the system supports conversational account balance checks, transaction history queries, and personalized financial advice.
- Agents: [Interface Agent](https://github.com/Coral-Protocol/Coral-Interface-Agent) | [Monzo Agent](https://github.com/Coral-Protocol/Coral-Monzo-Agent)


<details>

### 1. How to set up local model:

<details>

<summary>Click to expand Ollama instructions</summary>

Monzo Agent uses Ollama to run local LLM. Please make sure you have Ollama installed and the desired model downloaded before running the agent.

**1. Install Ollama**

- **Linux/macOS:**
  Follow the official instructions: [https://ollama.com/download](https://ollama.com/download)
  Or run:
  ```bash
  curl -fsSL https://ollama.com/install.sh | sh
  ```
- **Windows:**
  Download the installer from [Ollama's website](https://ollama.com/download).

**2. Download Local model**

```bash
ollama pull qwen3:latest
```

**3. Start Ollama Service**

Ollama usually starts automatically. If not, start it manually:
```bash
ollama serve
```

**4. Verify the model is running**

```bash
ollama list
```
Make sure no errors occur and Ollama is running at `http://localhost:11434`.

</details>

### 2. How to run:

<details>

<summary>Option 1: Agents running on docker without orchestrator:</summary>

Ensure that the [Coral Server](https://github.com/Coral-Protocol/coral-server) is running on your system

#### 1. Git clone and pull docker image

```bash
# Clone the repository
git clone https://github.com/Coral-Protocol/Qualcomn-Track-use-case-example----Personal-finance-advisor.git

# Pull docker images
docker pull coralprotocol/coral-interface-agent
docker pull coralprotocol/coral-monzo-agent
```

#### 2. Environment Configuration

##### For Coral Interface Agent:
Get the API Key: [OpenAI](https://platform.openai.com/api-keys).

Create a `.env` file in the `Coral-Interface-Agent` directory based on the `.env_sample` file:
```bash
cd Coral-Interface-Agent
cp -r .env_sample .env
# Edit .env with your specific configuration
```

##### For Monzo Agent:
Get the `MONZO_ACCESS_TOKEN` and `MONZO_ACCOUNT_ID`:[Monzo Developer Portal](https://developers.monzo.com/).

Create a `.env` file in the `Coral-Monzo-Agent` directory based on the `.env.example` file:
```bash
cd Coral-Monzo-Agent
cp -r env_example .env
# Edit .env with your specific configuration
```

#### 3. Run Agents in Separate Terminals

##### For Coral Interface Agent:

```bash
cd Coral-Interface-Agent
docker run --network host --env-file .env -it coralprotocol/coral-interface-agent
```

##### For Monzo Agent:

```bash
cd Coral-Monzo-Agent
docker run --network host --env-file .env -it coralprotocol/coral-monzo-agent
```

</details>

<details>

<summary>Option 2: Agents running on docker with orchestrator:</summary>

#### 1. Follow the steps in [How to Build a Multi-Agent System with Awesome Open Source Agents using Coral Protocol](https://github.com/Coral-Protocol/existing-agent-sessions-tutorial-private-temp)

#### 2. Pull the docker image

```bash
docker pull coralprotocol/coral-interface-agent
docker pull coralprotocol/coral-monzo-agent
```

#### 3. Update the config by updating the "application.yml" file

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

  monzo:
    options:
      - name: "MONZO_ACCESS_TOKEN"
        type: "string"
        description: "monzo access token"
      - name: "MONZO_ACCOUNT_ID"
        type: "string"
        description: "monzo account id"

    runtime:
      type: "docker"
      image: "coralprotocol/coral-monzo-agent:latest"
      environment:
        - name: "MONZO_ACCESS_TOKEN"
          from: "MONZO_ACCESS_TOKEN"
        - name: "MONZO_ACCOUNT_ID"
          from: "MONZO_ACCOUNT_ID"
```


</details>

<details>

<summary>Option 3: Agents running on executable with orchestrator:</summary>

#### 1. Follow the steps in [How to Build a Multi-Agent System with Awesome Open Source Agents using Coral Protocol](https://github.com/Coral-Protocol/existing-agent-sessions-tutorial-private-temp)

#### 2. Git clone the repository

```bash
# Clone the repository
git clone https://github.com/Coral-Protocol/Qualcomn-Track-use-case-example----Personal-finance-advisor.git
cd Qualcomn-Track-use-case-example----Personal-finance-advisor
```
#### 3. Update the config by updating the "application.yml" file

```bash
applications:
  - id: "app"
    name: "Default Application"
    description: "Default application for testing"
    privacyKeys:
      - "default-key"
      - "public"
      - "priv"

# Registry of agents we can orchestrate
registry:
  interface-local:
      options:
        - name: "OPENAI_API_KEY"
          type: "string"
          description: "OpenAI API Key"
        - name: "HUMAN_RESPONSE"
          type: "string"
          description: "Human response to be used in the interface agent"
  
      runtime:
        type: "executable"
        command:
          [
            "bash",
            "-c",
            "cd ../Coral-Interface-Agent && uv sync && uv run 0-langchain-interface.py",
          ]
        environment:
          - name: "API_KEY"
            from: "OPENAI_API_KEY"
          - name: "HUMAN_RESPONSE"
            from: "HUMAN_RESPONSE"

  Monzo:
      options:
        - name: "MONZO_ACCESS_TOKEN"
          type: "string"
          description: "monzo access token"
        - name: "MONZO_ACCOUNT_ID"
          type: "string"
          description: "monzo account id"
  
      runtime:
        type: "executable"
        command:
          [
            "bash",
            "-c",
            "cd ../Coral-Monzo-Agent && uv sync && uv run langchain-monzo-agent.py",
          ]
        environment:
          - name: "MONZO_ACCESS_TOKEN"
            from: "MONZO_ACCESS_TOKEN"
          - name: "MONZO_ACCOUNT_ID"
            from: "MONZO_ACCOUNT_ID"
```


</details>

<details>

<summary>Option 4: Agents running without docker or orchestrator:</summary>

Ensure that the [Coral Server](https://github.com/Coral-Protocol/coral-server) is running on your system

#### 1. Git clone the repository and install dependencies

```bash
# Clone the repository
git clone https://github.com/Coral-Protocol/Qualcomn-Track-use-case-example----Personal-finance-advisor.git

# Install `uv`:
pip install uv
```

##### For Coral Interface Agent
```bash
# Navigate to the interface agent agent directory
cd Coral-Interface-Agent

# Install dependencies from `pyproject.toml` using `uv`:
uv sync
```

##### For Monzo Agent
```bash
# Navigate to the monzo agent directory
cd Coral-Monzo-Agent

# Install dependencies from `pyproject.toml` using `uv`:
uv sync
```

#### 2. Environment Configuration

##### For Coral Interface Agent
Get the API Key: [OpenAI](https://platform.openai.com/api-keys).

Create a `.env` file in the `Coral-Interface-Agent` directory based on the `.env_sample` file:
```bash
cd Coral-Interface-Agent
cp -r .env_sample .env
# Edit .env with your specific configuration
```

##### For Monzo Agent
Get the `MONZO_ACCESS_TOKEN` and `MONZO_ACCOUNT_ID`:[Monzo Developer Portal](https://developers.monzo.com/).

Create a `.env` file in the `Coral-Monzo-Agent` directory based on the `.env.example` file:
```bash
cd Coral-Monzo-Agent
cp -r env_example .env
# Edit .env with your specific configuration
```

#### 3. Run Agents in Separate Terminals

###### For Coral Interface Agent:

```bash
cd Coral-Interface-Agent
uv run 0-langchain-interface.py
```

###### For Monzo Agent:

```bash
cd Coral-Monzo-Agent
uv run langchain-monzo-agent.py
```

</details>

### 3. How to use:

<details>

<summary>Click to expand sample input/output</summary>

#### 1. Input

```bash

```

#### 2. Output

```bash

```
</details>

</details>

### Prosus Track: Restaurant Agentic System Webapp

- A comprehensive restaurant voice agent system to provide an intelligent conversational experience for restaurant interactions.
- A voice-enabled system that handles customer reservations, takeaway orders, and payments without human staff intervention
- Uses Interface Agent to coordinate user instructions and Restaurant Voice Agent to manage real-time voice conversations across specialized functions
- Agents: [Interface Agent](https://github.com/Coral-Protocol/Interface-Agent-for-Webapp) | [Restaurant Voice Agent](https://github.com/Coral-Protocol/Restaurant-Voice-Agent)
- [Demo Video](https://drive.google.com/file/d/1LtUfTUzV9MPEPY7b4alElDiJoml7E089/view)

<details>

### 1. How to run:

<details>

<summary>Option 1: Agents running on docker without orchestrator:</summary>

Ensure that the [Coral Server](https://github.com/Coral-Protocol/coral-server) is running on your system

#### 1. Git clone and pull docker image

```bash
# Clone the repository
git clone https://github.com/Coral-Protocol/Restaurant-Agentic-Webapp

# Pull docker images
docker pull coralprotocol/coral-interface-agent-for-webapp
docker pull coralprotocol/coral-restaurant-voice-agent
```

#### 2. Environment Configuration

##### For Coral Interface Agent:
Get the API Key: [Groq](https://console.groq.com/keys).

Create a `.env` file in the `Interface-Agent-for-Webapp` directory based on the `.env_sample` file:
```bash
cd Interface-Agent-for-Webapp
cp -r .env_sample .env
# Edit .env with your specific configuration
```

##### For Restaurant Agent:
Get these api keys
GROQ_API_KEY=[Groq](https://console.groq.com/keys).

Note: If you want to use cloud services by Livekit then use [Livekit Cloud](https://cloud.livekit.io/) for these api keys and url but for Self hosting you can check out their documentation for [Self Hosting](https://docs.livekit.io/home/self-hosting/local/).

LIVEKIT_API_KEY=your_livekit_api_key_here 

LIVEKIT_API_SECRET=your_livekit_api_secret_here 

LIVEKIT_URL=your_livekit_url_here  

Create a `.env` file in the `Restaurant-Voice-Agent` directory based on the `.env.example` file:
```bash
cd Restaurant-Voice-Agent
cp -r env.example .env
# Edit .env with your specific configuration
```

#### 3. Run Agents in Separate Terminals

##### For Coral Interface Agent:

```bash
cd Interface-Agent-for-Webapp
docker run --env-file .env -it coralprotocol/coral-interface-agent-for-webapp
```

##### For Restaurant Agent:
Note: When running with docker you have to interact with the livekit agent using the UI with the same Livekit api key, secret key and url as the voice input will be from your UI.

```bash
cd Restaurant-Voice-Agent
docker run --env-file .env -it coralprotocol/coral-restaurant-voice-agent
```

</details>

<details>

<summary>Option 2: Agents running on docker with orchestrator:</summary>

#### 1. Follow the steps in [How to Build a Multi-Agent System with Awesome Open Source Agents using Coral Protocol](https://github.com/Coral-Protocol/existing-agent-sessions-tutorial-private-temp)

#### 2. Pull the docker image

```bash
docker pull coralprotocol/coral-interface-agent-for-webapp
docker pull coralprotocol/coral-restaurant-voice-agent
```

#### 3. Update the config by updating the "application.yml" file in the Coral Server:

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
  interface:
    options:
      - name: "GROQ_API_KEY"
        type: "string"
        description: "Groq API Key"
      - name: "HUMAN_RESPONSE"
        type: "string"
        description: "Human response to be used in the interface agent"

    runtime:
      type: "docker"
      image: "coralprotocol/coral-interface-agent-for-webapp:latest"
      environment:
        - name: "API_KEY"
          from: "GROQ_API_KEY"
        - name: "HUMAN_RESPONSE"
          from: "HUMAN_RESPONSE"

  restaurant:
    options:
      - name: "LIVEKIT_URL"
        type: "string"
        description: "LiveKit Server URL"
      - name: "LIVEKIT_API_KEY"
        type: "string"
        description: "LiveKit API Key"
      - name: "LIVEKIT_API_SECRET"
        type: "string"
        description: "LiveKit API Secret"
      - name: "GROQ_API_KEY"
        type: "string"
        description: "Groq API Key"
      - name: "DEEPGRAM_API_KEY"
        type: "string"
        description: "Deepgram API Key"
      - name: "CARTESIA_API_KEY"
        type: "string"
        description: "Cartesia API Key"

    runtime:
      type: "docker"
      image: "coralprotocol/coral-restaurant-agent:latest"
      environment:
        - name: "LIVEKIT_URL"
          from: "LIVEKIT_URL"
        - name: "LIVEKIT_API_KEY"
          from: "LIVEKIT_API_KEY"
        - name: "LIVEKIT_API_SECRET"
          from: "LIVEKIT_API_SECRET"
        - name: "API_KEY"
          from: "GROQ_API_KEY"
        - name: "DEEPGRAM_API_KEY"
          from: "DEEPGRAM_API_KEY"
        - name: "CARTESIA_API_KEY"
          from: "CARTESIA_API_KEY"
```


</details>

<details>

<summary>Option 3: Agents running on executable with orchestrator:</summary>

#### 1. Follow the steps in [How to Build a Multi-Agent System with Awesome Open Source Agents using Coral Protocol](https://github.com/Coral-Protocol/existing-agent-sessions-tutorial-private-temp)

#### 2. Git clone the repository

```bash
# Clone the repository
git clone https://github.com/Coral-Protocol/Restaurant-Agentic-Webapp
cd Restaurant-Agentic-Webapp
```
#### 3. Update the config by updating the "application.yml" file

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
  interface-local:
    options:
      - name: "GROQ_API_KEY"
        type: "string"
        description: "Groq API Key"
      - name: "HUMAN_RESPONSE"
        type: "string"
        description: "Human response to be used in the interface agent"

    runtime:
      type: "executable"
      command:
        [
          "bash",
          "-c",
          "cd ../Interface-Agent-for-Webapp && uv sync && uv run 0-langchain-interface.py",
        ]
      environment:
        - name: "API_KEY"
          from: "GROQ_API_KEY"
        - name: "HUMAN_RESPONSE"
          from: "HUMAN_RESPONSE"

  restaurant:
    options:
      - name: "LIVEKIT_URL"
        type: "string"
        description: "LiveKit Server URL"
      - name: "LIVEKIT_API_KEY"
        type: "string"
        description: "LiveKit API Key"
      - name: "LIVEKIT_API_SECRET"
        type: "string"
        description: "LiveKit API Secret"
      - name: "GROQ_API_KEY"
        type: "string"
        description: "Groq API Key"
      - name: "DEEPGRAM_API_KEY"
        type: "string"
        description: "Deepgram API Key"
      - name: "CARTESIA_API_KEY"
        type: "string"
        description: "Cartesia API Key"

    runtime:
      type: "executable"
      command:
        [
          "bash",
          "-c",
          "cd ../Restaurant-Voice-Agent&& uv sync && uv run main.py console", 
        ]
      environment:
        - name: "LIVEKIT_URL"
          from: "LIVEKIT_URL"
        - name: "LIVEKIT_API_KEY"
          from: "LIVEKIT_API_KEY"
        - name: "LIVEKIT_API_SECRET"
          from: "LIVEKIT_API_SECRET"
        - name: "API_KEY"
          from: "GROQ_API_KEY"
        - name: "DEEPGRAM_API_KEY"
          from: "DEEPGRAM_API_KEY"
        - name: "CARTESIA_API_KEY"
          from: "CARTESIA_API_KEY"

```


</details>

<details>

<summary>Option 4: Agents running without docker or orchestrator:</summary>

Ensure that the [Coral Server](https://github.com/Coral-Protocol/coral-server) is running on your system

#### 1. Git clone the repository and install dependencies

```bash
# Clone the repository
git clone https://github.com/Coral-Protocol/Restaurant-Agentic-Webapp

# Install `uv`:
pip install uv
```

##### For Coral Interface Agent
```bash
# Navigate to the interface agent agent directory
cd Interface-Agent-for-Webapp

# Install dependencies from `pyproject.toml` using `uv`:
uv sync
```

##### For Restaurant Agent
```bash
# Navigate to the monzo agent directory
cd Restaurant-Voice-Agent

# Install dependencies from `pyproject.toml` using `uv`:
uv sync
```

#### 2. Environment Configuration

##### For Coral Interface Agent
Get the API Key:
[Groq](https://console.groq.com/keys)

Create a `.env` file in the `Interface-Agent-for-Webapp` directory based on the `.env_sample` file:
```bash
cd Interface-Agent-for-Webapp
cp -r .env_sample .env
# Edit .env with your specific configuration
```

##### For Restaurant Agent
Get these api keys
GROQ_API_KEY=[Groq](https://console.groq.com/keys).

Note:
If you want to use cloud services by Livekit then use [Livekit Cloud](https://cloud.livekit.io/) for these api keys and url but for Self hosting you can check out there documentation for [Self Hosting](https://docs.livekit.io/home/self-hosting/local/).

LIVEKIT_API_KEY=your_livekit_api_key_here 
LIVEKIT_API_SECRET=your_livekit_api_secret_here  
LIVEKIT_URL=your_livekit_url_here 

Create a `.env` file in the `Restaurant-Voice-Agent` directory based on the `.env.example` file:
```bash
cd Restaurant-Voice-Agent
cp -r env.example .env
# Edit .env with your specific configuration
```
#### UI Frontend
To use the UI do this setup in a separate terminal:
```bash
cd UI
npm install
```
Create a `.env.local` file in the `UI` directory:
```bash
# Create .env.local with these variables:

# LiveKit Configuration
LIVEKIT_API_KEY=your_livekit_api_key_here 
LIVEKIT_API_SECRET=your_livekit_api_secret_here  
LIVEKIT_URL=your_livekit_url_here  

# API Endpoint Configuration (for Interface Agent)
NEXT_PUBLIC_CONN_DETAILS_ENDPOINT=/api/connection-details

# Interface Agent API Endpoint (default: http://localhost:8000)
NEXT_PUBLIC_INTERFACE_AGENT_API_ENDPOINT=http://localhost:8000
```

#### 3. Run Agents in Separate Terminals
Start all three components in their respective terminals:

#### Terminal 1: Start Coral Interface Agent
```bash
cd Interface-Agent-for-Webappt
uv run 0-langchain-interface.py
```

#### Terminal 2: Start Restaurant Voice Agent
```bash
cd Restaurant-Voice-Agent
uv run main.py dev
```

#### Terminal 3: Start UI Frontend
```bash
cd UI
npm run dev
```

</details>

### 2. How to Connect to UI:

<summary>Click to expand UI app running instructions</summary>

<details>

- Access the Application: Open your browser and navigate to the UI application (typically http://localhost:3000)

- Try Now Button: Click the "Try Now" button to be directed to the main page

- Start Conversation: On the main page, press the "Start Conversation" button for the restaurant agent

- Interact: You can now chat with the agentic system for restaurant-related queries and interactions

</details>

### 3. How to use:

<summary>Click to expand sample input/output</summary>

<details>

#### 1. Input

```bash

```

#### 2. Output

```bash

```
</details>

</details>

### Vultr Track: How to setup Coral on Vultr

- Sign up on Vultr and know more by looking into the [product documentation](https://docs.vultr.com/products)

- Choose and host an instance as per your system requirements

![Vultr Instance](images/vultr-instance.png)

- SSH into the instance (check IP) and enter the password of your instance

```bash
ssh root@95.179.233.169
```

<details>

### 1. How to run:

1. Follow the steps in [How to Build a Multi-Agent System with Awesome Open Source Agents using Coral Protocol](https://github.com/Coral-Protocol/existing-agent-sessions-tutorial-private-temp)

2. Build your multi-agent system and clone your system/ agent repository on the server and run.

</details>

(NOTE: The examples above are just to demonstrate how to use Coral. For the hackathon you have to create you own use case by either selecting from the list of agents from our [awesome agent list](https://github.com/Coral-Protocol/awesome-agents-for-multi-agent-systems) or create your own agents compatible on Coral.)

