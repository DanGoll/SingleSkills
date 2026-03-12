# SingleSkills

How to define these path variables (DATADIR_SK, WORKDIR_SK) to not have your path/folderstructure uploaded to git


The easiest way in R is usually a local .Renviron file.

user-level .Renviron

Run in R:
usethis::edit_r_environ()


Then add (just the two rows):

DATADIR_SK=/yourpath/datafolder/
WORKDIR_SK=/yourpath/folderwhere_out_folderisin/


Save, restart R

