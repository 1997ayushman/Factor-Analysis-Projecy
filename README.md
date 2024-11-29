#### Purpose:
The notebook performs **Factor Analysis** (FA), focusing on dimensionality reduction and identifying key latent variables in a dataset. 

#### Key Components:
1. **Tests for Suitability**:
   - Bartlett’s Test: Checks if the correlation matrix is an identity matrix.
   - Kaiser-Meyer-Olkin (KMO) Test: Measures data adequacy for factor analysis (KMO < 0.5 is inadequate).

2. **Factor Selection**:
   - Uses the Kaiser criterion and scree plot based on eigenvalues to determine the number of factors.

3. **Analysis Workflow**:
   - Correlation Matrix
   - Factor Loading Matrix
   - Eigenvalues
   - Communalities & Uniqueness
   - Transforming Data
   - Checking Factor Independence

4. **Dataset**:
   Reads a CSV file titled "Dataset_Divorce.csv" for analysis.

---

### Key Findings:
- **Suitability Tests**:
  - Bartlett’s and KMO tests confirm the data’s adequacy for FA.
  
- **Factor Identification**:
  - Multiple factors are extracted and evaluated using eigenvalues and loadings.

- **Transformation**:
  - The data is transformed into independent factors, ensuring uncorrelated components for further analysis.

Would you like me to include anything else or further refine the details?
