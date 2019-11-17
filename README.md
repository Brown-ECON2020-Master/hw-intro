# hw-intro

## Welcome to ECON 2020 "Computing for Economists"! 

This assignment is purposed to make all of you on the same page at the beginning of this course. 
**The due is the last mignight of the *second* meeting.** I recommend you to start this assignment as early as possible. 
At the first meeting, the instructor will answer your questions for this assignment so that you will be well prepared for submitting your work by the second meeting. Looking forward to meeting you all soon!

### Aims of this assignment:
- Getting started with Git and GitHub. 
- Get accustomed to using GitHub for downloading and submitting your assignment. 
- Set up the environment for using Python.

### Tasks:
1. Clone the private repository `hw-intro-yourusername` in the @Brown-ECON2020-Spring2020 organization into your local machine. See below for the detail steps.  
1. In your laptop, download the [Anaconda distribution of Python](https://www.anaconda.com/distribution/), which comes with all the packages you will need. Download the Python 3.x version (, not the Python 2.7 version).
1. Open Spyder, an Integrated Development Environment (IDE), which is downloaded with the Anaconda distribution. 
1. Write the code to print your name and research interests. In the same code, write the code to check if the following equations hold true in Python: (1) 0.1+0.1=0.2 & (2) 0.1+0.1+0.1=0.3. Use print(x == y) for obtaining the result ("True" or "False"). You can edit your code using the left side of Spyder as shown in the picture below. 
1. Save your code (.py file) in your local folder `hw-intro-yourusername`.  
1. Submit your .py file following the steps described below. 


### How to clone the repository into your local directory?
- Open GitBash (in Windows) or the Terminal (in Mac).

- Decide the location in your local machine where you want to put the local folder of this assignment. It can be anywhere in your machine (e.g., C: drive, Dropbox, D: drive, etc), but NOT be in an external hard drive.   
   
   E.g.) `$ git cd Dropbox/ECON2020/assignments`

- Clone the repository into your local directory which you set above:  
   
   `$ git clone https://github.com/Brown-ECON2020-Spring2020/hw-intro-yourusername`

- Likewise, you can clone the class materials: 
   
   `$ git cd Dropbox/ECON2020`
   `$ git clone https://github.com/Brown-ECON2020-Spring2020/class_materials`

- Finally, your local repository will look like this:
<img width="400" alt="Course Directory" src="https://dl.dropboxusercontent.com/s/pjkuf0t7t04t5z5/fig_intro_1.png?dl=0">


### How to use Spyder?
![Spyder](https://dl.dropboxusercontent.com/s/vqb91hwjyoecd5u/fig_spyder_1.png?dl=0 "Spyder")

### How to submit your work?
- Edit and save your code in your local folder `ECON2020/assignments/hw-intro-yourusername`.
- In GitBash or the Terminal, navitgate to that place:
   
   `$ git cd Dropbox/ECON2020/assignments/hw-intro-yourusername`
- Save the changes you have made and commit in Git:

   `$ git add -A`
   
   `$ git commit -m "Completed hw-intro"` (or something like that)
- Submit by writing: 
   `$ git push`
   
- Check that your code appears in the online GitHub repository at `https://github.com/Brown-ECON2020-Spring2020/hw-intro-yourusername`


*You can also see this [GitHub Classroom Guide for Students](https://github.com/jfiksel/github-classroom-for-students) for more detail.*

*The lecture on software engineering will soon cover more detail in utilizing Git & GitHub.*

