---
layout: page
permalink: /experiences/
title: Experiences
nav: true
nav_order: 2
---

<style>
.project0 {
    display: flex;
    margin-bottom: 2rem;
    padding: 1.5rem;
    border: 1px solid var(--global-divider-color);
    border-radius: 8px;
    background-color: var(--global-card-bg-color);
    transition: all 0.3s ease;
}

.project0:hover {
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    transform: translateY(-2px);
}

.image-container0 {
    flex: 0 0 120px;
    margin-right: 1.5rem;
}

.image-container0 img {
    width: 120px;
    height: 120px;
    object-fit: cover;
    border-radius: 8px;
    border: 1px solid var(--global-divider-color);
}

.project-details0 {
    flex: 1;
}

.heading {
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin-bottom: 0.5rem;
}

.heading h3 {
    margin: 0;
    color: var(--global-text-color);
}

.heading h3 a {
    color: var(--global-theme-color);
    text-decoration: none;
}

.heading h3 a:hover {
    color: var(--global-hover-color);
    text-decoration: underline;
}

.timeline {
    color: var(--global-text-color-light);
    font-weight: 500;
    font-size: 0.9rem;
}

.project-details0 p {
    margin: 0.25rem 0;
    color: var(--global-text-color);
}

.project-details0 ul {
    margin: 0.5rem 0;
    padding-left: 1.2rem;
}

.project-details0 li {
    margin-bottom: 0.3rem;
    color: var(--global-text-color);
}

@media (max-width: 768px) {
    .project0 {
        flex-direction: column;
    }
    
    .image-container0 {
        flex: none;
        margin-right: 0;
        margin-bottom: 1rem;
        text-align: center;
    }
}

/* Dark mode specific adjustments */
html[data-theme="dark"] .project0:hover {
    box-shadow: 0 4px 8px rgba(255, 255, 255, 0.1);
}
</style>

## Professional Experience

<div class="project0">
    <div class="image-container0">
        {% include figure.liquid loading="eager" path="assets/img/11.jpg"%}
    </div>
    <div class="project-details0">
        <div class="heading">
        <a href="https://wealthica.com/"><h3>Wealthica</h3></a>
        <span class="timeline">Jul 2024 - Present</span>
        </div>
        <p>Position: <strong>Software Engineer (Backend, AWS & Cloud)</strong></p>
        <p>Employment Type: <strong>Full Time</strong></p>
        <p>Location: <strong>Canada (Remote)</strong></p>
        <p><b>Key Achievements:</b></p>
        <ul>
            <li>Engineered robust backend systems using Node.js, TypeScript, and MongoDB powering scalable financial data pipelines at Wealthica</li>
            <li>Improved application response times by 25% by replacing legacy caching with Valkey</li>
            <li>Mitigated 30% request failures during peak hours by analyzing and implementing pre auto-scheduling with AWS CDK</li>
            <li>Helped fintech clients like Questrade, Flinks, and white-label partners in API integration of Wealthica with secure auth flows and optimized data access</li>
        </ul>
    </div>
</div>

<div class="project0">
    <div class="image-container0">
        {% include figure.liquid loading="eager" path="assets/img/12.jpg"%}
    </div>
    <div class="project-details0">
        <div class="heading">
        <a href="#"><h3>AutomateBoring</h3></a>
        <span class="timeline">Jul 2023 - Jul 2024</span>
        </div>
        <p>Position: <strong>Software Engineer (ML/AI & Backend)</strong></p>
        <p>Employment Type: <strong>Full Time</strong></p>
        <p>Location: <strong>United States (Remote)</strong></p>
        <p><b>Key Achievements:</b></p>
        <ul>
            <li>Automated the entire tax filing process of IRS using Django, AWS Lambda & EventBridge, improving efficiency by 40% and reducing errors by 25%</li>
            <li>Implemented a customer-facing conversational bot powered using CrewAI and LangChain</li>
            <li>Streamlined a secure upload and verification pipeline for driver's licenses, processing 500+ documents monthly with OCR</li>
            <li>Deployed microservices application using AWS EC2, ASG and ELB with a CI/CD pipeline</li>
        </ul>
    </div>
</div>

<div class="project0">
    <div class="image-container0">
        {% include figure.liquid loading="eager" path="assets/img/1.jpg"%}
    </div>
    <div class="project-details0">
        <div class="heading">
        <a href="https://myaskai.com/"><h3>MyAskAI</h3></a>
        <span class="timeline">Apr 2023 - Jul 2023</span>
        </div>
        <p>Position: <strong>AWS DevOps Engineer</strong></p>
        <p>Employment Type: <strong>Contract</strong></p>        
        <p>Location: <strong>United Kingdom (Remote)</strong></p>
        <p><b>Key Achievements:</b></p>
        <ul>
            <li>Analyzed application performance using Datadog and Cloudwatch, detecting 15 issues that were promptly addressed, leading to a 25% reduction in user-reported incidents</li>
            <li>Successfully migrated a three-tier app from Render to AWS with CI/CD using AWS CodePipeline, improving performance by 30% and reducing hosting costs by 20%</li>
            <li>Deployed a machine learning model on AWS, building an end-to-end pipeline with model hosting, input preprocessing, and result handling using services like Lambda, S3, and API Gateway</li>
        </ul>
    </div>
</div>

<div class="project0">
    <div class="image-container0">
        {% include figure.liquid loading="eager" path="assets/img/2.jpg"%}
    </div>
    <div class="project-details0">
        <div class="heading">
        <a href="#"><h3>Rehani Soko</h3></a>
        <span class="timeline">Jan 2023 - May 2023</span>
        </div>
        <p>Position: <strong>AWS DevOps Engineer</strong></p>
        <p>Employment Type: <strong>Contract</strong></p>        
        <p>Location: <strong>United States (Remote)</strong></p>
        <p><b>Key Achievements:</b></p>
        <ul>
            <li>Developed and optimized microservices for a real estate application, integrating AWS services such as serverless Lambda, S3, and DynamoDB to improve scalability and reduce latency by 18%</li>
            <li>Implemented CI/CD pipelines using AWS CodePipeline and CodeBuild, enabling automated testing, deployment, and rollback across multiple environments, cutting release times by 40%</li>
        </ul>
    </div>
</div>

## Career Progression & Impact

### **Technical Skills Development**
- **Backend Engineering**: Expertise in Node.js, TypeScript, Python, Django, Flask
- **Cloud & DevOps**: Advanced AWS services, CI/CD pipelines, infrastructure automation
- **AI/ML Integration**: LangChain, CrewAI, OpenAI APIs, document processing systems
- **Database Management**: MongoDB, DynamoDB, SQL optimization
- **Performance Optimization**: Caching strategies, load balancing, monitoring

### **Key Metrics & Achievements**
- **Performance Improvements**: 25-40% efficiency gains across multiple projects
- **Error Reduction**: 25-30% decrease in system failures and user-reported issues
- **Cost Optimization**: 20% reduction in hosting costs through strategic migrations
- **Scalability**: Built systems processing 500+ documents monthly
- **Client Impact**: Supported major fintech clients including Questrade and Flinks

### **Industry Experience**
- **Fintech**: Financial data pipelines, secure payment processing, API integrations
- **Tax Technology**: IRS automation, document verification, OCR processing
- **Cloud Migration**: Multi-tier application transitions, performance optimization
- **Real Estate Tech**: Microservices architecture, data processing pipelines

