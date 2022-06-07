# static_website_hosting_on_aws
This is an assessment on aws about host a static web file on s3 bucket, securing and distributing it with cloudfront during cloud developer training with ALX-Udacity . The webpage can be access through this link https://d2weqdbiomz1pi.cloudfront.net and the website_endpoint_url is http://udacity.aws.bucket.s3-website-us-east-1.amazonaws.com. A pictorial of the steps taken is shared below;

                                                    ```IMAGE VIEWS OF THE STEPS TAKEN```


* S3 bucket created (storage for our files) in the AWS Management console.
---------------------------------------------------


![Screenshot 2022-06-06 at 19 20 03](https://user-images.githubusercontent.com/54009597/172431392-cd09fbf3-4116-446f-b498-6838a5d04907.png)



* All website files uploaded to the S3 bucket created
---------------------------------------------------------------

![Screenshot 2022-06-06 at 19 20 09](https://user-images.githubusercontent.com/54009597/172431363-a881be10-b005-42b2-8e78-862e7e4278aa.png)



* S3 bucket is configured to support static website hosting. 
-----------------------------------------------------------


![Screenshot 2022-06-06 at 19 38 52](https://user-images.githubusercontent.com/54009597/172430945-6df335d8-86ab-40e3-b158-5340e19b08b4.png)


* Public accessibility of content of S3 bucket. This allows to access the content of your bucket by any request over the internet
---------------------------------------------------------------------------------------------------------------------------------------

![Screenshot 2022-06-06 at 19 21 23](https://user-images.githubusercontent.com/54009597/172431330-33958438-01e1-49c3-bd4e-4bbedf570d19.png)


* CloudFront has been enabled to retrieve and distribute website files.
----------------------------------------------------------------------


![Screenshot 2022-06-06 at 19 19 47](https://user-images.githubusercontent.com/54009597/172431431-5234cb4e-2ad9-4cdb-badd-83781d08d04f.png)

* Website is accessible publicly through domain_name endpoints 
---------------------------------------------------------------------
 ```https://d2weqdbiomz1pi.cloudfront.net ```
 

![Screenshot 2022-06-06 at 19 19 30](https://user-images.githubusercontent.com/54009597/172431458-ae556de7-2bb3-467f-900d-6a89ecdedbf7.png)


 * Website is accessible publicly through S3 website-endpoint URL 
 -----------------------------------------------------------------
``` http://udacity.aws.bucket.s3-website-us-east-1.amazonaws.com ```

![Screenshot 2022-06-07 at 17 33 23](https://user-images.githubusercontent.com/54009597/172434900-bc299278-9d86-4b16-b553-ebf937b760b8.png)

``` http://udacity.aws.bucket.s3-website-us-east-1.amazonaws.com ```


NOTE: Please, do give a like and follow if this helps you in any way. Thank you
-----




