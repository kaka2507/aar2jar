# Convert AAR to library for Ant

How to use: Copy your aar and all dependeces (jar and other aars into the directory which have convert.py)
```sh
$ convert.py -i your_project_without_extension -o output
```
After that, in output directory, we will have all projects which you can include into ant project (old build system for Android)

# Notices:
1. Python 2.7
2. 'android' have to install and add into $PATH