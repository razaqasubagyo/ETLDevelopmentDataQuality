<h1>ETL Development: Data Quality</h1>


<h2>Overview</h2>
Implemented data quality techniques in Talend to cleanse, validate, and deduplicate data, ensuring accuracy and consistency within ETL workflows.
<br />


<h2>Key Highlights</h2>

- **De-Duplication:** Used the `tUniqRow` component to output both unique and duplicate records to the console for review. 

- **Schema Checking:** Used the `tSchemaComplianceCheck` component to validate whether the data source complied with a predefined schema, ensuring structural integrity before processing. 

- ** Replacing Data:** Used the `tReplace` and `tReplaceList` components to substitute invalid or inconsistent values with predefined data or values from an external list.

- **Interval Matching:** Used the `tIntervalMatch` component to match records based on defined value ranges, enabling range-based data mapping and classification.

- **Fuzzy Matching:** Used the `tFuzzyMatch` component to match data using the Levenshtein distance algorithm, configuring minimum and maximum distance thresholds to identify near-duplicate records. 


<h2>Skills </h2>

Talend Open Studio, Data Quality, Data Cleansing, Schema Validation, Data Deduplication, Fuzzy Matching.

<h2>Documentation:</h2>

<p align="center">
De-Duplication - Job Designer Workflow <br/>
<img src="https://github.com/user-attachments/assets/e8cb6571-3663-4244-b7ac-c1d3dee45797" height="80%" width="80%" alt="Schema Handling"/>
<br />
<br />
Schema Checking - Job Designer Workflow  <br/>
<img src="https://github.com/user-attachments/assets/2170240a-9409-43db-bfae-e8abfdc17cce" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Replace Data - Job Designer Workflow <br/>
<img src="https://github.com/user-attachments/assets/3375f8df-9edf-47db-a45e-7ca4e0239011" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Interval Matching - Job Designer Workflow  <br/>
<img src="https://github.com/user-attachments/assets/c6e96d54-e615-4aae-b720-b6e9e3daa568" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Fuzzy Matching - Job Designer Workflow & Results  <br/>
<img src="https://github.com/user-attachments/assets/ccee8585-4332-49fd-b4c4-71f78d7a0904" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
