    This project is an Anti-Money Laundering (AML) risk scoring system built from transaction-level data. It is designed to identify potentially suspicious financial behavior using engineered behavioral patterns and risk-based features.
The goal is to generate interpretable risk scores using transaction behavior rather than treating the model as a black box.

⸻
Project Objectives:
* Detect suspicious transaction behavior
* Build a structured AML risk scoring framework
* Engineer behavioral features from raw transaction data
* Improve interpretability of risk signals

⸻
Features Engineered:
The model includes several behavioral and statistical features such as:
* Fan-out (number of unique receivers per sender)
* Fan-in (number of unique senders per receiver)
* Transaction count and activity span
* Total sent and total received amounts
* Sent percentile (relative transaction intensity)
* Sent log (log-transformed transaction values)
* Laundering rate and laundering indicators

⸻
Risk Scoring Approach:
Risk scores are derived from a combination of behavioral indicators and scaled percentiles of transaction activity.
Each sender account is assigned a risk category based on its overall behavior profile:
* Low Risk
* Medium Risk
* High Risk
* Critical Risk

⸻
Current Status
* AML risk table has been successfully built
* Feature engineering is completed
* Risk scoring has been implemented
* Pattern explanation layer is currently in progress
