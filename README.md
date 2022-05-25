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
