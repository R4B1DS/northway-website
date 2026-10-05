# NoWay RP: Loading Screen

A loading screen page I built for my GTA roleplay server, NoWay RP (Northway Roleplay). It has a full-screen background video, the server logo in the center, a welcome message and links to the server's social networks.

> 📌 **Note:** The server was closed a long time ago. This is an archived project, kept as part of my learning history. The audio file is not included in this repository, and the background video is hosted on YouTube.

## Preview

![Loading screen preview](img/site.png)

*Screenshot of the loading screen. The background video in this image is different from the one embedded in this repository.*

Background video embedded in this version:

[![NoWay RP loading screen background video](https://img.youtube.com/vi/_vbgxAowWJM/hqdefault.jpg)](https://www.youtube.com/watch?v=_vbgxAowWJM)

## Features

- Full-screen looping background video, embedded from YouTube
- Server logo centered on the screen, over a dark overlay
- Welcome message: *"Seja bem-vindo à sua nova história"* ("Welcome to your new story")
- Social network icons (TikTok, Instagram and YouTube) in the footer
- Keyboard shortcut to pause or play the music: press **P** (works if an `audio.mp3` file is added)
- Responsive: the logo and footer adapt to small screens

## Tech Stack

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

## Project Structure

```text
noway-loading-screen/
├── index.html
├── style.css
├── img/
│   ├── logo.png
│   ├── site.png
│   ├── tiktok.png
│   ├── instagram.png
│   └── youtube.png
└── README.md
```

## How to Run

The YouTube player does not load when you open the file directly from your computer. Run it with a local server:

1. Open the folder in **VS Code**
2. Install the **Live Server** extension (by Ritwick Dey)
3. Right-click `index.html` and choose **Open with Live Server**

You can also publish it with GitHub Pages and open the public link.

## What I Learned

- Browsers only allow autoplay when the video is muted, and audio needs user interaction first.
- Large media files should not go into a Git repository, so I used a YouTube embed for the video.
- A YouTube embed does not work when the page is opened as a local file (`file:///`), only from a server (`http://`).
- Server IPs and invite links should never be published in public code.

## Author

**Nicolas Borges Ocampos**
[LinkedIn](https://www.linkedin.com/in/nicolas-borges-ocampos)