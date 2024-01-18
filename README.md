# 🧱🔨 Cement Strength Prediction Project
**Brief:** A **Cement Strength Prediction Project** involves the development of models or algorithms to predict the strength of cement based on various factors and parameters. Cement strength is a crucial property in construction, as it directly influences the durability and performance of concrete structures. Predicting cement strength can help optimize the concrete mix design process, ensuring that the final product meets the required specifications and standards.


**Data Description:**

1. **Cement (component 1):**
   - **Data Type:** Quantitative
   - **Measurement Unit:** kg/m3 (kilograms per cubic meter)
   - **Description:** Represents the amount of cement in a cubic meter of the concrete mixture.

2. **Blast Furnace Slag (component 2):**
   - **Data Type:** Quantitative
   - **Measurement Unit:** kg/m3
   - **Description:** Indicates the quantity of blast furnace slag in a cubic meter of the concrete mixture.

3. **Fly Ash (component 3):**
   - **Data Type:** Quantitative
   - **Measurement Unit:** kg/m3
   - **Description:** Specifies the amount of fly ash in a cubic meter of the concrete mixture.

4. **Water (component 4):**
   - **Data Type:** Quantitative
   - **Measurement Unit:** kg/m3
   - **Description:** Represents the volume of water in a cubic meter of the concrete mixture.

5. **Superplasticizer (component 5):**
   - **Data Type:** Quantitative
   - **Measurement Unit:** kg/m3
   - **Description:** Signifies the quantity of superplasticizer in a cubic meter of the concrete mixture. Superplasticizers are additives used to improve the flow of concrete.

6. **Coarse Aggregate (component 6):**
   - **Data Type:** Quantitative
   - **Measurement Unit:** kg/m3
   - **Description:** Denotes the amount of coarse aggregate (e.g., gravel) in a cubic meter of the concrete mixture.

7. **Fine Aggregate (component 7):**
   - **Data Type:** Quantitative
   - **Measurement Unit:** kg/m3
   - **Description:** Represents the quantity of fine aggregate (e.g., sand) in a cubic meter of the concrete mixture.

8. **Age:**
   - **Data Type:** Quantitative
   - **Measurement Unit:** Days (1~365)
   - **Description:** Reflects the curing time of the concrete in days, indicating the duration between the preparation of the mixture and the assessment of compressive strength.

9. **Concrete Compressive Strength:**
   - **Data Type:** Quantitative
   - **Measurement Unit:** MPa (Mega Pascal)
   - **Description:** The target variable for the regression problem, representing the compressive strength of the concrete in Mega Pascals.


**Summary of the above Paragraph:**

Given is the variable name, variable type, the measurement unit and a brief description. The concrete compressive strength is the regression problem. The order of this listing corresponds to the order of numerals along the rows of the database.

**Name** -- **Data Type** -- **Measurement** -- **Description**

- Cement (component 1) -- quantitative -- kg in a m3 mixture -- Input Variable

- Blast Furnace Slag (component 2) -- quantitative -- kg in a m3 mixture -- Input Variable

- Fly Ash (component 3) -- quantitative -- kg in a m3 mixture -- Input Variable

- Water (component 4) -- quantitative -- kg in a m3 mixture -- Input Variable

- Superplasticizer (component 5) -- quantitative -- kg in a m3 mixture -- Input Variable

- Coarse Aggregate (component 6) -- quantitative -- kg in a m3 mixture -- Input Variable

- Fine Aggregate (component 7) -- quantitative -- kg in a m3 mixture -- Input Variable

- Age (Represents the curing time of concrete in days) -- quantitative -- Day (1~365) -- Input Variable

- Concrete compressive strength -- quantitative -- MPa(Mega Pascal) -- Output (Target) Variable



#### Dataset is taken from Kaggle and stored in mongodb


💿 Installing
1. Environment setup.
```
conda create -p venv python==3.9 -y
```
```
conda activate venv/
````
2. Install Requirements and setup
```
pip install -r requirements.txt
```
3. Run Application
```
python app.py
```

🔧 Built with
- fastapi
- Python 3.9
- Machine learning
- Scikit learn
- 🏦 Industrial Use Cases
