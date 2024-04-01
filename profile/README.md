## The OpenCog Project 👋
OpenCog aims to create AGI with a combination of exploration, engineering and basic science research.
Side quests have included robotics systems ([Hanson Robotics](https://www.hansonrobotics.com)),
financial systems (Aidiya),
genomics (MOZI and Rejuve.bio),
machine learning ([predicting risk from clinician notes](https://doi.org/10.1371/journal.pone.0085733)),
natural language chatbots ([virtual dog playing fetch](https://www.youtube.com/watch?v=FEmpGRLwbqE)) and more.
This project was pioneered by [Dr. Ben Goertzel](https://en.wikipedia.org/wiki/Ben_Goertzel).
Git repos fall into four categories:

### OpenCog AtomSpace
The core of the system: active, stable and supported.

* Base AtomSpace
* CogServer and atomspace-cog (for networking, json, websockets)
* atomspace-rocks (disk I/O subsystem)
* Proxy Nodes (for data routing, replaces attention bank)
* Link Grammar (including the learn subproject for neuro-symbolic structure learning)
* Docker containers (provide system integration)

### OpenCog Classic
Older, abandoned and obsolete components. These were educational and fun, but development has
halted. These projects are no longer maintained, but they may contain useful subsystems that
might be salvageable for future use. This includes:
* PLN, URE, Attention, SpaceTime, Ghost, Relex, R2L, ROS, Eva/Sophia, MOSES (but not as-moses, see below).

### OpenCog Hyperon
Being developed by [Singularity.net](https://singularitynet.io).

### OpenCog Incubator
These are the immature, incomplete, promising projects that haven't taken off yet.

* Atomspace-prolog proof-of-concept
* Chemistry proof-of-concept
* agi-bio (genomics subsystem use by MOZI and rejuve.bio)
* visualization (GUI to explore AtomSpace contents)
* as-moses (Port of MOSES to the AtomSpace)
* Vision proof-of-concept (Extracting structure from images, video)
* Hyperon-on-top-of-atomspace proof of concept (Hyperon backwards-compat)
* Any repo that is not marked "read-only" or "obsolete".
