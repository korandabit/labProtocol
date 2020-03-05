2017.04.05

This file explains the structure of experiment project folders. The parent folder ("00X project_name") is defined by a unifying project hypothesis it contains all the studies which apply to this hypothesis. Child folders are independent studies for the project.

writing		a centralized place where all abstracts, conference presentations, talks, 
		and publications are contained, ordered by date. 

analysis	contains all/only transformed data and analysis, files labeled in serial 
		order of transformations from raw to results write-up. grouped in files according to analyses projects.

X_study		Contains all activity for individual studies. Each have the identical, 
		following substructure and function. 0_study = pilot study

_readme.txt	This file.

# File structure inside study folders #

/0_develop	contains development tools and ongoing work for experimental stimuli 
		and structure (counterbalance).

/1_exp		contains the implemented study. To modify an ongoing study, 
		duplicate 1_exp, append last run subj, and explain changes in the log. 
		(e.g. if a change is made starting with participant 5, two unique 
		folders should be labeled '1_exp.p4' and '1_exp.pX')

/2_data		contains all/only raw participant data, including data entry and coding.

/log.studyX.txt	contains detailed notes about completed and ongoing project activity, 
		from development through data analysis, including deviations and 
		corrections. See log for details regarding how and what is logged.
