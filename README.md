# Blockchain_Ledger

This project consists of creating a blockchain-based ledger system with a user-friendly web interface using Python. 

Within the code, a new data class named Record was created that was able to save formalized data such as "sender", "receiver" and "amount" as attributes. Then, the "data" attribute within the Block class was renamed to "record". Last but not least, the Streamlit Interface code was modified to include user inputs for "sender", "receiver", and "amount" on the web app.  

Once the py file was ready, it was testing by running it through Streamlit. Values were entered for the "sender", "receiver", and "amount" attributes several times to store several blocks in the blockchain ledger. The block's contents and hashes were verified on the webapp. Down below includes a screenshot of the block's contents: 

<img width="1046" alt="Screenshot 2022-10-21 200710" src="https://user-images.githubusercontent.com/104874384/197307098-52b1037b-7532-4f9d-882f-0bb762766f2a.png">

Finally, the blockchain was validated, see screenshot below:

<img width="1109" alt="Screenshot 2022-10-21 201002" src="https://user-images.githubusercontent.com/104874384/197307108-7311e203-beb5-4d1e-81eb-5d286543ddb6.png">
