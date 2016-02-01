# automate-aws
Python script to automate instance creation in AWS using boto3

**Dependencies:**
- Python 2.7
- boto3 (`pip install boto3`)
 
**Required**
- Creation of the credentials file: ~/.aws/credentials

```
[default]
# The access key for your AWS account
aws_access_key_id=<YOUR ACCESS KEY ID>

# The secret key for your AWS account
aws_secret_access_key=<YOUR SECRET KEY>
```
    
**Usage:**

awsmain.py [-h] [--config CONFIG]

Automate AWS instances creation

optional arguments:

  -h, --help            show this help message and exit

  --config CONFIG, -c CONFIG
                        Path of the config file.

