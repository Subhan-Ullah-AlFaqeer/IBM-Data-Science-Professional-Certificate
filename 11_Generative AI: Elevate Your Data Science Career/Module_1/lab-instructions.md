# Hands-on Lab: Generative AI for Data Generation and Augmentation

**Estimated time needed**: **30** minutes

## Introduction.

One of the principal advantages of generative AI is its ability to generate realistic synthetic data. Synthetic data is generated when a pretrained generative model responds to a prompt, creates new data samples, or performs transfer learning on a given dataset. In addition, it generates samples that augment the existing data set while preserving its statistical distribution and interpretability.

In this lab, you will learn how to use generative AI to generate synthetic data samples and transfer learning on a given dataset.

## Learning objectives

By the end of this lab, you will be able to understand and apply key concepts of synthetic data generation using generative AI tools in practical scenarios.

-   Understand the concept of synthetic data generation using generative AI
    
-   Use tools such as **Tonic Fabicate** and **ilovecsv** to create synthetic data samples
    
-   Augment an existing CSV dataset while maintaining its statistical characteristics
    
-   Explore how generative AI can enhance datasets for analysis, modeling, and other downstream tasks
    

## Insurance dataset overview

The dataset used in this lab includes insurance records.

This dataset is a cleaned version of the original dataset, meaning the data has been processed to remove errors, handle missing values, and ensure consistency.

