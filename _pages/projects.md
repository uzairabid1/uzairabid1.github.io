---
layout: page
permalink: /projects/
title: Projects
nav: true
nav_order: 5
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
    margin: 0.5rem 0;
    color: var(--global-text-color);
}

.project-details0 button {
    background-color: var(--global-theme-color);
    color: white;
    border: none;
    padding: 0.5rem 1rem;
    margin: 0.25rem 0.5rem 0.25rem 0;
    border-radius: 4px;
    cursor: pointer;
    font-size: 0.9rem;
    transition: background-color 0.3s ease;
}

.project-details0 button:hover {
    background-color: var(--global-hover-color);
}

.project-details0 a {
    text-decoration: none;
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

## Featured AI & ML Projects

<div class="project0">
    <div class="image-container0">
        {% include figure.liquid loading="eager" path="assets/img/3.jpg" %}
    </div>
    <div class="project-details0">
        <div class="heading">
        <h3>Resume AI Assistant</h3>
        <span class="timeline">2025</span>
        </div>
        <p>Developed an intelligent resume optimization system powered by OpenAI GPT-4 and Pydantic for structured data validation. Features AI-powered resume tailoring against job descriptions, comprehensive gap analysis, automatic cover letter generation with customizable tones, visual diff highlighting of changes, and PDF upload support for seamless document processing.</p>
        <a href="https://huggingface.co/spaces/uzairabid1/resume-ai-assistant/tree/main"><button>View Project</button></a>
        <a href="https://uzairabid1-resume-ai-assistant.hf.space"><button>View Demo</button></a>
    </div>
</div>

<div class="project0">
    <div class="image-container0">
        {% include figure.liquid loading="eager" path="assets/img/4.jpg" %}
    </div>
    <div class="project-details0">
        <div class="heading">
        <h3>PDF Q&A Bot with Multi-LLMs</h3>
        <span class="timeline">2025</span>
        </div>
        <p>Developed an intelligent document analysis system using multiple open-source language models (Phi-3.5, Qwen 2.5, Llama 3.2, Gemma 2) from Hugging Face. Features 4-bit quantization for memory efficiency, automatic CPU offload, and a user-friendly interface for uploading PDFs and asking context-aware questions.</p>
        <a href="https://huggingface.co/spaces/uzairabid1/pdf-qa-with-multi-models/tree/main"><button>View Project</button></a>
        <a href="https://www.youtube.com/watch?v=nJNzuTuhM7I"><button>View Demo</button></a>
    </div>
</div>

<div class="project0">
    <div class="image-container0">
        {% include figure.liquid loading="eager" path="assets/img/5.jpg" %}
    </div>
    <div class="project-details0">
        <div class="heading">
        <h3>AI Tutor - Adaptive Learning Assistant</h3>
        <span class="timeline">2025</span>
        </div>
        <p>Built an intelligent tutoring system using OpenAI GPT-4o-mini that adapts explanations to different complexity levels (1-6). Features real-time streaming responses and dynamic level adjustment for the explanations, making learning accessible for students at any level.</p>
        <a href="https://huggingface.co/spaces/uzairabid1/ai-tutor-adaptive-learning-assistant/tree/main"><button>View Project</button></a>
        <a href="https://uzairabid1-ai-tutor-adaptive-learning-assistant.hf.space"><button>View Demo</button></a>
    </div>
</div>

<div class="project0">
    <div class="image-container0">
        {% include figure.liquid loading="eager" path="assets/img/6.jpg" %}
    </div>
    <div class="project-details0">
        <div class="heading">
        <h3>AI Calorie Tracker</h3>
        <span class="timeline">2025</span>
        </div>
        <p>Developed an intelligent food analysis application using OpenAI Vision API and Gradio. The system automatically identifies food items from uploaded images and provides detailed nutritional information, including calories, fat, and protein content. Perfect for health-conscious individuals and fitness enthusiasts.</p>
        <a href="https://huggingface.co/spaces/uzairabid1/calorie-tracker/tree/main"><button>View Project</button></a>
        <a href="https://uzairabid1-calorie-tracker.hf.space"><button>View Demo</button></a>
    </div>
</div>

<div class="project0">
    <div class="image-container0">
        {% include figure.liquid loading="eager" path="assets/img/7.jpg" %}
    </div>
    <div class="project-details0">
        <div class="heading">
        <h3>BlogPilot AI - WordPress Automation using CrewAI Agents</h3>
        <span class="timeline">2025</span>
        </div>
        <p>Developed an intelligent multi-agent content creation system using CrewAI that automates the entire blog writing workflow. Features four specialized AI agents for research, outlining, writing, and publishing, with seamless WordPress integration via REST API for automated content publishing.</p>
        <a href="https://github.com/uzairabid1/wordpress-content-generator-and-publisher-crewai"><button>View Project</button></a>
        <a href="https://www.youtube.com/watch?v=V-6mANoHE7M"><button>View Demo</button></a>
    </div>
</div>

## Data Science & Analytics Projects

<div class="project0">
    <div class="image-container0">
        {% include figure.liquid loading="eager" path="assets/img/8.jpg" %}
    </div>
    <div class="project-details0">
        <div class="heading">
        <h3>Analysis of Media Posts</h3>
        <span class="timeline">2023</span>
        </div>
        <p>Designed an NLP pipeline using scikit-learn to classify and analyze mental health related social media posts. The model identifies posts related to stress, anxiety, or depression, providing insight into online mental health discourse and supporting mental health awareness initiatives.</p>
        <a href="https://github.com/uzairabid1/categorize-posts-from-social-media"><button>View Project</button></a>
    </div>
</div>

<div class="project0">
    <div class="image-container0">
        {% include figure.liquid loading="eager" path="assets/img/9.jpg" %}
    </div>
    <div class="project-details0">
        <div class="heading">
        <h3>Flight Delay Prediction</h3>
        <span class="timeline">2025</span>
        </div>
        <p>Developed a machine learning model using XGBoost to forecast flight delays based on historical flight and weather data. Achieved improved prediction accuracy by performing extensive feature engineering and hyperparameter tuning, helping travelers make informed decisions.</p>
        <a href="https://github.com/uzairabid1/predict-flight-delay-xgboost"><button>View Project</button></a>
    </div>
</div>

<div class="project0">
    <div class="image-container0">
        {% include figure.liquid loading="eager" path="assets/img/10.jpg" %}
    </div>
    <div class="project-details0">
        <div class="heading">
        <h3>Basketball Shot Predictor</h3>
        <span class="timeline">2023</span>
        </div>
        <p>Created a statistical model using linear regression to predict shot success based on player movement, court position, and historical performance data. Demonstrated data preprocessing, visualization, and sports analytics techniques for basketball performance analysis.</p>
        <a href="https://github.com/uzairabid1/predict-basketball-shot"><button>View Project</button></a>
    </div>
</div>
---


