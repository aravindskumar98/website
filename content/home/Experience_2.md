---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: Experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 40

title: Experience
subtitle: 

# Date format for experience
date_format: Jan 2006
#   Leave `date_end` empty if it's your current employer.
#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
experience:
  - title: Data Scientist
    company: AB InBev
    company_url: 'https://www.ab-inbev.com/'
    # company_logo: org-gc
    location: Bangalore, India
    date_start: '2020-08-03'
    date_end: '2020-08-16'
    description: |2-
        Improved BrewRight, ABI’s legal analytics platform for detecting fraudulent transactions for financial compliance
        
        * Developed machine learning models and implemented hypotheses to flag anomalous and risky transactions
        * Set-up CICD for DevOps pipelines, optimized API data extraction scripts and achieved E2E Automation
        * Migrated existing codebase to run in PySpark using Databricks; reducing runtime by 70%, saving USD 100,000

  - title: Project Associate  
    company: Inspire Lab, IIT Madras
    company_url: 'https://www.ab-inbev.com/'
    # company_logo: org-gc
    location: Chennai, India
    date_start: '2021-05-03'
    date_end: '2021-09-16'
    description: |2-
        NDA Robot Design
        
        * Responsible for the design of a low-cost, modular surgical system to guide invasive surgical operations.
        * Designed to facilitate 360 degree access to the needle guide during surgical operations; Controlled through servo motors.
        

  - title: Research - Non-contact vibration analysis through video
    company: IIT Madras
    company_url: 'https://www.ab-inbev.com/'
    # company_logo: org-gc
    location: Chennai, India
    date_start: '2019-10-03'
    date_end: '2020-06-16'
    description: |2-
        Showcased video cameras as a quick and inexpensive way for remote, non-contact vibration analysis
        
        * Scale invariant features and optical flow algorithms used to extract the motion signal from the video frames
        * The peaks obtained from FFT plots generated using the motion signal were found to be in 8% of the body’s NF


  - title: Pneumonia Detection in X-Rays
    company: Astrazeneca-IITM Hackathon
    company_url: 'https://www.ab-inbev.com/'
    # company_logo: org-gc
    location: Chennai, India
    date_start: '2020-01-03'
    date_end: '2020-01-03'
    description: |2-
        AI based hackathon to diagnose pneumonia through abscesses or pleural effusions in X-Ray images 
        
        * Tackled as an object detection problem, with only one type of image to detect. Yolo-v3 from Darknet was used 
        * Achieved an IoU of 46.97% and MAP value of 35.44%.


  - title: Research - Monsoon Rainfall Prediction
    company: IIT Madras
    company_url: 'https://www.ab-inbev.com/'
    # company_logo: org-gc
    location: Chennai, India
    date_start: '2019-07-03'
    date_end: '2019-11-16'
    description: |2-
        Developed an ML model for prediction of Indian rainfall on monthly and seasonal time scales
        
        * Used RNNs to forecast rainfall for June to Sept (ISMR) by feeding data on rainfall and sea surface temps
        * Set-up CICD for DevOps pipelines, optimized API data extraction scripts and achieved E2E Automation
        * Temperature was used to augment, accounting for the fluctuations; the model achieved an RMS Error of 24 cm

  - title: Project - Quality Prediction in Iron Ore Mining
    company: IIT Madras
    company_url: 'https://www.ab-inbev.com/'
    # company_logo: org-gc
    location: Chennai, India
    date_start: '2019-01-03'
    date_end: '2019-05-16'
    description: |2-
        Specifics - 
        
        * Created a machine learning based model to predict purity of the Iron ore (percentage of Silica Impurity) prior to froth floatation, to enable engineers to take corrective actions and ensure that the product quality remains high
        * The model employed random forest classifiers, neural networks and XGBoost in an ensemble to predict the output Silica concentrate based on input ore properties, ore pulp condition, air flow rate &amp; other process parameters
        * The predicted value of silica concentrate in the ore was found have an R2 score of 0.941 in the testing set

  - title: Livestock Management Using Unique IDs
    company: Confederation of Indian Industries - Hackathon
    company_url: 'https://www.ab-inbev.com/'
    # company_logo: org-gc
    location: Chennai, India
    date_start: '2019-01-03'
    date_end: '2019-01-16'
    description: |2-
        2-tier Hackathon on sustainable development, organized by CII; contested by 300+ teams across 7 countries
        
        * Ideated, pitched, & showcased Dairy Folk: A start-up focusing on improving livestock management using unique IDs
        * Enabled continuous health monitoring of livestock by decentralizing storage of data for enhanced transparency


  - title: Moodle Crawler for Offline Back-ups
    company: IIT Madras
    company_url: 'https://www.ab-inbev.com/'
    # company_logo: org-gc
    location: Chennai, India
    date_start: '2019-05-03'
    date_end: '2019-07-16'
    description: |2-
        Specifics - 
        
        * Created a web crawler using selenium & bs4 for maintaining offline copy of course documents from Moodle.
        * Wrote a daemon to refresh the offline version daily; File system updated to match changes in course structure

  - title: Summer Intern
    company: Toyota
    company_url: 'https://www.ab-inbev.com/'
    # company_logo: org-gc
    location: Bangalore, India
    date_start: '2018-06-03'
    date_end: '2018-07-16'
    description: |2-
        Worked on predicting the work in progress (WIP) stock of the assembly shop. 
        
        * Optimized the process by making it data driven and helped reduce the WIP stock by 9%
        * Reduced monthly production shift planning time by 80%

  - title: Self-Balancing Bicycle Model
    company: IIT Madras
    company_url: 'https://www.ab-inbev.com/'
    # company_logo: org-gc
    location: Chennai, India
    date_start: '2018-07-03'
    date_end: '2018-11-16'
    description: 
        This was implemented using Arduino based PID control utilizing data from a gyroscope &amp. An accelerometer in a closed feedback loop to control the rotation speed of a flywheel, thereby maintaining the unstable equilibrium.
        



design:
  columns: '2'
---

