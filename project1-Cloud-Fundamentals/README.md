URL: http://uda-cloud-develop-chapter1.s3-us-west-2.amazonaws.com/index.html

- step 1: create a S3 Bucket. 
  - ![](./1.png)
- step 2: update static resources to S3 Bucket instance. 
  - ![](./2.png)
- step 3: uploaded. 
  - ![](./3.png)
- step 4: set Bucket Policy of S3 Bucket's Permissions 
  - ![](./4.png)
  - the version always be '2012-10-17' 
  - also got JSON from the link of Policy generator
- step 5: select Properties of Static website hosting 
  - ![](./5.png)
- step 6: create a distribution of Cloud Front with S3 Bucket 
  - ![](./6.png)
- step 7: wait the website deployed. 
  - ![](./7.png)
- step 8: borswer the website with URL 
  - ![](./8.png)