The original dataset, [Medical Insurance Price Prediction](https://www.kaggle.com/datasets/harishkumardatalab/medical-insurance-price-prediction?resource=download "Medical Insurance Price Prediction"), contains raw, unprocessed data and is available on [Kaggle](https://www.kaggle.com/ "Kaggle") under the [CC0 1.0 Universal License](https://creativecommons.org/publicdomain/zero/1.0/legalcode "CC0 1.0 Universal License"), which allows free use and distribution.

You can download the cleaned dataset file directly from the link provided here: [Insurance Dataset](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMSkillsNetwork-AI0271EN-SkillsNetwork/labs/v1/m1/data/insurance_dataset.csv "Insurance Dataset")

### Option 1: ilovecsv Tool

The **ilovecsv** tool is a simple, GUI-based tool. You will now explore how to use it.

#### 1\. Open the website

Click this [ilovecsv](https://ilovecsv.net/) link to open the website and interface.

This link opens in a new browser tab, and you should see a web page that looks similar to the following screen capture:

![](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/dvYPHjLlYAUvYdqkVz67GA/Image-1.png)

#### 2\. Create an account

You can create an account on this website free of charge, or you can simply log in using your Gmail ID. After you log in, you'll see the following interface:

![](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/XRI14YRR1TpM1pfCT3bVIg/Image-2.png)

#### 3\. Upload the dataset

-   Click on the `Upload` button given at the top of the page, and upload the CSV file of the data set to the interface.
    

![](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/9BZVwrUvEs8FlPG1mMzKJQ/Image-3.png)

-   After uploading the dataset, you will be able to see the **insurance\_dataset** file listed in the uploaded files section.
    

![](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/0yQ5QQh9Yupz5BHvhRO8IQ/Image-4.png)

#### 4\. Access the Data Augmentation tool

-   You are on the main dashboard page. Scroll down through the available sections until you locate the **AI and Machine Learning** section, or use the left-hand navigation panel to quickly navigate to it directly. ![](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/8AmIkX88Mlz7jX0alNDQEA/Image-5.png)
    
-   Within the AI and Machine Learning section, locate the **Data Augmentation Tool** from the available options and click on it to open the tool interface. ![](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/T5c1nvTOcoGvC3N5fkpvNw/Image-6.png)
    

#### 5\. Augment the data

Statistical augmentation in the ilovecsv tool involves generating synthetic rows from your existing dataset while preserving its statistical properties.

You can use the **Augmentation factor** to adjust the **density (number of rows)** of the synthetic dataset as required. ![](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/sYGOM5HlL1HS8hnrOam0Bg/Image-7.png)

Once you have adjusted the augmentation factor **(for example, 1x)**, click the `Execute Augmentation` button. ![](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/u5HTla0eVS4Wxw4p9TLALg/Image-8.png)

#### 6\. Download the synthetic data

After processing completes, you will see a notification that the operation is complete, similar to what you see in the following screen capture:

![](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/20W37BnXwJjdqwAn8Mfakg/Image-9.png)

Click the `See Results` hyperlink to open and view the final results in the editor.

![](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/VMAg4uxOnYzE5YlNiAxf_A/Image-10.png)

Close the results window and return to the previous page. Then click `Download` to save the output file to your local machine. ![](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/JXReidtuiFTqIl0s6CaZdA/Image-11.png) In the final result, you will get 2,676 rows, which is double the original file since you selected a 1× augmentation factor. You can now use this synthetic data set for data science operations, or you can also augment the original data set with these samples.

### Option 2: Tonic Fabricate

#### 1\. Open the website

Click this [Tonic Fabicate](https://fabricate.tonic.ai/ "Tonic Fabicate") link to open the website and interface.

This link opens in a new browser tab, and you should see a web page that looks similar to the following screen capture: ![](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/mrqkR_6MH2k6TrGfWjRfIQ/TF1.png)

#### 2\. Create an account

You can create an account on this website free of charge, or you can simply log in using your Gmail ID. After you log in, you'll see the following interface:

![](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/5u2lGG4mrEUmzsPELiq7nw/TF2.png)

#### 3\. Data Augmentation

This is a prompt-based tool that lets you customize synthetic data to meet your data science operational requirements. Upload the Insurance dataset using the **Attach a File** option and copy and paste the below prompt in the message box.

```
Generate a synthetic dataset based on the uploaded insurance data file. Preserve the original schema, column names, and data types. Maintain realistic distributions for key fields such as age, premium, policy type, claim amount, and tenure. Ensure logical relationships between variables (for example, higher age may correlate with higher premiums, and claim amounts should align with policy coverage). Avoid duplicates and unrealistic values. Generate clean, high-quality data suitable for analysis, ensuring synthetic data is statistically consistent with the source dataset and achieving approximately 80% similarity/accuracy. Create a dataset that is 1× the size of the original while introducing meaningful variations.

```

**_Note_**_: Synthetic data generation in this tool may take some time, so please be patient during the process._![](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/E8V9kJv8xLFW06BMojJq2w/TF3.png) Click `Send` to submit the prompt to initiate the process. ![](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/a2dyVEF7akV4tkuF_-8_AQ/TF4.png)

#### 4\. Download the synthetic data

Once the process is complete, you will be prompted with the message: **The data is ready for export or analysis. Would you like me to download it as a CSV?**. Type **Yes** to proceed with downloading the dataset. ![](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/xnFW5taTjVA_2cNK5fedaA/TF5.png) Click on `Download` to save the data to your local machine.

#### 5\. Analyze the report

This tool allows you to view details about the model used to generate the synthetic data.

Copy and paste the below prompt to see the report

```
Provide a detailed report on the model used for generating the synthetic data. Include information about the modeling approach, data distribution handling, and feature relationships learned. Also include performance metrics such as accuracy, AUC (Area Under the Curve), and any validation metrics used to assess the quality and similarity of the synthetic data relative to the original dataset. Present the report in a clear and structured format suitable for analysis.

```

After you give the prompt, you will see a detailed report along with visualizations. ![](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/sgT4jnxn_NP-89Y9euPlXg/TF6.png)

## Conclusion

Congratulations! You have completed the lab on data augmentation using iLoveCSV and Tonic Fabricate tools.

## Author(s)

Pooja Patel

> ![](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/nRmYgyM2KjRIIiG16R7ikg/ibmsn-footer-blue.png)

&nbsp;
