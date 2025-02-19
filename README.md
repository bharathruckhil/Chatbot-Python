# ChatterBot: Build a Chatbot with Python

This repository contains code related to the tutorial on [building a Python chatbot with ChatterBot]((https://bharathruckhil.framer.website/)).

Create and activate a [virtual environment](https://bharathruckhil.framer.website/), then install the necessary dependencies:

```sh
$ python -m venv venv
$ source venv/bin/activate
(venv) $ python -m pip install -r requirements.txt
```

Then you can navigate into the folder `source_code_final/` and train and start the interactive command-line interface chatbot by running `bot.py`:

```sh
(venv) $ cd source_code_final
(venv) $ python bot.py
```

After training, you'll see an interactive prompt that you can chat with:

```text
> hi
🪴 Welcome, friend 🤗
> thanks for visiting
🪴 
```

The bot will learn from the replies you give and improve its accuracy. You can quit the interactive prompt by typing any of the `exit_conditions` defined in `bot.py`.

You'll find the code for each step of the tutorial in a separate folder. The folders also include a SQLite database that contains the different phases of training at each step. Because of this, you can inspect the project at different stages and notice how it evolves when you add more data and interactions.
