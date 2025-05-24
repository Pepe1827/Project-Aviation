# Aircraft Analysis

![blueprint](images/blueprint.png)

Author : Jose Ortega

## Overview

In this project, I will use data cleaning, analysis and visualizations in order to generate insights for a business stakeholder.

## Business Problem

My company is expanding in to new industries to diversify its portfolio. Specifically, they are interested in buying and operating aircrafts for commercial and private use, but do not know anything about the potential risks of aircraft. My task is to analyse the data and come up with three business recommendations.

## The Data

The data used in this project is from the NTSB (National Transportation and Safety Board), that contains information from 1962 and later about civil aviation accidents and selected incidents within tha United States, its territories and possessions, and international waters. Some of the important variables in the dataset are : Aircraft damage, category, make, model, number of engines, engine type, injury severity and total injuries.
The original dataset can be found here 

**For a group project**, have only one team member do these steps:

1. Fork this repository to your personal account
   - In GitHub, go to this repository and click the "Fork" button in the upper right
   
2. Change the name of your fork of this repo to a _descriptive_ name of your choosing
   - In GitHub, go to your fork of this repo -> "Settings" -> "Options" -> "Repository Name" -> "Rename"
   - Make the name descriptive, since potential employers will read it. Ex: "Microsoft-Movie-Analysis" is better than "Project-1"

3. Use `git clone` to clone your fork of this repo to your local computer

4. **For a group project**, add team members as collaborators to your fork of this repo
   - In GitHub, go to your fork of this repo -> "Settings" -> "Manage Access" -> "Invite Teams or People"
   - Add your project team members as collaborators & send them the repo GitHub URL

### Work In Your Fork Of This Repository

- Work in the repo clone that you created on your local machine
- Start writing and coding in the Jupyter Notebook `dsc-phase1-project-template.ipynb`
- Fill in the README template in `TEMPLATE_README.md`
- Use `git add`, `git commit`, and `git push` often to update your repo in GitHub
   - For a refresher on how to do this and why it's important, review Topic 2: Bash and Git

### Use The Slide Template

1. Go to [this link](https://docs.google.com/presentation/d/1PaiH1bleXnhiPjTPsAXQSiAK0nkaRlseQIr_Yb-0mz0/copy) to make an editable copy of the slide deck in your own Google Drive account
2. Go to "Slide," select "Change Theme," and pick a theme you like so your presentation doesn't look like everyone else's
3. **For a group project**, click the "Share" button and add your teammates as editors

### Tidy Up Your Project

- Change the file name of the Jupyter Notebook (`dsc-phase1-project-template.ipynb`) to something more descriptive
- Save an appropriately-named PDF version of your slide deck to the repository
- Rename the template readme you've been working in by running `git mv TEMPLATE_README.md README.md`
- Delete unnecessary files from the repo using `git rm`
   - The presentation PDF: `DS_Project_Presentation_Template.pdf`
   - Any unused data files in the `zippedData` folder
   - Any unused images in the `images` folder
- Utilize the .gitignore file to ignore large unzipped data files in the `zippedData` folder
   - Add `*.csv`,`*.tsv`, and `*.db` to the .gitignore file

### Submit Your Project

To submit your project, please follow the instructions in the "Project Submission & Review" page in the Milestones course.

***
### Notes

- The visualizations in the notebook use best practices for visualization that you should try to emulate. For example, they have clear axes, descriptive titles, and appropriate number formatting
- The `dsc-phase1-project-template.ipynb` is intended to be the _final version_ of your project. The first notebook you create will not look like this. You are encouraged to start with a very disorderly notebook and clean it as you go
