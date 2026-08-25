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

## Research Experience

<div class="project0">
    <div class="image-container0">
        {% include figure.liquid loading="eager" path="assets/img/7.png"%}
    </div>
    <div class="project-details0">
        <div class="heading">
        <h3>LLM Agents for Consumer Behavior Research</h3>
        <span class="timeline">Ongoing</span>
        </div>
        <p>Role: <strong>Co-Author</strong>, with <a href="https://scholarworks.bwise.kr/hanyang/researcher-profile?ep=1216">Dr. Boram Lim</a> (formerly University of Kansas)</p>
        <p>Location: <strong>Remote</strong></p>
        <p><b>Contributions:</b></p>
        <ul>
            <li>Designing an agent-based simulation framework in which GPT-powered agents make restaurant-choice decisions, enabling controlled experiments on consumer behavior at a scale that is infeasible with human subjects</li>
            <li>Implementing a factorial experimental design over review-presentation algorithms (highest-rated vs. most-recent) and restaurant positioning (high-end vs. casual) to isolate their effects on choice</li>
            <li>Built bias-detection and dynamic review-supplementation components to reduce systematic drift in agent responses, plus structured behavioral logging for quantitative analysis of decision traces</li>
        </ul>
    </div>
</div>

<div class="project0">
    <div class="image-container0">
        {% include figure.liquid loading="eager" path="assets/img/rhino.png"%}
    </div>
    <div class="project-details0">
        <div class="heading">
        <h3>Smart Shelf Advertising on Low-Cost Edge Devices</h3>
        <span class="timeline">2024 - 2025</span>
        </div>
        <p>Role: <strong>Co-Author</strong></p>
        <p>Location: <strong>Karachi, Pakistan</strong></p>
        <p><b>Contributions:</b></p>
        <ul>
            <li>Developed a real-time retail system that detects product pick-up events and triggers contextual video advertisements, running end to end on low-cost edge hardware</li>
            <li>Trained a custom YOLOv8 segmentation model on a self-collected dataset of 3,500+ images, achieving 97.4% mAP@0.5 with real-time inference on constrained devices</li>
            <li>Integrated AprilTag-based tracking and Arduino-controlled lighting into a single pipeline, validating robustness under varied shelf and lighting conditions</li>
        </ul>
    </div>
</div>

<div class="project0">
    <div class="image-container0">
        {% include figure.liquid loading="eager" path="assets/img/ssuet.png"%}
    </div>
    <div class="project-details0">
        <div class="heading">
        <h3>Simulation Study on Edge-Cloud Traffic</h3>
        <span class="timeline">2023</span>
        </div>
        <p>Role: <strong>Research Assistant</strong> to Engr. Muhammad Rehan Rasheed</p>
        <p>Location: <strong>Sir Syed University, Karachi</strong></p>
        <p><b>Contributions:</b></p>
        <ul>
            <li>Built a Java-based discrete simulation of edge-cloud environments to analyze traffic-management strategies and their effect on latency and throughput</li>
        </ul>
    </div>
