
# Assignment week 3
```
module load git
git init
git status
touch README.md 
git add README.md 
git status
```
# Add some data files
```
mkdir data
cd data
touch sample{001..100}.txt

#count number of files:
ls *.txt | wc -l
#  Stage data directory
git adddata/*


