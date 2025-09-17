---
layout: page
permalink: /teaching/
title: Teaching
nav: true
nav_order: 6
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

## Teaching Experience

<div class="project0">
    <div class="image-container0">
        {% include figure.liquid loading="eager" path="assets/img/stanford_code_in_place_logo.jpg" title="Stanford Code in Place" %}
    </div>
    <div class="project-details0">
        <div class="heading">
        <h3><a href="https://codeinplace.stanford.edu/">Stanford's Code in Place</a></h3>
        <span class="timeline">2025</span>
        </div>
        <p><strong>Section Leader</strong></p>
        <p>Taught basic Python to 10+ students from all over the world and guided them through Stanford's CS106A course. Provided personalized mentorship and helped students master fundamental programming concepts.</p>
        <p><strong>Completion Certificate:</strong> <a href="https://digitalcredential.stanford.edu/check/A5098045EE9F09EBDAA4B47A56F97A5C5F878EF3DF543AFEFC0A6100CB44901AaE5uQmlGYmFEUkRPTmRZV2Z2UXAyVFJxWEFwYk1UL0F6ZnhhT1RucWc3NTRoRm54"><button>View Certificate</button></a></p>
    </div>
</div>

<div class="project0">
    <div class="image-container0">
        {% include figure.liquid loading="eager" path="assets/img/icodeguru.jpg" title="icodeguru" %}
    </div>
    <div class="project-details0">
        <div class="heading">
        <h3><a href="https://icode.guru/">ICodeGuru</a></h3>
        <span class="timeline">April 2025 - Present</span>
        </div>
        <p><strong>Trainer & Moderator</strong></p>
        <p>At ICodeGuru, we teach, train, mentor, and guide students from underprivileged areas of Pakistan to improve their professional skills. I taught coding to these students and helped them solve LeetCode problems, focusing on algorithmic thinking and problem-solving techniques.</p>
        <p>Checkout some of my live classes:</p>
        <a href="https://www.facebook.com/iCodeguru/videos/827891879496385"><button>Langchain Workshop</button></a>
    </div>
</div>

## Community Impact

Through my teaching roles, I have:
- **Mentored 50+ students** across different platforms and programs
- **Conducted workshops** on Python programming, algorithms, and AI/ML concepts
- **Bridged the digital divide** by providing quality tech education to underprivileged communities
- **Developed curriculum** for practical coding skills and industry-relevant technologies
- **Fostered inclusive learning** environments that encourage participation from diverse backgrounds

## Teaching Philosophy

I believe in **hands-on learning** combined with **theoretical understanding**. My approach focuses on:
- Breaking down complex concepts into digestible parts
- Encouraging practical application through projects
- Building confidence through incremental challenges
- Creating supportive learning environments
- Connecting academic concepts to real-world applications

---
