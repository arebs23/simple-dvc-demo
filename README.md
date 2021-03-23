create env

'''bash
conda create -n wineQ python=3.7 -y
'''

activate env
''' bash
conda activate wineQ
'''

created a req file

install the req

'''bash
pip install -r requirements.txt
'''
download the data from

https://drive.google.com/drive/folders/1xw0XX-WK74uxtFFLySbtnX-ODdmdK5Ec
'''bash
git init
'''

'''bash
dvc init
'''

'''bash
dvc add
'''

'''bash
dvc add data given/winequality.csv
'''

'''bash
git add .
'''

oneliner updates for readme

'''bash
git add . && git commit -m "update Readme.md"
'''

'''bash
git remote add origin git@github.com:arebs23/simple-dvc-demo.git
git branch -M main
git push origin main
'''