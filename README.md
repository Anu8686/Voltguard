# ⚡ VoltGuard

A Python-based application for monitoring and managing voltage and energy usage,
designed to improve power safety and efficiency in real time.

---

## 🔍 What It Does

- 📊 Monitors voltage and energy consumption in real time
- ⚠️ Alerts users when voltage exceeds safe thresholds
- 📈 Tracks energy usage over time for efficiency analysis
- 🔒 Designed with power safety as the core priority

---

## 🛠️ Installation

**Requirements:** Python 3.8+

```bash
# 1. Clone the repository
git clone https://github.com/Anu8686/Voltguard.git

# 2. Navigate into the project folder
cd Voltguard

# 3. Install dependencies
pip install -r requirements.txt

# 4. Run the application
python main.py
```

---

## 🚀 Usage Example

```python
from voltguard import Monitor

# Initialize the monitor with a safe voltage threshold
monitor = Monitor(threshold=240)

# Start monitoring
monitor.start()

# Check current voltage reading
print(monitor.current_voltage())  # Output: 235.4V — Safe

# Trigger alert if voltage exceeds threshold
monitor.check_alert()  # Output: ⚠️ Warning! Voltage at 248V exceeds limit.
```

---

## 📁 Project Structure
