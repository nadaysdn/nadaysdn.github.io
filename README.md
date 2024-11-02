---
layout: page
title: About
permalink: /
---
<div style="display: flex; align-items: center;">
    <img src="{{ '/asset/images/profile_pic1.jpg' | relative_url }}" alt="Profile Picture" style="width:150px; height:auto; border-radius: 50%;">
    <p class="animated-text" style="font-size: 36px; color: #000080; font-weight: bold; margin-left: 15px;">
        Hello! I am Nada 👋
      </p>
</div>

<style>
.animated-text span {
    display: inline-block; /* Keep spans inline */
    transform: translateY(20px); /* Start position slightly down */
    opacity: 0; /* Start invisible */
    animation: slideIn 0.5s forwards; /* Animation for each letter */
}

/* Animation with a delay based on the index */
@keyframes slideIn {
    0% {
        transform: translateY(20px); /* Start position */
        opacity: 0; /* Start invisible */
    }
    100% {
        transform: translateY(0); /* End position */
        opacity: 1; /* Fully visible */
    }
}

/* Adding delay to each letter's animation */
.animated-text span:nth-child(1) { animation-delay: 0s; }
.animated-text span:nth-child(2) { animation-delay: 0.1s; }
.animated-text span:nth-child(3) { animation-delay: 0.2s; }
.animated-text span:nth-child(4) { animation-delay: 0.3s; }
.animated-text span:nth-child(5) { animation-delay: 0.4s; }
.animated-text span:nth-child(6) { animation-delay: 0.5s; }
.animated-text span:nth-child(7) { animation-delay: 0.6s; }
.animated-text span:nth-child(8) { animation-delay: 0.7s; }
.animated-text span:nth-child(9) { animation-delay: 0.8s; }
.animated-text span:nth-child(10) { animation-delay: 0.9s; }
.animated-text span:nth-child(11) { animation-delay: 1.0s; }
.animated-text span:nth-child(12) { animation-delay: 1.1s; }
.animated-text span:nth-child(13) { animation-delay: 1.2s; }
.animated-text span:nth-child(14) { animation-delay: 1.3s; }
.animated-text span:nth-child(15) { animation-delay: 1.4s; }
.animated-text span:nth-child(16) { animation-delay: 1.5s; }
</style>

<br>I am a detail-focused Data Analyst with over 3 years of experience, specializing in data warehousing, process validation, and business needs analysis. I have a proven track record of understanding customer requirements and translating them into actionable insights and strategic project plans. My passion for Big Data, along with a commitment to delivering impactful results, drives my dedication to optimizing business processes and enabling data-driven decision-making.
<br>Feel free to check out my projects and let's connect!
