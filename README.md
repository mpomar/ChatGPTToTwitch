<a name="readme-top"></a>

<!-- PROJECT SHIELDS -->
[![Language][language-shield]][language-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![LinkedIn][linkedin-shield]][linkedin-url]
[![Twitter][twitter-shield]][twitter-url]

<!-- PROJECT LOGO & HEADER -->
<br />
<div align="center">
  <a href="https://github.com/mpomar/ChatGPTToTwitch">
    <img src="https://cdn-cjmik.nitrocdn.com/UjszoEMIGzQLBmRYICliaPmdTnvQlovN/assets/images/optimized/rev-036ec8e/www.aalpha.net/wp-content/uploads/2020/11/ChatBot_ace-1.gif" alt="Logo" width="80">
  </a>

  <h3 align="center">ChatGPT to Twitch</h3>

  <p align="center">
    Twitch chatbot to interact with ChatGPT in your channel!
  </p>
</div>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#about-the-project">About The Project</a></li>
    <li><a href="#prerequisites">Prerequisites</a></li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>

<!-- BODY -->
## About The Project

[FootballChatbot](https://github.com/mpomar/FootballChatbot) marked my initial venture into developing a Twitch chatbot. Motivated by the extensive use of ChatGPT, I felt compelled to embark on creating a new Twitch chatbot. The functionality is straightforward: upon executing the script, the bot joins the designated Twitch channel and monitors the chat activity. When the `!ai` command is utilized followed by a ChatGPT prompt, the bot promptly shares the generated response in the chat.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Prerequisites

* Install Python and add to PATH
* Create and activate virtual environment
* Clone or download the repository
* Install all dependencies 
* Create an account on Open AI
* Get your API key from [here](https://platform.openai.com/api-keys)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Usage

- Define the required variables in config.py 
  - username: This is the bot's username on Twitch 
  - oauth_token: This represents the Oauth Token of the Twitch bot
  - channel: Indicate the Twitch channel that the bot will join
  - openai.api_key: The Open API Key required for connecting to Open AI
- You may also wish to adjust certain Open AI parameters:
  - model: This determines the model Open AI will utilize to generate responses 
  - temperature: This influences the creativity of the answers. I've set it to 0.3 to ensure informative responses rather than overly creative ones
  - max_tokens: This parameter controls the length of the answers. I've set it to 20 to maintain concise responses, keeping in mind that Open AI charges more for longer answers.
- Run main.py to launch the bot

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Contributing

Any contributions are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request:

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request 

You can also simply open an issue with the tag "enhancement".

Don't forget to give the project a star! 🌟

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Contact

M. Pomar - [@deliverymgt](https://twitter.com/deliverymgt) - m.pomar@outlook.com

Project Link: [https://github.com/mpomar/ChatGPTToTwitch](https://github.com/mpomar/ChatGPTToTwitch)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Acknowledgments


* [Twitch](https://twitch.tv/)
* [ChatGPT](https://chat.openai.com/)
* [Shields.io](https://shields.io)
* [Best-README-Template](https://github.com/othneildrew/Best-README-Template)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- MARKDOWN LINKS & IMAGES -->
[language-shield]: https://img.shields.io/github/languages/top/mpomar/ChatGPTToTwitch?style=for-the-badge
[language-url]: https://github.com/mpomar/ChatGPTToTwitch
[forks-shield]: https://img.shields.io/github/forks/mpomar/ChatGPTToTwitch?style=for-the-badge
[forks-url]: https://github.com/mpomar/ChatGPTToTwitch/network/members
[stars-shield]: https://img.shields.io/github/stars/mpomar/ChatGPTToTwitch?style=for-the-badge
[stars-url]: https://github.com/mpomar/ChatGPTToTwitch/stargazers
[issues-shield]: https://img.shields.io/github/issues/mpomar/ChatGPTToTwitch?style=for-the-badge
[issues-url]: https://github.com/mpomar/ChatGPTToTwitch/issues
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/manfredipomar
[twitter-shield]: https://img.shields.io/badge/-Twitter-black.svg?style=for-the-badge&logo=twitter&colorB=555
[twitter-url]: https://twitter.com/deliverymgt
