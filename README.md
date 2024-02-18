# AWS-S3-Object-Lambda-Dynamic-Watermark

Amazon S3 Object Lambda allows you to add your own code to S3 GET, HEAD, and LIST requests to modify data as it is returned to an application. You can use custom code to modify the data returned by S3 GET requests to convert data formats (for example, XML to JSON), dynamically resize images, redact confidential data, and much more.

In this project I have used S3 Object Lambda to add a watermark to an image as it is retrieved from Amazon S3. S3 Object Lambda can be used to modify data as it is retrieved from Amazon S3, without changing the existing object or maintaining multiple derivative copies of the data. By presenting multiple views of the same data and removing the need to store derivative copies, you can save on storage costs.
