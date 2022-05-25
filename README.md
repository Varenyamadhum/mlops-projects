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

```bash
 git init
 ```
```bash
 dvc init
 ``` 
 It will create certain folders called .dvcignore etc.,
 
Add winequality data set to data_given folder
```bash
 dvc add data_given/winequality.csv
 ```

``` bash
 git add .
 ```
To commit the changes 
```bash
git commit -m "First commit"
```

To add and commit the changes to the specific file in one step
```bash
git add . && git commit -m "update README.md"
```
Create a new github respository and execute the below command which will add entire code to the repository - master
```bash 
git remote add origin https://github.com/Varenyamadhum/mlops-projects.git
```

Now change the master to main
```bash
git branch -M main
```
Now get all the vscode to your repository 
```bash
git push -f -u origin main
```` 
