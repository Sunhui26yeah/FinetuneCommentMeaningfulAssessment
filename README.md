# 🚀 Finetuned Comment Importance Detector & Automated Notification System

> **Detect meaningful comments in GitHub Pull Requests, and send automated notifications to developers.**

---

## 🧠 Project Overview

This project focuses on **identifying meaningful comments** during GitHub Pull Request (PR) reviews, and **automatically notifying developers** based on the detected important comments.  
It leverages a fine-tuned BERT model for classification and integrates a simple **email notification system** to assist developers in timely reviewing significant feedback.
**Zenodo Archive**: [Dataset and Materials available here](https://zenodo.org/records/15293180)


✨ Main Features:
- 🔍 Fine-tuned BERT model to classify PR comments into "meaningful" and "not meaningful".
- 📩 Automatic email notifications triggered by important comment detection.
- 📊 Scripts for data collection, preprocessing, model training, and evaluation.

---

## 📚 Paper Information

> **Paper Title**: *Fine-tuning Comment Importance Detection for Automated Developer Notifications*  
> **Authors**: Hui Sun, Xingyue Shi, Mohan Reddy


---
## 🛠️ Project Structure

This is the HW of 722, we fine tuned a bert base model to predict if a comment in GitHub PR is useful. 
1500data.xlsx is the file that we three annotated 1500 comments sampled from 495 projects, over 4 million PRs from Github Platform.
finetuned_BERT_comments_detector.ipynv is the code used to finetune bert model.
fintuned_BERT_epoch_5.ipynb is the fifth model trained by our code which is also the model performed better.
senEmailNoti.ipynb is the file used to predict a comment usefulness and send email to users with a email title to notify stakeholders if the comment in a PR is important or not
Interview Plan.pdf is the file we used to interview users.
