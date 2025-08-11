---
hide:
  - navigation
---

# CS492(C): Diffusion and Flow Models

<h3><b>
<a href="http://mhsung.github.io/" target="_blank">Minhyuk Sung</a>, <a href="https://www.kaist.ac.kr/" target="_blank">KAIST</a>, Fall 2025
</b></h3>
<br />

![Teaser](assets/teaser.png){ width=97.5% }


## Time & Location
**Time**: Mon/Wed 10:30 a.m. - 11:45 a.m. (KST)   
**Location**: E3-5 Rm 210.

<!-- [Zoom Link](https://kaist.zoom.us/j/83695846631){:target="_blank" .md-button} -->


## Description
Recent breakthroughs in generative AI have amazed people with the unprecedented quality of generated images and videos, as exemplified by SORA, Midjourney, StableDiffusion, and many others. These advancements have been achieved using diffusion models, which have become the new standard technique for generative models. Diffusion models offer numerous advantages, including superior performance in the quality of generated outputs, as well as capabilities in conditional generation, personalization, zero-shot manipulation, and knowledge distillation.

In this course, we will discuss the theoretical foundations and practical applications of diffusion models. While the goal is to cover both theory and practice, the focus will be on gaining hands-on experience by implementing diffusion model techniques in programming assignments and solving real-world problems in the course project. There will be no midterm or final exams.


## Prerequisites
This course is designed for students with a fundamental understanding of deep learning and experience using PyTorch.


## Course Staff
**Instructor**: [Minhyuk Sung](https://mhsung.github.io/){:target="_blank"} ([mhsung@kaist.ac.kr](mailto:mhsung@kaist.ac.kr))

**Course Assistants:**

- Yuseung Lee ([phillip0701@kaist.ac.kr](mailto:phillip0701@kaist.ac.kr))
- Seungwoo Yoo ([dreamy1534@kaist.ac.kr](mailto:dreamy1534@kaist.ac.kr))
- Juil Koo ([63days@kaist.ac.kr](mailto:63days@kaist.ac.kr))
- Yunhong Min ([dbsghd363@kaist.ac.kr](mailto:dbsghd363@kaist.ac.kr))


## Past Years
- [CS492(D): Diffusion Models and Their Applications](https://mhsung.github.io/kaist-cs492d-fall-2024/){:target="_blank"}


## Grading
- Programming Assignments: 45%
- Project: 45%
- In-Class Participation: 10%

<!--
## Paper List

[Paper List](https://docs.google.com/spreadsheets/d/1j7amDru9bRQsQgp2pfm1a8GrZ6K0HWwCDORGq-sj7dQ/edit?usp=sharing){:target="_blank" .md-button}
-->


## Useful Resources
- [SIGGRAPH 2024 Course: Diffusion Models for Visual Content Generation](https://geometry.cs.ucl.ac.uk/courses/diffusion4ContentCreation_sigg24/){:target="_blank"}
- [CVPR 2023 Tutorial: Denoising Diffusion Models: A Generative Learning Big Bang](https://cvpr2023-tutorial-diffusion-models.github.io/){:target="_blank"}
- ["Generative Modeling by Estimating Gradients of the Data Distribution", Yang Song.](https://yang-song.net/blog/2021/score/){:target="_blank"}
- ["What are Diffusion Models?", Lilian Weng.](https://lilianweng.github.io/posts/2021-07-11-diffusion-models/){:target="_blank"}
- ["Understanding Diffusion Models: A Unified Perspective". Calvin Luo.](https://arxiv.org/abs/2208.11970){:target="_blank"}
- ["Tutorial on Diffusion Models for Imaging and Vision". Stanley H. Chan.](https://arxiv.org/abs/2403.18103){:target="_blank"}
- ["Step-by-Step Diffusion: An Elementary Tutorial". Preetum Nakkiran, Arwen Bradley, Hattie Zhou, and Madhu Advani.](https://arxiv.org/abs/2406.08929){:target="_blank"}

<!--
## Important Dates
ALL ASSIGNMENTS ARE DUE 23:59 KST.  

(Subject to Change)  

- 1st Programming Assignment: ==Due Sep 29 (Sun)==  
- 2nd Programming Assignment: ==Due Oct 9 (Wed)==  
- 3rd Programming Assignment: ==Due Oct 21 (Mon)==  
- 4th Programming Assignment: ==Due Nov 5 (Tue)==  
- 5th Programming Assignment: ==Due Nov 18 (Mon)==  
- 6th Programming Assignment: ==Due Dec 6 (Fri)==  
- 7th Programming Assignment: ==Due Dec 13 (Fri)==  
- Project Proposal: ==Due Oct 19 (Sat)==  
- Project Interim Report: ==Due Nov 9 (Sat)==  
- Project Early Reporting Due: ==Due Nov 22 (Fri)==  
- Project Submission: ==Due Nov 30 (Sat)==  


## Schedule
(Subject to Change) 

| Week | Mon | Topic | Wed | Topic |
| :----: | :----: | :----: | :----: | :----: |
| 1  | Sep 02 | __Course Introduction__<br>[**Slides**]({{links.lec01}}){:target="_blank"} | Sep 04 | __Introduction to Generative Models /__<br>__GAN / VAE__<br>[**Slides**]({{links.lec02}}){:target="_blank"}<br>[**Recording**]({{links.rec02}}){:target="_blank"} |
| 2  | Sep 09 | __DDPM 1__<br>[**Slides**]({{links.lec03}}){:target="_blank"}<br>[**Recording**]({{links.rec03}}){:target="_blank"} | Sep 11 | __DDPM 2__<br>[**Slides**]({{links.lec04}}){:target="_blank"}<br>[**Recording**]({{links.rec04}}){:target="_blank"}<br>==[Assignment 1 Session](https://github.com/KAIST-Visual-AI-Group/Diffusion-Assignment1-DDPM){:target="_blank"}==<br>[**Slides**]({{links.asgmt01}}){:target="_blank"} |
| 3  | Sep 16 | No Class (Chuseok)                      | Sep 18 | No Class (Chuseok) |
| 4  | Sep 23 | __DDIM 1__<br>[**Slides**]({{links.lec05}}){:target="_blank"}<br>[**Recording**]({{links.rec05}}){:target="_blank"} | Sep 25 |  __DDIM 2 / CFG__<br>[**Slides**]({{links.lec06}}){:target="_blank"}<br>[**Recording**]({{links.rec06}}){:target="_blank"}<br>==[Assignment 2 Session](https://github.com/KAIST-Visual-AI-Group/Diffusion-Assignment2-DDIM-CFG){:target="_blank"}==<br>[**Slides**]({{links.asgmt02}}){:target="_blank"} |
| 5  | Sep 30 | __CFG / Latent Diffusion /__<br>__ControlNet / LoRA__<br>[**Slides**]({{links.lec07}}){:target="_blank"}<br>[**Recording**]({{links.rec07}}){:target="_blank"} | Oct 02 | No Class (Substitution of Hangul Day) | 
| 6  | Oct 07 | __Zero-Shot Applications__<br>[**Slides**]({{links.lec08}}){:target="_blank"}<br>[**Recording**]({{links.rec08}}){:target="_blank"}<br>==[Assignment 3 Session](https://github.com/KAIST-Visual-AI-Group/Diffusion-Assignment3-ControlNet-LoRA){:target="_blank"}==<br>[**Slides**]({{links.asgmt03}}){:target="_blank"} | ~~Oct 09~~<br>Oct 10 (Thu)<br>4:00pm KST | __Guest Lecture 1__<br>**[Or Patashnik](./guest-lecture-or-patashnik){:target="_blank"}**<br>Ph.D. Student at Tel-Aviv University<br>[**Recording**]({{links.guest_rec1}}){:target="_blank"}  |
| 7  | Oct 14 | __DDIM Inversion / Score Distillation 1__<br>[**Slides**]({{links.lec09}}){:target="_blank"}<br>[**Recording**]({{links.rec09}}){:target="_blank"} | Oct 16 | __Score Distillation 2__<br>[**Slides**]({{links.lec10}}){:target="_blank"}<br>[**Recording**]({{links.rec10}}){:target="_blank"}<br>==[Assignment 4 Session](https://github.com/KAIST-Visual-AI-Group/Diffusion-Assignment4-Distillation){:target="_blank"}==<br>[**Slides**]({{links.asgmt04}}){:target="_blank"} |
| 8  | Oct 21 | No Class (Midterm Week)                         | Oct 23 | No Class (Midterm Week) |
| 9  | Oct 28 | __Diffusion Synchronization__<br>[**Slides**]({{links.lec11}}){:target="_blank"}<br>[**Recording**]({{links.rec11}}){:target="_blank"} | Oct 30 | ==[Assignment 5 Session](https://github.com/KAIST-Visual-AI-Group/Diffusion-Assignment5-Synchronization){:target="_blank"}==<br>[**Slides**]({{links.asgmt05}}){:target="_blank"} |
| 10 | Nov 04 | __Inverse Problems 1__<br>[**Slides**]({{links.lec12}}){:target="_blank"}<br>[**Recording**]({{links.rec12}}){:target="_blank"} | Nov 06 | __Inverse Problems 2__<br>[**Slides**]({{links.lec13}}){:target="_blank"}<br>[**Recording**]({{links.rec13}}){:target="_blank"}<br>Project Orientation Session |
| 11 | Nov 11 | __Probability Flow ODE / DPM-Solver__<br>[**Slides**]({{links.lec14}}){:target="_blank"}<br>[**Recording**]({{links.rec14}}){:target="_blank"} | Nov 13 | ==[Assignment 6 Session](https://github.com/KAIST-Visual-AI-Group/Diffusion-Assignment6-DPMSolver){:target="_blank"}==<br>[**Slides**]({{links.asgmt06}}){:target="_blank"} |
| 12 | Nov 18 | __Flow Matching 1__<br>[**Slides**]({{links.lec15}}){:target="_blank"}<br>[**Recording**]({{links.rec15}}){:target="_blank"}       | Nov 20 | __Flow Matching 2__<br>[**Slides**]({{links.lec16}}){:target="_blank"}<br>[**Recording**]({{links.rec16}}){:target="_blank"}<br>==[Assignment 7 Session](https://github.com/KAIST-Visual-AI-Group/Diffusion-Assignment7-Flow){:target="_blank"}==<br>[**Slides**]({{links.asgmt07}}){:target="_blank"} |
| 13 | Nov 25 | __Course Summary__<br>[**Slides**]({{links.lec17}}){:target="_blank"}<br>[**Recording**]({{links.rec17}}){:target="_blank"} | Nov 27 | __Guest Lecture 2__<br>**[Jiaming Song](./guest-lecture-jiaming-song){:target="_blank"}**<br>Chief Scientist at Luma AI |
| 14 | Dec 02 | Project Presentations 1                   | Dec 04 | Project Presentations 2 |
| 15 | Dec 09 | No Class (Conference Trip)                      | Dec 11 | No Class (Conference Trip) |
| 16 | Dev 16 | No Class (Final Week)                           | Dec 18 | No Class (Final Week) |
-->


## AI Coding Assistant Tool Policy
**You are allowed (and even encouraged) to utilize AI coding assistant tools**, such as ChatGPT, Copilot, Codex, and Code Intelligence, for your programming assignments and projects. Utilizing AI coding assistant tools will not be deemed as plagiarism. However, it is still **strictly prohibited to directly copy code from the Internet or from someone else**. Doing so will lead to a score of zero and a report to the university.

<br />
