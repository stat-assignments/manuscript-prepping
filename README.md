# manuscript-prepping
Assignment to go through the initial steps of setting up a manuscript to be sent to a Statistics journal.

For this assignment you are working in the following scenario: it's the end of the next Fall, and you have successfully written up your statistics project for the Comprehensive Exam. You and your advisor are getting ready to submit: a) pick one of the high-impact (in the top quarter (Q1)) journals among the statistics & and probability journals: https://www.scimagojr.com/journalrank.php?wos=true&category=2613Links to an external site.

b) find the journal's website and look for 'instructions for authors'. There should be a LaTeX template (if not, you might want to pick a different journal - I have not checked them all, but I'd go with a 99% probability that there is a LaTeX template).

c) Download the template into the repository (accept the Github classroom invite and make a local clone).

d) Turn the .tex template into an Rnw document.

e) Adjust the title and author information. 

f) Add a (hidden) code chunk that loads the palmerpenguins data and includes your ugly plot from 850. - If you created that chart in python, you can use one of the charts in the palmerpenguins help. For Rnw, you need to work in R. 

g) Add a caption to the figure describing your plot. 

h) Refer to the figure using the latex command \autoref

i) Add the reference for the palmer penguins data and the palmer penguins package to the paper. 

j) Add a section at the end of the paper called "Computational Tools" and list the tools/packages you used (with the version - have a look at the output of  sessioninfo::session_info).  

j) make sure that everything renders without error. 

k) add the Rnw, the tex and the pdf file to the github repository (and all files that are necessary to render those files). 

l) add a link on the Readme.md file to your Rnw file. 

For the submission, submit the link to the github classroom repo. 

 
