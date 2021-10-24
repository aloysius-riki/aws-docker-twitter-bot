# aws-docker-twitterbot
A twitter bot built on AWS running on Docker
<div id="top"></div>

[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]



<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/zjukamu-riki/aws-docker-twitter-bot">
    <img src="images/zjukamu_bot_logo.png" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">AWS Docker Twitter Bot</h3>

  <p align="center">
    An awesome README template to jumpstart your projects!
    <br />
    <a href="https://github.com/zjukamu-riki/aws-docker-twitter-bot"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://twitter.com/zjukamu_bot">View Live Bot</a>
    ·
    <a href="https://github.com/zjukamu-riki/aws-docker-twitter-bot/issues">Report Bug</a>
    ·
    <a href="https://github.com/zjukamu-riki/aws-docker-twitter-bot/issues">Request Feature</a>
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

[![Product Name Screen Shot][product-screenshot]](https://example.com)

I created this twitter bot to try out the Twitter API via Tweepy and get a feel of what can be accomplished with it.

I learnt:
* The API exposes a lot of useful functions that can be automated
* Twitter enforces strict restrictions to ensure their users experience is not dulled by aggresive bots
* The twitter develpoer platform is very easy to use

I will continue to add more features to this bot as time goes by.


<p align="right">(<a href="#top">back to top</a>)</p>



### Built With


* [Tweepy](https://www.tweepy.org/)
* [Python](https://www.python.org/)
* [Docker](https://www.docker.com/)

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

To get the bot up and running follow these simple example steps.

### Prerequisites

1. Twitter API Authentication Credentials [https://developer.twitter.com/](https://developer.twitter.com/)
2. AWS Account  [https://aws.amazon.com/](https://aws.amazon.com/)


### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/zjukamu-riki/aws-docker-twitter-bot.git
   ```
2. Install Docker
   ```sh
   sudo apt-get update
   sudo apt-get install docker.io
   sudo adduser ubuntu docker
   exit
   ```
3. Build Docker Image
   ```sh
   docker build . -t fav-retweet-bot .
   ```
3. Run Docker Image
   ```sh
   docker run -d --restart always \
   -e CONSUMER_KEY="YourConsumerKey" \
   -e CONSUMER_SECRET="YourConsumerSecret" \
   -e ACCESS_TOKEN="YourAccessToken" \
   -e ACCESS_TOKEN_SECRET="YourTokenSecret" \
   fav-retweet-bot
    ```

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- USAGE EXAMPLES -->
## Usage

This bot can be configured for use in many cases. For example, you can source for freelance writing jobs using hastags and show interest by liking and retweeting a potential clients message. 

_For more examples, check out this article [8 Ways Twitter Bots Are Actually Useful](https://www.hongkiat.com/blog/using-twitter-bots/)_

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- ROADMAP -->
## Roadmap

- [] Add Changelog
- [x] Add back to top links
- [] Multi-language Support
    - [] Japanese
    - [] Swahili

See the [open issues](https://github.com/zjukamu-riki/aws-docker-twitter-bot/issues) for a full list of proposed features (and known issues).

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Zjukamu Riki - [@zjukamu_riki](https://twitter.com/zjukamu_riki)

Project Link: [https://github.com/zjukamu-riki/aws-docker-twitter-bot](https://github.com/zjukamu-riki/aws-docker-twitter-bot)

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

Use this space to list resources you find helpful and would like to give credit to. I've included a few of my favorites to kick things off!

* [Choose an Open Source License](https://choosealicense.com)
* [GitHub Emoji Cheat Sheet](https://www.webpagefx.com/tools/emoji-cheat-sheet)
* [Malven's Flexbox Cheatsheet](https://flexbox.malven.co/)
* [Malven's Grid Cheatsheet](https://grid.malven.co/)
* [Img Shields](https://shields.io)
* [GitHub Pages](https://pages.github.com)
* [Font Awesome](https://fontawesome.com)
* [React Icons](https://react-icons.github.io/react-icons/search)

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/zjukamu-riki/aws-docker-twitter-bot.svg?style=for-the-badge
[contributors-url]: https://github.com/zjukamu-riki/aws-docker-twitter-bot/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/zjukamu-riki/aws-docker-twitter-bot.svg?style=for-the-badge
[forks-url]: https://github.com/zjukamu-riki/aws-docker-twitter-bot/network/members
[stars-shield]: https://img.shields.io/github/stars/zjukamu-riki/aws-docker-twitter-bot.svg?style=for-the-badge
[stars-url]: https://github.com/zjukamu-riki/aws-docker-twitter-bot/stargazers
[issues-shield]: https://img.shields.io/github/issues/zjukamu-riki/aws-docker-twitter-bot.svg?style=for-the-badge
[issues-url]: https://github.com/zjukamu-riki/aws-docker-twitter-bot/issues
[license-shield]: https://img.shields.io/github/license/zjukamu-riki/aws-docker-twitter-bot.svg?style=for-the-badge
[license-url]: https://github.com/zjukamu-riki/aws-docker-twitter-bot/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/zjukamu
[product-screenshot]: images/screenshot.png