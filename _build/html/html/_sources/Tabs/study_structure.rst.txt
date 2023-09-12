##############################
Directory Structure Guidelines 
##############################



Study-General Directory Structure
#################################






Project-General Directory Structure
###################################

When it comes time to crack into a new set of data or analyze previously published data with a new method, this is a good time to intialize a project directory. 

.. N.B. ended up going with a slightly different structure so below is not the most relevant
.. I was inspired by Hrvoje Stojić's directory structure in `this OSF repository <https://osf.io/539ps/?view_only=>`_ where he structures his code with prefixes that denote the "type" of materials one would expect to find (e.g. directories with `c` prefix denote code).





In consultation with  `the tidyverse style guide <https://style.tidyverse.org/>`_ here is my proposal:

.. N.B. include .. in order to reference relative to the home directory 
.. literalinclude:: ../_static/project_dir.txt



description of folders

* analysis_scripts 
    * organize these according to a specfic analytic step with numbered steps 
    * e.g. [01-descriptive_stats/01.1-gen_descriptive_stats.R] and [01-descriptive_stats/01.2-descriptive_stats_tables.R]       