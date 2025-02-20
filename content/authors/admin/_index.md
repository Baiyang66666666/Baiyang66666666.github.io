---
# Display name
title: Baiyang Qu
Email address: baiyangqu6@gmail.com

# Full name (for SEO)
first_name: Baiyang
last_name: Qu

# Status emoji
status:
  icon: ☕️

# Is this the primary user of the site?
superuser: true

# Role/position/tagline
role: AI Engineer

# Organizations/Affiliations to display in Biography blox
organizations:
  - name: VIVACITY
    url: https://www.vivacityapp.com/ # 如果有更具体的公司网址，请替换

# Social network links
# Need to use another icon? Simply download the SVG icon to your `assets/media/icons/` folder.
profiles:
  - icon: at-symbol
    url: 'mailto:baiyangqu6@gmail.com'
    label: E-mail Me
  # - icon: brands/x
  #   url: https://twitter.com/GetResearchDev # Replace with actual Twitter URL if available
  - icon: brands/github
    url: https://github.com/Baiyang66666666 # Replace with actual GitHub URL if available
  - icon: brands/linkedin
    url: https://www.linkedin.com/in/baiyang-qu-6b1b19249 # Replace with actual LinkedIn URL if available
  # - icon: brands/instagram
  #   url: https://www.instagram.com/ # Replace with actual Instagram URL if available

education:
  - area: MSc Computer Science with Speech and Language Processing
    institution: University of Sheffield
    date_start: 2022-09-01
    date_end: 2023-09-01
    summary: |
      Completed with Distinction Degree.

      Modules included: Speech Technology, Scalable Machine Learning, Text Processing, Speech Processing, Natural Language Processing, Machine Learning and Adaptive Intelligence, Team Software Project, Computer Professional Issues.

      Dissertation: Improving Automatic Speech Recognition to help the prediction of Transient Loss of Consciousness consultations.
    dissertation_file: uploads/BaiyangQu_MScDissertation.pdf
      
  - area: BSc Electronic Information Engineering
    institution: Qingdao University
    date_start: 2017-09-01
    date_end: 2021-06-01
    summary: |
      GPA: 81.68/100

      Modules included: C Language Programming, Embedded System and Application, Signal and System, Algorithms and Data Structure, Python Programming, Circuit Principle, Object-Oriented Programming, Pattern Recognition, LabVIEW, etc.

