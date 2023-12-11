# myresume
This resume was inspired by tinytechnicaltutorials...all thanks to her (Amber)

I basically followed the steps highlighted in her YouTube videos to create the resume as an interactive website. The resume was created during my training as AWS Solutions Architect (Dec 2023)

The resume uses HTML, CSS and Javascript (all copied and edited LOL. I was yet to learn coding). The files were uploaded on S3 Bucket that I configured with static website hosting (definitely with public access).

The S3 static website endpoint was initially used as endpoint under Route 53 (Alias option) just to test it before attaching certificate. 

Additionally, I generated an SSL/TLS generated from AWS Certificate Manager (ACM) and also created a CloudFront Distribution. The certifcate was attached to the CF Distribution.

Finally, the initial S3 Static website endpoint was replaced with the created CF Distribution DNS endpoint on Route 53.
