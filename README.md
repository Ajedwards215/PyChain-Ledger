# Pychain Ledger

This project involved the development of a blockchain-based ledger system with a user-friendly web interface for conducting financial transactions between partner banks and verifying the integrity of the data in the Ledger. The project was undertaken by a fintech engineer who was prompted to act as the lead developer on a decentralized finance team at one of the five largest banks in the world. The engineer made several updates to an existing Python file, which already contained the basic PyChain ledger structure created throughout the module.

The updates included

 -Creating a new data class named Record.

 -Modifying the existing Block data class to store Record data.

-Adding relevant user inputs to the Streamlit interface. 

-Testing the PyChain Ledger by storing records. 

The Record data class was created with a formalized data structure that consisted of sender, receiver, and amount attributes. The data attribute in the Block class was renamed to record, and its data type was set to Record.
Additional input areas were added to the Streamlit interface to capture the sender, receiver, and amount for each transaction stored in the Block record. The updated Block consisted of an attribute named record set equal to a Record containing the sender, receiver, and amount values. The updated Block also included attributes for creator_id and prev_hash.
The complete PyChain Ledger and user interface were tested by running the Streamlit application and storing mined blocks in the PyChain Ledger. The blockchain validation process was also tested using the web interface.
