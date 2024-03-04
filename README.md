# Automatic Enrollment Bot

Nowadays, courses at universities tend to fill up before a student has the opportunity to enroll. With the automatic enrollment bot, students will have a tool to automate their enrollment process.

A student provides the bot with specific courses they'd like to monitor, and the bot will take care of everything else. When a course is full, the bot will continually monitor the status of that course until it becomes open. Upon opening, it will automatically enroll the student and send them a mobile notification upon successful enrollment.

## Disclaimer

The bot requires a user to provide their student information in a local text file. Although the text file is local, this is still unsafe. The bot was made for educational purposes and personal use. Before using the bot, please understand that you are using it at your own risk. If anything occurs, the developer takes no responsibility.

## Getting Started

1. You will need Python3 to run the bot.
2. Create two files and fill them out with your information: `user_information.txt` and `twilio_information.txt`.
3. Examine `start.py` and modify it based on your needs. Read the comments as they are important.
4. To start the bot, run the following script:

```bash
python3 start.py
```

**Note:** Before using the bot, ensure you have reviewed the code and understand the implications of automating the enrollment process. Usage may be subject to your university's policies, and the developer is not responsible for any consequences.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
