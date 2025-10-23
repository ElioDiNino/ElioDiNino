<!-- markdownlint-disable MD041 MD033 MD023 MD007 -->
<!----- Picture & Links ----->

<p id="profile-picture" align="center">
  <img width=30% src="https://github.com/user-attachments/assets/4134fac0-4d4a-44f5-9b69-77c1c21bdbe5" alt="Profile Picture">
</p>

<div id="badges" align="center">
  <a href="https://www.linkedin.com/in/eliodinino/">
    <img src="https://img.shields.io/badge/LinkedIn-22242d?logo=linkedin&logoColor=white&style=for-the-badge" alt="LinkedIn Badge">
  </a>
  <a href="https://eliodinino.com">
    <img src="https://img.shields.io/badge/Website-22242d?style=for-the-badge&logo=Google-chrome&logoColor=white" alt="Website Badge">
  </a>
  <a href="https://eliodinino.com/Resume.pdf">
    <img src="https://img.shields.io/badge/Resume-22242d?style=for-the-badge&logo=giphy&logoColor=white" alt="Resume Badge">
  </a>
  <a href="mailto:contact@eliodinino.com">
    <img src="https://img.shields.io/badge/Email-22242d?style=for-the-badge&logo=gmail&logoColor=white" alt="Email Badge">
  </a>
  <a href="https://www.instagram.com/eliodinino/">
    <img src="https://img.shields.io/badge/Instagram-22242d?logo=instagram&logoColor=white&style=for-the-badge" alt="Instagram Badge">
  </a>
</div>

<br/>

<!----- About Me ----->

<h1 align="center">About Me</h1>

I am a driven UBC Computer Engineering student passionate about building impactful software and contributing back to the community. I have an abundance of experience working in teams to solve challenges with innovative software solutions, ranging from quantum computing pipelines to autonomous aircraft systems.

