## Toktarkhan Karymbayev

Computer Science & AI undergraduate at **Coventry University Kazakhstan**, based in Astana.
I build applied AI for city government — systems that produce a number an administrator can
act on, not a notebook that proves a point.

### What I've built

**[EcoRoute AI](https://github.com/tokha-t/ecoroute-ai)** — predictive waste collection and routing
· *[live demo](https://ecoroute-ai-baikonur.streamlit.app)*

Replaces fixed waste-collection schedules with demand-driven routing. Projects daily fill levels,
classifies stops as mandatory or optional by detour efficiency, and generates capacity-safe truck
routes with landfill returns and shift limits using Google OR-Tools over a 252×252 real-road
distance matrix. Across a 30-day simulation of 250 collection sites in Astana's Zhastar catchment
it cut **overflow events by 61.7% (153 vs 399)** and **driving distance by 7.5% (3,076 km vs
3,326 km)** against the fixed-schedule baseline — and showed the current four-truck fleet cannot
reach zero overflow, which is the answer an operations lead actually needs. Bilingual RU/EN
dispatcher interface; runs fully offline on cached OSRM refuse-truck profiles.

Built for the Astana Innovation Accelerator. **A pilot deployment in Astana is under discussion**
through the joint programme of the Accelerator, Astana Hub and the city akimat.

`Python` `Google OR-Tools` `scikit-learn` `pandas` `NumPy` `Plotly` `Streamlit` `OSRM` `OpenStreetMap`

**[JAUAP](https://github.com/tokha-t/jauap)** — AI-assisted civil-claim routing for municipal government
· *[live demo](https://jauap-demo.streamlit.app)*

Takes a citizen complaint written in Russian, Kazakh or a mix of both, works out what kind of claim
it is and which department owns it, computes the statutory response deadline under Kazakhstan's
Administrative Procedural Code, clusters it against related complaints about the same location, and
scores escalation risk with transparent weights. **88.4% classification accuracy against a 60.0%
rule-based baseline**, 96.4% topic accuracy, 100% location accuracy on the synthetic evaluation
corpus. A confidence gate sends 13.6% of cases to human review — accuracy is 94.0% on what it
passes and 52.9% on what it flags, so the gate finds the genuinely hard claims. Offline address
resolution and mapping, no external geocoding dependency.

Submitted to the Smart City Accelerator, Aqmola Hub.

`Python 3.11` `Google Gemini API` `Streamlit` `clustering` `multilingual NLP`

### Beyond the code

- **Startup Programmes Intern, NU STeP** — Nazarbayev University Science & Technology Park;
  ABC Incubation and Quick Start.
- **Technical Staff Team Lead, [IOAI 2026](https://ioai2026.kz/)** — led 30+ trained technical
  volunteers for 70+ hours at the 3rd International Olympiad in Artificial Intelligence, Astana,
  owning critical-incident escalation during live competition.
- **ICPC Kazakhstan Regional 2025** — Honourable Mention, Team "CovGen".
- **AWS Academy Cloud Foundations** · **Cisco Networking Basics** (2026).

📫 [LinkedIn](https://www.linkedin.com/in/toktarkhan-karymbayev) · toktarhankarymbaev@gmail.com

<sub>Also: future King of the Pirates. 🏴‍☠️</sub>
