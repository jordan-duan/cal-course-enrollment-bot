# UC Berkeley Course Enrollment Bot

Hey there! 😊 Enrolling in UC Berkeley courses can be a bit of a race sometimes, right? No worries! I've got your back with this handy enrollment assistant.

## Prerequisites

First things first, make sure you have Python installed on your machine. Then, run the following command to install the required dependencies:

```bash
pip install -r requirements.txt
```
OR

```bash
pip install python-dotenv
pip install selenium

```

Oh, and don't forget to download the appropriate web driver (GeckoDriver or ChromeDriver) and pop it into the project folder. Easy peasy!

## Configuration

1. Now, copy `env_example` to a new file called `.env`.
2. Open up `.env` and toss in your UC Berkeley username and password like you're making a secret sauce:

```env
USERNAME="CALNETID"
PASSWORD="CALNETPW"
```

3. Adjust the `target_time` variable in the `main.py` script to your enrollment time. Trust me, it's a piece of cake with the format provided.

## Preparation

Load up your shopping cart with all the classes you want to enroll in. It's like online shopping, but for your brain!

## Let's Roll!

Finally, kick off the magic with this command:

```bash
python3 main.py
```

Now, grab a snack, sit back, and relax. Your enrollment will be done within 9 seconds of your enrollment time starting! 🚀

**Note:** Take a peek at the code if you're into that sort of thing, and remember, use this responsibly and be aware of your university's policies. I'm just here to make your life a bit easier!

Happy enrolling! 📚✨
