# myresume
This hands-on was inspired by tinytechnicaltutorials...all thanks to her (Amber)

I basically followed the steps highlighted in her YouTube videos to create the resume as a webpage.

This resume was created during my training as AWS Solutions Architect

The resume uses HTML, CSS and Javascript (all copied and edited). The files were uploaded on S3 that I configured with static website hosting with public access.

The S3 static website endpoint is then used under Alias in Route 53. 

Finally, an SSL/TLS generated from AWS Certificate Manager (ACM) was attached to CloudFront Distribution (which later became the endpoint for the Route 53).
