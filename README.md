## Workshop: Learning Analytics capacity within your VLE platforms

Above are two data files from Moodle, and Python code that generates some analytics from the two files (the code is a work in progress).

The two files are:
1. Course_Activity_Obfuscated.csv , an activity file downloaded from Moodle and obfuscated
2. Course_Grades_Obfuscated.csv, a Moodle grade book with two additional grades added: end of term exam grade; and the overall grade for the course. 

AnalyseData.ipynb is written to run in the cloud on Googles colaborative library for AI: https://colab.research.google.com
Running the code will upload selected files to the cloud. Alternatively, you can take the option to run it locally. This requires Anaconda to be installed on your machine.  Anaconda can be downloaded from https://www.anaconda.com/download.

When running AnalyseData.ipynb, you are asked for a few pieces of information:

```markdown
- Course start date
- Course end date
- The name of the column that holds student ID
- The name of the column that holds the final grade for the module
- The code divides students into three groups based on overall grade. You can congifure the boundary grades for the three groups.
```

