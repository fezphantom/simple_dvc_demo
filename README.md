create env

'''bash
conda create -n wineq python=3.9.2 -y
'''

activate env

'''
source activate wineq
'''

create a requirements.txt file

'''
touch requirements.txt  or you can manually create it in your project directory
'''

populate requirements.txt with packages to install

'''
dvc
dvc[gdrive]
sklearn
'''

install the packages in requirements.txt

'''
pip install -r requirements.txt
'''
