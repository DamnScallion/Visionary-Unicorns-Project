# 🚀Visionary-Unicorns-Project
### Contain original Penguins vs Turtles dataset from Kaggle in the data/original folder
### https://www.kaggle.com/datasets/abbymorgan/penguins-vs-turtles

# 🔥Project Migration / Integrate all in one
### This repo was created for us to work with the same data directory. So we don't have to code separately within our own Google Drive directory.
### More important, we can run anyone's cells in Colab though it wasn't written by you. Cuz it wasn't mounted with a personal Drive anymore 🔗‍💥
### Unfortunately, Google Colab doesn't support clone private repo. So we need to keep it public.

# 🛠️Usage (Useful Tutorial Video https://youtu.be/FGNDZu0fCWQ)
### Step 1: Click any notebook file and then click the Open in Colab icon at the top

### Step 2: Clone the repo to Google Colab notebook, run the below command in Colab cell first
##### !git clone https://github.com/DamnScallion/Visionary-Unicorns-Project.git

### Step 3: Click the folder icon 🗀 on the Colab notebook left-hand side, will see the folder names Visionary-Unicorns-Project

### Step 4: Copy and paste your code into the current .ipynb file

### Step 5: Change all paths to align with the Visionary-Unicorns-Project folder

### Step 6: Update notebook code to the Github repo. 
##### a. Click File at the top of Colab notebook, and select Save a copy in Github.
##### b. Select the Repository names DamnScallion/Visionary-Unicorns-Project and type any text in Commit message
##### c. Click ok. Then u will see the updated .ipynb file you changed in our repo

### Step 7: Happy coding 💀


# 🌲Data Folder tree
```bash
└─data
    ├─5k_augmented
    │  └─5k_train
    └─original
        ├─train
        └─valid
```

# 🌲YOLO Data Folder tree
```bash
└─data-yolo-format
    ├─5k_augmented
    │  ├─images
    │  │  └─train
    │  └─labels
    │      └─train
    └─original
        ├─images
        │  ├─train
        │  └─valid
        └─labels
            ├─train
            └─valid
```


# 👻Git Sample Usage:
###### Pull updated source code from remote branch MAIN and merge it with you local branch code
git pull origin main
###### Add all locally changed files ready for commit
git add .
###### Save all changed files as a checkpoint ready for push
git commit -m 'feature: yolo bbox attributes deconstruction'
###### Push these changed files to a remote repository at branch MAIN
git push origin main


# 👽Other Useful Commands:
### Git clone
git clone <https://name-of-the-repository-link>
### Git branch
###### Creating a new branch:
git branch BRANCH-NAME
###### Viewing branches:
git branch or git branch --list
###### Deleting a branch:
git branch -d BRANCH-NAME
