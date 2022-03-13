# CS-4843
Basic overview of the website- 
This is a very basic website. The website contains one video on the index page and 4 seperate pages of quotes from 4 different greek philosophers. 

Programming Languages- 
HTML (Hypertext Markup Language)- The website utilized html to stucture the webpages and their content.

CSS (Cascading Style Sheets)- CSS was used to style the format of the HTML elements we created.

JavaScript- JavaScript gave the website its functionality, more specifically the hyperlink redirection.

Infrastructure-

Security-
To ensure security I utilized AWS IAM Policy and restricted s3 bucket access. This manner of restriction ensures that the s3 bucket will only be accessed via the Cloud Front URL. Furthermore, the bucket's IAM policy explicitly allows Cloud Front to access any objects in the specified bucket by using the ARN of the Cloud Front distribution. This ARN includes the Cloud Front OAI (Origin Access Identity) which allows us to access a private S3 bucket.


Cloud Front access: https://d1qt83pap8xcfv.cloudfront.net/index.html
