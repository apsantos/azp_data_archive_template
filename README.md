# Directory structure and readme for projects

Clone and rename like this:

```
dir_name=project-name
git clone https://github.com/apsantos/azp_data_archive_template.git $dir_name
cd $dir_name
rm -rf .git protocol.* SupplementaryInfo/ .gitignore
mv project-name/* .
rm -r project-name
```