work:
  - position: AI Engineer
    company_name: VIVACITY
    company_url: https://www.vivacityapp.com/ # 如果有更具体的公司网址，请替换
    company_logo: '' # Add logo URL if available
    date_start: 2024-05-01
    date_end: ''
    summary: |2-
      AI Text Processing & Multi-Functional System (RAG Project) | Full Stack Developer

      * Developed a distributed AI-driven text processing system using Cloudflare Workers and LangChain.
      * Implemented RAG technology for enhanced text generation accuracy.
      * Built serverless architecture with Cloudflare Workers and Durable Objects.
      * Developed AI agents for dynamic task handling and integrated LangChain.
      * Used asynchronous programming and task queues (Cloudflare Queue) for efficient data processing.
      * Optimized SQL database for storing and retrieving user data.

      Azure AI-based Automated Image Classification System | AI Engineer**

      * Fine-tuned a Large Language Model (LLM) with labeled data for improved accuracy.
      * Built the backend with NestJS, integrated pretrained LLM for classification, and used Redis Queue for batch tasks.
      * Developed MongoDB storage for metadata and classification logs, adding an error correction module to improve model training.

      WeChat Mini-Program User Analysis & Business Insights**

      * Used Google BigQuery for large-scale data analysis and Looker for real-time visualizations.
      * Applied SQL for data cleaning and aggregation, with time-series analysis to detect trends in active users and query volumes.

      Industry-Specific Translation & Terminology Management System | AI Engineer**

      * Designed and implemented Glossary datastore (Cloudflare D1 Database) for managing industry-specific terms, ensuring consistency and accuracy in translations.
      * Developed RESTful APIs for glossary updates and integrated Azure OpenAI for customized machine translation.
      * Used SQL for efficient data storage and real-time glossary synchronization, providing flexible and fast translation.

      
  - position: Student Internship
    company_name: VoiceBase, Inc., A LivePerson (LPSN) Company
    company_url: ''
    company_logo: '' # Add logo URL if available
    date_start: 2023-03-03
    date_end: 2023-07-28
    summary: |2-
      * Re-implemented the method to automate the prediction of Mean Opinion Score (MOS) for synthetic speech using LDNet model.
      * Implemented LDNet on VCC2018 and BVCC datasets.
      * Gained experience in managing data and algorithm pipelines on HPC systems.
  - position: Graduate Teaching Assistant
    company_name: University of Sheffield
    company_url: https://www.sheffield.ac.uk/ # 如果有学校网址，请替换
    company_logo: '' # Add logo URL if available
    date_start: 2022-10-04
    date_end: 2022-12-02
    summary: |2-
      * Served as a Technical Demonstrator in Module Engineering Software Design.
      * Contributed to practical laboratory classes, conducted demonstrations and experiments.
      * Participated in module development and assisted in designing experiments on embedded systems (NXP-KL25Z).
      * Guided students in deploying microcontrollers.
  - position: Algorithm Intern
    company_name: ByteDance PICO
    company_url:  # 可以添加公司网址，如果希望展示
    company_logo: '' # Add logo URL if available
    date_start: 2021-06-10
    date_end: 2021-08-13
    summary: |2-
      * Verified the accuracy of visual positioning by calibrating VR sensor data with visual input.
      * Recorded and analyzed motion tracking data for positioning algorithm improvement.
      * Collaborated with a multidisciplinary team.
  - position: Team Leader
    company_name: Little Sunflower Volunteer Team in Qingdao University
    company_url:  # 可以添加组织网址，如果希望展示
    company_logo: '' # Add logo URL if available
    date_start: 2017-10-01
    date_end: 2021-08-01
    summary: |2-
      * Spearheaded a team for volunteer activities in communities and rural areas.
      * Developed VR software (UE4) for children's English learning and conducted programming courses.
      * Pioneered VR travel experiences for individuals with mobility difficulties and elderly residents.

  - name: Hobbies # 技能大类：兴趣爱好 (放在 Skills 下面)
    color: '#eeac02' # 保留原 hobbies 的颜色设置
    color_border: '#f0bf23' # 保留原 hobbies 的边框颜色设置
    items: # 具体爱好列表
      - name: Hiking
        description: ''
        percent: 60 # 爱好百分比可以根据需要调整，这里沿用之前的
        icon: person-simple-walk
      - name: Basketball
        description: ''
        percent: 70
        icon: basketball-ball
      - name: Frisbee
        description: ''
        percent: 70
        icon: disc-flying

# Skills
skills:
  - name: Technical Skills # 技能大类：技术技能
    items:
      - name: Programming Languages - Python, JavaScript/Node.js, C++, MATLAB  # 技能子类：编程语言
        description: ''
        icon: devicon/python
        items: # 具体技能列表
          - name: Python
            percent: 90
            icon: devicon/python
          - name: JavaScript/Node.js
            percent: 85
            icon: devicon/javascript
          - name: C++
            percent: 70
            icon: devicon/cplusplus
          - name: MATLAB
            percent: 60
            icon: devicon/matlab
      - name: Databases - MongoDB, Cloudflare D1, Redis, Azure SQL Database # 技能子类：数据库
        description: ''
        icon: devicon/sql
        items: # 具体技能列表
          - name: SQL
            percent: 80
            icon: devicon/sql
          - name: MongoDB
            percent: 70
            icon: simple-icons/mongodb
          - name: Redis
            percent: 70
            icon: simple-icons/redis
          - name: Azure Cosmos DB
            percent: 70
            icon: simple-icons/azure
          - name: Azure SQL Database
            percent: 70
            icon: simple-icons/azure
      - name: Cloud Platforms - Azure Cloud(Azure OpenAI, Azure ML, AKS, Azure Data Lake Storage, Azure DevOps), Cloudflare # 技能子类：云平台
        description: ''
        icon: simple-icons/azure
        items: # 具体技能列表
          - name: Azure Cloud
            percent: 80
            icon: simple-icons/azure
            description: Azure OpenAI, Azure ML, AKS, Azure Data Lake Storage, Azure DevOps
          - name: Google Cloud
            percent: 70
            icon: simple-icons/googlecloud
            description: BigQuery, GCS
          - name: Cloudflare
            percent: 80
            icon: simple-icons/cloudflare
            description: Cloudflare Workers
          - name: DigitalOcean
            percent: 60
            icon: simple-icons/digitalocean
      - name: AI/ML & Data Science - LLMs Deployment(OpenAI, DeepSeek, Gemini, Claude, etc.), Data Pipeline, Data Analysis & Visualization(Looker, PowerBI) # 技能子类：AI/ML & 数据科学
        description: ''
        icon: simple-icons/languagemodel
        items: # 具体技能列表
          - name: LLMs
            percent: 80
            icon: simple-icons/languagemodel
            description: LLM Deployment, LLM Fine-tuning, RAG
          - name: ML Frameworks
            percent: 75
            icon: simple-icons/neuralnetwork
            description: PyTorch, TensorFlow, Neural Networks
          - name: Computer Vision
            percent: 70
            icon: simple-icons/computervision
            description: Image Classification
          - name: Time-Series Analysis
            percent: 70
            icon: chart-line
            description: ''
          - name: Data Pipeline
            percent: 70
            icon: simple-icons/pipeline
            description: Data Pipeline Optimization
          - name: Data Analysis & Visualization
            percent: 60
            icon: simple-icons/powerbi
            description: Looker, PowerBI
      - name: DevOps & Infrastructure - Docker, HPC, Linux/Bash, Kubernetes # 技能子类：DevOps & 基础设施
        description: ''
        icon: devicon/docker
        items: # 具体技能列表
          - name: Docker
            percent: 75
            icon: devicon/docker
          - name: HPC
            percent: 70
            icon: simple-icons/hpc
          - name: Linux/Bash
            percent: 80
            icon: devicon/linux
          - name: Azure Kubernetes Service (AKS)
            percent: 75
            icon: simple-icons/kubernetes

  - name: Hobbies # 技能大类：兴趣爱好 (放在 Skills 下面)
    color: '#eeac02' # 保留原 hobbies 的颜色设置
    color_border: '#f0bf23' # 保留原 hobbies 的边框颜色设置
    items: # 具体爱好列表
      - name: Hiking
        description: ''
        percent: 60 # 爱好百分比可以根据需要调整，这里沿用之前的
        icon: person-simple-walk
      - name: Basketball
        description: ''
        percent: 70
        icon: basketball-ball
      - name: Frisbee
        description: ''
        percent: 70
        icon: disc-flying
      - name: Table Tennis
        description: ''
        percent: 70
        icon: table-tennis-paddle-ball
      - name: Snowboarding
        description: ''
        percent: 70
        icon: snowboard


