---
content_type: page
parent_title: Modeling and Manipulating Biomolecular Interactions
parent_uid: 52f93d5d-eeab-ca0a-0c75-5793cc45656c
title: Protein Design Project
uid: 4e768918-89cb-0ab8-82ea-1711a42e3666
---

_This design project accompanies the_ [_Modeling and Manipulating Biomolecular Interactions_]({{< baseurl >}}/pages/modeling-and-manipulating-biomolecular-interactions) _section._

Bromodomains are protein domains that specifically recognize acetylated lysines. Given the prevalence of acetylated lysines in complexes involved in chromatin-remodeling, DNA damage and cell-cycle control, bromodomains play a key role in a variety of cellular processes. In this project, we will use computational tools to mutate an existing bromodomain such that it has a higher affinity for a novel acetylated peptide compared to its actual biological peptide substrate. The project will consist of four stages:

1.  Use [PyMOL](http://www.pymol.org/) and [PyRosetta](http://www.pyrosetta.org/) to visualize the original bromodomain-ligand complex (If you are a student or teacher, you may be able to [register for an educational-use-only PyMOL license](http://pymol.org/edu/).)
2.  Outline the thermodynamic cycle required to calculate the difference in the binding energy between a mutant bromodomain and the novel peptide and a mutant bromodomain and the original peptide.
3.  Utilize PyRosetta to replace the original peptide ligand with the new peptide ligand and optimize the resulting interface without mutating the bromodomain.
4.  Utilize PyRosetta to optimize the interface of the new complex by mutating the bromodomain. Compute the change in binding energy / affinity mentioned above using thermodynamic cycles and the energetics obtained from PyRosetta.

 Note: Appendix A is a basic PyMOL primer. Appendix B is a basic PyRosetta primer.

| PROJECT HANDOUTS | SUPPORTING FILES |
| --- | --- |
| [Protein Design Project - Parts 1 and 2 and Appendices A and B (PDF - 1.6MB)]({{< baseurl >}}/resources/mit20_320f12_pr_de_pr_p1-2) | [2DVQ\_project.pdb (PDB)]({{< baseurl >}}/resources/2dvq_project) |
| [Protein Design Project - Part 3 and Appendices A and B (PDF - 2.2MB)]({{< baseurl >}}/resources/mit20_320f12_pr_de_pro_pa3) | [peptide\_assignments.xls (XLS)]({{< baseurl >}}/resources/mit20_320f12_pept_assign) |
| [Protein Design Project - Part 4 and Appendices A and B (PDF - 2.2MB)]({{< baseurl >}}/resources/mit20_320f12_pr_de_pro_pa4) |