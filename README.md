# Assignment-3---BornToSurvive-How to Run



# First Step-Link for access 
setup ganache and link to metamask



# 2nd step-create nft tokens
- open the /nft_factions/amarr then run through all relevant slides, meaning: 
- update .env with relative files 
- run the relative .sol files in remix
- update .json with update and personalised ABI upon completion of combile function in remix 
- deploy file then select second option "registerArtwork": select account info and place relative URL provided in file /resources/photourl 
- now run the relative file via "streamlit run ,,,.py" with relative file i.e: "streamlit run scout.py"
- Repeat now 3 times for the remaining three nft's left
- Congratulations you've now finished the creation of the four seperate base NFTS 



# 3rd step - run marketplace 
- run the BTScoin/contract/BTStoken.sol in remix
- collect and update the BTScoin/contract/compiled/bts_abi.json file with relative abi code from running in remix
- now update .env file loacted inside assignment_3/Marketplace/.env
- now is the fun part, run the bts_marketplace by the following code "streamlit run bts_marketplace.py"
- now enjoy the virtual marketplace note of errors encountered in marketplace; you can only see the pictures per category once per loading of the streamlit app. 
