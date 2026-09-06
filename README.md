 # Computational Biology and Bioinformatics

Doctoral-level course materials, practical exercises, code, datasets, and learning resources for **Computational Biology and Bioinformatics**.

**Course lead:** Dr. Manosh Kumar Biswas  
**Course period:** September 7–October 15, 2026  
**Schedule:** Two sessions per week for six weeks  
**Level:** PhD  
 

## Course overview

This course provides PhD students with the computational foundations needed for modern research in agriculture, biology, environmental science, and medical science. It is designed for learners with diverse backgrounds and does not assume previous formal training in programming.

The course combines conceptual instruction with practical exercises using Unix/Linux, Bash, reproducible software environments, biological data formats, high-performance computing (HPC), phylogenetics, data visualization, and integrated research workflows.

## Learning outcomes

By the end of the course, students should be able to:

- Work confidently in Unix/Linux and command-line environments.
- Organize computational research projects and biological datasets.
- Write Bash scripts to automate repetitive analytical tasks.
- Create and document reproducible software environments.
- Inspect, validate, filter, and transform molecular and ecological data.
- Submit, monitor, and optimize analytical jobs on an HPC cluster.
- Conduct introductory phylogenetic and evolutionary analyses.
- Create informative scientific visualizations and interpret biological results.
- Design and execute an end-to-end computational workflow.
- Communicate methods, results, assumptions, and limitations clearly.

## Course schedule

| Session | Date | Topic | Focus |
|---:|---|---|---|
| 01 | September 7, 2026 | Introduction to Computational Biology and Research Computing | Computational biology and bioinformatics; applications in life sciences; research-computing concepts; introduction to Unix/Linux; terminal navigation; `pwd`, `ls`, and `cd`; files, directories, and paths. |
| 02 | September 10, 2026 | Unix Systems and Shell Mastery | Linux architecture; permissions; file manipulation; pipes and redirection; searching and processing text with `grep`, `awk`, and `sed`; guided command-line exercises. |
| 03 | September 14, 2026 | Reproducible Research and Environment Management | Reproducibility principles; project organization; software dependencies; Conda environments; package installation; software versions; introduction to version control. |
| 04 | September 17, 2026 | Bash Scripting and Workflow Automation | Scripts, variables, arguments, loops, conditionals, functions, error handling, reusable code, and automation of simple analytical pipelines. |
| 05 | September 21, 2026 | Molecular and Ecological Data: Structure, Quality, and Metadata | FASTA, FASTQ, VCF, CSV/TSV, and ecological tables; metadata standards; data integrity; identifiers; annotation; quality assessment. |
| 06 | September 24, 2026 | Data Processing and Exploratory Analysis | Filtering, transforming, joining, and summarizing data; exploratory analysis; quality checks; preparation of analysis-ready datasets. |
| 07 | September 28, 2026 | High-Performance Computing Foundations | HPC architecture; login and compute nodes; storage; job schedulers; SLURM scripts; resource requests; submitting and managing jobs. |
| 08 | October 1, 2026 | Advanced HPC Workflows and Optimization | Monitoring and debugging jobs; memory and runtime efficiency; parallel execution; job arrays; workflow scaling; responsible use of shared resources. |
| 09 | October 5, 2026 | Phylogenetic Analysis and Evolutionary Inference | Sequence alignment; model selection; tree-building methods; support values; tree visualization; interpretation, uncertainty, and validation. |
| 10 | October 8, 2026 | Data Visualization and Biological Interpretation | Visualization principles; comparative plots; clustering; heatmaps; figure design; identifying patterns without overstating conclusions. |
| 11 | October 12, 2026 | Integrated Computational Project I: Workflow Design and Analysis | Research-question formulation; dataset selection; workflow design; preprocessing; pipeline implementation; quality control; guided project development. |
| 12 | October 15, 2026 | Integrated Computational Project II: Interpretation and Final Presentation | Final analysis; validation; visualization refinement; biological interpretation; limitations; reproducibility review; project presentation. |

## Repository organization

```text
computational-biology-bioinformatics-course/
├── README.md
├── syllabus/
├── lectures/
│   ├── L01_introduction/
│   ├── L02_unix_shell/
│   ├── L03_reproducibility/
│   ├── L04_bash_scripting/
│   ├── L05_biological_data/
│   ├── L06_data_processing/
│   ├── L07_hpc_foundations/
│   ├── L08_hpc_optimization/
│   ├── L09_phylogenetics/
│   ├── L10_visualization/
│   ├── L11_project_I/
│   └── L12_project_II/
├── practicals/
├── datasets/
├── scripts/
├── environments/
├── projects/
└── resources/
```

Each lesson folder may contain:

- Lecture slides or notes
- Practical instructions
- Example commands and scripts
- Small teaching datasets or links to public datasets
- Expected outputs
- Supplementary reading

## Getting the course materials

### Option 1: Clone the repository

```bash
git clone https://github.com/USERNAME/computational-biology-bioinformatics-course.git
cd computational-biology-bioinformatics-course
```

Replace `USERNAME` with the instructor's GitHub username or organization name.

To download later updates:

```bash
git pull
```

### Option 2: Download a ZIP file

Select **Code → Download ZIP** from the repository homepage. Extract the downloaded archive before beginning the practical exercises.

## Software requirements

The exact software environment will be introduced during the course. Students should have access to:

- A Unix/Linux terminal, macOS Terminal, Windows Subsystem for Linux, or an approved remote Linux server
- Git
- Conda or Miniforge
- A text editor or Visual Studio Code
- Institutional HPC credentials when required

Installation instructions and environment files will be provided in the `environments/` directory.

## Practical-work guidelines

1. Read the practical `README.md` before running any command.
2. Keep raw data unchanged and separate from generated results.
3. Record commands, parameters, software versions, and errors.
4. Store reusable commands in scripts instead of relying only on terminal history.
5. Verify outputs before interpreting biological meaning.
6. Do not upload confidential, sensitive, clinical, or unpublished research data.
7. Follow the submission instructions provided for each assignment.

## Questions and answers

Use **GitHub Discussions** for course-related questions. Recommended categories are:

- Announcements
- Questions and Answers
- Practical Help
- HPC and Technical Problems
- Course Resources
- General Discussion

Before posting a question:

1. Search existing discussions for a similar question.
2. Use a clear and specific title.
3. Include the lesson number and relevant command.
4. Copy the complete error message using a code block.
5. Describe what you expected and what happened.
6. Never post passwords, access tokens, personal data, or confidential datasets.

Example:

````markdown
### L02: `grep` returns no results

Command:

```bash
grep "ATGC" data/example.fasta
```

Expected result: matching sequence lines  
Observed result: no output  
Environment: Ubuntu 24.04
````

## Responsible and reproducible research

Students are expected to follow good scientific-computing practices, including transparent documentation, appropriate attribution, data protection, reproducible environments, careful validation, and honest reporting of uncertainty and limitations.

## Assessment

Assessment details, deadlines, submission instructions, and grading criteria will be provided in the `syllabus/` and `projects/` directories. Unless explicitly authorized, students should not publish assessment solutions in public repositories.

## License and reuse

Add the selected license before publicly releasing the repository. A practical approach is:

- **Teaching materials:** Creative Commons Attribution 4.0 International (`CC BY 4.0`)
- **Code:** MIT License

## Contact

For questions that may help the whole class, use GitHub Discussions. Use the official university communication channel for private, personal, or assessment-related matters.

---

**Course lead:** Dr. Manosh Kumar Biswas  
**Course:** Computational Biology and Bioinformatics
