# Visualizing Healthcare: Insights from Nursing Home Data Analysis
## Overview
The healthcare sector is among the top industries in which data is continuously growing and kept
in documents. By examining these documents, numerous forecasts, better decision-making, patient satisfaction, and
optimal health outcomes can all be achieved. Visualizing healthcare data is a crucial first step to improving
patient care, identifying trends, detecting fraud and errors within healthcare organizations, and enabling
medical staff to interpret data analytics results more quickly. Healthcare data visualization is done using a variety of tools, such as Tableau,
Power BI, d3js, plotty, etc. The data is displayed using dashboards, charts, graphs, geographic
maps, and other visual representations.
## Why it is Interesting and Challenging
The numerous advantages healthcare data visualizations provide for healthcare professionals
make them interesting and challenging. Among the advantages are:
- **Patient care:** The ability to visualize medical data will help healthcare professionals
make clinical decisions and make it easier for them to foresee and respond to possible
risks. To facilitate this process, patient data can be used to raise the standard of
care, spot uncommon trends in reports on patient data, and make critical clinical
decisions about the enhancement of overall patient health.
- **Recognising disease trends:** Users can understand better how a particular disease
affects a group of people by using visualizations that highlight differences between the
affected individuals. Making decisions about preventative measures and lifestyle
adjustments as a result will contribute to reducing the impact of disease spreading among
individuals and themselves.
- **Improving Intelligibility:** Individuals needing a medical background may find it challenging
to comprehend the complexity of healthcare data. Thus, without considering a person's background, visualizations can, at times, assist in understanding complex
health data, making the information valuable and available to everyone.
This idea is very interesting because of the additional benefits, which include enhanced
healthcare performance and fraud detection. The complexity of this topic is increased by applying machine learning algorithms to identify relevant patterns and generate appropriate
predictions.

## Dataset and Data Preprocessing
### Description
1. **Provider Number:** The 6-digit identification number for the home health agency on the
claim.
2. **Agency Name:** The home health agency name reported in the POS file.
3. **Street Address:** The home health agency address reported in the POS file.
4. **City:** The city where the home health agency is located, as reported in the POS file.
5. **State:** The state where the home health agency is located, as reported in the POS file.
6. **Zip Code:** The home health agency’s zip code, as reported in the POS file.
7. **Total Episodes (Non-LUPA):** Total count of non-LUPA episodes provided by a specific
home health agency or in a unique HHRG category in the calendar year.
8. **Distinct Users (Non-LUPA):** Number of distinct Medicare beneficiaries receiving at least
one non-LUPA home health episode in the calendar year.
9. **Total HHA Charge Amount (Non-LUPA):** Total charges the home health agency
submitted for non-LUPA episodes.
10. **Total HHA Medicare Payment Amount (Non-LUPA):** Total amount that Medicare paid
for non-LUPA episodes. Home health services do not have any cost-sharing.

### Cardinality:
Certification Number: 6 digits.
Agency Name, Street Address, City: Variable alphanumeric.
State: Two-letter postal abbreviation.
Zip Code: Numeric.
Total Episodes, Users, Charges, Medicare Payments: Numeric.

#### Attributes for Visualization and Types:
- Relevant attributes for visualization include provider_id, agency_name, street_address,
city, state, zip_code, etc.
- Attribute types range from numerical to Variable. Most of them are numerical values.
- 
### Dataset Preprocessing
- The dataset contains no missing values. As a result, computation or dropping of missing
values is not required. The dataset is prepared for further analysis and representation.
- If there were missing values, the two most common ways to deal with them are dropping
rows/columns containing missing values and computation, which replaces missing values
with a calculated or estimated value. One way to substitute data is using the
corresponding column's mean, median, or mode to replace missing values.

### Data Collection
- As the characteristics for the visualization questions we selected are already included in
the dataset, which we don't intend to change; no additional data is required for this
project.
- As it is a healthcare dataset, permissions from healthcare authorizations may be necessary
if we want to gather accurate data. Collection methods such as online surveys, online
reports and documents, etc., would be great for this data if collecting data becomes
mandatory in the future
