# AWS-S3-staticWebsite

Migrate an existing website to static website hosting on Amazon S3 to improve reliability.

![overview](https://github.com/awilali/AWS-S3-staticWebsite/assets/60300580/58dd750c-514d-4339-81a6-188dc8f02fa5)

General information:

In Amazon S3, any type of file, and any metadata that describes that file, is called an "object". Objects are stored in S3 containers called buckets.

This solution uses an S3 bucket to host a static website. In Amazon S3, the static website can sustain any conceivable level of traffic, at a very modest cost, without the need to set up, monitor, scale, or manage any webserver.

Along with an HTML file, files that support webpage functionality, such as client-side scripts and stile sheets, are uploaded to the S3 bucket. Any S3 buckets can be configured to host a static website.

When an S3 bucket is configured for website hosting, the bucket is assigned a URL. When requests are made to this URL, Amazon S3 returns the HTML file, known as the root object, that was set for the bucket.

For others to access the bucket, or specific objects in it, permissions (written in JSON format) must be configured to allow that access.
