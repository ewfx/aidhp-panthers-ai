# GenAI Recommendations System

This project demonstrates the generation of customer data and their inquiries using the Faker library. The generated data is then used to create a recommendation system using ChromaDB and LangChain.

## Files

- `GenAI_Recommendations.ipynb`: Jupyter notebook containing the code to generate customer data and build the recommendation system.
- `products_info.csv`: CSV file containing the generated customer data.

## Setup

1. Install the required libraries:
    ```bash
    pip install faker pandas numpy chromadb langchain langchain-community langchain-core transformers sentence-transformers bitsandbytes accelerate streamlit openai
    ```

2. Open the `GenAI_Recommendations.ipynb` file in Jupyter Notebook or JupyterLab.

## Usage

1. Run the cells in the notebook sequentially to generate the customer data and build the recommendation system.
2. The generated data will be saved in the `products_info.csv` file.

## Data Description

### Customer Data
- `Customer ID`: Unique identifier for the customer.
- `Age`: Age of the customer.
- `Gender`: Gender of the customer.
- `Marital Status`: Marital status of the customer.
- `Income Level`: Income level of the customer.
- `Education`: Education level of the customer.
- `Occupation`: Occupation of the customer.
- `Residential Status`: Residential status of the customer.
- `Dependents`: Number of dependents.
- `Debt-to-Income`: Debt-to-income ratio.
- `Credit_Bureau`: Credit bureau score.

### Inquiries
- `last_3months_personal_loan_inq`: Whether the customer made a personal loan inquiry in the last 3 months.
- `last_3months_credit_card_inq`: Whether the customer made a credit card inquiry in the last 3 months.
- `last_3months_mortgage_inq`: Whether the customer made a mortgage inquiry in the last 3 months.
- `last_6months_personal_loan_inq`: Whether the customer made a personal loan inquiry in the last 6 months.
- `last_6months_credit_card_inq`: Whether the customer made a credit card inquiry in the last 6 months.
- `last_6months_mortgage_inq`: Whether the customer made a mortgage inquiry in the last 6 months.

## License


## 👥 Team
- **Poonam** - [GitHub](#) | [LinkedIn](#)
