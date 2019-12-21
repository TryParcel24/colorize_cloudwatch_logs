Colorize CloudWatch Logs
========================

This is a Google Chrome extension. You can install this extension by this address: [Chrome Web Store](https://chrome.google.com/webstore/detail/colorize-cloudwatch-logs/fkagnmcbeokmapmcbecbcmpccmlbhkpl).

The purpose of this extension is to group visually the logs on AWS CloudWatch. There are three rules:
- Set a different background color for each log group of AWS Lambda invocation. Therefore, you can easily recognize beginning, body and end of the logs of the same invocation.
- Set font wieght of lines having `[REPORT]` and `[ERROR]` keywords to bold.
- Set color of ANSI terminal codes in the logs. (by [@oguimbal](https://github.com/oguimbal))

This extension doesn't collect any user and webpage information. It only runs on AWS CloudWatch Logs webpage. It is free to use.

Overhead is very low, colorize operation takes 10 milliseconds, listen operation for new event logs takes just 0.5 milliseconds in every second.

Contributions are welcome. Please follow the standart.js convention if you want to contribute.