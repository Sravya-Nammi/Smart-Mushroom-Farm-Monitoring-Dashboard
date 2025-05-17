# 🍄 Smart Mushroom Farm Dashboard

A real-time web-based GUI designed to monitor and automate environmental control in mushroom fruiting chambers. This system was developed in collaboration with Pilzling GmbH to address real-world automation needs using Angular, MQTT, Docker, and Grafana.

---

## 🚀 Key Features of the User Interface

### 📊 1. Graphs Page

**Scenario:** A user notices a sudden temperature drop on the graph and wants to investigate.

This page displays live visualizations from Grafana, showing:
- Temperature
- Humidity
- CO₂ levels

These allow users to proactively detect abnormal conditions and take action.

**🖼️ Graphs Page:**  
 <br/>
<img src="https://i.imgur.com/ToLXgiy.png" height="80%" width="80%" />
<br />


---

### 🤖 2. Auto Mode Page

**Scenario:** A grower introduces a new mushroom strain ("Zitronenseitling") and sets the optimal growth phase ("Pinning").

Users can select:
- Mushroom strain (e.g., Rosenseitling, Zitronenseitling, Austern)
- Growth stage (e.g., Incubation, Inoculation, Pinning, Harvest)

The system automatically adjusts environmental conditions based on optimal parameters for the selected strain and phase.

**🖼️ Auto Mode Page:**  
 <br/>
<img src="https://i.imgur.com/r50d1OC.png" height="80%" width="80%"/>
<br />


---

### 🛠️ 3. Actuator Control Page

**Scenario:** The humidity rises unexpectedly, prompting the user to manually activate ventilation.

Users can manually toggle:
- Ventilation system
- Hot blowers
- Mistifiers

Allows direct control of the climate in fruiting chambers.

**🖼️ Actuator Control Page:**  
 <br/>
<img src="https://i.imgur.com/61YWBkd.png" height="80%" width="80%"/>
<br />


---

### 🎛️ 4. Custom Mode Page

**Scenario:** The grower wants to fine-tune exact temperature and humidity values for a unique mushroom variant.

Users can input desired values for:
- Temperature
- Humidity
- CO₂

Gives complete manual control over the environment.

**🖼️ Custom Mode Page:**  
 <br/>
<img src="https://i.imgur.com/r50d1OC.png" height="80%" width="80%"/>
<br />


---

### 🗂️ 5. Overview Page

**Scenario:** The user wants to compare current conditions across two chambers to identify imbalances.

Provides a side-by-side summary of:
- Mushroom strains
- Current temperature, humidity, and CO₂ levels
- Development phase

Facilitates fast comparison and condition tracking.

**🖼️ Overview Page:**  
 <br/>
<img src="https://i.imgur.com/PwqWtch.png" height="80%" width="80%"/>
<br />



---

## 🔧 Tech Stack

- **Frontend:** Angular, HTML, CSS, TypeScript
- **Visualization:** Grafana, InfluxDB
- **Backend Services:** Python, MQTT, ESP32 Integration
- **Deployment:** Docker, Virtual Machine
- **Monitoring:** Real-time sensor data display

**🖼️ System Architecture:**  
 <br/>
<img src="https://i.imgur.com/QXD8sKI.png" height="80%" width="80%"/>
<br />

---

## 🧪 Developed with Real-World Insights

This project was developed through iterative feedback and brainstorming with **Christian Vetter**, CEO of Pilzling GmbH, ensuring that every feature meets actual agricultural automation needs.

---
