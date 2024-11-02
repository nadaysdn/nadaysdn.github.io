---
layout: page
title: About
permalink: /
---
<div style="display: flex; align-items: center;">
    <img src="{{ '/asset/images/profile_pic1.jpg' | relative_url }}" alt="Profile Picture" style="width:150px; height:auto; border-radius: 50%;">
    <p class="animated-text" style="font-size: 36px; color: #000080;">Hello! 👋
      <br> I am Nada.</p>
</div>

<style>
.animated-text {
    transform: translateX(-100%); /* Start from the left */
    opacity: 0; /* Start invisible */
    animation: slideIn 1s forwards; /* Animation name and duration */
    font-weight: bold; /* Make the text bold */
}

@keyframes slideIn {
    0% {
        transform: translateX(-100%); /* Start position */
        opacity: 0; /* Start invisible */
    }
    100% {
        transform: translateX(0); /* End position */
        opacity: 1; /* Fully visible */
    }
}
</style>

<br>I am a detail-focused Data Analyst with over 3 years of experience, specializing in data warehousing, process validation, and business needs analysis. I have a proven track record of understanding customer requirements and translating them into actionable insights and strategic project plans. My passion for Big Data, along with a commitment to delivering impactful results, drives my dedication to optimizing business processes and enabling data-driven decision-making.
<br>Feel free to check out my projects and let's connect!
