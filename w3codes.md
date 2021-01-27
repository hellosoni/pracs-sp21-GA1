
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
git add data/*

# Update README.md file:
echo "Change the file extension for the dummy files in data in the rename-data-files branch by using the "for" loop >README.md
echo "The for loop codes:
```
```
for oldname in *.txt
do
newname=$(basename $oldname txt)csv
echo "Old name: $oldname"
   echo -e "New name: $newname \n"
    mv "$oldname" "$newname"
done" > README.md

git add README.md
git commit -m "Add code block in README"
git status

# Push your local repo online
```
git remote add origin git@github.com:hellosoni/pracs-sp21-GA1.git
git branch -M main
git push -u origin main
```

