create env

```bash
conda create -n wineq python=3.10 -y
```

activate env
```bash
conda activate wineq
```

created a requirements.txt file
installl the requirements
```bash
 pip install -r requirements.txt
 ```

 Download the data from 
 https://drive.google.com/drive/folders/1xw0XX-WK74uxtFFLySbtnX-ODdmdK5Ec

 git init

 dvc init
 ``` 
 It will create certain folders called .dvcignore etc.,
 

 dvc add data_given/winequality.csv

 git add .

git commit -m "First commit"

git add . && git commit -m "update README.md"

``` Create a new github respository and execute the below command which will add entire code to the repository - master
git remote add origin https://github.com/Varenyamadhum/mlops-projects.git
```
```
Now change the master to main
git branch -M main
```
```Now get all the vscode to your repository 
git push -f -u origin main
```` 
