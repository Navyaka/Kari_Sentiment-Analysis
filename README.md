# Sentiment Analysis of Reviews for "Kari" by Amruta Patil

## Abstract

This report details the process and findings of a sentiment analysis conducted on reviews for the book "Kari" by Amruta Patil. The analysis involved extracting reviews from multiple online platforms and performing sentiment analysis to understand the overall sentiment and subjectivity expressed in the reviews. 

## Introduction

● Objective:

&nbsp;&nbsp;&nbsp;&nbsp; The primary aim is to analyze the sentiment of reviews for the book "Kari" by Amruta Patil. 

● Sources:

&nbsp;&nbsp;&nbsp;&nbsp; Reviews were collected from Amazon, Flipkart, Goodreads, and The StoryGraph. 

## Methodology

● Data Extraction

1. **Tools and Libraries**:

&nbsp;&nbsp;&nbsp;&nbsp;  ○ **Selenium**: A tool used for automating web browsers to extract data. 

&nbsp;&nbsp;&nbsp;&nbsp; ○ **WebDriver Manager**: Manages browser drivers needed for Selenium to operate. 

2. **Process**:

&nbsp;&nbsp;&nbsp;&nbsp; ○ Reviews were extracted from Amazon.com and Flipkart using web scraping techniques. Selenium was used to navigate the websites and extract review data. 

&nbsp;&nbsp;&nbsp;&nbsp; ○ The extracted reviews were stored in a list for further processing. 

&nbsp;&nbsp;&nbsp;&nbsp; ○ Reviews from Amazon.in, Goodreads and The StoryGraph are extracted manually. 

● Sentiment Analysis

1. **Tools and Libraries**:

&nbsp;&nbsp;&nbsp;&nbsp; ○ **Pandas**: A data manipulation library in Python used for handling and analyzing data. 

&nbsp;&nbsp;&nbsp;&nbsp; ○ **TextBlob**: A library for processing textual data, used for performing sentiment analysis. 

&nbsp;&nbsp;&nbsp;&nbsp; ○ **Openpyxl**: A library used to read and write Excel files in Python. 

2. **Process**:

&nbsp;&nbsp;&nbsp;&nbsp; ○ Reviews were read from an Excel file. 

&nbsp;&nbsp;&nbsp;&nbsp; ○ **Sentiment Analysis**: Using TextBlob, each review was analyzed to calculate two key metrics:

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; ■ **Polarity**: Indicates the sentiment of the review, ranging from -1 \(very negative\) to 1 \(very positive\). 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; ■ **Subjectivity**: Indicates how subjective or objective the review is, ranging from 0 \(very objective\) to 1 \(very subjective\). 

&nbsp;&nbsp;&nbsp;&nbsp; ○ The results of the sentiment analysis were saved to a new Excel file. 

## Results

● The analysis provided insights into the polarity and subjectivity of the reviews. 

● **Polarity**: Most reviews fell within a certain range, indicating the overall sentiment of the reviewers. 

● **Subjectivity**: This metric helped identify how personal or impersonal the reviews were. 

## Discussion

● The overall sentiment of the reviews was analyzed and compared across different platforms. 

● Differences in sentiment and subjectivity between platforms were noted and discussed. 

## Conclusion

● The sentiment analysis provided a clear understanding of how readers feel about "Kari" by Amruta Patil. 

● Recommendations for improving the analysis in the future include expanding the number of reviews and sources, and refining the sentiment analysis methods. 

<br>
<br>
<br>
<br>
-Navyaka Kandula



