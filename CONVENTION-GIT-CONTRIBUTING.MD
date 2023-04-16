``` YAML

- ContributionWorkflow:
    1. Fork repository: use GitHub UI
    2. Clone forked repository: git clone https://github.com/<your_username>/<repository>.git
    3. Add upstream remote: git remote add upstream https://github.com/<original_owner>/<repository>.git
    4. Create feature branch: git checkout -b <branch_name>
    5. Make changes: edit code using your preferred editor
    6. Commit changes with prefix: git commit -m "<prefix>: <commit_message>"
       - Stage changes: git add <file(s)>
    7. Sync with upstream:
       - git fetch upstream
       - git merge upstream/main (or upstream/master)
    8. Push changes to fork: git push origin <branch_name>
    9. Create pull request: use GitHub UI
    10. Review and merge by maintainer: use GitHub UI


Contribution Recipe

Instructions:

1. Prepare the workspace:
   - Fork the repository on GitHub (use GitHub UI)

2. Get the ingredients:
   - Clone the forked repository: git clone https://github.com/<your_username>/<repository>.git

3. Connect the sources:
   - Add the original repository as an upstream remote: git remote add upstream https://github.com/<original_owner>/<repository>.git

4. Create the mix:
   - Create a new feature branch: git checkout -b <branch_name>

5. Add your changes:
   - Modify or update the code as needed (use your preferred editor)

6. Assemble the commit:
   - Stage changes: git add <file(s)>
   - Commit your changes with the appropriate prefix: git commit -m "<prefix>: <commit_message>"

7. Sync with the source:
   - Fetch changes from the upstream repository: git fetch upstream
   - Merge changes: git merge upstream/main (or upstream/master)

8. Serve your contribution:
   - Push your changes to your fork: git push origin <branch_name>

9. Share the dish:
   - Create a pull request to the original repository (use GitHub UI)

10. Enjoy the teamwork:
   - Maintainer reviews and merges the pull request (use GitHub UI)
``` YAML    