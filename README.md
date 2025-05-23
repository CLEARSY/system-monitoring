# system-monitoring

This repository contains supporting material for the article "Use of certified industrial tools for formal analysis and monitoring of Communications-Based Train Control Systems" submitted to RSSRail2025, which describes a methodology for formally analysing and monitoring CBTC (Communications-Based Train Control) systems using the CLEARSY Safety Platform (CSSP) — a set of certified industrial tools tailored for safety-critical applications.
 
## About the Methodology
 
The methodology introduced in the article enables the formal specification, testing, and runtime monitoring of CBTC safety requirements by reusing B specifications developed using the Atelier B toolchain. 

It provides:
- Strong traceability between requirements, specifications, and tests.
- Continuous monitoring of system behavior based on formalized safety properties.
- A lightweight integration into CBTC systems without altering their architecture.

The approach builds upon existing certified assets, ensuring deployability and certifiability, and leverages the CSSP to enforce safety properties both during testing and operation.
 
## Repository Contents
 
This repository includes:
- 🧠 B Projects (.arc files): Formal models developed in Atelier B, directly usable with the CSSP.
    - The abstract machine logic and the implementation logic_i contain the specification used in the article.
    - These examples mirror the case study presented in the paper.
- 🛠 Installer for the latest version of the CLEARSY Safety Platform (not yet publicly available on the CLEARSY website).
Provided here for reviewers and replicability purposes.
 
📄 Note: A detailed explanation of the methodology and its rationale can be found in the article. The case study presented in the models illustrates how CBTC system safety requirements can be specified and monitored using the CSSP.


Shield: [![CC BY 4.0][cc-by-shield]][cc-by]

This work is licensed under a
[Creative Commons Attribution 4.0 International License][cc-by].

[![CC BY 4.0][cc-by-image]][cc-by]

[cc-by]: http://creativecommons.org/licenses/by/4.0/
[cc-by-image]: https://i.creativecommons.org/l/by/4.0/88x31.png
[cc-by-shield]: https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg
