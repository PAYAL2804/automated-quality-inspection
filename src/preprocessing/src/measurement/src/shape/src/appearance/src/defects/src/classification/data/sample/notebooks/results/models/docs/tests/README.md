# Automated Quality Inspection Using Computer Vision

## About the Project

Automated Quality Inspection is a software-based computer vision system designed to analyze product images and identify whether a product meets predefined quality requirements.

The system focuses on analyzing key quality parameters such as:

* Size and dimensions
* Shape and geometric characteristics
* Appearance and label characteristics
* Visible defects or abnormalities

Based on the inspection results, the system will classify the product as **Accept** or **Reject**.

## Problem Statement

Manual inspection of manufactured products can be time-consuming, subjective, and prone to human error. This project aims to develop an automated image-based inspection system that can assist in evaluating product quality using computer vision techniques.

## Proposed System

The proposed system follows the workflow:

**Product Image → Image Preprocessing → Product Analysis → Size & Shape Analysis → Appearance/Label Analysis → Defect Detection → Quality Evaluation → Accept/Reject**

## Technologies Used

* Python
* OpenCV
* NumPy
* Matplotlib
* Scikit-learn
* Jupyter Notebook / Google Colab
* GitHub

## Project Modules

### 1. Image Preprocessing

Prepares the input image for further analysis through operations such as resizing, filtering, and thresholding.

### 2. Size Measurement

Analyzes the dimensions of the product in pixels. Real-world measurements such as millimetres may be obtained later using image calibration or a reference scale.

### 3. Shape Analysis

Analyzes product contours and geometric characteristics to determine whether the expected shape is maintained.

### 4. Appearance and Label Analysis

Evaluates visible appearance and label-related characteristics of the product.

### 5. Defect Detection

Identifies visible defects or abnormalities in the product image.

### 6. Quality Classification

Combines the inspection results and provides the final **Accept / Reject** decision.

## Expected Output

The system is expected to provide:

* Product size/dimension information
* Shape analysis result
* Appearance/label inspection result
* Visible defect detection result
* Final **Accept / Reject** classification

## Project Status

**Current Stage:** Review 1 – Project Planning and Design

The project is currently in the planning, literature review, architecture design, and initial development stage.

## Future Work

* Dataset preparation and image collection
* Development of individual inspection modules
* Integration of the inspection modules
* Model/algorithm evaluation
* System testing and performance evaluation
* Final demonstration

## Team

**Project:** Automated Quality Inspection Using Computer Vision
**Branch:** Information Science and Engineering (ISE)

