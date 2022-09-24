# flask-with-ibm-object-cloud-storage

This is a sample flask program to upload file to IBM Cloud Object Storage 

Need to install  ibm-cos-sdk library
-----------------
pip install ibm-cos-sdk

Credentials setup for flask program
-----------------

Replace the below XXXXX with the credentials of Service Credentials of IBM Cloud Object Storage

COS_ENDPOINT = "XXXXXX" # Current list avaiable at https://control.cloud-object-storage.cloud.ibm.com/v2/endpoints

COS_API_KEY_ID = "XXXXX" # eg "W00YixxxxxxxxxxMB-odB-2ySfTrFBIQQWanc--P3byk"

COS_INSTANCE_CRN = "XXXX"

If Service Credentails are bot present then we have to create a new Service Credentails using Manager Role

Steps to run
----------
open command prompt where the files are present


python app.py


url:  http://127.0.0.1:8080/uploader

References
-----
https://cloud.ibm.com/docs/cloud-object-storage?topic=cloud-object-storage-python
