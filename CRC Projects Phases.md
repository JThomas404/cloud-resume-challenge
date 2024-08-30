## My AWS Cloud Resume Challenge Project ☁

I am thrilled to present the latest progress on my AWS Cloud Resume Challenge project, showcasing both Phase I and Phase II advancements.

---

### Phase I: Static Website Deployment

**Project Highlights:**
- **Static Website:** Developed using basic HTML and CSS.
- **AWS S3 Hosting:** Deployed on AWS S3 for reliable accessibility.
- **CI/CD Automation:** Established a CI/CD pipeline using GitHub Actions.

**Live Website:**  
Explore the live version of the website here: [Live Website](https://lnkd.in/d2kfa-AB)

**Purpose:**  
The primary goal was to create a straightforward website to demonstrate my cloud skills and proficiency with AWS services. This phase focused on cloud infrastructure and automation rather than elaborate web design.

---

### Phase II: AWS Lambda and DynamoDB Integration

**Phase II Highlights:**
- **Lambda Function:** Developed to manage and update view counts in DynamoDB.
- **DynamoDB Integration:** Configured to store and increment view counts on each page refresh.

**GitHub CI/CD Pipeline for Phase I:**
- **GitHub Actions Workflow:** Automated deployment process using GitHub Actions. Ensured the website updates automatically with each commit to the repository.

**GitHub CI/CD Pipeline for Phase II:**
- **Updated Workflow:** Integrated the Lambda function deployment into the CI/CD pipeline. This setup ensures that updates to the Lambda function are automatically deployed, facilitating seamless integration with DynamoDB.

---

### Journey Documentation:

**1. Most Difficult Aspect of Phase II:**  
The most challenging part of Phase II was configuring the AWS Lambda function to interact correctly with DynamoDB. Handling data types and ensuring accurate updates were key hurdles.

**2. Problems Overcome:**

- **Issue:** Syntax Error in Lambda Function  
  **Error Message:** Syntax error in module 'lambda_function': '{' was never closed  
  **Solution:** Corrected syntax errors by ensuring proper closure of JSON structures and return statements.

- **Issue:** View Count Not Updating  
  **Error Message:** Observed incorrect view count behavior  
  **Solution:** Revised the Lambda function to accurately increment and update the view count. Ensured proper data retrieval and update logic in DynamoDB.

**3. Modifications Implemented:**

- **Increment Logic:** Added to the Lambda function to increase the view count by 1 with each page refresh.
- **API Interaction:** Enhanced Lambda function to handle 'get' and 'update' actions, integrating effectively with DynamoDB.

**What I Learned:**  
Gained practical experience with AWS Lambda and DynamoDB integration, focusing on serverless computing and real-time data management. Improved skills in debugging and configuring serverless functions.

---

**Images from Phase I and Phase II:**

![Phase I Deployment](assets/static-website.png)
![Phase II Lambda Function](assets/lambda-dynamodb.png)

**Videos:**

[Testing the Lambda Code Counter](https://example.com/video-link)
---
