# SMH-DCTOOL
This is Discord multi-tool that can grab IP,Brute_Force Nitro Code,Webhook Spam,MassDM. This Tool is created by MejbanKadir, My Youtube Channel name is "Believe Me I'M Not a Programmer("https://youtube.com/@not_a_programmer69?si=k6Yb5pYqsPZXlEWR") 

# DCTOOL - Discord Utility Tool

![Screenshot 2025-02-04 144014](https://github.com/user-attachments/assets/287deb59-9ebb-4aaf-8ca3-8d56604e3e65)



## Overview
DCTOOL is a versatile console application designed to provide various utilities for Discord users. It offers a range of features that can assist in managing and interacting with Discord more effectively. Whether you're looking to send messages via webhooks, generate and check Nitro codes, or manage direct messages, DCTOOL has you covered.

## Features
1. **Webhook Message**: Send a single message to a Discord channel using a webhook URL.
2. **Webhook Spammer**: Send multiple messages to a Discord channel using a webhook URL.
3. **Nitro Code Generator and Checker**: Generate and validate Discord Nitro codes.
4. **IP Grabber**: Start a local server to capture IP addresses of visitors.
5. **Token Grabber**: Retrieve and display user information using a Discord token.
6. **Mass Direct Messaging (DM)**: Send a single message to multiple Discord users simultaneously.

## Usage
### Webhook Message
1. Enter the webhook URL.
2. Enter the message you want to send.
3. The message will be sent to the specified Discord channel.

### Webhook Spammer
1. Enter the webhook URL.
2. Enter the message you want to send.
3. Specify the number of times you want to send the message.
4. The messages will be sent repeatedly to the specified Discord channel.

### Nitro Code Generator and Checker
1. Choose the length of the Nitro code.
2. The application will generate and check Nitro codes.
3. Valid codes will be saved in `working_codes.txt`.
4. Invalid codes will be saved in `not_working_codes.txt`.

### IP Grabber
1. Enter the port to listen on (default is 8080).
2. Share the generated URL with the target.
3. The application will capture the IP addresses of visitors and save them in `captured_ips.txt`.

### Token Grabber
1. Enter the Discord user token.
2. The application will retrieve and display user information associated with the token.

### Mass Direct Messaging (DM)
1. Enter your Discord token.
2. Enter the message you want to send.
3. Provide the path to a file containing user IDs.
4. The application will send the message to all specified users.

## Important Notes
- **Rate Limits**: Be aware of Discord's rate limits to avoid restrictions.
- **Token Security**: Never share your Discord token. A compromised token can put your account at risk.
- **Permissions**: Ensure you have the necessary permissions to perform actions like sending DMs.

## Troubleshooting
- **Invalid Token**: Verify that the token is correct.
- **File Not Found**: Ensure the file path is correct.
- **Failed Messages**: Verify that users haven't blocked you and that their IDs are correct.
- **Rate Limit Errors**: Increase the delay between messages in the code if rate-limited.

## Example User IDs File
Save the following in a text file (e.g., `user_ids.txt`):
```
123456789012345678
987654321098765432
112233445566778899
```

## Example Usage
1. Launch DCTOOL.
2. Select the desired feature from the menu.
3. Follow the on-screen instructions to use the feature.

## Disclaimer
This tool is intended for educational and legitimate purposes only. Misuse of this tool for malicious activities is strictly prohibited. The developers are not responsible for any misuse or damage caused by this tool.

## Support
For any issues or support, please contact the developer.

---

Enjoy using DCTOOL!
