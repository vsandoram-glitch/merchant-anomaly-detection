# Merchant Anomaly Monitor — Streamlit deployment

Deploy `streamlit_app.py` on Streamlit Community Cloud.

Repository contents:
- `streamlit_app.py` — app entry point (defaults to Streamlit app mode)
- `requirements.txt` — Python dependencies
- `outputs/daily_sales_prepared.csv`
- `outputs/business_daily_prepared.csv`
- `outputs/merchant_risk.csv`

The hosted demo uses the prepared outputs. To enable the **Run / Refresh Analysis** button, also add these original source files to the repository root:
- `Transactions.csv`
- `merchant.csv`
- `business.csv`
- `status.csv`

Optional new-dataset files can also be added for batch modelling:
- `Transactions_New.csv`
- `merchant_New.csv`
- `business_New.csv`
- `status_New.csv`
