# cgp-project-template

*This is a template folder for creating a project, this file is a template for structuring a project. For more detailed information on creating a new project and how to contribute check out CONTRIBUTING.md*

*To start with replace the title **cgp-project-template** with the name of the project.*
*All italic text should be replaced with project specific information*

## Project summary
| | |
|-|-|
| **Goal** | *Robust NovaSeq demux* |
| **Priority** | *1* |
| **Estimated duration** | *3 months* |
| **Team Members** | *ES, BS, KN* |
| **Coordinator** | *ES* |
| **External Members** | *-* |

## Project description

*We can remove demultiplexing as a bottleneck in our workflows, this can be achieved by moving the demultiplexing to Hasta and also doing it on the Dragen hardware whenever possible. We can improve the possibility to overview the demultiplexing by having cg starting it and Trailblazer monitoring it. We can be more transparent towards our customers if we have integrated demux into cg and can show dates and demux version on the Delivery Report. First we have to make the demux-process more robust and easy to handle for example re-runs of problematic runs*

### Aim(s)

1. *Search unmatched reads for index errors*
2. *Correct the way the demultiplexed fastq-files are added in the database since the data today are named using line number in Sample Sheet, and that Leeds to duplicated data in cases we need to correct a demultiplexing that have been done using an incorrect sample sheet.*
3. *Add documentation about how to deal with flow cells taken back from PDC*
4. *Save Undetermined files also on hasta since they are removed from Thalamus*
5. *Integrate demultiplexing in cg if possible, see also issue #65*

### Description

*A more extended description of what needs to be done and why*

### Resources required

*What resources are required to complete the project*

### Milestones

*Are there any milestones included in the project?*

## Project activities
*This section shows the tasks that are needed to complete the project and the status of the tasks.* *Tasks are made as issues*
*Add and arrange tasks in the Projects section*

![Projects][projects]

[projects]: .github/img/projects.png
