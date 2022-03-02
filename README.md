# Document_Clustering
## Problem Statement
You have decided to organize the files on your laptop. You have been saving files in three directories called red, blue, green but you now realize that you need to reorganize these files based on content, into 3 new directores. Naming these files file-1, file-2 etc. was also not such a great idea ….

Armed with your newly minted data science degree, you decide on the following reorg scheme:
- You will first group files based on their content, using 3 groups (note: this really depends on the contents of the files but we will assume they fall into 3 groups for simplicity)
- for each group you will create a directory named something that hints at the contents of the files in that dir.
- each file will be renamed using the most frequently occurring word in the file and its frequency (e.g. bond7), taking care to exclude common words like the, and etc. The renamed file will be saved to its new directory created in step (b) above.
- you will also create a summary visual that will remind you of what’s in the files and save that visual as a file picture.png in the same dir. This way, you can look at the picture first before deciding to look in the files (When you decide to get organized you spare no expense!)
