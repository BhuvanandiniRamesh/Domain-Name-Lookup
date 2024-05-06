# Objective:
The objective of this project is to enrich domain names with associated company names and VAT numbers.

# Background:
Often, domain names are not directly associated with the owning company or its VAT number. This information can be valuable for various purposes such as business analysis, compliance, or customer relationship management. However, obtaining this data can be challenging as domain registrars do not typically provide such information publicly.

# Data Sources:
A dataset containing information about companies registered in Norway, including organizational number, company name, registration date, and website. A free resource for looking up companies in Norway, though no domain lookup. https://data.brreg.no/enhetsregisteret/api/docs/index.html#introduksjon

A list of domain names.

# Approach:
We aim to connect domain names with company information using the available datasets. This will involve matching domain names from the list to the corresponding websites in the company dataset. Once matched, we can retrieve the associated company name and organizational number. Additionally, we may need to consider the registration date to ensure the accuracy of the mapping, especially in cases where a domain may have changed ownership over time.

# Challenges:
Matching domain names to websites accurately, considering variations in domain formats and website URLs.
Handling cases where multiple companies may share the same domain name or where a domain may have changed ownership.
Ensuring the reliability and completeness of the company dataset, as missing or incorrect information may affect the accuracy of the mapping.

# Deliverables:
The final output of this project will be a dataset containing enriched domain names with associated company names and organizational numbers. This dataset will provide valuable insights for various stakeholders, including researchers, businesses, and regulatory authorities.

# Description:
This project aims to enrich domain names with associated company information, including company names and organizational numbers (VAT numbers). By connecting domain names to registered companies, the dataset becomes valuable for various applications such as business analysis, compliance, and customer relationship management.

# Datasets Used:
Company Dataset: Contains information about registered companies in Norway, including organizational numbers, company names, registration dates, and websites.
Domain List: A list of domain names for which we seek to find associated company information.

# Approach:

# Data Preprocessing:
Clean the company dataset by removing irrelevant columns and handling missing values.
Standardize website URLs to ensure consistency for matching.

# Data Matching:
Match domain names from the domain list to corresponding websites in the company dataset.
Consider variations in domain formats and website URLs for accurate matching.
Utilize registration dates to verify the accuracy of mappings.

# Output Generation:
Produce a final dataset containing enriched domain names with associated company names and organizational numbers.
Ensure data integrity and completeness in the final output.

# Challenges:
Handling variations in domain formats and website URLs during matching.
Dealing with cases of multiple companies sharing the same domain name or domain ownership changes.
Ensuring the reliability and completeness of the company dataset for accurate mapping.

# Deliverables:
A final dataset containing enriched domain names with associated company names and organizational numbers.
Documentation detailing the data preprocessing steps, matching approach, and challenges encountered during the project.

# Dependencies:
Python libraries used in this project include pandas, numpy, and re for data manipulation and regex operations.

