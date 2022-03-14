# CS-4843
Basic overview of the website- 
This is a very basic website. The website contains one video on the index page and 4 seperate pages of quotes from 4 different greek philosophers. 

Programming Languages- 
HTML (Hypertext Markup Language)- The website utilized html to stucture the webpages and their content.

CSS (Cascading Style Sheets)- CSS was used to style the format of the HTML elements we created.

JavaScript- JavaScript gave the website its functionality, more specifically the hyperlink redirection.

Infrastructure-
The S3 bucket allows for reduced cost and ensures a reliable access to objects world wide. Amazons Cloud Front utilizes content delivery networks to provide a globally-distributed network of proxy servers that cache media content locally to consumers, ultimately lowering latency issues and improving overall access speed for downloading said media content.

Security-
To ensure security I utilized AWS IAM Policy and restricted s3 bucket access. This manner of restriction ensures that the s3 bucket will only be accessed via the Cloud Front URL. IAM policy permits CloudFronts access to the objects in the s3 bucket via the ARN. The ARN contains the origin access identity, allowing for a private bucket.


Cloud Front access: https://d1qt83pap8xcfv.cloudfront.net/index.html
