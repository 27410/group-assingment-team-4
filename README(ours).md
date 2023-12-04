[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=12060715&assignment_repo_type=AssignmentRepo)
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/27410/[PUT-YOUR-REPOSITORY-HERE]/main)

# 27410 - Group assignment - Group [4] - [Metabolic Engineering of <i>Saccharomyces cerevisiae</i> for production of farnesene]

> Dear students, thank you for accepting the group assignment. Please fill in the
> requested information below and above ([Group Number] and [TITLE]) and remove this quoted part before submission (everything prepended with a >).
> Please also replace `[PUT-YOUR-REPOSITORY-HERE]` up in the first line 👆 with the name of your repository here on GitHub.
> That way someone can click on the Binder badge icon and open your project in Jupyter lab to explore it.
> For this to work you will also have to keep `requirements.txt` up to date (by running `pip freeze > requirements.txt`).
> Furthermore, this will only work if you decide to make your repository public (which you can do under Settings -> Options),
> which I would encourage you to do – up to you. A lot of good science happens out in the open these days.
> Good luck!

## Project summary (<300 words)
The aim of our project was to engineer a robust <i>Saccharomyces cerevisiae</i> cell factory for the efficient and sustainable production of β-farnesene. This sesquiterpene compound holds significant industrial value due to its applications in biofuels, cosmetics, lubricants, and pharmaceuticals. The traditional methods of obtaining β-farnesene, such as chemical synthesis and extraction from plant material, are energy-intensive, environmentally unfriendly, and economically impractical due to low yields and susceptibility to climate conditions.

In our work we employed computational tools and analyses to optimize the production capabilities of <i>S. cerevisiae</i>. The first step in the experimental approach was the integration of a heterologous β-farnesene synthase from <i>Artemisia annua</i> into yeast. Additionally, we investigated the impact of media composition, focusing on mimicking YPD media to enhance growth rates and productivity. The findings highlight substantial improvements in growth rate, productivity, and theoretical yield when comparing minimal to YPD (complex) media. 

In order to increase β-farnesene production, we manually simulated five popular and well established metabolic enginering strategies. Despite their widespread usage, the impact that those had in the production of β-farnesene was minimal. Through flux variability scanning, we identified potential gene targets for upregulation, by comparing them with literature-supported enhancements in terpenoid production. The investigation into the interplay between growth, oxygen availability, and β-farnesene production unveils crucial insights, including the linear negative correlation between growth and β-farnesene production and the optimal oxygen uptake rate for maximum production. Fianlly, cofactor swap optimization revealed no targets for optimizing β-farnesene production. 

In summary, the project successfully employs metabolic engineering strategies, media optimization, and computational analyses to significantly improve the efficiency of β-farnesene production in <i>S. cerevisiae</i>. The identified gene targets and the understanding of growth and oxygen uptake dynamics contribute valuable knowledge for the development of high-performing <i>S. cereviciae</i> cell factories. 

## Project overview
Our project is organized into three main folders:
1. Yeast-GEM-8.7.0 contains the yeast8 model 
2. The analysis folder contains the main report and the accompanying analysis files 
3. The figures folder contains all the figures generated from the analysis and used in the report


Table of contents

1 Introduction
- 1.1 Literature Review of the Compound
   Applications of the Product
   Evaluation of Market Potential
   Biosynthetic Pathway/Genes
- 1.2 Literature Review of the Cell Factory - Saccharomyces cerevisiae as a Cell Factory for the Production of β-farnesene
   General Advantages
   General Disadvantages
   Suitability of the Cell Factory for the Product

2 Problem Definition

3 Selection and Assessment of Existing GSM

4 Computer-Aided Cell Factory Engineering
- 4.1 Introducing the Heterologous Pathway to the Model
- 4.2 Media Optimization
- 4.3 Modeling of Manually Derived Targets
- 4.4 Identification of Overexpression Targets
- 4.5 Phenotypic Phase Plane Analysis
- 4.6 Co-factor Swapping Targets
- 4.7 Top 10 List of Most Promising Cell Factory Proposals for Implementation

Discussion

Conclusion

References

