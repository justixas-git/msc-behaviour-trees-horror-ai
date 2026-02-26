# Behaviour Trees for VR Horror AI  
**Gameplay AI Research — System Design & Evaluation (Unity / C#)**

This repository documents my ongoing Master’s research focused on **antagonist behaviour modeling using Behaviour Trees** in virtual reality horror games.

The work explores how different AI modelling approaches influence **player perception, predictability, tension, and believability**, with special attention to **VR-specific constraints**.

> **Scope note:** This project is intentionally research- and prototype-driven.  
> It is not presented as a finished, production-ready AI framework.

---

## Research Focus

The core research question is:

**How do different behaviour modelling approaches affect player experience in VR horror games, and why are Behaviour Trees particularly suitable for this context?**

The work emphasizes:
- system clarity and control,
- predictable structure with controlled variability,
- maintainability and extensibility over time,
- player-facing consequences of AI design decisions.

---

## Why Behaviour Trees

Behaviour Trees are explored as a middle ground between:
- fully scripted logic (high control, low flexibility),
- and fully emergent systems (high variability, low predictability).

Key motivations for using Behaviour Trees in this research:
- clear hierarchical structure,
- explicit control over execution flow,
- easier debugging and tuning compared to large FSMs,
- suitability for authoring tension-aware behaviour in horror scenarios.

---

## Comparative Approach

The research considers and contrasts multiple AI modelling techniques, including:
- Scripted logic
- Finite State Machines (FSM / HFSM)
- Goal-Oriented Action Planning (GOAP)
- Behaviour Trees (BT)
- Hybrid approaches

Each approach is evaluated not just technically, but in terms of **player experience impact**, especially under VR conditions.

---

## Evaluation Criteria

Rather than focusing purely on algorithmic performance, the evaluation prioritizes:

- **Predictability vs variability**  
  (Does the player learn patterns without feeling bored?)
- **Perceived intelligence**  
  (Does the antagonist feel intentional rather than random?)
- **Tension control**  
  (Can behaviour be authored to support pacing and horror beats?)
- **Authoring complexity**  
  (How feasible is iteration and tuning during development?)
- **VR suitability**  
  (Comfort, readability of behaviour, and player embodiment)

These criteria guide both analysis and prototyping decisions.

---

## Prototyping Status

Current work includes:
- Behaviour Tree structure design
- Analysis of node composition and execution flow
- Early Unity-based prototyping experiments
- Design documentation and evaluation planning

Planned next steps:
- Implementing small, focused BT prototypes
- Comparing authored behaviour scenarios across approaches
- Documenting observed strengths and limitations

---

## Relationship to Other Projects

This research directly complements my gameplay systems work:

- **Solaris Adventure** demonstrates system-level design and implementation discipline.
- This project focuses on **decision-making systems** and their experiential consequences.
- The long-term goal is to bridge **gameplay systems** and **AI behaviour** in a cohesive design approach.

---

## Technology & Tools

- Unity
- C#
- Behaviour Trees (custom and conceptual)
- Academic research and comparative analysis

---

## Notes on Scope & Honesty

This repository is intentionally presented as:
- a **research and exploration space**,
- a place to document design reasoning and evaluation,
- not a claim of production-ready AI implementation.

The emphasis is on **thinking clearly about AI systems**, not overstating finished results.
