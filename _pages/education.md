---
layout: page
permalink: /education/
title: Education
nav: true
nav_order: 3
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

## Academic Background

<div class="project0">
    <div class="image-container0">
        {% include figure.liquid loading="eager" path="assets/img/ssuet.png" title="Sir Syed University of Engineering & Technology" %}
    </div>
    <div class="project-details0">
        <div class="heading">
        <h3><a href="https://www.ssuet.edu.pk/">Sir Syed University of Engineering & Technology</a></h3>
        <span class="timeline">2020 - 2024</span>
        </div>
        <p><strong>Bachelor's of Science in Computer Engineering</strong></p>
        <p><strong>Key Achievements:</strong></p>
        <ul>
            <li>Ranked in the top 10% of the batch and 1st in the section.</li>
            <li>Graduated with a CGPA of 3.58 out of 4.0.</li>
            <li>Led the Final Year Project as the Group Leader and got awarded with Ignite's funding for our FYP.</li>
            <li>Volunteered and mentored in different University's societies.</li>
        </ul>
    </div>
</div>

<div class="project0">
    <div class="image-container0">
        {% include figure.liquid loading="eager" path="assets/img/gdgc.jpg" title="Govt. Degree Science and Commerce College" %}
    </div>
    <div class="project-details0">
        <div class="heading">
        <h3><a href="https://www.facebook.com/GovtDegreeCollegeGulshanEIqbalBlock7/">Govt. Degree Science and Commerce College</a></h3>
        <span class="timeline">2017 - 2019</span>
        </div>
        <p><strong>Higher Secondary School Certificate (H.S.S.C), Pre-Engineering</strong></p>
        <p>Completed intermediate education with focus on mathematics, physics, and chemistry, building a strong foundation for engineering studies.</p>
    </div>
</div>

<div class="project0">
    <div class="image-container0">
        {% include figure.liquid loading="eager" path="assets/img/sps.jpg" title="Shaheen Public School" %}
    </div>
    <div class="project-details0">
        <div class="heading">
        <h3><a href="https://shaheenpsc.com/">Shaheen Public School</a></h3>
        <span class="timeline">2015 - 2017</span>
        </div>
        <p><strong>Secondary School Certificate (S.S.C), Computer Science</strong></p>
        <p>Completed secondary education with specialization in Computer Science, laying the groundwork for future technical studies and career in software engineering.</p>
    </div>
</div>
