# 🖥️ SystemPulse — Automated System Monitoring Tool

## 📝 Overview

SystemPulse is a Python automation tool that monitors system resources and generates periodic log files.
It collects information about CPU usage, memory usage, disk usage, network activity, and running processes.

---

## 🚀 Features

* Automated system monitoring
* Periodic log file generation
* CPU and RAM usage tracking
* Disk usage reporting
* Network activity monitoring
* Running process information logging

---

## 🧩 Project Structure

```
SystemSurveillanceX.py   → Main monitoring script
```

---

## ⚙️ Tech Stack

* Python
* psutil
* schedule

---

## 📦 Installation

Install the required dependencies:

```
pip install psutil schedule
```

---

## ▶️ How to Run

Run the script using:

```
python SystemSurveillanceX.py <TimeInterval> <LogDirectory>
```

Example:

```
python SystemSurveillanceX.py 5 Logs
```

This will:

* Monitor the system every **5 minutes**
* Store log files inside the **Logs** directory

---

## 📊 Logged Information

Each log file includes:

* CPU usage
* RAM usage
* Disk usage
* Network data sent and received
* Running processes (PID, name, username, status, start time, CPU usage, memory usage)

---

## 🎯 Purpose

This project demonstrates **system monitoring, automation, and log generation using Python**.
