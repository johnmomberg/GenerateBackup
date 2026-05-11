# Generate Backup 

Copies all of the contents of a folder to another folder. 

All files and folders listed in skip_files.txt will be ignored. 

Why not just keep your projects in OneDrive? If you have large data files that don't need to be backed up, or .git folders which store old versions, you will quickly run out of space in your OneDrive. This notebook allows you to specify specific folders to ignore when creating the backup. 

Another benefit is that you can run this command multiple times to create multiple backups, such as one in your OneDrive and one on an external hard drive. 

Output creates two logging files: 

backup_details.csv: Lists out every single file in the original folder and specifies whether it was included or not 
backup_summary.txt: Gives the total file size of the original and backed up folder 
