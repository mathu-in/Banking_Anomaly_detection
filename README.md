Business scenario
You are working for a banking company.

The bank processes thousands of transactions every day. Your responsibility is to identify suspicious transactions and flag them for investigation.

You receive historical transaction data that represents normal customer behaviour.

Later, new transactions arrive from customers.

Your ML model should identify whether each new transaction is normal or potentially anomalous.


Historical transaction data
Amount, transactions per hour
        |
        |
        v
Data preprocessing
Feature selection and scaling
        |
        |
        v
Train anomaly detection models
Isolation Forest, LOF, One-Class SVM, Elliptic Envelope
        |
        |
        v
New incoming transactions
Real-time or batch transaction data
        |
        |
        v
Normal/Anomaly

Normal : Allow normal transaction processing
Anomaly: Flag for further investigation