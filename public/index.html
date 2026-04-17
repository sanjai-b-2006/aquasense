<!DOCTYPE html>
<html lang="en" data-theme="dark">
<head>
<meta charset="UTF-8">
<link rel="manifest" href="/manifest.json">
<meta name="theme-color" content="#0f172a">
<meta name="viewport" content="width=device-width, initial-scale=1.0, viewport-fit=cover">
<title>WAMOT LAB Pro</title>
<script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">

<style>
:root {
  --bg-color: #0f172a;
  --bg-gradient: radial-gradient(circle at top, #0f172a, #020617);
  --card-bg: rgba(255,255,255,0.05);
  --card-border: rgba(255,255,255,0.1);
  --text-main: #ffffff;
  --text-muted: #94a3b8;
  --primary: #38bdf8;
  --primary-glow: rgba(56,189,248,0.4);
  --success: #22c55e;
  --danger: #ef4444;
  --warn: #f59e0b;
  --input-bg: rgba(255,255,255,0.1);
  --shadow: 0 10px 30px rgba(0,0,0,0.5);
}

[data-theme="light"] {
  --bg-color: #f8fafc;
  --bg-gradient: radial-gradient(circle at top, #ffffff, #e2e8f0);
  --card-bg: rgba(255,255,255,0.7);
  --card-border: rgba(0,0,0,0.1);
  --text-main: #0f172a;
  --text-muted: #475569;
  --primary: #0284c7;
  --primary-glow: rgba(2,132,199,0.3);
  --input-bg: rgba(0,0,0,0.05);
  --shadow: 0 10px 30px rgba(0,0,0,0.1);
}

* { box-sizing: border-box; }
body {
  margin: 0;
  font-family: 'Inter', sans-serif;
  background: var(--bg-gradient);
  background-attachment: fixed;
  color: var(--text-main);
  -webkit-text-size-adjust: 100%;
  transition: all 0.3s ease;
  min-height: 100vh;
}

/* Scrollbar customization */
::-webkit-scrollbar { width: 8px; }
::-webkit-scrollbar-track { background: transparent; }
::-webkit-scrollbar-thumb { background: var(--card-border); border-radius: 4px; }

/* TOAST NOTIFICATIONS */
.toast-container {
  position: fixed;
  top: 20px;
  right: 20px;
  z-index: 9999;
  display: flex;
  flex-direction: column;
  gap: 10px;
}
.toast {
  background: var(--card-bg);
  backdrop-filter: blur(15px);
  -webkit-backdrop-filter: blur(15px);
  border: 1px solid var(--card-border);
  padding: 12px 20px;
  border-radius: 12px;
  box-shadow: var(--shadow);
  display: flex;
  align-items: center;
  gap: 10px;
  animation: slideIn 0.3s ease forwards;
  opacity: 0;
  transform: translateX(100%);
  color: var(--text-main);
}
@keyframes slideIn {
  to { opacity: 1; transform: translateX(0); }
}
@keyframes fadeOut {
  to { opacity: 0; transform: translateX(100%); }
}

/* LOGIN */
.login-container {
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  padding: 20px;
}
.login-card {
  background: var(--card-bg);
  backdrop-filter: blur(25px);
  -webkit-backdrop-filter: blur(25px);
  border: 1px solid var(--card-border);
  padding: 40px 30px;
  border-radius: 24px;
  width: 100%;
  max-width: 360px;
  text-align: center;
  box-shadow: var(--shadow);
}
h2 { color: var(--primary); margin-top: 0; font-weight: 700; display: flex; align-items: center; justify-content: center; gap: 8px; }
.input-group {
  position: relative;
  margin: 15px 0;
}
.input-group i {
  position: absolute;
  left: 15px;
  top: 50%;
  transform: translateY(-50%);
  color: var(--text-muted);
}
.password-toggle {
  position: absolute;
  right: 15px;
  top: 50%;
  transform: translateY(-50%);
  cursor: pointer;
  color: var(--text-muted);
}
input {
  width: 100%;
  padding: 14px 45px 14px 45px;
  border-radius: 12px;
  border: 1px solid var(--card-border);
  background: var(--input-bg);
  color: var(--text-main);
  font-size: 16px;
  transition: all 0.3s ease;
}
input:focus {
  outline: none;
  border-color: var(--primary);
  box-shadow: 0 0 10px var(--primary-glow);
}
button {
  width: 100%;
  padding: 14px;
  margin-top: 10px;
  border-radius: 12px;
  border: none;
  background: linear-gradient(45deg, var(--primary), #06b6d4);
  color: #fff;
  cursor: pointer;
  font-weight: 600;
  font-size: 16px;
  transition: transform 0.2s, box-shadow 0.2s;
  box-shadow: 0 4px 15px var(--primary-glow);
}
button:hover { transform: translateY(-2px); box-shadow: 0 6px 20px var(--primary-glow); }
button:active { transform: translateY(0); }

/* TOPBAR */
.topbar {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 15px 25px;
  background: var(--card-bg);
  backdrop-filter: blur(15px);
  -webkit-backdrop-filter: blur(15px);
  border-bottom: 1px solid var(--card-border);
  margin-bottom: 20px;
}
.topbar-left { display: flex; align-items: center; gap: 15px; }
.topbar-logo { font-size: 20px; font-weight: 700; color: var(--primary); display: flex; align-items: center; gap: 8px;}
.topbar-right { display: flex; align-items: center; gap: 15px; }
.icon-btn {
  background: var(--input-bg);
  border: 1px solid var(--card-border);
  color: var(--text-main);
  width: 40px;
  height: 40px;
  border-radius: 50%;
  display: flex;
  justify-content: center;
  align-items: center;
  cursor: pointer;
  font-size: 16px;
  transition: 0.3s;
}
.icon-btn:hover { background: var(--primary); color: #fff; border-color: var(--primary); }
.clock { font-size: 14px; color: var(--text-muted); font-weight: 500; }
.sync-icon { transition: transform 1s; }
.syncing { transform: rotate(360deg); color: var(--primary); }

/* DASHBOARD */
.dashboard { display: none; }
.layout {
  display: flex;
  gap: 20px;
  padding: 0 20px 20px 20px;
  max-width: 1200px;
  margin: 0 auto;
}
.left, .right {
  display: flex;
  flex-direction: column;
  gap: 20px;
}
.left { flex: 1.2; }
.right { flex: 2; }

.card {
  background: var(--card-bg);
  backdrop-filter: blur(20px);
  -webkit-backdrop-filter: blur(20px);
  border: 1px solid var(--card-border);
  border-radius: 20px;
  padding: 20px;
  box-shadow: var(--shadow);
  text-align: center;
}
.card-header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin-bottom: 15px;
}
.card-header h2 { margin: 0; font-size: 18px; }

.value-display {
  font-size: 42px;
  font-weight: 700;
  margin: 10px 0;
  text-shadow: 0 0 15px var(--primary-glow);
}
.unit { font-size: 18px; color: var(--text-muted); font-weight: 400; }

.status {
  padding: 8px 16px;
  border-radius: 20px;
  font-size: 14px;
  font-weight: 600;
  display: inline-flex;
  align-items: center;
  gap: 8px;
  max-width: max-content;
  margin: 0 auto;
}
.good { background: rgba(34,197,94,0.2); color: var(--success); border: 1px solid var(--success); }
.warn { background: rgba(245,158,11,0.2); color: var(--warn); border: 1px solid var(--warn); }
.bad { background: rgba(239,68,68,0.2); color: var(--danger); border: 1px solid var(--danger); }

/* SETTINGS INPUTS (Thresholds) */
.settings-grid {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 15px;
  text-align: left;
}
.settings-group label {
  display: block;
  font-size: 13px;
  color: var(--text-muted);
  margin-bottom: 5px;
  font-weight: 600;
}
.settings-group input { padding: 10px; font-size: 14px; width: 100%; border-radius: 8px;}
.save-btn { padding: 10px; font-size: 14px; margin-top: 10px; border-radius: 8px;}

/* SWITCH & MOTOR CONTROL */
.motor-controls {
  display: flex;
  flex-direction: column;
  align-items: center;
  gap: 15px;
}
.switch-container { display: flex; align-items: center; gap: 15px; }
.switch { position: relative; width: 60px; height: 32px; }
.switch input { opacity: 0; width: 0; height: 0; }
.slider {
  position: absolute;
  cursor: pointer;
  top: 0; left: 0; right: 0; bottom: 0;
  background-color: var(--card-border);
  border-radius: 34px;
  transition: .4s;
}
.slider:before {
  position: absolute;
  content: "";
  height: 24px;
  width: 24px;
  left: 4px;
  bottom: 4px;
  background-color: white;
  border-radius: 50%;
  transition: .4s;
  box-shadow: 0 2px 5px rgba(0,0,0,0.2);
}
input:checked + .slider { background-color: var(--primary); box-shadow: 0 0 15px var(--primary-glow); }
input:checked + .slider:before { transform: translateX(28px); }

.mode-buttons { display: flex; gap: 10px; width: 100%; }
.mode-btn {
  flex: 1;
  background: var(--input-bg);
  color: var(--text-main);
  border: 1px solid var(--card-border);
  box-shadow: none;
  font-weight: 500;
}
.mode-btn.active {
  background: var(--primary);
  border-color: var(--primary);
  box-shadow: 0 4px 15px var(--primary-glow);
  color: #fff;
}
.mode-disabled { opacity: 0.5; pointer-events: none; }
.switch-label { font-weight: 700; font-size: 18px; width: 50px; text-align: left;}

/* CHART */
.chart-container {
  position: relative;
  height: 350px;
  width: 100%;
}
canvas { width: 100% !important; height: 100% !important; }

@media (max-width: 900px) {
  .layout { flex-direction: column; }
  .settings-grid { grid-template-columns: 1fr; }
}
@media (max-width: 480px) {
  .topbar { padding: 15px; }
  .clock { display: none; }
  .login-card { padding: 30px 20px; }
  .value-display { font-size: 32px; }
}
</style>
</head>
<body>

<div id="toastContainer" class="toast-container"></div>

<div class="login-container" id="loginScreen">
  <div class="login-card">
    <h2><i class="fa-solid fa-droplet"></i> WAMOT Pro</h2>
    <p style="color: var(--text-muted); margin-bottom: 25px; font-size: 14px;">Log in to remotely monitor and control your water system.</p>
    
    <div class="input-group">
      <i class="fa-solid fa-microchip"></i>
      <input id="device_id" type="text" placeholder="Device ID" autocomplete="off">
    </div>
    
    <div class="input-group">
      <i class="fa-solid fa-lock"></i>
      <input id="password" type="password" placeholder="Password">
      <i class="fa-solid fa-eye password-toggle" id="togglePassword" onclick="togglePass()"></i>
    </div>
    
    <button onclick="login()">Access Device <i class="fa-solid fa-arrow-right" style="margin-left: 5px;"></i></button>
  </div>
</div>

<div class="dashboard" id="dashboard">
  
  <div class="topbar">
    <div class="topbar-left">
      <div class="topbar-logo"><i class="fa-solid fa-droplet"></i> WAMOT</div>
      <div class="clock" id="clockDisplay">--:--:--</div>
    </div>
    <div class="topbar-right">
      <i class="fa-solid fa-rotate sync-icon" id="syncIcon" title="Sync Status"></i>
      <button class="icon-btn" onclick="toggleTheme()" title="Toggle Theme"><i class="fa-solid fa-moon" id="themeIcon"></i></button>
      <button class="icon-btn" onclick="toggleFullscreen()" title="Fullscreen"><i class="fa-solid fa-expand" id="fullscreenIcon"></i></button>
      <button class="icon-btn" onclick="logout()" title="Logout"><i class="fa-solid fa-right-from-bracket"></i></button>
    </div>
  </div>

  <div class="layout">
    <div class="left">
      
      <div class="card">
        <div class="card-header">
          <h2><i class="fa-solid fa-vial"></i> TDS Level</h2>
          <i class="fa-solid fa-circle-info" style="color: var(--text-muted);" title="Total Dissolved Solids"></i>
        </div>
        <div class="value-display" id="tds">-- <span class="unit">ppm</span></div>
        <div id="waterStatus" class="status">--</div>
      </div>

      <div class="card">
        <div class="card-header">
          <h2><i class="fa-solid fa-water"></i> Water Level</h2>
        </div>
        <div class="value-display" id="level">-- <span class="unit">%</span></div>
        <div class="progress-bar-container" style="background: var(--input-bg); height: 10px; border-radius: 5px; overflow: hidden; margin-top: 15px;">
            <div id="levelProgress" style="background: var(--primary); height: 100%; width: 0%; transition: width 0.5s;"></div>
        </div>
      </div>

      <div class="card">
        <div class="card-header">
          <h2><i class="fa-solid fa-gear"></i> Threshold Limits</h2>
        </div>
        <div class="settings-grid">
          <div class="settings-group">
            <label>Max Safe TDS (ppm)</label>
            <input type="number" id="tdsLimit" value="300">
          </div>
          <div class="settings-group">
            <label>Danger TDS (ppm)</label>
            <input type="number" id="tdsDanger" value="600">
          </div>
        </div>
        <button class="save-btn" onclick="saveThresholds()"><i class="fa-solid fa-check"></i> Save Limits</button>
      </div>

      <div class="card">
         <div class="card-header">
          <h2><i class="fa-solid fa-fan"></i> Motor Control</h2>
         </div>
         <div class="motor-controls">
            <div class="mode-buttons">
              <button class="mode-btn active" id="btnAuto" onclick="setMode('AUTO')">Auto</button>
              <button class="mode-btn" id="btnManual" onclick="setMode('MANUAL')">Manual</button>
            </div>
            
            <div id="switchContainer" class="switch-container" style="margin-top: 10px;">
              <span style="font-weight:600; color:var(--text-muted);">Relay:</span>
              <label class="switch">
                <input type="checkbox" id="relaySwitch" onchange="toggleRelay()">
                <span class="slider"></span>
              </label>
              <span class="switch-label" id="switchLabel" style="color: var(--text-muted)">AUTO</span>
            </div>
         </div>
      </div>

    </div>

    <div class="right">
      <div class="card">
         <div class="card-header">
           <h2><i class="fa-solid fa-chart-line"></i> Water Level History</h2>
           <button class="icon-btn" onclick="exportData()" title="Export CSV" style="width: 35px; height: 35px; font-size: 14px;"><i class="fa-solid fa-download"></i></button>
         </div>
         <div class="chart-container">
           <canvas id="chart"></canvas>
         </div>
      </div>
    </div>
  </div>
</div>

<script>
// STATE
let device_id = "";
let password = "";
let chart;
let manualOverride = false;
let currentMode = "AUTO";

// SETTINGS (Defaults)
let limitSafeTds = 300;
let limitDangerTds = 600;
let chartDataHistory = [];

// INIT FEATURES ON LOAD
window.onload = () => {
    loadTheme();
    loadThresholds();
    startClock();
};

function startClock() {
    setInterval(() => {
        const now = new Date();
        document.getElementById('clockDisplay').innerText = now.toLocaleDateString() + ' ' + now.toLocaleTimeString();
    }, 1000);
}

function showToast(message, type = 'success') {
    const container = document.getElementById('toastContainer');
    const toast = document.createElement('div');
    toast.className = 'toast';
    
    let icon = '';
    if(type === 'success') icon = '<i class="fa-solid fa-check-circle" style="color: var(--success); font-size: 20px;"></i>';
    if(type === 'error') icon = '<i class="fa-solid fa-circle-exclamation" style="color: var(--danger); font-size: 20px;"></i>';
    if(type === 'info') icon = '<i class="fa-solid fa-info-circle" style="color: var(--primary); font-size: 20px;"></i>';
    if(type === 'warn') icon = '<i class="fa-solid fa-triangle-exclamation" style="color: var(--warn); font-size: 20px;"></i>';

    toast.innerHTML = `${icon} <span style="font-weight: 500">${message}</span>`;
    container.appendChild(toast);

    setTimeout(() => {
        toast.style.animation = 'fadeOut 0.3s ease forwards';
        setTimeout(() => toast.remove(), 300);
    }, 3000);
}

function togglePass() {
    const passInput = document.getElementById("password");
    const toggleIcon = document.getElementById("togglePassword");
    if (passInput.type === "password") {
        passInput.type = "text";
        toggleIcon.classList.replace("fa-eye", "fa-eye-slash");
    } else {
        passInput.type = "password";
        toggleIcon.classList.replace("fa-eye-slash", "fa-eye");
    }
}

function toggleTheme() {
    const html = document.documentElement;
    const currentTheme = html.getAttribute('data-theme');
    const newTheme = currentTheme === 'dark' ? 'light' : 'dark';
    html.setAttribute('data-theme', newTheme);
    localStorage.setItem('wamot_theme', newTheme);
    updateThemeIcon(newTheme);
    if(chart) {
       Chart.defaults.color = newTheme === 'dark' ? '#94a3b8' : '#475569';
       chart.update();
    }
}

function loadTheme() {
    const savedTheme = localStorage.getItem('wamot_theme') || 'dark';
    document.documentElement.setAttribute('data-theme', savedTheme);
    updateThemeIcon(savedTheme);
}

function updateThemeIcon(theme) {
    const icon = document.getElementById('themeIcon');
    if(theme === 'dark') {
        icon.className = 'fa-solid fa-sun';
    } else {
        icon.className = 'fa-solid fa-moon';
    }
}

function toggleFullscreen() {
    if (!document.fullscreenElement) {
        document.documentElement.requestFullscreen().catch(err => {
            showToast(`Error attempting to enable fullscreen: ${err.message}`, 'error');
        });
        document.getElementById("fullscreenIcon").className = "fa-solid fa-compress";
    } else {
        document.exitFullscreen();
        document.getElementById("fullscreenIcon").className = "fa-solid fa-expand";
    }
}

function loadThresholds() {
    if (localStorage.getItem('wamot_tdsSafe')) {
        limitSafeTds = parseInt(localStorage.getItem('wamot_tdsSafe'));
        limitDangerTds = parseInt(localStorage.getItem('wamot_tdsDanger'));
    }
    document.getElementById("tdsLimit").value = limitSafeTds;
    document.getElementById("tdsDanger").value = limitDangerTds;
}

function saveThresholds() {
    limitSafeTds = parseInt(document.getElementById("tdsLimit").value);
    limitDangerTds = parseInt(document.getElementById("tdsDanger").value);
    localStorage.setItem('wamot_tdsSafe', limitSafeTds);
    localStorage.setItem('wamot_tdsDanger', limitDangerTds);
    showToast("Threshold limits saved successfully", "success");
    
    // Refresh status instantly with new bounds if we have a current TDS
    const currentTdsText = document.getElementById("tds").innerText;
    if (currentTdsText && currentTdsText !== '-- ppm') {
        updateWaterStatus(parseFloat(currentTdsText));
    }
}

function exportData() {
    if(chartDataHistory.length === 0) {
        showToast("No data to export", "warn");
        return;
    }
    let csvContent = "data:text/csv;charset=utf-8,Time,WaterLevel\n";
    chartDataHistory.forEach(row => {
        let timeLabel = new Date(row.created_at).toLocaleTimeString();
        csvContent += `${timeLabel},${row.water_level}\n`;
    });
    const encodedUri = encodeURI(csvContent);
    const link = document.createElement("a");
    link.setAttribute("href", encodedUri);
    link.setAttribute("download", "wamot_history.csv");
    document.body.appendChild(link);
    link.click();
    link.parentNode.removeChild(link);
    showToast("Data exported successfully", "success");
}

function logout() {
    device_id = "";
    password = "";
    document.getElementById("loginScreen").style.display = "flex";
    document.getElementById("dashboard").style.display = "none";
    document.getElementById("device_id").value = "";
    document.getElementById("password").value = "";
    showToast("Logged out successfully", "info");
}

// API CALLS & CORE LOGIC
async function login() {
  device_id = document.getElementById("device_id").value;
  password = document.getElementById("password").value;

  if(!device_id || !password) {
      showToast("Please enter both ID and Password", "error");
      return;
  }

  try {
      const res = await fetch("/api/login", {
        method: "POST",
        headers: {"Content-Type": "application/json"},
        body: JSON.stringify({ device_id, password })
      });

      const data = await res.json();
      if (!data.success) {
          showToast("Invalid Credentials. Access Denied.", "error");
          return;
      }

      showToast("Access Granted. Welcome!", "success");
      document.getElementById("loginScreen").style.display = "none";
      document.getElementById("dashboard").style.display = "block";

      // Setup charts theme
      Chart.defaults.color = document.documentElement.getAttribute('data-theme') === 'dark' ? '#94a3b8' : '#475569';
      Chart.defaults.font.family = "'Inter', sans-serif";

      syncData();
  } catch(e) {
      showToast("Network error. Please try again.", "error");
  }
}

async function syncData() {
    const syncIcon = document.getElementById("syncIcon");
    if(syncIcon) syncIcon.classList.add("syncing");
    
    await Promise.all([
        getData(),
        loadHistory(),
        getRelayState()
    ]);
    
    if(syncIcon) setTimeout(() => { syncIcon.classList.remove("syncing"); }, 500);
}

async function getData() {
  try {
      const res = await fetch("/api/get-data", {
        method: "POST",
        headers: {"Content-Type": "application/json"},
        body: JSON.stringify({ device_id, password })
      });
      const data = await res.json();

      let tdsVal = data.tds ?? "--";
      let lvlVal = data.water_level ?? "--";

      document.getElementById("tds").innerHTML = `${tdsVal} <span class="unit">ppm</span>`;
      document.getElementById("level").innerHTML = `${lvlVal} <span class="unit">%</span>`;

      if(lvlVal !== "--") {
          let clampedLvl = Math.max(0, Math.min(100, parseFloat(lvlVal)));
          document.getElementById("levelProgress").style.width = clampedLvl + "%";
          if(clampedLvl < 20) {
              document.getElementById("levelProgress").style.background = "var(--danger)";
          } else {
              document.getElementById("levelProgress").style.background = "var(--primary)";
          }
      }

      if(tdsVal !== "--") {
          updateWaterStatus(parseFloat(tdsVal));
      }
  } catch(e) {
  }
}

function updateWaterStatus(tds) {
  const status = document.getElementById("waterStatus");

  if (tds <= limitSafeTds) {
    status.innerHTML = '<i class="fa-solid fa-check"></i> Excellent (Drinkable)';
    status.className = "status good";
  } else if (tds < limitDangerTds) {
    status.innerHTML = '<i class="fa-solid fa-triangle-exclamation"></i> Moderate';
    status.className = "status warn";
  } else {
    status.innerHTML = '<i class="fa-solid fa-skull-crossbones"></i> Danger (Not Drinkable)';
    status.className = "status bad";
    if(status.dataset.lastState !== 'bad') {
        showToast(`Warning! TDS Limit Exceeded (${tds} ppm)`, "error");
    }
  }
  status.dataset.lastState = status.className.includes('bad') ? 'bad' : 'ok';
}

async function getRelayState() {
  if (manualOverride) return;

  try {
      const res = await fetch("/api/get-relay", {
        method: "POST",
        headers: {"Content-Type": "application/json"},
        body: JSON.stringify({ device_id, password })
      });
      const data = await res.json();
      updateRelayUI(data.relay || data.state);
  } catch(e) {}
}

function updateRelayUI(state) {
  const box = document.getElementById("switchContainer");
  const sw = document.getElementById("relaySwitch");
  const label = document.getElementById("switchLabel");

  if (state === "ON") {
    sw.checked = true;
    box.classList.remove("mode-disabled");
    label.innerText = "ON";
    label.style.color = "var(--primary)";
  } else if (state === "OFF") {
    sw.checked = false;
    box.classList.remove("mode-disabled");
    label.innerText = "OFF";
    label.style.color = "var(--text-muted)";
  } else {
    box.classList.add("mode-disabled");
    label.innerText = "AUTO";
    label.style.color = "var(--text-muted)";
  }
}

function toggleRelay() {
  if(currentMode === "AUTO") {
      showToast("Overriding AUTO mode...", "info");
      setMode("MANUAL");
  }
  
  manualOverride = true;
  const state = document.getElementById("relaySwitch").checked ? "ON" : "OFF";
  setRelay(state);
  showToast(`Motor manually turned ${state}`, "info");
  
  const label = document.getElementById("switchLabel");
  label.innerText = state;
  label.style.color = state === "ON" ? "var(--primary)" : "var(--text-muted)";

  setTimeout(() => manualOverride = false, 3000);
}

function setMode(mode) {
  currentMode = mode;
  manualOverride = true;
  
  document.getElementById("btnAuto").classList.remove("active");
  document.getElementById("btnManual").classList.remove("active");

  if (mode === "AUTO") {
    document.getElementById("btnAuto").classList.add("active");
    document.getElementById("switchContainer").classList.add("mode-disabled");
    document.getElementById("switchLabel").innerText = "AUTO";
    document.getElementById("switchLabel").style.color = "var(--text-muted)";
    setRelay("AUTO");
    showToast("System switched to AUTO mode", "success");
  } else {
    document.getElementById("btnManual").classList.add("active");
    document.getElementById("switchContainer").classList.remove("mode-disabled");
    showToast("System switched to MANUAL mode", "info");
  }

  setTimeout(() => manualOverride = false, 3000);
}

async function setRelay(state) {
  try {
      await fetch("/api/set-relay", {
        method: "POST",
        headers: {"Content-Type": "application/json"},
        body: JSON.stringify({ device_id, password, state })
      });
  } catch(e) {
      showToast("Error updating relay state", "error");
  }
}

async function loadHistory() {
  try {
      const res = await fetch("/api/get-history", {
        method: "POST",
        headers: {"Content-Type": "application/json"},
        body: JSON.stringify({ device_id, password })
      });

      const data = await res.json();
      if(!Array.isArray(data)) return;

      chartDataHistory = data; 

      const labels = data.map(d => new Date(d.created_at).toLocaleTimeString([], {hour: '2-digit', minute:'2-digit'}));
      const values = data.map(d => d.water_level);

      drawChart(labels, values);
  } catch(e) {}
}

function drawChart(labels, values) {
  if (chart) chart.destroy();

  const canvas = document.getElementById("chart");
  if(!canvas) return;
  const ctx = canvas.getContext("2d");

  const gradient = ctx.createLinearGradient(0, 0, 0, 400);
  gradient.addColorStop(0, 'rgba(56,189,248,0.5)');
  gradient.addColorStop(1, 'rgba(56,189,248,0.0)');

  chart = new Chart(ctx, {
    type: "line",
    data: {
      labels,
      datasets: [{
        label: "Water Level (%)",
        data: values,
        borderColor: "#38bdf8",
        backgroundColor: gradient,
        fill: true,
        tension: 0.4,
        pointRadius: 4,
        pointHoverRadius: 6,
        borderWidth: 3
      }]
    },
    options: {
      responsive: true,
      maintainAspectRatio: false,
      plugins: {
          legend: { display: false }
      },
      scales: {
          x: { grid: { color: 'rgba(148, 163, 184, 0.1)' } },
          y: { 
              grid: { color: 'rgba(148, 163, 184, 0.1)' },
              beginAtZero: true
          }
      }
    }
  });
}

// Periodic Updates
setInterval(() => {
  if (device_id) {
    syncData();
  }
}, 5000);
</script>

<script>
if ("serviceWorker" in navigator) {
  navigator.serviceWorker.register("/service-worker.js")
    .then(() => console.log("Service Worker Registered"));
}
</script>

</body>
</html>
