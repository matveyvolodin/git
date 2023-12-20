Git

Here you can find some git commands that I used to do tasks during my QA studies.

#### Creating, cloning, pushing repositories
```git
git init matveyvolodin                                    # Create your repository with the same name as
git clone git@github.com:matveyvolodin/matveyvolodin.git  # Clone your repository on your computer to a separate folder
git clone git@github.com:testrusau/testrusau.git          # Сlone github.com/testrusau/testrusau to your computer to a separate folder
cp -r ~/Desktop/GitHub_repo/testrusau/*                   # Push data from testrusau local repository to your own local repository
~/Desktop/GitHub_repo/matveyvolodin 
                                                          # README.md has been edited manually
git commit -m "Info updated"                              # Open the README.md file and replace each block with a separate commit
git push origin main
```

#### Creating, adding remote repositories  
```git
git init testing_documentation                            # Create separate repository for portfolio item
git remote add testing_documentation                      # Declarie repository remotely
git@github.com:testrusau/testrusau.git
touch README.md                                           # Create readme.md inside the repository
README.md edited manually                                 # Add links to your repositories to the README.md file
git add README.md                                         # Add README.md to index
git commit "readme updated"                                 
git push origin main                                      # Push changes to the main branch of your remote repository
```