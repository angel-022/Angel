# github Tasks:

## Task 2: Create a new githab repository
```bash
git clone git@github.com:angel-022/Angel.git
cd Angel
git branch -m master
```
![githab Task2](https://github.com/user-attachments/assets/916e655f-af4c-418b-a413-ca38c9508aad)

---

## Task 3: Create Task1 folder in the master branch and push ./Task1/README.md file.
```bash
mkdir Task1
touch Task1/README.md
git add .
git commit -m "adding Task1 folder and the README file on the master branch"
git push origin master
```
![githab Task3](https://github.com/user-attachments/assets/863cf2fc-50b1-4c05-9124-c6e03e5a93fa)

---

## Task 4: Create a new dev branch and push a test file.
```bash
git checkout -b dev
touch test
git add .
git commit -m "adding test file to the dev branch"
git push --set-upstream origin HEAD
```
![githab Task4](https://github.com/user-attachments/assets/557aa75d-95cd-4124-ad43-c749df78aba4)

---

## Task 5: Create a new branch %USERNAME-new_feature.
```bash
git checkout -b %USERNAME-new_feature
```
![githab Task5](https://github.com/user-attachments/assets/34fac80e-93cc-4d40-a8e2-dede1e51c50b)

---

## Task 6: Add README.md to %USERNAME-new_feature branch.
```bash
touch README.md
```
![githab Task6](https://github.com/user-attachments/assets/09252a0c-0227-4d88-b4be-d4b07529914b)

---

## Task 7: Check repository status using git status.
```bash
git status
```
![githab Task7](https://github.com/user-attachments/assets/880bb521-f565-4a91-8dad-9379362b8a6f)

---

## Task 8: Add .gitignore file to ignore files starting with .
```bash
echo ".*" > .gitignore
```
![githab Task8](https://github.com/user-attachments/assets/0fa8b31a-f49d-4c0c-a203-5d1d686737d8)

---

## Task 9: Commit and push changes to the githab repo.
```bash
git add -f .
git commit -m "adding readme and gitignore file %USERNAME-new_feature"
git push --set-upstream origin HEAD
```
![githab Task9](https://github.com/user-attachments/assets/9c935914-7d97-492f-9180-680d0a6b8ae1)

---

## Task 10: Create a Merge Request (MR) to the dev branch.
```bash
#No commands here!
```

<p>first open your repo and click on Merge requests</p>

![githab Task10-1](https://github.com/user-attachments/assets/4ad052a4-0805-4ff2-9516-bb023fa0aaeb)

<p>next click on New Merge request </p>

![githab Task10-2](https://github.com/user-attachments/assets/f6c66b8c-869a-4a68-a64b-f23aa698a2e9)

<p>chouse the branch as you see on image </p>

![githab Task10-3](https://github.com/user-attachments/assets/585b9aef-239a-462e-9e3d-e572066c0f70)

<p>now create the merge request, next do the merge on terminal as the next step and come back for the next merge request</p>

![githab Task10-4](https://github.com/user-attachments/assets/bde0f3a7-aae4-4034-b04f-d76e205cb15c)

<p>after the commands you will see this image it meed the branches has been merged</p>

![githab Task10-6](https://github.com/user-attachments/assets/dc6e656b-eae1-447b-99f8-bd594eaa1d4a)

<p>now chouse the branches for the merge as the image show</p>

![githab Task10-7](https://github.com/user-attachments/assets/bea9fa0f-231f-44da-8591-e49649aa6d71)

<p>now create the merge request</p>

![githab Task10-8](https://github.com/user-attachments/assets/f55640f7-61ed-46da-b491-f557e0ad5934)

<p>now go to the next step to continue the merge commands </p>

![githab Task10-8]()
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
![githab Task11-1](https://github.com/user-attachments/assets/b492e174-c110-431f-8f00-9cf83b512766)
![githab Task11-2](https://github.com/user-attachments/assets/a93ae0bb-37d3-4db3-b960-339fddc3a248)


---

## Task 12: Checkout %USERNAME-new_feature, make changes to README.md, commit, and revert the last commit.
```bash
git checkout %USERNAME-new_feature
echo "this the New readme.md on the %USERNAME-new_feature branch" > README.md
git add .
git commit -m "editing the README file on the %USERNAME-new_feature branch"
git revert HEAD
```
![githab Task12](https://github.com/user-attachments/assets/6b86ca3b-d48f-4ae1-8b78-de6a7dcfa484)

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
![githab Task13](https://github.com/user-attachments/assets/94b9b2d7-d558-4038-b800-f19bcf710d19)


---

## Task 14: Delete local and remote %USERNAME-new_feature branch.
```bash
git branch -D %USERNAME-new_feature
git push origin --delete %USERNAME-new_feature
```
![githab Task14](https://github.com/user-attachments/assets/c8e99615-aa66-47a8-976d-bb83ffa4dd5f)
---

## Task 15: Add all used commands to git_commands.md in the dev branch.
```bash
#No commands on this step!
#this file is the last step
```
