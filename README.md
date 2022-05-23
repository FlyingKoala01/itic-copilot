<p align="center">
  <img src="https://user-images.githubusercontent.com/49844173/162380728-c396ab95-0566-437d-9882-656ef5503fd9.png" alt="iTIC Copilot - The browser extension" width="75%" />
</p>

----

<p align="center"><strong>
  Get in on <a href="https://chrome.google.com/webstore/detail/opcjpngfgjgceflfdajgekochbmclgmh">Chrome</a>,
  <a href="https://addons.mozilla.org/firefox/addon/itic-copilot/">Firefox</a>,
  <a href="https://microsoftedge.microsoft.com/addons/detail/bjokdnpmhkdokhpkdbgbpgbpmjbknjoh">Edge</a>,
  <a href="https://addons.opera.com/es/extensions/details/itic-copilot/">Opera</a>
  and <a href="https://www.youtube.com/watch?v=dQw4w9WgXcQ">Safari</a>!
</strong></p>
  
----
<p align="center">
  <em>Made by <a href="https://github.com/royalmo">royalmo</a> (Eric Roy). Logo made by <a href="https://github.com/PepitoGrillo7281">PepitoGrillo7281</a> (Josep Sucarrats). Translations by <a href="https://github.com/aidavede">aidavede</a> (Aida Vers). Issues & Feedback by <a href="https://github.com/FlyingKoala01">FlyingKoala01</a> (Isaac Iglesias).</em>
</p>


## Contents
- [What is it?](#what-is-it)
- [Features](#features)
- [Usage](#usage)
- [Manual instalation](#manual-instalation)

## What is it?

<p>
  <img src="https://user-images.githubusercontent.com/49844173/158698760-a9dcbb61-3f0d-4b67-9af2-ef7eed17cdd1.png" alt="Logo iTIC" width=25%" />
</p>

I'm studying an ICT Systems Engineering degree (called also iTIC). During the degree I've found that some tools that we needed to use were a little bit hard to understand at first, or they weren't just as productive as they could be.

That's why I created a browser extension that could, at least, try to make the navigation experience better. It is available on all the browsers that let users publish their extensions without having to be rich.

### Extension's public description

iTIC Copilot is the "must have" browser extension for the ICT Systems Students at EPSEM.
We know the sites that you will be sitting in front of during hours (mostly because we did it too), so you will be, with no doubt, pleased with the features that we developed.

Featuring an anti-downloader and a full-downloader at OCW's website, an Atenea & Escriny autologin, a grades calculator at Atenea's website, and a combination of  Escriny's and Overleaf's websites.
But that's not all! We also created some documents with advices that we would have loved to hear about when we were studying.

Boost your productivity with iTIC Copilot, and not by getting inside an atomic_block ! (you will understand the joke by the end of 2nd grade)

## Features

This extension makes the browsing experience of iTIC students much, much easier.

### Better navigation in the OpenCourseWare

- It disables the 'forced download' when accessing some files. Specially, the PDF's, that with the extension are opened with the browser.
- It has a 'download subject' option, that creates a `.zip` file with all the resources of a subject, to make massive downloads easier.

### Escriny (iTIC's subversion) productivity

Work in progress. For the moment, there's nothing here.

## Usage

For the moment, there isn't any user interface, so just head into some of the iTIC websites (like the [OCW](https://ocwitic.epsem.upc.edu)) and look for the new buttons nested in the rendered website.

## Manual instalation

By downloading the source code you can use the extension and play with it. As long as you respect the extension's liscence, you can do what you want.

Here you have a tutorial for the manual instalation in Google Chrome. For the other browsers, it should be more or less the same instructions.

### 1. Clone the repository

Assuming you have git installed, run
```
git clone https://github.com/royalmo/ocw-anti-download.git
```

Otherwise, you can [download the zip file](https://github.com/royalmo/ocw-anti-download/archive/refs/heads/main.zip) of the repository, and unzip the downloaded file.

### 2. Activate Chrome developer mode

Go to [`chrome://extensions/`](chrome://extensions/) on your Chrome browser and enable **Developer mode** at the top right of the page.

![Developer mode](https://user-images.githubusercontent.com/49844173/158700807-1788513c-1581-482d-b9db-b12c30bb7774.png)

### 3. Load the extension folder

A **Load unpacked** button will appear at the top left of the page after enabling *Developer mode*. Click there, and select the *ocw-anti-download* folder you just cloned.

![Load unpacked](https://user-images.githubusercontent.com/49844173/158700864-62b51048-0768-4926-b1d7-272f7f4bbf97.png)


That's it! You should be able to open OCW's files without downloading them. **Caution!** Make sure you don't delete the downloaded folder! Chrome loads the extension from there every time you open the browser.
