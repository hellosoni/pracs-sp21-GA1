Change the file extention for the dummy files in data in the rename-data-files branch by using the for loop
# Change the name in data file
```
for oldname in *.txt
do
newname=$(basename $oldname txt)csv
echo "Old name: $oldname"
   echo -e "New name: $newname \n"
    mv "$oldname" "$newname"
done" > README.md
```
