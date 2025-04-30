


# 🚦 SmartRouteRL  
_Reinforcement Learning for Intelligent Traffic Routing_



https://github.com/user-attachments/assets/15f32503-efe5-425c-9327-dda11569059b

<img width="1166" alt="RL_ss2" src="https://github.com/user-attachments/assets/5abfc7f1-5ef8-43bd-8510-ac81c5acdf50" />

<img width="1141" alt="RL_ss" src="https://github.com/user-attachments/assets/01fde095-05f4-480f-b852-0108689808d6" />

```markdown

### 💡 Overview  
SmartRouteRL is a reinforcement learning–powered route optimization framework built using Q-Learning and SARSA. Simulated with SUMO, it tackles urban traffic congestion by dynamically learning efficient routing strategies that outperform traditional algorithms like Dijkstra.

---

### 🧠 Tech Stack  
- **Language:** Python  
- **Simulator:** [SUMO](https://www.eclipse.dev/sumo/)  
- **Algorithms:** Q-Learning, SARSA  
- **Libraries:** NumPy, Matplotlib  

---

### ⚙️ Setup  

```bash
# Clone repository
git clone https://github.com/your-username/SmartRouteRL.git
cd SmartRouteRL

# Install dependencies
pip install -r requirements.txt

# Set SUMO path in main.py
os.environ["SUMO_HOME"] = "D:/path/to/SUMO"

# Run the project
python main.py
```

---

### 📊 Features  
- Adaptive route learning in static traffic networks  
- Customizable reward functions  
- Visual route and performance analysis  
- Baseline comparison with Dijkstra’s algorithm  
- Scenarios for increasing traffic density

---

### 📁 Project Structure  
```
SmartRouteRL/
│
├── agent.py            # RL agent logic
├── environment.py      # SUMO environment wrapper
├── main.py             # Training and execution script
├── utils.py            # Helper functions
├── network_files/      # SUMO network files
└── results/            # Output graphs and plots
```

---

### 📈 Visual Output  

```python
env.visualize_plot(edge_path)         # Route Map  
env.plot_performance(episodes, log)   # Learning Curve  
```

---

### 🛠️ Evaluation  
- Convergence speed of agents  
- Route efficiency vs Dijkstra  
- Adaptability to traffic scenarios  
- Reward scaling behavior

---

### 🧭 Use Cases  
- Smart city navigation  
- Simulation of urban mobility policies  
- Benchmarking intelligent transport systems  

---

### 🌍 Future Directions  
- Real-time data integration (e.g., live traffic)  
- Multi-agent RL models  
- Federated learning across city zones

---

> _SmartRouteRL — Driving smarter decisions, one route at a time._

