# RuralGuard
# 🌍Overview

RuralGuard is a **distributed mobile-based incident Control and Support Relay(ICSR) system** designed for rural African communities. Many regions lack **fast emergency reporting and coordination**, leading to delayed responses and preventable losses. RuralGuard allows citizens to report incidents via a mobile app while automatically connecting them to local responders or nearby communities even during network outages.

# 🚨Problem
- Emergencies (fires, accidents, floods, health crisis) often go unreported in rural areas.
- Centralised systems fail during outages.
- Local Communities often lack reliable, low-cost and fault-tolerant reporting systems.

# ⛓️How it works
- **Frontend:** Citizens report incidents with GPS, photos, and descriptions. Works offline and syncs automatically. Responders receive realt time alerts
- **Backend (Distributed Services):** Multiple nodes handle reports, notifications, and responder coordination. Data is replicated for fault tolerance and queues managed concurrent processing
- **Data & Coordination:** Distributed databases store incident across nodes. Eventual consistency ensures updates propagate reliably, even if some nodes are offline.

# 🧠 Distributed System feautres
This system is
**- Fault Tolerant
- Scalable
- Resilient
- Consistent**

# Author
- Ngoh Maximus Ayisih
- Distributed Systems and Cloud Computing