languages:
  - name: English
    percent: 100 # 请根据实际情况调整百分比
  - name: Chinese
    percent: 100 #  母语，所以调整为 100%
  - name: French
    percent: 25
# Awards.
awards:
  - title: Outstanding Graduates of Qingdao University
    date: '2020-01-01' #  修改为 YYYY-MM-DD 格式
    awarder: Qingdao University
    icon: school #  可以更换更合适的图标
    summary: |
      Outstanding Graduates of Qingdao University
  - title: University Academic Excellence Scholarship
    date: '2017-01-01' # 修改为 YYYY-MM-DD 格式 (起始年份)
    awarder: Qingdao University
    icon: school #  可以更换更合适的图标
    summary: |
      University Academic Excellence Scholarship (2017-2021)
  - title: Honorable Mention on Mathematical Contest in Modeling (MCM/ICM)
    date: '2020-01-01' #  修改为 YYYY-MM-DD 格式
    awarder: MCM/ICM
    icon: award # 可以更换更合适的图标
    summary: |
      Honorable Mention on Mathematical Contest in Modeling (MCM/ICM)
  - title: First Prize on National Mathematical Contest in Modeling
    date: '2019-01-01' #  修改为 YYYY-MM-DD 格式
    awarder: National Mathematical Contest in Modeling
    icon: award # 可以更换更合适的图标
    summary: |
      First Prize on National Mathematical Contest in Modeling
  - title: First Prize on National Undergraduate Electronic Design Contest
    date: '2019-01-01' #  修改为 YYYY-MM-DD 格式
    awarder: National Undergraduate Electronic Design Contest
    icon: award # 可以更换更合适的图标
    summary: |
      First Prize on National Undergraduate Electronic Design Contest
  - title: First Prize on Provincial University Internet of Things Contest of Innovation
    date: '2019-01-01' #  修改为 YYYY-MM-DD 格式
    awarder: Provincial University Internet of Things Contest of Innovation
    icon: award # 可以更换更合适的图标
    summary: |
      First Prize on Provincial University Internet of Things Contest of Innovation
  - title: Second Prize of Provincial College Student Physics Competition
    date: '2019-01-01' #  修改为 YYYY-MM-DD 格式
    awarder: Provincial College Student Physics Competition
    icon: award # 可以更换更合适的图标
    summary: |
      Second Prize of Provincial College Student Physics Competition
---