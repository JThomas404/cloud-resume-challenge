# My AWS Cloud Resume Challenge Project ☁

I'm thrilled to share my journey through the AWS Cloud Resume Challenge. This project has been a fantastic opportunity to apply and showcase my skills in AWS cloud technologies. Here’s a detailed look at my progress through the various stages of the challenge.

## Stage I: Static Website Deployment

In the first stage, I focused on building a static website. This was a crucial step to demonstrate my foundational skills in web development and cloud hosting.

### Project Highlights
- **Static Website:** Crafted with basic HTML and CSS to showcase essential web design skills.
- **AWS S3 Hosting:** Deployed on AWS S3, ensuring reliable and scalable access.
- **CI/CD Automation:** Set up a CI/CD pipeline using GitHub Actions to streamline deployment.

![Screenshot1](https://s3.amazonaws.com/my-cloud-resume-bucket1234/1.jpeg)
![Screenshot2](https://s3.amazonaws.com/my-cloud-resume-bucket1234/3.jpeg)

### Explore the Live Website
[Check out the live site](https://lnkd.in/d2kfa-AB)

### Purpose of the Project
The goal was to create a simple yet effective website to demonstrate my expertise in cloud infrastructure and automation. By focusing on the backend setup rather than complex design elements, I highlighted my technical abilities in managing and deploying cloud solutions.

### Reflections on Phase I

**1. What aspect of Phase I’s work did I find the most difficult?**

The most challenging part was configuring the CI/CD pipeline with GitHub Actions. Integrating it with AWS S3 to ensure smooth, automatic deployments required a deep dive into various configurations and best practices. It was a complex process, but it taught me a lot about the intricacies of automated workflows.

**2. What problems did I overcome to get the static site deployed?**

- **Issue:** I ran into permission problems with the S3 bucket, which resulted in a "403 Forbidden" error when trying to access the site.
  - **Solution:** I updated the bucket policy to allow public access to the site files, adjusting the settings in the AWS S3 console to ensure that all necessary permissions were granted.

- **Issue:** The GitHub Actions workflow failed due to incorrect HTML configuration.
  - **Solution:** I carefully reviewed and corrected the HTML file for the GitHub Actions workflow, using documentation to fix syntax errors and ensure proper configuration.

**3. What would I have done differently, or added, if I had more time?**

With more time, I would have added advanced features like responsive design and interactive elements to the website. Additionally, integrating a custom domain through AWS Route 53 would enhance the site’s professional appearance. These changes would not only improve the user experience but also showcase a more refined project.

**4. Did I try any mods, and how did they improve the project?**

Yes, I implemented a CI/CD pipeline using GitHub Actions to automate the deployment process. This mod was a significant upgrade from the basic challenge requirements. It introduced automation into the deployment workflow, reducing manual effort and demonstrating practical DevOps skills in a cloud environment.

---

## Stage II: Lambda and DynamoDB Integration (Back-End API)

The second stage of the project involved integrating AWS Lambda with DynamoDB to create a dynamic view counter for my website. This step allowed me to delve into serverless computing and database interactions.

![Screenshot3](https://s3.amazonaws.com/my-cloud-resume-bucket1234/Py.png)
![Screenshot4](https://s3.amazonaws.com/my-cloud-resume-bucket1234/code+200.png)

### Reflections on Stage II

**1. What aspect of Stage II’s work did I find the most difficult?**

The toughest challenge was ensuring that the Lambda function communicated correctly with DynamoDB and incremented the view count reliably. Debugging data type issues and managing DynamoDB permissions required detailed troubleshooting and fine-tuning of the function’s logic.

**2. What problems did I overcome to get the cloud function talking to my database?**

- **Issue:** I encountered a syntax error in the Lambda function code that halted execution.
  - **Solution:** I reviewed and corrected the code to fix syntax issues, ensuring all brackets and syntax were properly aligned.

- **Issue:** The view count wasn’t updating as expected.
  - **Solution:** I adjusted the Lambda function’s logic to ensure it correctly incremented the count and updated DynamoDB. This involved verifying and refining the update operation within the function.

**3. Did I implement any mods, and how did they enhance the project?**

I chose to add functionality to increment the view count by 1 with each page refresh. This enhancement provided a dynamic feature to the static site, showcasing real-time interaction with the database and leveraging serverless computing. It made the project more engaging and practical.

**4. What would I have done differently, or added, if I had more time?**

With additional time, I would have incorporated comprehensive error handling and logging within the Lambda function. This would help track and address issues more effectively. Additionally, I would explore adding analytics to monitor page views and integrate other AWS services for more advanced data management.

---

This project has been an incredible learning experience so far, and I’m eager to continue expanding my cloud skills and tackling new challenges and next phases.
