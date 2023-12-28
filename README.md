# AWS Lambda Layers for Whanpia - Call & Message Alert Service

This repo contains Python packages in Lambda Layer required for [whanpia-alerts](https://github.com/nedd-ludd/whanpia-alerts/).

The following are included:

- boto3
- telnyx
- six

In order to upload as an AWS Lambda Layer, the "python" directory and contents must be compressed as a .zip file prior to uploading.

## Misc Information

A virtual environment was created for package dependency issues, then packaged using the code in.. <mark>code

N.B. The Python version used was 3.10 and packaged using the following code

Please refer to the full project [README.md](https://github.com/nedd-ludd/whanpia-alerts/blob/main/README.md)
