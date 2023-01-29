## Linux Command used


### Remove all folder and file in the dir
``` sudo rm -r destination/* ```

### Copy all file listed in the file to its destination
``` cp -R $(cat mv_list) destination ```

### List all file and folder in the destination folder
``` ls -a destination ```

### Copy all files and folders in the destination folder to s3 bucket 
``` aws s3 cp destination s3://devlook.tech --recursive ```

