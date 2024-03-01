# Practice
Practice

# Create a new repository by github directly

# Step 1 
create a new repo in github itself
add commit and save a repo file in git

# step 2  configure git
git config --global user.name 'SujithNaik-DA'               
git config --global user.email 'sujithnaik08642@gmail.com'
git config --list                                  -- to check wheather this cofiguration worked or not

# step 3 Basic command used
git clone 'https code'

clear               -- used to clear all the command line
cd 'Desktop'        -- move inside of folder in local computer
cd ..               -- to come out from the folder
ls                  -- give the list of folder or files inside the folder
ls -a               -- show all the list of folder or files inside the folder
pwd                 -- give the present working directory

git status          -- check whether the file got commited or what

                like there are 4 types
                        1. Untracked            -- new filre that git doesn't yet tracked
                        2. Unmodified           -- Unchanged
                        3. Modified             -- Changed
                        4. Staged               -- File is ready to commited


                                        here if change\new file 
                                                modified\untracked          it is in between    
                                                                                use add -- we call as staged
                    