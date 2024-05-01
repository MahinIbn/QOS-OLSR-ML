# QOS-OLSR3.0-ML

Version Highlights:
1. ML Model: GRU with a convolutional layer.
2. Inputs to the ML model: LQ, NLQ, RSSI, Trend, Tau.
3. The ML model was converted to C using the keras2c library and is completely integrated into the QoS-OLSR 3.0.
4. The probability (ML models output) is propagated through valueBandwidth.
5. Trend and tau based link cost calculations are completely removed.
6. A more dynamic cost mechanism based on ML models' output is used for link cost calculation.
7. This protocol uses the updated JSON plugin, which we modified to include trend, tau, and RSSI in the JSON. 

The fully integrated protocol code is uploaded to the following drive:
https://drive.google.com/drive/folders/1Vq2ZIo1l35SNdCCQ8pD94iBKUHtsEW_l?usp=sharing
