# Recipe-Finder-WebApp
Developed a Recipe Finder web app facilitating intuitive recipe discovery and exploration, hosted on AWS S3 for reliable and scalable static web hosting.<br>
Tech Stack: HTML, CSS, JavaScript , Amazon S3 (AWS) for static website hosting.

## Steps for hosting a static website on AWS S3
### 1. Sign in to AWS Console:
➢Log in to your AWS account at AWS Management Console.
### 2. Navigate to S3:
➢Go to the S3 service in the AWS Management Console.
### 3. Create a Bucket:
➢Click on "Create Bucket" and provide a unique name for your bucket.
### 4. Configure Bucket:
➢In the "Properties" tab, enable static website hosting.<br>
➢Set the index document (e.g., index.html,error.html) and error document if needed.
### 5. Set Permissions:
➢Go to the "Permissions" tab.<br>
➢Adjust the bucket policy to allow public read access. A sample policy:
![image](https://github.com/Jhajibhaskar/Recipe-Finder-WebApp/assets/84240276/8e718b1e-a5ce-45af-9c22-4eaab94e5e15)
### 6. Upload Website Files:
➢In the "Overview" tab, upload your HTML, CSS, JavaScript files, and any other assets to the bucket.<br>
### 7. Enable Static Website Hosting:
➢Go back to the "Properties" tab, and click on the static website hosting section.<br>
➢Note the endpoint URL (e.g., http://your-bucket-name.s3-website-your-region.amazonaws.com).<br>
### Click Here to experience the hosted website on AWS: http://kaleyranitpy.s3-website.ap-south-1.amazonaws.com/
