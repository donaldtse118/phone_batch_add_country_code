# For who moved to another country

### In short..
A simple tool that help mass edit to add country code like +852 (Hong Kong), +44 (English) in Google contact. 
i.e. 99889988 -> +852 99889988

### Why I need this tool
Your contact might usually save your friends mobile nunmber **without** country code. It perfectly works fine when you in local. 
However, when you travel to another country or using a SIM card from other country. Your default country code do not apply, as the result you application like whatsapp able to regonize the contact stored

e.g. While you in HK, added a friend mobile 9988 9988 and stored a Google contact. As you are in HK, it works work fine. When you dial, no matter +852 9988 9988 or 9988 9988 (without country code), both case working fine. However, if you using a foreign SIM card like in UK. Whatsapp contact would treat the contact as +852 9988 9988 (with country code), which is not exist in your Google contact. Whatsapp cannot regonize this contact

To fix it, you need to add country code to each contact, or your might try this tool

- *Caution you might lost contact profile photo you added yourself*
- *Caution it might not work for contact more than 4 phone number entered*

## How this tool work
Just a simple python program, to country 

## Steps
1. Export contact from [contacts.google.com](https://contacts.google.com/) (export as Google CSV format), 
 - **!! Please backup !!**
 - **!! Please backup !!**
 - **!! Please backup !!**
2. Edit prefered country code to add. [I dunno my country code](https://countrycode.org/)
3. Run this notebook, upload the downloaded `contact.csv`
4. download the processed csv file `processed_contact.csv`
5. Visit Google contact and select all contact to delete (please bear the risk)
- *Caution you might lost contact profile photo you added yourself*
- *Caution it might not work for contact more than 4 phone number entered*
6. Import processed csv  
