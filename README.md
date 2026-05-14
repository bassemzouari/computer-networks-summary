# Computer Networks Lecture Summary

Comprehensive LaTeX-based lecture summary for a university-level  
Computer Networks course covering routing algorithms, Internet  
architecture, and modern networking concepts.

Language: German 🇩🇪  
This repository contains German lecture summaries and notes.

The project focuses on structured technical documentation,  
formal networking concepts, and concise explanations of routing  
algorithms, Internet protocols, and distributed communication models.

---

## Topics Covered

- Network Fundamentals  
- Internet Architecture  
- Routing Basics  
- Flooding & Static Routing  
- Adaptive Routing Algorithms  
- Distance Vector Routing (DVR)  
- Count-to-Infinity Problem  
- Split Horizon & Poison Reverse  
- Link-State Routing (Dijkstra)  
- Hierarchical Routing  
- Autonomous Systems (AS)  
- Intra-AS vs Inter-AS Routing  
- Border Gateway Protocol (BGP)  
- Routing Policies & Scalability  
- Mobile Routing (DSR)  
- Overlay Networks  
- Internet Protocol (IPv4 & IPv6)  
- Subnetting & CIDR  

---

## Build Instructions

Requirements:
- A LaTeX installation (e.g. MikTeX or TeX Live)
- Installation of the TU Darmstadt template:  
  https://github.com/tudace/tuda_latex_templates
- Pygments for code highlighting:  
  `pip install Pygments`

Clone the repository:

```bash
git clone <your-repo-url>
```

Compile using:

```bash
latexmk --shell-escape
```

If using VS Code (LaTeX Workshop), add:

```jsonc
"latex-workshop.latex.tools": [
    {
        "name": "latexmk",
        "command": "latexmk",
        "args": [
            "--shell-escape",
            "-synctex=1",
            "-interaction=nonstopmode",
            "-file-line-error",
            "-lualatex",
            "-outdir=%OUTDIR%",
            "%DOC%"
        ]
    },
],
```

---

## Preview

The compiled PDF can be found in:

```text
output/summary.pdf
```

---

## Goals of the Project

- Create a structured and maintainable networking reference  
- Summarize theoretical and practical networking concepts  
- Provide concise explanations of routing algorithms and protocols  
- Improve technical documentation and LaTeX workflow skills  

---

## Disclaimer

This document was independently written for educational purposes.  
It serves as a personal lecture summary and study reference.

Some topics may be based on university lecture material and publicly  
known networking concepts. All rights to original course content remain  
with their respective owners.

---

## License

This repository is licensed under the MIT License.
