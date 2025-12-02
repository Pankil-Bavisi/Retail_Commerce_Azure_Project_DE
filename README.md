# Azure Retail Commerce Data Engineering Project
<html>
  <h2 tabindex="-1"><a aria-hidden="true"></a>  
<!--     tabindex="-1"><a aria-hidden="true" -->
    Introduction:
  </h2>
  <p dir="auto">
    <br style="display: block; margin:10px 0; content=''; ">
    <p style="margin-top: 0px; text-size: 50px;" dir="auto">The objective of this Retail Commerce Data Engineering project is to help the client ingest and centralize diverse Retail Data from multiple sources—including Azure Data Lake Storage Gen2, Amazon S3, and Azure SQL Database—into a unified platform.</p>
    <p>The project implements an enterprise-grade data pipeline capable of performing rigorous validation checks on incoming vendor files.</p>
    <p>Key validations include ensuring that order_id values are unique and that order_status values match the valid statuses defined in the Lookup Table stored in Azure SQL Database.</p>  
  <ul>
      <li>Files failing validation are automatically routed to the Discarded folder.</li>
      <li>Files meeting all criteria are moved to the Staging folder for further processing.</li>
  </ul>
  <p>In addition to data ingestion and validation, the project delivers analytical capabilities to derive meaningful metrics and insights from growing Retail Commerce datasets using modern Big Data technologies and a wide range of Azure cloud services.</p>
  <p>This repository presents a full end-to-end workflow of the project, detailing the complete architecture, implementation processes, and the Azure services leveraged throughout the solution.</p>
  </p>
  
  <!-- <h2>Architecture:</h2> -->
  <!-- <p dir="auto">
    <a href="https://github.com/Pankil-Bavisi/HC_Azure_Project_DE/blob/main/images/Architecture.png">
      <img id="architecture" src="https://github.com/Pankil-Bavisi/HC_Azure_Project_DE/blob/main/images/Architecture.png" style="margin-top: 0px; text-size: 50px;"> </img>
    </a>
  </p> -->
  
  <h2>Technology Used</h2>
    <ul>
      <li>Programming Language: Python, SQL, PySpark</li>
      <li>Big Data Processing: Apache Spark</li>
    </ul>
    <p>==) Amazon Cloud Services:</p>
    <ol>
      <li>Amazon S3</li>
    </ol>
    <p>==) Azure Cloud Services:</p>
    <ol>
      <li>Azure Storage Account(ADLS Gen2)</li>
      <li>Azure SQL Database</li>
      <li>Linked Service</li>
      <li>Azure Key Vault</li>
      <li>Azure Databricks</li>
      <li>Azure Data Factory</li>
      <li>ADF: Storage Event Trigger</li>    
    </ol>
    <p>==) Other Functionalities:</p>
    <ol>
      <li>Made the code generic</li>
      <li>Read the filename dynamically rather than hardcoding - leveraging 'parameterized approach'</li>
      <li>Pushed the result to Azure SQL DB for the 'Reporting and BI Team'</li>
      <li>Implemented naming conventions & folder structure</li>
    </ol>
      
  <h2>Dataset Used</h2>
    <p dir="auto">Retail Ecommerce Dataset contains various areas of data such as Orders, Customers, Order_items, Products, Departments, Categories, etc.</p>
    <!-- <p>Here is the dataset used in the project - <a href="https://github.com/Pankil-Bavisi/HC_Azure_Project_DE/blob/main/datasets">https://github.com/Pankil-Bavisi/HC_Azure_Project_DE/blob/main/datasets</a></p> -->
    
  <!-- <h2>Data Model</h2> -->
  <!-- <p>
    <a href="https://github.com/Pankil-Bavisi/HC_Azure_Project_DE/blob/main/images/DataModel.png">
      <img id="architecture" src="https://github.com/Pankil-Bavisi/HC_Azure_Project_DE/blob/main/images/DataModel.png"></img>
    </a>
  </p> -->
  
  <h2 tabindex="-1" dir="auto">End of Project</h2>
  <p dir="auto">Keep Learning, Keep Going | Be Strong | Never Give Up</p>
  
</html>

