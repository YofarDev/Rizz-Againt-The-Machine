
# Rizz Againt The Machine

A small game based on LLMs. [Play it for free](https://rizzatm.web.app/).

Earn or lose points based on your rizz (points are arbitrarily assigned by the LLM, so I don't think it's esport ready).



<p align="center">
  <img src="image/README/1721656715690.png" width="48%" />
  <img src="image/README/1721656670448.png" width="48%" />
</p>

**Warning : it contains NSFW assets (nothing crazy).**

## Features

Choose from multiple LLM models (your local models via Ollama, or the most popular ones via API).

<p align="center">
  <img src="image/README/1721656490980.png" width="50%" />
</p>


Quality of the game will be affected by the quality of the LLM model and its capabilities to follow the system prompts and stay in character.

Except for the clouded models, anything else is local and all information is stored in cache.

There are different expressions the avatar can display based on the interactions, and some hidden actions (like moving from a place to another).

Desktop version and Android version may be available soon.

## Demo Video on YouTube

[![Demo Video](https://img.youtube.com/vi/jKWzCjDpbtY/0.jpg)](https://www.youtube.com/watch?v=jKWzCjDpbtY)

## How to Run

### MacOS

1. Download the latest MacOS release from the [releases page](https://github.com/YofarDev/Rizz-Againt-The-Machine/releases/).
2. Extract the archive and run the application.

### Linux

1. Download the latest Linux release from the [releases page](https://github.com/YofarDev/Rizz-Againt-The-Machine/releases/).
2. Extract the archive.
3. Make sure the executable has the proper permissions:
    ```sh
    chmod +x rizz_against_the_machine
    ```
4. Run the application:
    ```sh
    ./rizz_against_the_machine
    ```

### Android

1. Download the latest Android release from the [releases page](https://github.com/YofarDev/Rizz-Againt-The-Machine/releases/).
2. Open the APK with your android device to install the application.

### Windows

TODO

## Issues

- Ollama is currently not working with the web version (CORS error).
- I have not tested Anthropic and OpenAI APIs so maybe it doesn't work you tell me.