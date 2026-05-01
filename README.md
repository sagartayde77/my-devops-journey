# My DevOps Journey

![Day](https://img.shields.io/badge/Day-1%20of%20100-purple)
![Status](https://img.shields.io/badge/Status-Active-brightgreen)
![Started](https://img.shields.io/badge/Started-April%2019%202026-blue)

---

## Introduction

Hello, my name is **Sagar Tayde**. I graduated in 2025 and I am currently learning **Cloud and DevOps**.  
This repository documents my daily progress, projects, and hands-on practice.

---

## Connect With Me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sbt7)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-181717?logo=github&logoColor=white)](https://github.com/sagartayde77)

---

## Goals

- Become a Cloud & DevOps Engineer
- Build real-world projects
- Develop strong Linux fundamentals
- Master CI/CD pipelines
- Document daily learning progress

---

## Technologies I Plan to Learn

| Technology | Status |
|------------|--------|
| Linux | 🔄 In Progress |
| Python | 🔄 In Progress |
| Git & GitHub | 🔄 In Progress |
| AWS | 📅 In Progress |
| Docker | 📅 Planned |
| Kubernetes | 📅 Planned |
| Terraform | 📅 Planned |
| Jenkins | 📅 Planned |
| CI/CD Pipelines | 📅 Planned |
| SQL / MySQL | 📅 Planned |

---

## Progress Tracker

| Week | Focus | Status |
|------|-------|--------|
| Week 1 | Python basics, Linux, Git & GitHub | 🔄 In Progress |
| Week 2 | Python functions, Bash scripting, AWS basics | 📅 Planned |
| Week 3 | Docker & containerisation | 📅 Planned |
| Week 4 | More AWS + projects | 📅 Planned |

---

## Daily Log

### Day 1 — 2026-04-19

#### Topics Covered
- What is Cloud Computing
- What is Python 
- Basic Linux commands

#### What I Learned
I learned about What is Cloud Computing, Linux and Python. What is the actual use of them in real world projects.
- Introduction to Python and history of Python.
- Introduction to Linux, History of Linux.
- What is cloud computing, Why it exists.

*This README is updated daily. Last updated: 2026-04-19*

### Day 2 — 2026-04-20

#### Topics Covered

Git & Version Control:
- What is Version Control System (VCS)
- What is Distributed Version Control System (DVCS)
- What is Git
- Git workflow (Working directory → Staging → Commit → Repository)
- Types of repositories (local and remote)

#### Practical Performed

- Installed Git
- Initialized local repository
- Added files to staging area
- Created commits
- Connected local repository with GitHub
- Pushed code to remote repository

#### Key Understanding

Git helps track changes in code and allows reverting to previous versions if something breaks.

Distributed Version Control System means each developer has full copy of project repository, which improves reliability and collaboration.

*This README is updated daily. Last updated: 2026-04-20*

### Day 3 — 2026-04-21

#### Topics Covered

AWS:
- Load Balancer
- Target Group
- Auto Scaling Group
- Launch Template

Git:
- Distributed Version Control System (DVCS)
- Git workflow (working directory → staging → commit → repository)
- Types of repository (local and remote)
- Installed Git on EC2 instance

#### Practical Performed

- Created Application Load Balancer
- Created Target Group
- Connected multiple EC2 instances to Load Balancer
- Created Auto Scaling Group using Launch Template
- Tested traffic distribution
- Installed Git on EC2 instance
- Used Git from local system

#### Key Understanding

Load Balancer distributes incoming traffic across multiple servers to improve availability.

Auto Scaling automatically adjusts number of EC2 instances based on demand, which helps maintain performance and reduce manual work.

Git helps track changes in code and makes collaboration easier.

---

*Last updated: 2026-04-21*

### Day 4 - 2026-04-22

#### Topics Covered

AWS:
- Blue-Green Deployment

Git:
- Git local repo
- GitHub Repo
- Git Commands(git init, git status, git add, git commit, git log, git show, git push, git pull)

#### practical Performed

- Deployed 2 portfolio versions on Blue-Green environment with 0 downtime
- Run git commands on local system and Ec2 instance

#### Key Understanding

#### Blue-Green Deployment:
Blue-Green Deployment means Deploying a product without having 0 downtime having different version. and easy to rollback. With the help of 2 Target Group (Blue-TG, Green-TG). By editing the rule in in load balancer listener rules.

#### Git commands:
- git init
it is use to initialize git in local repo.

- git add
it is used to add changed files in stagin area.
- git commit -m ""
it is used to do commit change.
- git status
it is used to check the status of current repo.
 -git log
 it is used to see the git logs
 - git show 
 it is used to see the changes who did by git commit id
 - git push
 it is used to push local changes to github repo.

 - git pull
 it is used to pull the changes from github to local repo.

 ---
 *Last updated: 2026-04-22*

 ### Day 5 - 2026-04-23

 #### Topics Covered

 AWS:
 - CloudWatch
 - Alarms
 - Metrics, Threshold

 Git:
 - Branch
 - Pull requests

 ### Practical Performed

 - Performed git branch commands on local system.
 - Checked Actual changes on GitHub
 - Generated pull request

 #### Key Understanding

 #### AWS CloudWatch:
 AWS CloudWatch is monitoring and observability service which is run on mainly 3 principles that are ALARMS, LOGS & EVENTS. CloudWatch service can be integret with other aws services.

 #### Git Branch:
 Branching system is used to develope the product parallely, Each branch is seperated from each other but has the clone of main branch. We can also merge the branches and pull changes from branches.

 ---
 *Last updated: 2026-04-23*

### Day 6 — 2026-04-24

#### Topics Covered

AWS:
- CloudWatch Logs
- Events

Git:
- Basic workflow revision

#### Practical Performed

- Explored CloudWatch logs concept (theory)
- Reviewed Git commands (add, commit, push)

#### Key Understanding

CloudWatch Logs:
Used to collect and monitor logs from AWS resources for debugging and analysis.

Events:
Used to trigger actions based on specific activities happening in AWS services.

---

*Last updated: 2026-04-24*

### Day 7 — 2026-04-25

#### Topics Covered

- Revision day

#### What I Did

- Reviewed:
  - Load Balancer
  - Auto Scaling
  - CloudWatch basics
  - Git workflow and branching

#### Key Understanding

Revision helps strengthen concepts and improve clarity.  
Repeated exposure makes complex topics easier to understand.

---

*Last updated: 2026-04-25*

### Day 8 - 2026-04-26

#### Topic Covered 

- Practical of AWS CloudWatch

#### Key Understanding

Metrics:
I set alarm on CPU-Utilization under 10%. With trigering the SNS topic to inform and used EC2 instance action "STOP".

Lambda:
Created lambda funtions to stop and start on a perticular time. Used EventBridge to Invoke lambda funtion.

--- 

*Last update: 2026-04-26*

### Day 9 — 2026-04-27

#### Topics Covered
- No new topics

#### What I Did
- Took a break from regular study
- Stepped away to recharge

#### Key Understanding
Consistency is important, but rest is also required to avoid burnout.  
Taking a break helps maintain long-term focus.

---

*Last updated: 2026-04-27*

### Day 10 -2026-04-28

*nothing new topic covered, did revision*

### Day 11 — 2026-04-29

#### Topics Covered

AWS:
- EC2 instance types
- EC2 families

#### What I Did

- Explored different EC2 instance categories in AWS console
- Compared instance types and their purpose
- Understood why different workloads need different instance types

#### Key Understanding

EC2 instances are not one-size-fits-all.

Different families are designed for different workloads:

- General purpose → balanced usage
- Compute optimized → CPU-heavy tasks
- Memory optimized → large data workloads
- Storage optimized → high I/O operations

Choosing the right instance improves performance and avoids unnecessary cost.

---

*Last updated: 2026-04-29*

### Day 12 — 2026-04-30

*No New Topic*

### Day 13 — 2026-05-01

#### Topics Covered

AWS:
- CloudWatch concepts
- Metrics, Logs, Events

#### What I Did

- Understood how metrics, logs and events actually work
- Connected these concepts with real AWS flow (alarms, triggers, actions)
- Reviewed previous CloudWatch practical with better clarity

#### Key Understanding

Metrics:
Numeric data collected over time (like CPU utilization).  
Used for monitoring system health and setting thresholds.

Logs:
Detailed records of system activity.  
Used for debugging and understanding what actually happened.

Events:
Triggers generated when a condition occurs.  
Used to start automated actions (like Lambda execution).

Flow:

Metrics → condition detected  
Event → trigger generated  
Logs → help in debugging  

Monitoring is not just observing, it is detecting and taking action.

---

*Last updated: 2026-05-01*