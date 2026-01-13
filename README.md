<h1 align="center" style="color:#00F7FF; font-family: monospace;">
  PAVAN
</h1>

<p align="center" style="color:#9CA3AF; font-family: monospace;">
  Robotics • Embedded Systems • Python • System Architecture
</p>

<p align="center">
  <img src="assets/header.svg" alt="Cyberpunk HUD Animation" width="100%">
</p>

---

<h2 style="color:#00F7FF; font-family: monospace;">SYSTEM VIEW</h2>

<pre style="background-color:#0d1117;color:#00f7ff;padding:16px;border-radius:8px;">
┌────────────┐
│    SENSOR    │  Camera / Distance / State
└─────┬──────┘
      ↓
┌────────────┐
│ PERCEPTION │  Signal → Meaning
└─────┬──────┘
      ↓
┌────────────┐
│  DECISION  │  State Machines / Control Logic
└─────┬──────┘
      ↓
┌────────────┐
│ ACTUATION  │  Motors / Alerts / Response
└─────┬──────┘
      ↓
┌────────────┐
│ MONITORING │  Failure Detection / Recovery
└────────────┘
</pre>

<p style="color:#9CA3AF; font-family: monospace;">
I think in pipelines, states, and failure modes.  
If a system can’t fail safely, it’s not finished.
</p>

---

<h2 style="color:#00F7FF; font-family: monospace;">SELF-DESCRIBING SYSTEM</h2>

```python
class Engineer:
    def __init__(self):
        self.domain = ["Robotics", "Embedded Systems"]
        self.focus = [
            "System architecture",
            "Control logic",
            "Reliability under failure"
        ]
        self.method = "Build → Break → Analyze → Improve"

    def philosophy(self):
        return "If it works only once, it doesn't work."