</div>

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
        <p>Position: <strong>Head of Web Data Acquisition</strong> (promoted Jun 2025); previously <strong>Software Engineer</strong></p>
        <p>Employment Type: <strong>Full Time</strong></p>
        <p>Location: <strong>Canada (Remote)</strong></p>
        <p><b>Key Achievements:</b></p>
        <ul>
            <li>Architected an AI-powered auto-remediation platform (Claude API, GitHub Actions, RabbitMQ, SigNoz, Slack, ClickUp) that detects connector failures, scrubs PII, drafts pull requests, and applies path-restricted AI fixes through CI/CD, cutting manual triage time by 70% and issue resolution time by 50%</li>
            <li>Built a browser-automation platform driven by a custom-trained ML model that parses web-page structure to automate data extraction, improving extraction efficiency by 35% and reducing manual effort by 60%</li>
            <li>Engineered backend services in Node.js, TypeScript, MongoDB, Redis, Docker, and REST APIs powering scalable financial data pipelines</li>
            <li>Eliminated 30% of peak-hour request failures by profiling load patterns and introducing predictive pre-scheduling of jobs with AWS CDK</li>
            <li>Led API integrations for fintech partners including Questrade and Flinks, covering secure authentication flows and optimized data access</li>
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
        <p>Position: <strong>Software Engineer (ML/AI &amp; Backend)</strong></p>
        <p>Employment Type: <strong>Full Time</strong></p>
        <p>Location: <strong>United States (Remote)</strong></p>
        <p><b>Key Achievements:</b></p>
        <ul>
            <li>Built retrieval-augmented generation (RAG) systems pairing embedding models with vector databases (Pinecone, FAISS) to ground LLM outputs in proprietary corpora, substantially reducing hallucination on knowledge-intensive tasks</li>
            <li>Fine-tuned open-source LLMs with LoRA/QLoRA (PEFT) on curated instruction datasets, matching the quality of substantially larger models at a fraction of training and inference cost</li>
            <li>Accelerated inference via 4-bit/8-bit quantization and vLLM-based serving, increasing throughput while reducing GPU memory footprint and latency in production</li>
            <li>Developed computer-vision pipelines for object detection, segmentation (YOLOv8), and OCR in PyTorch, using mixed-precision and distributed (DDP) training to shorten experiment cycles</li>
            <li>Established MLOps practice: experiment tracking (Weights &amp; Biases), automated evaluation harnesses with LLM-as-judge, model versioning, and CI/CD, enabling reproducible experiments and dependable releases</li>
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
            <li>Deployed a machine learning model on AWS as an end-to-end pipeline with model hosting, input pre-processing, and result handling using Lambda, S3, and API Gateway</li>
            <li>Migrated a three-tier application from Render to AWS with CI/CD via CodePipeline, improving performance by 30% and reducing hosting costs by 20%</li>
            <li>Instrumented observability with Datadog and CloudWatch, surfacing 15 latent issues and cutting user-reported incidents by 25%</li>
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
            <li>Developed and optimized microservices for a real-estate platform using Lambda, S3, and DynamoDB, reducing latency by 18%</li>
            <li>Implemented CI/CD pipelines (CodePipeline, CodeBuild) with automated testing, deployment, and rollback across environments, cutting release times by 40%</li>
        </ul>
    </div>
</div>

## Technical Skills

| Area | Tools & Technologies |
| --- | --- |
| **Languages** | Python, TypeScript/JavaScript, Java, SQL, Bash |
| **ML & AI** | PyTorch, TensorFlow, scikit-learn, Hugging Face Transformers, PEFT (LoRA/QLoRA), vLLM, LangChain, CrewAI, OpenCV, YOLOv8, Weights & Biases |
| **LLM Systems** | RAG, vector databases (Pinecone, FAISS), quantization (4/8-bit), evaluation harnesses & LLM-as-judge, agentic workflows |
| **Backend** | Node.js, Express.js, Nest.js, FastAPI, Django, Flask, MongoDB, Redis, DynamoDB, REST APIs |
| **Cloud & DevOps** | AWS (Lambda, S3, EC2, DynamoDB, API Gateway, CDK, CodePipeline), Docker, Kubernetes, GitHub Actions, Datadog, SigNoz |

## Impact Highlights

- **AI-driven automation**: 70% reduction in manual triage time and 50% faster issue resolution through an autonomous remediation pipeline
- **Data acquisition at scale**: 35% higher extraction efficiency and 60% less manual effort via ML-guided browser automation
- **Reliability**: 30% fewer peak-hour request failures and 25% fewer user-reported incidents
- **Efficiency**: 4/8-bit quantization and vLLM serving for higher throughput at lower GPU cost; 20% lower hosting costs after cloud migration
- **Delivery**: 40% shorter release cycles through automated CI/CD with testing and rollback
- **Domains**: fintech data pipelines, retail computer vision on edge devices, real-estate microservices, and LLM research tooling
