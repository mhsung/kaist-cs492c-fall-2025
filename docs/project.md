---
hide:
  - navigation
---

# CS492(D): Diffusion Models and Their Applications

<h3><b>
<a href="http://mhsung.github.io/" target="_blank">Minhyuk Sung</a>, <a href="https://www.kaist.ac.kr/" target="_blank">KAIST</a>, Fall 2024
</b></h3>


## Project

^^Project Proposal Due^^: ==Due Oct 19 (Sat)==  
^^Project Interim Report Due^^: ==Due Nov 9 (Sat)==  
^^Project Early Reporting Due^^: ==Due Nov 22 (Fri)==  
^^Project Submission Due^^: ==Due Nov 30 (Sat)==  
^^Where to submit^^: Gradescope


**The course project is to create your own diffusion model using one of the provided datasets and benchmark setups.** Below are the project topics.


### Project Topics
1. **Modeling the Distribution of Natural Disasters**:<br>[https://github.com/KAIST-Visual-AI-Group/Diffusion-Project-Natural-Disasters](https://github.com/KAIST-Visual-AI-Group/Diffusion-Project-Natural-Disasters){:target="_blank"}
2. **Sketch Stroke Generation**:<br>[https://github.com/KAIST-Visual-AI-Group/Diffusion-Project-Drawing](https://github.com/KAIST-Visual-AI-Group/Diffusion-Project-Drawing){:target="_blank"}
3. **Lighting-Conditioned Image Translation**:<br>[https://github.com/KAIST-Visual-AI-Group/Diffusion-Project-Illumination](https://github.com/KAIST-Visual-AI-Group/Diffusion-Project-Illumination){:target="_blank"}
4. **3D Volume Generation**:<br>[https://github.com/KAIST-Visual-AI-Group/Diffusion-Project-3DVolume](https://github.com/KAIST-Visual-AI-Group/Diffusion-Project-3DVolume){:target="_blank"}


You’ll need to form a team with your classmates to work on the project throughout the semester, and each team must select one of the project topics listed above.


### Project Team Matching
You are allowed to form a team with a **maximum of three people**. All teams will be assessed in the same way, regardless of how many people are in the team. It is hence recommended to have three people in the team. All members of a project team will receive the same grade for the project, unless under extraordinary circumstances.


### Project Proposal
Submit a project proposal for each **team**, including the following information **within three A4 pages** (no template provided):

- Names and student IDs of all team members
- Dataset/Benchmark title
- Basic ideas for the diffusion model implementation
- Timeline for implementation
- Plans for task allocation to team members


### Project Interim Report
Based on the timeline in the proposal, submit a write-up of **up to three pages** for each **team**, **color-coding** each item in the timeline as follows:

- <mark style="background-color: #00FF00">Completed</mark>  
- <mark style="background-color: #FFFF00">In progress (as scheduled)</mark>  
- <mark style="background-color: #C0C0C0">Delayed</mark> - Briefly explain why.
- <mark style="background-color: #FF5C5C">Have issues</mark> - Briefly explain the issues. 

For the cases marked as <mark style="background-color: #C0C0C0">Delayed</mark> or <mark style="background-color: #FF5C5C">Have issues</mark>, provide a brief explanation of the problems and propose solutions.

Keep it concise; avoid creating a lengthy write-up.


### Project Early Reporting
- **Submit Your Quantitative Results Early!** (See the deadline above.) Teams with the best quantitative results will receive up to 5% bonus credit for the project (which can change your grade!)

- You do not need to submit your code or pretrained models for the early reporting. However, your results in the final submission must be equal to or better than those submitted during the early reporting. Otherwise, the bonus credits you received will be canceled.

- The submitted results will be shared with other teams (without team identification) to be used as a baseline for reference.


### Project Submission

Submit the followings for each **team** (maximum 100MB in total):

- Poster
- Report
- Source code and trained models


### Poster Guidelines

- A **single PNG** file (maximum 10MB).
- Must be in **2560x1280** resolution.
- Poster template: [<b>Link</b>](https://onedrive.live.com/edit?id=60562023B6640282!33908&resid=60562023B6640282!33908&ithint=file%2cpptx&authkey=!ALOOMsedTCkU4Es&wdo=2&cid=60562023b6640282){:target="_blank"}<br>
Do not need to use this template.
- The poster must include the following:
    - **Project title**: It is the project title of your own team, not the project topic.
    - **Project topic**: It is one of the four items in the list [above](#project-topics).
    - **Team ID**
    - **All team member names**
    - **Problem definition**: Input (at test time), desired output, training data, assumptions, etc.
    - **Key ideas**: Key ideas of your approach.
    - **Method**: Details of your approach.
    - **Qualitative results**: Visualization of the generated data. All qualitative results must be based on your own work. **Borrowing images from other sources will be considered plagiarism and will result in a score of zero.**
    - **Quantitative results**: Benchmark results.
    - **References**:
        - For any papers you cited.
        - For any images from other sources used in the poster.
        - For any data or code borrowed from other sources.
    - **Acknowledgments**: Describe the role of each team member. If anyone outside the team contributed to the project, list their names and the details of their support.

- Resources: [<b>How to Make a More Effiective Research Poster (Zoya Bylinskii)</b>](https://web.mit.edu/zoya/www/posterRecommendations.pdf){:target="_blank"}


### Report Guidelines

- A single PDF file (maximum 10MB) within four pages.
- No specific template is required, but the following template is recommended (abstract is not needed): [<b>Link</b>](https://www.overleaf.com/latex/templates/template-for-iclr-2021-conference-submission/mmpfhsxmqdkp){:target="_blank"}
- The report must include the following:
    - **Project title**: It is the project title of your own team, not the project topic.
    - **Project topic**: It is one of the four items in the list [above](#project-topics).
    - **Team ID**
    - **All team member names and student IDs**
    - **Method**: Provide all the details about your approach: Describe the main algorithm but not the code. While using existing ideas is allowed, the source of these ideas (e.g., paper, blog, GitHub repo) must be properly cited.
    - **Implementation details**: Include comprehensive information on aspects such as neural network architecture, hyperparameters, data augmentation, and pre-processing and post-processing techniques.
    - **Reproduction Instructions**: Provide detailed instructions on how to reproduce the trained model(s) and the generation results using the provided code and dataset. Ensure that someone else can replicate the trained model(s) based on your description.
    - **References**:
        - For any papers you cited.
        - For any images from other sources used in the report.
        - For any data or code borrowed from other sources.
    - **Acknowledgments**: Describe the role of each team member. If anyone outside the team contributed to the project, list their names and the details of their support.


### Evaluation
Projects will be evaluated based on the following four criteria, each of which is scored on a scale from 1 to 5:

- **Quantitative Results [1-5]**
    - Results should be based on the evaluation metrics provided in each benchmark.
    - You must provide quantitative results for **all** evaluation metrics. Missing results for any metric will result in the lowest score.
    - Failing to reproduce the results will lead to a score of zero for the entire project (not just for the quantitative results).
- **Qualitative Results [1-5]**
    - Showcase qualitative results as comprehensively as possible.
    - Demonstrating not only good results but also a sufficient quantity of them will help convince others of the quality of your work.
- **Creativity [1-5]**
    - While it is acceptable to use existing ideas (provided you properly cite the source, e.g., paper, blog, GitHub repo), the creativity of your approach will be assessed.
- **Presentation [1-5]**
    - Your project will be presented at the poster session during the first week of December, and the quality of the presentation will be evaluated.

For the last three factors (Qualitative Results, Creativity, and Presentation), **your classmates will also participate in the evaluation**, alongside the instructor and TAs. For Quantitative Results, however, the instructor and TAs will evaluate based on the results without peer reviews.


### ^^[IMPORTANT] What is Allowed and What is Not Allowed (Please Read Carefully)^^
The followings are allowed:

- Using existing ideas and code, provided that you properly cite these sources (e.g., paper, blog, GitHub repo) in your poster, report, and code.
- Using existing pretrained models or additional data to train other neural networks or diffusion models **ONLY** for data preprocessing and showcasing additional applications, but not for training the resulting diffusion model.

^^Violating any of the following will result in zero score for the project^^:

- **Late submission or failure to submit**: Late submissions are not permitted under any circumstances. It is strongly recommended to submit early and revise if needed.
- **Incomplete submission**: Missing any of the required components (poster, report, or code/trained models) will be considered as incomplete submission.
- **Using test data in training or as results (not as reference) in evaluation**: Using test data for any purpose other than as a reference in evaluation (e.g., using it in training, displaying it as qualitative results, or using it in quantitative results) will be considered serious misconduct, even if done accidentally. Please be careful.
- **Using existing pretrained models or additional data for training the diffusion model**, except for the specific version of Stable Diffusion used in the Lighting-Conditioned Image Translation project (the specific version is described in the GitHub repository). However, it is still permitted to use existing pretrained models/additional data and train other neural networks or diffusion models for data preprocessing and to showcase additional applications.
- **Failure to reproduce trained models and quantitative/qualitative results**: All trained models and generation results (both quantitative and qualitative) must be reproducible using the provided code and trained models. Detailed instructions for reproduction must be included in the report. Failure to reproduce the results will result in a score of zero for the project. (Small differences in outputs due to randomness in the code are acceptable.)
- **Missing citations**: Failing to cite any existing ideas or code used in your methods will be considered plagiarism.
- **Zero contribution to the project**: While all teammates will generally receive the same score, if it is confirmed that a teammate contributed nothing to the project, that teammate will receive zero score.


**Violating any of the following will result in a penalty**:

- **Missing any quantitative metric results**: You must report the results for all quantitative evaluation metrics. Failing to include any of them in the poster will result in a score of zero for the quantitative evaluation.

- **Missing any items/information in the poster/report**: Ensure that all information listed in the poster and report guidelines is included. Missing any required items will result in a penalty (the amount of which will be determined by the instructor and/or TAs).

- **Absence from the poster session**: All students are required to attend both poster sessions in their entirety. Any absence during the session will result in a penalty of at least 20% of the project score for each instance of absence.

- **No submission of peer evaluation**: All students are required to submit peer evaluation results for all other projects. Failure to submit on time will result in a penalty of at least 20% of the project score for each poster session.

^^The instructor and TAs may impose penalties for any misconduct not explicitly listed above. If you are unsure whether your actions may result in a penalty, please contact the instructor for clarification.^^


<br />
