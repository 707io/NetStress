# NetStress

**NetStress** is a Python-based project created for learning and practicing network stress-testing in a controlled lab environment. 
It demonstrates how UDP traffic floods work and how multi-threading can impact performance.

⚠️ It is designed **strictly for educational and research purposes** such as:

- Demonstrating the principles of denial-of-service (DoS) attacks in a **controlled environment**
- Testing resilience of your own lab servers or simulated IoT devices
- Red team training and cybersecurity courses

> **Disclaimer:**
> This tool must only be used in lab environments you own or have explicit authorization to test.
> Unauthorized use against networks, services, or devices is illegal.

---

## ✨ Features

- **Single-threaded UDP traffic generator**
- **Multi-threaded UDP stress tester** (configurable number of threads)
- **HTTP flood simulation** with randomized request paths
- **Customizable packet size, ports, and request count**
- **Real-time progress logging per thread**

---

## 📦 Requirements

- Python 3.x
- Standard libraries (`socket`, `threading`, `time`, `random`, `sys`, `string`, `datetime`)

No external dependencies are required.

---

## 🚀 Usage

```bash
python netstress.py
```

Choose:
1. **Single-thread attack (basic)**
2. **Multi-thread attack (Pisowifi / IoT stress test)**

---

## ⚙️ Example Output

```
Select attack mode:
1. Single-thread attack (Router)
2. Multi-thread attack (Pisowifi)
Enter your choice (1 or 2): 2
Enter Gateway IP : 192.168.1.1
Enter Starting Port : 80
Enter Number of Threads (1-50): 10
Starting 10 threads to attack 192.168.1.1
Thread 1 started attacking 192.168.1.1:80
Thread 2 started attacking 192.168.1.1:81
...
```

---

## 🔒 Legal & Ethical Notice

This project is provided for **educational use only**. Running it against targets without permission is:

- Illegal under computer misuse and cybercrime laws
- Potentially disruptive to real-world services

**Always limit testing to your own devices or lab networks.**

---

## 🏷️ Credit

Made by **707** ([github.com/707io](https://github.com/707io))

