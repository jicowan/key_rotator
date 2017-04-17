# Key Rotator
This script can be used to rotate AWS access keys.  
Usage: 
key_rotator.py --username <username> --key <aws_access_key> 

optional flags: 

--delete (deletes a key)

--disable (disables a key)

The script assume that the user executing the script has an IAM policy that allows them to create/modify/delete AWS access keys. 
