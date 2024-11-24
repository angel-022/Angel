# gitlab Tasks:
test
## Task 2: Create a new gitlab repository
```bash
git clone https://gitlab.com/EL-HOUSS-BRAHIM/gitlab.git
cd gitlab
git branch -m master
```
![gitlab Task2](https://github.com/user-attachments/assets/a865fe8a-bf1c-4b49-91d2-d41d352cf077)

---

## Task 3: Create Task1 folder in the master branch and push ./Task1/README.md file.
```bash
mkdir Task1
touch Task1/README.md
git add .
git commit -m "adding Task1 folder and the README file on the master branch"
git push origin master
```
![gitlab Task3](https://github.com/user-attachments/assets/1105a462-62fa-4903-b551-3f17b2bb392d)

---

## Task 4: Create a new dev branch and push a test file.
```bash
git checkout -b dev
touch test
git add .
git commit -m "adding test file to the dev branch"
git push --set-upstream origin HEAD
```
![gitlab Task4](https://github.com/user-attachments/assets/fcfeaa1c-6363-4a58-8428-e4be34c83238)

---

## Task 5: Create a new branch %USERNAME-new_feature.
```bash
git checkout -b %USERNAME-new_feature
```
![gitlab Task5](https://github.com/user-attachments/assets/a25cf01a-b7d6-4332-9761-040bab55d476)

---

## Task 6: Add README.md to %USERNAME-new_feature branch.
```bash
touch README.md
```
![gitlab Task6](https://github.com/user-attachments/assets/56b6dde6-30e0-49ab-bc47-f416b097cc64)

---

## Task 7: Check repository status using git status.
```bash
git status
```
![gitlab Task7](https://github.com/user-attachments/assets/af98f5e7-7c6c-4a49-84ad-035ccc4119d6)

---

## Task 8: Add .gitignore file to ignore files starting with .
```bash
echo ".*" > .gitignore
```
![gitlab Task8](https://github.com/user-attachments/assets/4b98c566-0419-4f55-aeeb-564e2446a998)

---

## Task 9: Commit and push changes to the gitlab repo.
```bash
git add -f .
git commit -m "adding readme and gitignore file %USERNAME-new_feature"
git push --set-upstream origin HEAD
```
![gitlab Task9](https://github.com/user-attachments/assets/c8b9abee-c843-430e-8f2b-46f6e1d857bb

---

## Task 10: Create a Merge Request (MR) to the dev branch.
```bash
#No commands here!
```
<p>first open your repo and click on Merge requests</p>
![gitlab Task10-1](https://github.com/user-attachments/assets/459d0020-f3a9-4804-9d76-46e6c537173d)
<p>next click on New Merge request </p>
![gitlab Task10-2](https://github.com/user-attachments/assets/8d0c10a2-b857-4bd9-8833-0b146a09934d)
<p>chouse the branch as you see on image </p>
![gitlab Task10-3](https://github.com/user-attachments/assets/2cfb3072-94b1-4790-be79-6b7887011fe9)
<p>now create the merge request, next do the merge on terminal as the next step and come back for the next merge request</p>
![gitlab Task10-4](https://github.com/user-attachments/assets/7a893937-93e1-4c7e-81f0-c83d3a061cb9)
<p>after the commands you will see this image it meed the branches has been merged</p>
![gitlab Task10-6](https://github.com/user-attachments/assets/7d820056-0c36-41aa-a2f1-3f2501ed5249)
<p>now chouse the branches for the merge as the image show</p>
![gitlab Task10-7](https://github.com/user-attachments/assets/e271b204-3acd-4feb-9bab-4580010b8480)
<p>now create the merge request</p>
![gitlab Task10-8](https://github.com/user-attachments/assets/a4535192-65e6-4a25-9184-9936b96176e7)
<p>now go to the next step to continue the merge commands </p>
![gitlab Task10-8](https://github.com/user-attachments/assets/1afba23a-0b46-432e-bf1e-21533b90ea00)
---

## Task 11: Merge %USERNAME-new_feature with dev and create an MR to master. Merge dev with master.
```bash
git checkout dev
git merge %USERNAME-new_feature
git push origin HEAD

git checkout master
git branch --unset-upstream
git merge dev
git push origin HEAD
```
![gitlab Task11-1](https://github.com/user-attachments/assets/f0603c83-d143-4dbe-b88c-415e81136ef7)
![gitlab Task11-2](https://gitlab.com/EL-HOUSS-BRAHIM/git/-/raw/master/images/gitlab17.png)

---

## Task 12: Checkout %USERNAME-new_feature, make changes to README.md, commit, and revert the last commit.
```bash
git checkout %USERNAME-new_feature
echo "this the New readme.md on the %USERNAME-new_feature branch" > README.md
git add .
git commit -m "editing the README file on the %USERNAME-new_feature branch"
git revert HEAD
```
![gitlab Task12](https://gitlab.com/EL-HOUSS-BRAHIM/git/-/raw/master/images/gitlab18.png)

---

## Task 13: Check the repo with git log, create log.txt in master, and save git log output.
```bash
git checkout master
git log
git log > log.txt
git add log.txt
git commit -m "Save git log output to log.txt"
git push origin HEAD
```
![gitlab Task13](https://gitlab.com/EL-HOUSS-BRAHIM/git/-/raw/master/images/gitlab19.png)

---

## Task 14: Delete local and remote %USERNAME-new_feature branch.
```bash
git branch -D %USERNAME-new_feature
git push origin --delete %USERNAME-new_feature
```
![gitlab Task14](https://gitlab.com/EL-HOUSS-BRAHIM/git/-/raw/master/images/gitlab20.png)

---

## Task 15: Add all used commands to git_commands.md in the dev branch.
```bash
#No commands on this step!
#this file is the last step
```
![gitlab Task3](https://gitlab.com/EL-HOUSS-BRAHIM/git/-/raw/master/images/gitlab21.png)

