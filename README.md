⚡ Project Overview

MiroFish is a next-generation AI prediction engine based on multi-agent technology. By extracting seed information from the real world (such as breaking news, policy drafts, financial signals), it automatically builds a highly realistic parallel digital world.

Within this environment, thousands of intelligent agents—with independent personalities, long-term memory, and behavioral logic—interact freely and evolve socially.

You can inject variables dynamically from a “god’s perspective” to accurately simulate future outcomes:

👉 Let the future be rehearsed in a digital sandbox, so decisions succeed after countless simulations.

You only need to:
Upload seed materials (data analysis reports or even interesting stories)
Describe your prediction requirements using natural language
MiroFish will return:
A detailed prediction report
A highly interactive and realistic digital world
🌍 Our Vision

MiroFish aims to create a swarm intelligence mirror of reality by capturing emergent group behavior from individual interactions:

At the macro level:
A simulation lab for decision-makers to test policies and strategies without risk
At the micro level:
A creative sandbox for individuals to explore ideas, simulate stories, and experiment freely

👉 From serious forecasting to fun simulations, we make every “what if” visible—and make predicting anything possible.

🌐 Online Experience

You can try the demo here:
👉 https://666ghj.github.io/mirofish-demo/

This demo showcases prediction simulations of trending public opinion events.

📸 System Screenshots

(Screenshots showing different system interfaces and simulations)

🎬 Demo Videos
1. Wuhan University Public Opinion Simulation + MiroFish Explanation

Watch how MiroFish generates prediction reports based on public opinion data.

2. Lost Ending Prediction of Dream of the Red Chamber

MiroFish predicts the missing ending based on the first 80 chapters.

👉 More examples like financial forecasting and political simulations are coming soon.

🔄 Workflow
Graph Construction
Extract real-world data + inject individual/group memory + build GraphRAG
Environment Setup
Entity relationship extraction + character generation + simulation parameter setup
Start Simulation
Parallel simulation + automatic understanding of prediction goals + dynamic memory updates
Report Generation
ReportAgent interacts deeply with the simulation environment
Deep Interaction
Talk with agents inside the simulation or interact with ReportAgent
🚀 Quick Start
1. Source Code Deployment (Recommended)
Requirements
Tool	Version	Purpose
Node.js	18+	Frontend runtime
Python	3.11–3.12	Backend runtime
uv	Latest	Python package manager
Step 1: Configure Environment Variables
cp .env.example .env

Edit .env and add required API keys:

LLM_API_KEY=your_api_key
LLM_BASE_URL=https://dashscope.aliyuncs.com/compatible-mode/v1
LLM_MODEL_NAME=qwen-plus

ZEP_API_KEY=your_zep_api_key
Step 2: Install Dependencies
npm run setup:all

Or manually:

npm run setup
npm run setup:backend
Step 3: Start the Application
npm run dev

Access URLs:

Frontend: http://localhost:3000
Backend API: http://localhost:5001
Run separately:
npm run backend
npm run frontend
2. Docker Deployment
cp .env.example .env
docker compose up -d

Ports:

Frontend → 3000
Backend → 5001
📬 Community & Hiring

MiroFish team is hiring full-time and interns.
Send your resume to:

📧 mirofish@shanda.com

📄 Acknowledgements
Supported and incubated by Shanda Group
Powered by OASIS (CAMEL-AI open-source project)
📈 Project Stats

(Star history and GitHub analytics)
