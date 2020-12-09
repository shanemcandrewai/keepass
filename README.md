# Keepass managment
## Configuration file
### Windows
C:\Users\[user name]\AppData\KeePass\KeePass.config.xml
## Export DB as XML
1. Open DB in Keepass
2. File>Export>KeePass XML (2.x)
## Comparison in vim
1. :e file1.xml
2. :se nowrap
3. :difft
4. :vs
5. CTRL-W w
6. :e file2.xml
7. :difft
8. ]c
## Importing XML to Keepass
1. File>New
2. Enter master password
3. Emergency sheet skip
4. File>Import KeepPass XML (2.x)
5. Import Bahaviour - Overwrite existing
6. Delete Sample Entries
7. Tools>Data Tools>Delete Empty Groups
8. save







