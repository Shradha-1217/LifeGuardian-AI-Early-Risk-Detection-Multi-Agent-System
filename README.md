# 🌟 LifeGuardian AI

**Multi-Agent Early-Danger Detection & Prevention System for Daily Life**

![LifeGuardian AI Banner](https://via.placeholder.com/800x200.png?text=LifeGuardian+AI)

---

## 🏆 Project Overview

**LifeGuardian AI** is a **highly innovative multi-agent system** designed to monitor a user's digital behavior and daily habits to **predict and prevent hidden risks**.  

It focuses on:

- **Mental Health Risk** – stress, burnout, late-night activity  
- **Digital Safety Risk** – scams, suspicious links, risky online behavior  
- **Physical Health Risk** – irregular sleep, dehydration, overwork  
- **Productivity & Social Risk** – distractions, procrastination, social isolation  

> LifeGuardian AI acts like an **AI guardian angel**, detecting invisible risks, providing evidence-backed suggestions, and escalating emergencies when necessary.

---

## 🧩 Multi-Agent Architecture

LifeGuardian AI uses **5 interconnected agents**:

| Agent | Functionality | Key Features |
|-------|---------------|--------------|
| **Behavior Monitor Agent** | Tracks user activity, messages, sleep, and study patterns | Uses Memory Bank, sentiment analysis, flags stress and late-night activity |
| **Risk Detection Agent** | Evaluates risk scores based on behavior | Parallel processing, scoring algorithms, produces risk outputs |
| **Evidence Collector Agent** | Fetches scientific references to support detected risks | Web scraping, credible sources (WHO, APA, Sleep Foundation, PubMed) |
| **Guardian Action Agent** | Provides preventive actions to mitigate risks | Suggests exercises, breaks, sleep routines, digital safety checks |
| **Emergency Escalation Agent** | Triggers emergency protocols for repeated critical risks | Notifications (demo), distraction blocking, high-risk alerting |

---

## 🚀 Features

- **Multi-Agent System:** Combines sequential, parallel, and loop agents.  
- **Memory Bank:** Tracks long-term user behavior for personalized analysis.  
- **Evidence-Based Suggestions:** Uses real scientific sources to guide actions.  
- **Emergency Protocols:** Escalates high-risk situations for safety.  
- **Kaggle-Ready:** Fully compatible with Kaggle Notebook environment.  

---

## 🛠 Installation

**Requirements:**

- Python 3.9+  
- Kaggle Notebook or Local Python environment  

**Install Libraries:**

```bash
pip install textblob requests beautifulsoup4 lxml
````

**Download NLTK Data:**

```python
import nltk
nltk.download('punkt')
nltk.download('averaged_perceptron_tagger')
```

---

## 📝 Project Structure

```
LifeGuardian-AI/
│
├── behavior_memory.json           # Stores user activity logs
├── risk_memory_demo.json          # Stores risk scores
├── risk_evidence.json             # Stores collected evidence
├── escalation_memory.json         # Stores escalation events
├── agents/
│   ├── 1_behavior_monitor.ipynb
│   ├── 2_risk_detection.ipynb
│   ├── 3_evidence_collector.ipynb
│   ├── 4_guardian_action.ipynb
│   └── 5_emergency_escalation.ipynb
├── main_controller.ipynb          # Runs all agents sequentially
└── README.md
```

---

## 💻 Usage Instructions

1. Open Kaggle Notebook or Jupyter Notebook.
2. Run **Cell 1 – Setup** to install libraries and prepare the environment.
3. Execute each agent in order:

   1. **Behavior Monitor Agent** → detects stress and late-night behavior.
   2. **Risk Detection Agent** → calculates risk scores.
   3. **Evidence Collector Agent** → fetches references to support alerts.
   4. **Guardian Action Agent** → provides actionable suggestions.
   5. **Emergency Escalation Agent** → escalates critical risks.
4. Optionally, run **Main Controller** to execute all agents at once.
5. Observe alerts, evidence, suggested actions, and escalations directly in notebook output.

---

## 🔧 Example Workflow

1. User types a stressful message → **Behavior Monitor Agent** detects stress.
2. Late-night scrolling detected → **Risk Detection Agent** flags burnout and mental health risk.
3. **Evidence Collector Agent** fetches WHO guidelines for mental health.
4. **Guardian Action Agent** suggests grounding exercises, breaks, or adjusted schedules.
5. Repeated high-risk activity → **Emergency Escalation Agent** triggers a demo notification.

---

## 📂 Memory & Data Files

| File                     | Purpose                                                       |
| ------------------------ | ------------------------------------------------------------- |
| `behavior_memory.json`   | Stores all logged user activities and stress/late-night flags |
| `risk_memory_demo.json`  | Stores computed risk scores for each activity                 |
| `risk_evidence.json`     | Stores evidence from credible sources for each risk type      |
| `escalation_memory.json` | Stores repeated critical risk events for escalation           |

---

## 🧠 Technical Highlights

* **Multi-Agent Design**: Combines sequential, parallel, and loop processing.
* **Custom Risk Scoring**: Evaluates mental, physical, social, and digital risks.
* **Web Evidence Integration**: Scrapes credible resources to validate alerts.
* **Real-Time Alerts**: HTML output in Kaggle notebook for immediate visualization.
* **Persistent Memory**: JSON-based storage for session continuity.

---

## 📈 Future Enhancements

* Integrate **real-time chat/message API** to monitor live digital activity.
* Use **AI NLP models** for more accurate sentiment and risk detection.
* Add **mobile notifications** for real-time alerts.
* Implement **customizable thresholds** and personalized risk scoring.

---

## 👥 Contribution

We welcome contributions! Steps to contribute:

1. Fork the repository.
2. Create a new branch: `git checkout -b feature-name`.
3. Make changes and add tests.
4. Commit: `git commit -m "Add new feature"`.
5. Push: `git push origin feature-name`.
6. Open a Pull Request.

---

## 📜 License

This project is **open-source** under the MIT License.

---

## 🎯 Acknowledgements

* **Google ADK / Kaggle Notebook** – execution environment
* **NLTK & TextBlob** – sentiment analysis
* **BeautifulSoup & Requests** – web scraping evidence
* Inspiration from multi-agent AI design and “Agents for Good” competitions

---

## 🔗 Demo / Screenshots

<img width="767" height="618" alt="Screenshot 2025-11-30 231352" src="https://github.com/user-attachments/assets/6e5d15e6-236e-43dd-9f7b-befd4579280b" />
<img width="478" height="330" alt="Screenshot 2025-11-30 231406" src="https://github.com/user-attachments/assets/5d0497a2-df24-4609-96db-d0f03d36a891" />


---

**LifeGuardian AI – Your AI Guardian Angel for Everyday Life.**


