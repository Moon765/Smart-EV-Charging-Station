<h1 align="center">⚡ Smart EV Charging Station with Solar PV & Grid Integration ⚡</h1>

<p align="center">
  <img src="https://img.shields.io/badge/MATLAB-Simulink-orange?logo=mathworks" alt="MATLAB"/>
  <img src="https://img.shields.io/badge/EV-Charging-green?logo=evcharging" alt="EV Charging"/>
  <img src="https://img.shields.io/badge/Renewables-Solar%20PV-yellow?logo=solarpower" alt="Solar PV"/>
</p>

<p align="center">
  <b>Graduate project (ENEL 678, University of Calgary)</b><br>
  Design and simulation of a <b>smart EV charging station</b> integrating <b>Solar PV, Battery Energy Storage (BESS), and Grid</b> in MATLAB/Simulink.
</p>

---

<h2>📌 Project Overview</h2>
<p>
This project addresses the challenge of limited EV charging infrastructure in remote areas by proposing a <b>smart DC fast charging station</b> powered by:
<ul>
  <li>🌞 600 kW <b>Solar PV array</b></li>
  <li>🔋 550 kWh <b>Battery Energy Storage System (BESS)</b></li>
  <li>⚡ Utility Grid Integration (208V → 400V DC)</li>
</ul>

The system was designed, optimized, and validated in <b>MATLAB/Simulink</b>, focusing on <b>reliability, efficiency, and renewable integration</b>.
</p>

---

<h2>⚡ Features</h2>
<ul>
  <li>📊 <b>Load Analysis</b> – 5 DC fast chargers (150 kW each, 20–80% SoC in 20–30 mins)</li>
  <li>🌞 <b>PV Integration</b> – Fuzzy Logic-based MPPT controller with boost converter</li>
  <li>🔋 <b>BESS Integration</b> – SOC-based bidirectional DC/DC control</li>
  <li>⚡ <b>Grid Integration</b> – 3-phase transformer + PWM rectifier</li>
  <li>🔀 <b>Energy Management System (EMS)</b> – prioritizes Solar → Battery → Grid</li>
  <li>🔧 <b>EV Charger Model</b> – CCCV (Constant Current / Constant Voltage) charging protocol</li>
  <li>🖥️ <b>MATLAB/Simulink Simulation</b> – validated under varying load & irradiance</li>
</ul>

---

<h2>📂 Repository Structure</h2>


---

<h2>⚙️ Technical Specifications</h2>

- **Solar PV**: 600 kW, 200 parallel strings × 8 modules (375 W each)  
- **Battery**: Li-ion, 400V, 1400 Ah capacity  
- **DC Bus Voltage**: 400 V (±5%)  
- **EV Chargers**: 5 × 150 kW (CCCV charging)  
- **MPPT**: Fuzzy logic controller  
- **Simulation Environment**: MATLAB/Simulink  

---

<h2>📊 Validation Results</h2>
<ul>
  <li>✅ Stable DC bus voltage at ~400 V</li>
  <li>🌞 PV output ~580 kW at 1000 W/m² irradiance</li>
  <li>🔋 Battery SOC management validated with charge/discharge cycles</li>
  <li>⚡ EV charging at ~120–130 kW per charger</li>
  <li>🔀 EMS logic ensured optimal routing of solar, battery, and grid power</li>
</ul>

---

<h2>🌟 Future Improvements</h2>
<ul>
  <li>📡 Vehicle-to-Grid (V2G) capability</li>
  <li>🔋 Inductive / wireless charging</li>
  <li>📈 Advanced EMS with pricing & load forecasting</li>
  <li>⚠️ Full safety & protection schemes (surge, fault detection)</li>
</ul>

---

<h2>👨‍💻 Authors</h2>
<p>
Team 5 – ENEL 678 Graduate Project, University of Calgary  
<ul>
  <li>Md Mahadi Hasan Moon</li>
  <li>Safayetul Wahab Chowdhury</li>
  <li>Anik Kumar Paul</li>
  <li>Kankon Biswas</li>
  <li>Md Nazmul Hossain</li>
  <li>Md Imran Hossain</li>
</ul>
</p>

<p align="center">
  <i>“Integrating renewable energy with EV charging for a sustainable future ⚡🌱🚗”</i>
</p>
