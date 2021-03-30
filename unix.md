# Unix
## Useful commands 
```
  du -sk * | sort -n                        # Find large files and folders
  
  find . -name "*.log" | grep "<String>"    # Find a string in all .log files.
  find . -mtime +31 | *.log                 # Find log files greater than 31 days old.
  find . -mtime +90 -exec rm -f {} \;       # Find log files greater than 90 days old and remove them.
  
  grep -ir "<String>" *                     # Find a String in all files recursivity down the file structure 
  grep -r "Andrew" Server*/SystemOut*.log*  # Find user in each of the server SystemOut.log
  
  ps -ef | grep java                        # Find java process runing.
  
  passwd                                    # Change password 
  
  gzip -d file.gz                           # unzip a file
  tar xvf file.tar 		                      # extract the contents of Tar file
```
