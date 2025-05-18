# Branch B1
git checkout -b B1
echo "<p>Branch B1 work - Date: $(date)</p>" >> index.html
git commit -am "Added B1 content"
git checkout main
git merge B1

# Branch B2
git checkout -b B2
echo "<p>Branch B2 work - Date: $(date)</p>" >> index.html
git commit -am "Added B2 content"
git checkout main
git merge B2

# Branch B3
git checkout -b B3
echo "<p>Branch B3 work - Date: $(date)</p>" >> index.html
git commit -am "Added B3 content"
git checkout main
git merge B3
