<!----- Picture & Links ----->

<p id="profile-picture" align="center">
  <img width=30% src="https://github.com/ElioDiNino/ElioDiNino/blob/main/profile.png" alt="Profile Picture">
</p>

![Intro Line](https://github.com/ElioDiNino/ElioDiNino/blob/master/intro.gif)

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

I am a driven UBC Computer Engineering student passionate about software development and technology. I have an abundance of experience working in teams to solve challenges with innovative software solutions, ranging from quantum computing pipelines to autonomous aircraft systems.

<details>
  <summary>:spiral_notepad: Read More</summary>
  
  <br/>
  
  In my free time, I enjoy pursuing personal programming projects, cycling, playing soccer, flying drones, learning about new technologies, and [taking landscape photos](https://photography.eliodinino.com). Within the university, I contribute as a Teaching Assistant and lead a team of 70 students on [UBC Uncrewed Aircraft Systems](https://ubcuas.com).

  My commitment to learning drives me to take on projects that require gaining new skills and pursuing challenges outside my comfort zone. I believe that continuous learning and embracing new experiences are pivotal to personal growth and adaptability.
  
  ## :dart: Professional Goal
  I'm on a mission to build impactful technologies through scalable software, courageous innovation, and ambitious leadership while relentlessly pursuing my passion for contributing to technology to better society.
  
</details>

<!----- Projects ----->

<h2 align="center">What I'm Up To</h2>
<details>
  <summary>:card_file_box: Past Projects</summary>

  ### :computer: [Personal Website](https://github.com/ElioDiNino/eliodinino.com)
  This is something I had long desired to work on. I have quite a bit of experience building websites with services such as Wix, WordPress, and Squarespace, but I didn't have much experience with actually programming a website. I used React to build my site as it has applicable skills to UAS and is something I could see myself using in the future (although I understand it is far from the best thing to use for a static website). I am happy with my current implementation but I am looking to improve it going forward.

  ### :ocean: [D-Wave Quantum](https://dwavequantum.com/)
  I worked as a DevOps Co-op to improve existing systems and introduce new technologies. Although none of the code or systems I have developed are public, here is a summary of my biggest accomplishments:
  - Implemented a new Kubernetes-based development platform utilizing Terraform to automate setup and define infrastructure as code, simplifying programming environments for over 80 individuals and boosting efficiency by 20%
  - Overhauled the build and publication process of company Docker images by creating a Jenkins function that runs builds in the on-premises Kubernetes cluster, reducing work required by 95% and eliminating previous cloud costs
  - Centralized company Docker images in a single repository that automated all build, testing, and publishing steps with only 6 lines of configuration per image, eliminating redundant Jenkins pipelines and improving overall organization
  - Developed Grafana dashboards integrated with Prometheus metrics, enabling real-time monitoring of service health and key statistics, resulting in improved visibility and informed decision-making
  - Pioneered a Terraform provider template in Golang which allowed multiple internal providers to be created and automatically deployed to Artifactory for general use

  ### :closed_lock_with_key: [3FA - Multi-Factor Authentication System](https://github.com/Computing-Collective/3FA)
  - Created a backend API in Python using Flask and SQLite with over 20 endpoints to authenticate users and serve files
  - Designed and implemented the authentication flow which included session and authentication tokens, encrypted communications, hashed passwords, and automatic timeouts to meet OWASP security standards
  - Reduced manual work by 7x with GitHub workflows to automate testing for all parts of the system, create app releases and executables, package the backend as a Docker image, and automated dependency updates
  - Used Pytest to achieve 98% line and branch coverage as well as set up Postman to improve manual testing
  
  ### :school: UBC Course Projects
  *Code access is available upon request for all projects
  #### [Multi-Client Server](https://cpen221-ubc.notion.site/Message-Queues-Pub-Sub-with-Twitter-c5965b28ed01482aad44dbaadac19b77) - CPEN 221
  - Constructed a server supporting multiple simultaneous clients capable of interacting and fetching tweets from Twitter
  - Enabled dual-server routing so that either server can be connected to, and no interruptions occur if one goes offline
  - Followed security protocols by hashing and salting all passwords and encrypting incoming and outgoing data via AES
  
  #### Simple RISC Machine - CPEN 211
  - Implemented a Turing Complete 16-bit RISC machine using System Verilog on an FPGA board in 3 weeks
  - Subdivided the machine into smaller modules to be designed, tested, and debugged more easily
  - Utilized pipelining to increase operations per cycle by 300% and go beyond course expectations
  
  #### [Graphs, Games, and Interplanetary Travel](https://cpen221-ubc.notion.site/Graphs-Games-and-Interplanetary-Travel-79cb9a0844634b7288226639604eb0b0) - CPEN 221
  - Collaboratively built the “Kamino Game” in Java and produced the most optimal solution to win the course competition
  - Implemented graph and tree data structures with associated algorithms while optimizing time and space complexity
  - Exercised best practices including unit testing, documentation, and encapsulation to ensure quality and correctness
  
  ### :airplane: [UBC Uncrewed Aircraft Systems](https://ubcuas.com)
  - Integrated a new camera system into the drone and software suite for use in machine vision
  - Reduced image streaming latency from 12s to 1s with a shell script running on an onboard Linux microcomputer
  - [ACOM](https://github.com/ubcuas/acom): Running on the drone, this is our main communication method with the ground station for the software subteam. I worked on adding support for controlling a winch system, monitoring RC connection, and keeping track of the battery usage.
  - [GCOM-X](https://github.com/ubcuas/gcom-x): Our previous ground station control software. I helped work on the frontend redesign, updated the backend API, integrated a Django server with the React frontent, and added a login page to connect to competiton servers.
  
  ### :robot: [Quote Bot](https://github.com/ElioDiNino/Quote)
  This is a rehost of [nakayoshi](https://github.com/nakayoshi)'s Discord Quote bot which was taken offline in early 2022. In the process of rehosting it I updated some of the bot's commands and patched several security vulnerabilities. A few weeks after, I also completed an overhaul of the bot with slash command support, improved error-handling, thread channel support, patched [vulnerabilities](https://github.com/nakayoshi/quote/issues/5), and other improvements. Since the overhaul, the bot has been up and running for free on Google Cloud without any issues. I continue to keep the bot up to date with the latest Discord.js and dependency releases.
  
  ### :scroll: [SSC Scripts](https://github.com/ElioDiNino/SSC-Scripts)
  This repository is home to different scripts for pulling information off of [UBC's SSC](https://ssc.adm.ubc.ca/) and then notifying the specified emails of what new information is available. It uses [UBC's Webmail](https://webmail.student.ubc.ca/) so that any user with a [CWL](https://it.ubc.ca/services/accounts-passwords/campus-wide-login-cwl) can use the scripts without having to worry about what email service they use for their primary email. An example of one of these scripts is [`grades.py`](https://github.com/ElioDiNino/SSC-Scripts/blob/master/src/grades.py) which checks for when new grades are posted. It can check for multiple course grades at a time and has many other customizable options.
  
  ### :robot: [Autonomous Claw](https://github.com/ElioDiNino/Autonomous-Claw)
  This is a collection of the programming work that went into the autonomous claw project for UBC's APSC 101. The goal of the project was to semi-autonomously pick up objects of different sizes and weights and transport them to a drop-off location accurately and efficiently.
  
  ### :abacus: [Harvard's CS50](https://github.com/ElioDiNino/CS50)
  This is a collection of the code I wrote for [Harvard's CS50](https://cs50.harvard.edu/) that I am proud of and that was of interest to me. I took part in the course during the [Spring 2021 session](https://cs50.harvard.edu/college/2021/spring/).
  
  ### :shield: [UBC Bot](https://github.com/ElioDiNino/UBC-Bot)
  This was my friend and I's final project for CS50. It is a basic Discord moderation bot that has a mix of different commands. It is quite basic but we used it as a way to learn about Discord.js and learn the basics for future Discord bot projects.
  
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
  
  ### :airplane: [UBC Uncrewed Aircraft Systems](https://ubcuas.com)
  I lead as captain and formerly worked on the software subteam as a co-lead for UBC UAS, a design team focused on designing autonomous drones and their support systems. The team repositories can be seen [here](https://github.com/ubcuas). Last year, my focus as co-lead was keeping projects on track and supporting the 18 software subteam members where needed. That being said, with my past experience on the team, I got to work on a variety of microsystems. Some of my notable contributions as both a developer and as co-lead can be seen below as well as in the past projects section.
  - Improved cross-platform compatibility with Docker containers and made related CI/CD pipelines with GitHub Actions (E.g. [ACOM](https://github.com/ubcuas/ACOM))
  - [UASITL](https://github.com/ubcuas/UASITL): Overhauled our simulation pipeline by supporting new vehicle types (planes and VTOLs) and building software images for additional computer architectures (ARMv7 and ARM64)
  - Revamped the team website using an opensource Go framework (Hugo) to decrease load times from 10s to 0.7s
  - Increased team documentation and task tracking by over 5x after integrating Jira and Confluence into our workflows

  ### :globe_with_meridians: Home Server & Security System
  Leveraging the synergy between [Tailscale](https://tailscale.com/) and [Home Assistant](https://www.home-assistant.io/), I've established a distributed home server network alongside a home security system. My tailnet (Tailscale network) includes a variety of devices including Linux, macOS, and Windows machines as well as Android smartphones, an Apple TV, and a Google Chromecast. With a fine-tuned tailnet policy file I can securely remote into other devices, route my traffic through selected devices, and restrict the access that certain devices have (e.g. smartphones being used as cameras can't access other devices). This setup not only facilitates the execution of projects and applications on continuously connected remote devices but also enables the creation of a robust network of cameras using repurposed smartphones.

  The security system I've implemented involves a Dockerized Home Assistant instance operating on my Linux machine. This setup offers a live feed of camera footage, camera management functionalities, and real-time alerts for motion detection events.

  My future roadmap involves expanding the tailnet by integrating additional devices to amplify computational capabilities and augment the surveillance network by incorporating more cameras. Moreover, I plan to set up more Home Assistant automations to automatically record motion events based on specific conditions (such as time or an armed status) and implement an efficient system for managing and purging older recordings.
</details>

<!-- <div id="language-stats" align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=ElioDiNino&layout=compact&langs_count=6&bg_color=22242d&hide_border=true&text_color=c9d1d9&title_color=c9d1d9">
</div> -->
