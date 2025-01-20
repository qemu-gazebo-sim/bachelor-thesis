<div align="center">
    <a href="https://www.latex-project.org">
        <img 
            alt="Made with Latex" 
            src="https://img.shields.io/badge/made_with-LaTeX-brightgreen?style=for-the-badge&color=%23006400" 
            height="30"
        >
    </a>
    <a href="https://www.overleaf.com">
        <img 
            alt="Made with Overleaf" 
            src="https://img.shields.io/badge/uses-overleaf-brightgreen?style=for-the-badge&labelColor=FFFFFF&color=%23098842" 
            height="30"
        >
    </a>
</div>


# 🤖 Monografia / Bachelor Thesis - Embedded systems simulator for robotics applications

> Bachelor Thesis (referred as `Monográfia` in Portuguese by the University) for 2024 course conclusion in the Universidade de São Paulo. The bachelor thesis focuses on embedded system simulation in the field of robotics.

This bachelor thesis was primarily prepared using [overleaf](https://www.overleaf.com). To view the overleaf version of the bachelor thesis, please click [here](https://www.overleaf.com/read/dvvdcznfvxsr#93ac22).

<p align="center">
    <a href="https://github.com/qemu-gazebo-sim/bachelor-thesis/blob/master/Monografia.pdf" title="Embedded systems simulator for robotics applications">
        <img src="https://raw.githubusercontent.com/qemu-gazebo-sim/bachelor-thesis/master/docs/front_view_bt.png" width="400" alt="Embedded systems simulator for robotics applications" title="Embedded systems simulator for robotics applications" />
    </a>
</p>


## :rocket: Implementation

This bachelor thesis was written primarily using [overleaf](https://www.overleaf.com). To view the overleaf version of the bachelor thesis, please click [here](https://www.overleaf.com/read/dvvdcznfvxsr#93ac22).

The whole project was organized following the structure below:

```
src
├─── monografia.tex
├─── bibliography.bib
├─── chapters/
├─── files/
├─── finals/
├─── images/
├─── preliminaries/
│    |───pre_report.tex
│    └───acronyms_symbols.tex
└─── utils/
     |───commands.tex
     └───package_config.tex
```

- `monografia.tex`: The main LaTeX project file. It mainly compiles the entire thesis document by including other files and resources;
- `bibliography.bib`: A BibTeX file containing references and citations of the thesis;
- `chapters/`: A folder containing the LaTeX files for each individual chapters of the thesis;
- `files/`: A folder to store supplementary files, like PDFs;
- `finals/`: A folder containing the final part of the thesis, which is not referred to as a chapter, such as attachments and appendices;
- `images/`: A folder to hold images, diagrams, and other graphical assets;
- `preliminaries/`: A directory for preliminary content:
    - `pre_report.tex`: A file for pre-reports or preliminary files, such abstract, dedication etc;
    - `acronyms_symbols.tex`: A file defining acronyms, abbreviations, and symbols used throughout the project;
- `utils/`: A directory for utility and configuration files:
    - `commands.tex`: A file containing custom LaTeX commands;
    - `package_config.tex`: A file to configure LaTeX packages and the project theme.