<details>
  <summary>:spiral_notepad: Read More</summary>

  ### Branching Out

  In my spare time, I enjoy pursuing personal programming projects, cycling, playing soccer, flying drones, learning about new technologies, and [taking landscape photos](https://photography.eliodinino.com) - you could say I’m a full-time developer by day, and a full-time hobbyist by night. Beyond academic pursuits, I enjoy being a Teaching Assistant for aspiring computer engineers, as well as contributing to large-scale projects such as the development I led on [UBC Uncrewed Aircraft Systems](https://ubcuas.com) to [place 3rd nationally in 2024](https://www.aerialevolution.ca/annual-student-competition/).

  ### New PRs

  My commitment to learning drives me to take on projects that require gaining new skills and pursuing challenges outside my comfort zone. I believe that continuous learning and embracing new experiences are pivotal to personal growth and adaptability.

  ### Queued Actions

  I'm on a mission to build impactful technologies through scalable software, courageous innovation, and ambitious leadership while relentlessly pursuing my passion for contributing to technology to better society.

</details>

<!----- Projects ----->

<h2 align="center">What I'm Up To</h2>
<details>
  <summary>:card_file_box: Past Projects</summary>

  ### :cloud: [AWS Automation - CPEN 431](https://github.com/ElioDiNino/CPEN431-Automation)

  As part of UBC's CPEN 431, I developed deployment automation tooling using Terraform and Bash to streamline the provisioning of cloud infrastructure on AWS. The purpose of the project was to fully automate the otherwise manual deployment and testing of the distributed computing system we were building in the course.

  ### :electron: [Quantum Computing Research Replication - CPEN 400Q](https://github.com/ElioDiNino/CPEN400Q-Project)

  I worked with a team of 3 others to replicate and evaluate the results of a quantum computing research paper titled "Exploring Hybrid Quantum-Classical Methods for Practical Time-Series Forecasting". We successfully reproduced the results of the paper by implementing both quantum and classical models for time-series forecasting using PennyLane.

  ### :airplane: [UBC Uncrewed Aircraft Systems](https://ubcuas.com)

  I led as captain and also worked on the software sub-team as a lead for UBC UAS, a design team focused on designing autonomous drones and their support systems. The team repositories can be seen [here](https://github.com/ubcuas). My focus as lead was keeping projects on track and supporting the 18 software sub-team members where needed. That being said, with my past experience on the team, I got to work on a variety of microsystems. Some of my notable contributions as both a developer and as lead are as follows:

  * Improved cross-platform compatibility with Docker containers and made related CI/CD pipelines with GitHub Actions
  * [UASITL](https://github.com/ubcuas/UASITL): Overhauled our simulation pipeline by supporting new vehicle types (planes and VTOLs) and building software images for additional computer architectures (ARMv7 and ARM64)
  * Revamped the team website using a Golang framework (Hugo) to decrease load times from 10s to 0.7s
  * Integrated a new camera system into the drone and software suite for use in machine vision
  * [ACOM](https://github.com/ubcuas/acom): Running on the drone, this was our main communication method with the ground station for the software sub-team. I worked on adding support for controlling a winch system, monitoring RC connection, and keeping track of the battery usage.
  * [GCOM-X](https://github.com/ubcuas/gcom-x): Our previous ground station control software. I helped work on the frontend redesign, updated the backend API, integrated a Django server with the React frontend, and added a login page to connect to competition servers.

  ### :computer: [Personal Website](https://github.com/ElioDiNino/eliodinino.com)

  This is something I had long desired to work on. I had quite a bit of experience building websites with services such as Wix, WordPress, and Squarespace, but I didn't have much experience actually programming a website. I used React to build my site as it had applicable skills to [UAS](#️airplane-ubc-uncrewed-aircraft-systems) and was something I saw myself using in the future (although I understood it is far from the best thing to use for a static website). With the solid foundation I built, I now only make occasional tweaks to the site from time to time.

  ### :closed_lock_with_key: [3FA - Multi-Factor Authentication System](https://github.com/Computing-Collective/3FA)

  * Created a backend API in Python using Flask and SQLite with over 20 endpoints to authenticate users and serve files
  * Designed and implemented the authentication flow which included session and authentication tokens, encrypted communications, hashed passwords, and automatic timeouts to meet OWASP security standards
  * Reduced manual work by 7x with GitHub workflows to automate testing for all parts of the system, create app releases and executables, package the backend as a Docker image, and automated dependency updates
  * Used Pytest to achieve 98% line and branch coverage as well as set up Postman to improve manual testing

  ### :school: UBC Computer Engineering Projects (Year 2)

  *Code access is available upon request for all projects

  #### [Multi-Client Server](https://cpen221-ubc.notion.site/Message-Queues-Pub-Sub-with-Twitter-c5965b28ed01482aad44dbaadac19b77) - CPEN 221

  * Constructed a server supporting multiple simultaneous clients capable of interacting and fetching tweets from Twitter
  * Enabled dual-server routing so that either server can be connected to, and no interruptions occur if one goes offline
  * Followed security protocols by hashing and salting all passwords and encrypting incoming and outgoing data via AES

  #### Simple RISC Machine - CPEN 211

  * Implemented a Turing Complete 16-bit RISC machine using System Verilog on an FPGA board in 3 weeks
  * Subdivided the machine into smaller modules to be designed, tested, and debugged more easily
  * Utilized pipelining to increase operations per cycle by 300% and go beyond course expectations

  #### [Graphs, Games, and Interplanetary Travel](https://cpen221-ubc.notion.site/Graphs-Games-and-Interplanetary-Travel-79cb9a0844634b7288226639604eb0b0) - CPEN 221

  * Collaboratively built the “Kamino Game” in Java and produced the most optimal solution to win the course competition
  * Implemented graph and tree data structures with associated algorithms while optimizing time and space complexity
  * Exercised best practices including unit testing, documentation, and encapsulation to ensure quality and correctness

  ### :robot: [Quote Bot](https://github.com/ElioDiNino/Quote)

  This was a rehost of [nakayoshi](https://github.com/nakayoshi)'s Discord Quote bot which was taken offline in early 2022. In the process of rehosting it, I updated some of the bot's commands and patched several security vulnerabilities. A few weeks later, I also completed an overhaul of the bot with slash command support, improved error-handling, thread channel support, patched [vulnerabilities](https://github.com/nakayoshi/quote/issues/5), and other improvements. After the overhaul, the bot ran for free on Google Cloud without any issues. I kept the bot up to date with the latest Discord.js and dependency releases, before shutting it down 1.5 years later due to the release of Discord's native quote feature (message forwarding).

  ### :scroll: [SSC Scripts](https://github.com/ElioDiNino/SSC-Scripts)

  This repository was home to different scripts for pulling information off of [UBC's (now defunct) SSC](https://ssc.adm.ubc.ca/) and then notifying the specified emails of what new information was available. It used [UBC's Webmail](https://webmail.student.ubc.ca/) so that any user with a [CWL](https://it.ubc.ca/services/accounts-passwords/campus-wide-login-cwl) could use the scripts without having to worry about what email service they use for their primary email. An example of one of these scripts is [`grades.py`](https://github.com/ElioDiNino/SSC-Scripts/blob/main/src/grades.py), which checked for when new grades were posted. It could check for multiple course grades at a time and had many other customizable options.

  ### :robot: [Autonomous Claw](https://github.com/ElioDiNino/Autonomous-Claw)

  This is a collection of the programming work that went into the autonomous claw project for UBC's APSC 101. The goal of the project was to semi-autonomously pick up objects of different sizes and weights and transport them to a drop-off location accurately and efficiently.

  ### :abacus: [Harvard's CS50](https://github.com/ElioDiNino/CS50)

  This is a collection of the code I wrote for [Harvard's CS50](https://cs50.harvard.edu/) that I am proud of and that was of interest to me. I took part in the course during the [Spring 2021 session](https://cs50.harvard.edu/college/2021/spring/).

  ### :shield: [UBC Bot](https://github.com/ElioDiNino/UBC-Bot)

  This was my friend and I's final project for [CS50](#abacus-harvards-cs50). It is a basic Discord moderation bot that has a mix of different commands. It is quite basic, but we used it as a way to learn about Discord.js and learn the basics for future Discord bot projects.

  ### :pencil2: [Scratch](https://scratch.mit.edu/projects/426417770)

  This is the Scratch project I made as part of CS50's [Week 0 tasks](https://cs50.harvard.edu/college/2021/spring/psets/0/scratch/). It is a simple but fun game with randomized music and an infinite scrolling background.

  ### :snake: [Python Learning](https://github.com/ElioDiNino/Python-Learning)

  This is a collection of the Python code I wrote for a high school programming class where we followed the lessons and tasks from [Program Arcade Games](http://programarcadegames.com/). At the end, I also did a final project exploring machine learning using the [Titanic dataset](https://www.kaggle.com/c/titanic).

  ### :joystick: [OpenProcessing](https://openprocessing.org/user/143581)

  This is a site I used as part of one of my high school programming classes. It uses [p5js](https://p5js.org/) and I used it to make a couple of different games and get experience with object-oriented programming and other common programming principles.

  ---

</details>

<details open>
  <summary>:card_index_dividers: Current Projects</summary>

  ### :globe_with_meridians: [Homelab](https://github.com/ElioDiNino/Homelab)

  I run a homelab to self-host a variety of services and manage smart home automation. My setup is centered around a custom-built NAS running Proxmox, which virtualizes key components: Docker for containerized services, Home Assistant OS for home automation, and HexOS (TrueNAS Scale) for storage management. Secure access is managed through Tailscale (a mesh VPN), with Cloudflare Tunnels used to selectively expose public services. The system also includes an ODROID N2+ that functions as a staging environment for testing new services prior to production deployment. Check out [the repository](https://github.com/ElioDiNino/Homelab) for more details.
</details>
