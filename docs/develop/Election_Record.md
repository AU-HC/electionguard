### Election Record

The Election Record are the files required at the end of the election to verify the election and are intended to be posted publicly. There should not be any sensitive data (eg: no guardian private keys) in the record. These include the following:

- Encryption Devices Information
- Guardian Records
- Decrypted Spoiled Ballots
- Encrypted Submitted Ballots
- Lagrange Coefficients Record
- Election Constants
- Election Context
- Encrypted Tally
- Manifest
- Decrypted Tally

## Folder Structure

The Election Record should be expected to be a zip folder containing the following information. 

```
📂 record
--- 📁 encryption_devices
------- 📄 device_id_1.json
------- 📄 device_id_2.json
------- ...
--- 📁 guardians
------- 📄 guardian_id_1.json
------- 📄 guardian_id_2.json
------- ...
--- 📁 spoiled_ballots
------- 📄 spoiled_ballot_id_3.json
------- 📄 spoiled_ballot_id_4.json
------- ...
--- 📁 submitted_ballots
------- 📄 submitted_ballot_id_1.json
------- 📄 submitted_ballot_id_2.json
------- ...
--- 📄 coefficients.json
--- 📄 constants.json
--- 📄 context.json
--- 📄 encrypted_tally.json
--- 📄 manifest.json
--- 📄 tally.json
```