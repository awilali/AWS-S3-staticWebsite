<h2><b>Overview of the project:</b></h2>

![overview](https://github.com/awilali/AWS-S3-staticWebsite/assets/60300580/aed12db1-1058-4bbe-95a4-fbc251110873)

<br>

<h3><b>Steps to create the S3 bucket:</b></h3>

1. First I create the S3 bucket and select a unique name: <br>

2. Turning off "Block all public access" and create the bucket.

![s3](https://github.com/awilali/AWS-S3-staticWebsite/assets/60300580/1ee0bbcf-31c9-42f0-84d6-fcceb1927205)
 
 <br>

<b><h3>Enabling the static website:</h3></b>

1. Go to "Properties" of the S3 bucket and at the bottom of the page enable the static website. <br>

![staticwebEnabled](https://github.com/awilali/AWS-S3-staticWebsite/assets/60300580/d6159ea2-e475-4af5-9d38-ceb04898611c)

<br>

<b><h3>Allowing access from the internet:</b></h3>

1. Go to "Permissions" --> "Bucket policy":

![permissions](https://github.com/awilali/AWS-S3-staticWebsite/assets/60300580/051d3c24-5b8d-4936-8754-92aeeca2a87c)

<br>

<b><h3>Upload the static website files onto the S3.</b></h3> 

1. Click on the S3 bucket name and drag and drop your html files then upload.

![BucketFiles](https://github.com/awilali/AWS-S3-staticWebsite/assets/60300580/082e7d10-9896-4516-8b58-5b48cd22d3b5)

<br>

<b><h3>Test the static website</b></h3>

1. Open the S3 bucket, tick the index.html page and "Open"

![test](https://github.com/awilali/AWS-S3-staticWebsite/assets/60300580/ff359008-748e-4930-b2c3-ac4bd851073b)

<br>
If the connection is successfull the website should as appear!

![stwebsite](https://github.com/awilali/AWS-S3-staticWebsite/assets/60300580/26df8371-8809-4537-a071-f3bed4552ad7)

END OF PROJECT!
