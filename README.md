# AI-Based Skill Gap Analyzer

An AI-based system designed to help students and job seekers understand the skill gap between their current skills and the requirements of a target job role.

## 📌 Project Overview

The AI-Based Skill Gap Analyzer compares a candidate's resume with a selected job description. It extracts important skills from both documents, normalizes different names and abbreviations, and identifies the candidate's matched, partially matched, and missing skills.

The system also aims to generate a priority-based learning roadmap with suitable learning resources for the missing skills.

## 🎯 Objectives

* Extract text from a candidate's resume and job description.
* Identify important technical and soft skills using NLP techniques.
* Normalize synonyms, abbreviations, and different names for the same skill.
* Compare the resume and job description using TF-IDF and Cosine Similarity.
* Classify skills as Matched, Partially Matched, or Missing.
* Generate a priority-based learning roadmap for missing skills.
* Store skill information and learning resources using an SQL database.

## 🔄 System Workflow

```text
Resume + Job Description
          ↓
   Text Extraction
          ↓
  NLP Pre-processing
          ↓
    Skill Extraction
          ↓
   Skill Normalization
          ↓
 TF-IDF + Cosine Similarity
          ↓
    Skill Gap Analysis
          ↓
Matched / Partial / Missing
          ↓
   Learning Roadmap
```

## 🧠 Technologies and Techniques

* Python
* Natural Language Processing (NLP)
* Machine Learning
* TF-IDF
* Cosine Similarity
* Skill Extraction
* Skill Normalization
* Named Entity Recognition (NER)
* SQL Database

## 🏗️ Main Modules

### 1. Document Ingestion

Accepts the candidate's resume and target job description and converts them into clean text.

### 2. NLP Pre-processing

Cleans and prepares the extracted text using techniques such as tokenization, stop-word removal, and lemmatization.

### 3. Skill Extraction

Identifies technical and soft skills from the resume and job description.

### 4. Skill Normalization

Maps synonyms, abbreviations, and different skill names to a common skill name.

### 5. Similarity Matching

Uses TF-IDF and Cosine Similarity to compare the resume with the job requirements.

### 6. Gap Classification

Classifies required skills into:

* ✅ Matched
* 🟡 Partially Matched
* ❌ Missing

### 7. Learning Roadmap

Prioritizes missing skills and connects them with suitable learning resources.

## 📊 Expected Output

The system is expected to provide:

* Overall resume-to-job match score
* Matched skills
* Partially matched skills
* Missing skills
* Priority-based learning roadmap
* Learning resources for missing skills

## 🗄️ Database

The planned SQL database will store:

* Skill taxonomy
* Skill synonyms
* Learning resources
* Previous analysis history

## 🚧 Project Status

**Under Development**

This project is being developed as a mini project in the Artificial Intelligence, Natural Language Processing, and Machine Learning domain.

## 👨‍💻 Team Members

1. Kikkari Sai Kumar
2. Badhiga Vardhan
3. Karikati Nikhilesh
4. Renati Siddeswar

## 🎓 Academic Information

**Project:** AI-Based Skill Gap Analyzer
**Academic Year:** 2026–2027
**Domain:** Artificial Intelligence (AI), Natural Language Processing (NLP), and Machine Learning
