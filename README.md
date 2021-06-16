# PhotoDetails

Appplication is to 
- Fetch data from https://jsonplaceholder.typicode.com/photos
- Process json data 
- Create TSV file with columns "photo_id, title, url, timestamp"
- Gzip the TSV
- Upload file to S3 bucket

Configurable AWS Credentials and s3 Bucket
---------------
Add your ACCESS_KEY and SECRET_KEY in settings.py
```
ACCESS_KEY = ""
SECRET_KEY = ""

BUCKET_NAME = "photo-details-2021"
```

To Run
-------
make run


Testing
-------
make test 


