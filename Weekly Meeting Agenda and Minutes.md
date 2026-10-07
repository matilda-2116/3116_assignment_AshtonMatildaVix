# Wk 2 Meeting
**Attendance** :  Ashton and Matilda
**Date/Time** : 23/09/2026 11:30AM

## Agenda
* Set up a code repository
* Decide which project we will work on
* Begin assigning tasks


## Minutes
 ### Agenda Item 1 - Set up repository
* Repository set up by Matilda, titled 3116_assignment_AshtonMatildaVix
* published to GitHub, changed to public
* Added Group members as collaborators
* Tested whether or not we can edit the same file simultaneously (We can't - maybe we ask in the tutorial if we did something wrong)

### Agenda Item 2 - Picking a project
* We have selected Option 1 - Accreted Milky Way Globular Clusters

### Agenda Item 3 - Begin Assigning tasks
List of things that need to be done:
* Figure out what accreted globular clusters are (research)
* Look into what data is available and what data we need
* import data into github repository
* read Van den Berg article and summarise for understanding.

Assigning:
* All team members read article/research accreted globular clusters so that we have a basic understanding
* Matilda to import data from moodle
* Ashton, Vix, (and matilda?) to perform preliminary analysis of data (e.g. looking for outliers, noting which columns will be useful for what)

Meeting end time: 12:02PM


# Week 3 Meeting
**attendees**: Ashton, Matilda, Vix
**Time**: 12:50

## Agenda
- what progress has been made
- next steps

## Minutes
- Figure out what measurements of the globular clusters that we need to be looking at - relevant variables
- After doing this we plot the variables we think will be important and compare.
- Ashton theorises that velocity will be important - globular clusters inside our galaxy will have similar velocity. 
- Read papers to find more information
- plot every variable in the data we have to start looking at trends
- From the textbook - we can tell globular clusters have merged into our galaxy because they look different to our globular clusters
- Ashton suggests plotting against position in the sky, discussion about whether this would be beneficial. 
- plotting velocity against metallicity might help - as these both can be used to infer age (Check this)


## Actions
- Each of us will take one of the csv files, and start plotting the data 
- this will include looking for outliers and making the data more readable
- We will try lots of combinations of axes, think about how they might be related (add this in ), and look at what we find
- Vix will look at Krause21.csv
- Ashton will look at HarrisPartI
- Matilda will look at vandenBerg_table2
- next week we will look at our graphs, compare them, and see what patterns we have found, and use these findings to plan next steps.
- Right now Matilda will make separate files for each dataset analysis so that we can edit simultaneously

**Meeting end**: 13:09



# Week 4
**attendees:** Ashton,  Matilda, Vix
**Date/time:** 7/10/26 12:30PM

## agenda
- discussing what progress we have made
- Talking about next steps and goal for this week
- dividing up the work so that we can work on it simultaneously

## minutes
**Progress so far**
Matilda's progress:
- looked at my table and read the paper to figure out what the data in the table is 
- plotted metallicity as it's an important variable for identifying accreted globular clusters
- first did a box plot which didn't show any outliers, didn't trust my boxplot graphing skills so I manually checked for outliers using the IQR formula, so there were no outliers
- in the GC video we were taught that bimodal distribution of metallicity is an indicator of accreted globular, lower mode of metallicity GCs more likely to be accreted, so I plotted a histogram
- Trialed number of categories (bins) 
- there are two modes of metallicity
- my plan from here is to identify the 8 or so low metallicity GCs to look at their other variables

Vix's progress
- wanted to try and find a way to compile the datasets into one dataset so we could compar directly the information from different variables
- Looked through the IDs of the Globular Clusters to find the common globular clusters
- details of how she did this are in the code/comments
- Appended the data sets on the rows of the common IDs
- now we have one dataset with all of the data for the common globular clusters (51 total, which is a pretty good data set)
- Caveat: She only looked through the NGC ID GCs with code, but hand-checked the name-only GCs and doesn't think there's any common ones in that set

Ashton's progress:
- plotted the data in regard to different locational variables so we have information about where globular clusters are concentrated 
- This will be useful when we are doing further analysis on the properties of Globular Clusters for comparison.

**Next Steps and Wk4-5 Goal**
- identify globular clusters with low metallicity
- plot kinematic data from Vix's combined dataset
- identify GCs with interesting kinematics, check for commonality with interesting globular clusters
- Matilda wrote notes on what to plot for kinematics: Velocity and rotation kinematics (GC's moving or rotating much faster or slower), plotting distance against recessional velocity
- Ashton suggests plotting eccentricity of orbits of GCs
- Variables like metallicity, eccentricity, velocity etc will be plotted individually as histograms first to identify the most likely relevant globular clusters, and then from there scatter plots will be made to compare variables and identify GCs that are candidates for accreted GCs in both variables

**dividing up the work**
- Matilda will identify low-metallicity GCs
- Ashton will plot distance against recessional velocity
- Vix will plot eccentricity, and eccentricity against metallicity
- Matilda will plot velocity and rotation data. She will also compare low metallicity globular clusters to their ages (younger low-metallicity are more likely to be accreted)





