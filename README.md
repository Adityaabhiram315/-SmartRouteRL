🚦 SmartRouteRL
Reinforcement Learning–Based Traffic Routing Optimization
Solving urban congestion through intelligent route planning

✨ Overview
SmartRouteRL leverages Q-Learning and SARSA algorithms within a SUMO-simulated traffic environment to optimize vehicular routing in congested cities. Designed with efficiency and scalability in mind, it aims to outperform traditional models by learning dynamic routing policies.

🧠 Core Tech Stack
Python · NumPy · Matplotlib

SUMO (Simulation of Urban Mobility)

Q-Learning & SARSA (TD Algorithms)

🔍 Features
RL-driven route decision-making

Adjustable reward functions

Visual performance tracking

Scalable to real-world maps (e.g., Sunway City)

Comparative evaluation against Dijkstra’s algorithm

🚀 Setup
bash
Copy
Edit
# 1. Clone repo
git clone <repo_url>
cd SmartRouteRL

# 2. Install dependencies
pip install -r requirements.txt

# 3. Set SUMO directory
# main.py
os.environ["SUMO_HOME"] = "D:/path/to/SUMO/"

# 4. Run
python main.py
🧪 Evaluation Metrics
Policy Convergence Speed

Route Efficiency (time & distance)

Computational Performance

Traffic Density Response

📈 Visualizations
python
Copy
Edit
env.visualize_plot(edge_path)        # Route Map  
env.plot_performance(episodes, log)  # Learning Curve
🌍 Future Scope
Real-time traffic API integration

Multi-agent RL deployment

Reward shaping for real-world constraints

A cleaner city starts with smarter routing.
Crafted for cities that move.
