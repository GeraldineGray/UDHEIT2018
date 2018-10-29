## UDHEIT 2018 Workshop: Learning Analytics capacity within your VLE platforms

The objective of this project is to give faculty feedback on how their Moodle page is being used, and if that usage offers meaningful indicators of student engagement. Above are two sample files from Moodle (an activity log and a grade book), and an early draft of Python code that generates analytics from these two files.

The two files are:
1. Course_Activity_Obfuscated.csv, an activity file downloaded from Moodle and obfuscated
2. Course_Grades_Obfuscated.csv, a Moodle grade book with two additional columns added: end of term exam grade; and the overall grade for the course. 

AnalyseData.ipynb is written to run on the cloud on Googles colaborative library for AI: https://colab.research.google.com
Running the code will upload selected files to the cloud. Alternatively, you can take the option to run it locally. This requires Anaconda to be installed on your machine.  Anaconda can be downloaded from https://www.anaconda.com/download.


When running AnalyseData.ipynb, you are asked for a few pieces of information:

```markdown
- Course start date
- Course end date
- The name of the column that holds student ID
- The name of the column that holds the final grade for the module
- The code divides students into three groups based on overall grade. 
  You can congifure the boundary grades for the three groups (currently called A, B and C).
- The name of the activity file
- The name of the grade file
```

###### Thanks to developer Mohammed Ibrahim, MSc student at TU Dublin, and lecturers at TU Dublin for donating anonymised Moodle files.
