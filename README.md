<a name="vol"></a>


<!-- Adding custom IDs allows you to link directly to headings and modify them with CSS. To add a custom heading ID, enclose the custom ID in curly braces on the same line as the heading. -->
<!-- <h1 id="#vol">volume-vault [WIP]</h1> -->
# volume-vault 
#### <ins>__*a macOS app for boosting max audio output*__</ins>

<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#view">Project Overview</a>
      <ul>
        <li><a href="#obj">Objectives</a></li>
      </ul>
    </li>
    <li>
      <a href="#tech">Technologies and Programming Languages</a>
      <ul>
        <a href="#built">Built With</a>
        <a href="#devenv">Development Environment</a>
      </ul>
    </li>
    <li><a href="#start">Getting Started</a></li>
    <li>
      <a href="#map">Roadmap</a>
      <ul>
        <li><a href="#line">Timeline</a></li>
        <ul>
          <li><a href="#time">Time Estimate</a>></li>
        </ul>
        <li><a href="#todo">To-Do List</a></li>
      </ul>
    </li>
    <li><a href="#flow">Basic Workflow</a></li>
    <li><a href="#io">Basic I/O Details</a></li>
    <li>
      <a href="#use">Usage</a>
      <ul>
        <li><a href="#pre">Prerequisites</a></li>
        <li><a href="#inst">Installation</a></li>
      </ul>
    </li>
    <li><a href="#feat">Key Features</a></li>
    <li><a href="#give">How to Contribute</a></li>
    <li><a href="#plus">Future Enhancements</a></li>
    <li><a href="#lic">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#ack">Acknowledgments</a></li>
  </ol>
</details>
  
> Unleash the ~Audio Amplification Adventure~
> 

---------------------------

<a name="view"></a>
## Project Overview
<ins>__*volume-vault*__</ins> is a macOS application that breaks through Apple's pre-set maximum audio playback volume restrictions, enabling users to boost and amplify their favorite audio media content by up to 2000%. 

This entertaining project features a simple and minimalistic user interface, offering users the choice to use it as a Mac menu bar drop-down widget or a standalone application for an enjoyable audio amplification experience.


<a name="obj"></a>
### Objectives
The main objective of <ins>__*volume-vault*__</ins> is to provide macOS users with a playful solution to amplify their audio volume beyond the limitations imposed by Apple. 

By offering a user-friendly interface and a humorous touch, <ins>__*volume-vault*__</ins> aims to enhance the audio experience for users who desire louder sound without compromising on quality.

<p align="right">(<a href="#vol">back to top</a>)</p>

---------------------

<a name="tech"></a> 
## Technologies and Programming Languages
For the *front-end* and *UI* development, the following technologies and programming languages are recommended:
> - **<ins>Swift</ins>:** As the primary language for macOS app development.
> - **<ins>SwiftUI</ins>:** To create a modern and visually appealing minimalistic user interface.
&nbsp;

For the *back-end* and audio processing, the following library can be considered:
> - **<ins>Core Audio</ins>:** For audio manipulation and volume boosting.


<a name="built"></a>
### Built With:


<a name="devenv"></a>
### Development Environment:

- **Operating System:** macOS Ventura *(version 14.3.1)*
- **Architecture:** Apple arm64


<p align="right">(<a href="#vol">back to top</a>)</p>

---------------------

<a name="map"></a>
## Roadmap


<a name="line"></a>
### Timeline: 

> ##### <ins>__Started__</ins>: Not yet
>
> ##### <ins>__Completed On__</ins>: Idk

<a name="time"></a>

#### Time Estimate: 

The time required for completing <ins>__*volume-vault*__</ins> can vary based on the developer's expertise and the desired level of polish. 

- For a *basic* version with the primary features, it may take around 2-4 weeks. 
- For a *more refined* version with additional features and thorough testing, it may take up to 6-8 weeks or more.

  
<a name="todo"></a>
### To-Do List: 
- [ ] Create a New macOS SwiftUI Project
- [ ] Pseudocode
- [ ] Add Additional Templates w/ Examples

&nbsp; 

1. **<ins>UI Design</ins>:**
    - Design a simple and visually appealing user interface, considering both the menu bar widget and standalone application.
2. **<ins>Implement Volume Boosting</ins>:**
    - Integrate Core Audio to enable volume boosting beyond Apple's pre-set maximum volume.
3. **<ins>Configure UI Controls</ins>:**
    - Add sliders, buttons, or other controls to allow users to adjust the volume and enable/disable the volume boost.
4. **<ins>Menu Bar Integration</ins>:**
    - Implement the functionality to run the application as a menu bar widget with a dropdown interface.
5. **<ins>Standalone Application</ins>:**
    - Create a separate standalone application with the same functionality and minimal UI.
6. **<ins>User Preferences</ins>:**
    - Allow users to customize settings, such as preferred volume levels or startup behavior.
7. **<ins>Testing</ins>:**
    - Perform rigorous testing to ensure smooth functionality and handle potential edge cases.
8. **<ins>Code Optimization</ins>:**
    - Refine the codebase and optimize performance for a seamless user experience.
9. **<ins>Deployment</ins>:**
    - Prepare the application for distribution on the Mac App Store.

<p align="right">(<a href="#vol">back to top</a>)</p>

---------------------

≈
## Time Estimate
The time required for completing <ins>__*volume-vault*__</ins> can vary based on the developer's expertise and the desired level of polish. 

- For a *basic* version with the primary features, it may take around 2-4 weeks. 
- For a *more refined* version with additional features and thorough testing, it may take up to 6-8 weeks or more.

<p align="right">(<a href="#vol">back to top</a>)</p>

---------------------
<a name="start"></a>

## Getting Started

1. **<ins>Install Xcode</ins>:** Download and install Xcode, the integrated development environment for macOS app development, from the Mac App Store.
2. **<ins>Create a New macOS SwiftUI Project</ins>:** Set up a new project and define the basic UI elements and application structure.

<p align="right">(<a href="#vol">back to top</a>)</p>

---------------------
<a name="flow"></a>
## Basic Workflow Guide

1. Upon launching <ins>__*volume-vault*__</ins>, the user is presented with a clean and straightforward UI, either as a menu bar widget or a standalone application.
2. The user can toggle the volume boost feature on/off using a button or checkbox.
3. A slider allows the user to adjust the level of volume boost they desire, ranging from 0% to 2000%.
4. The application utilizes Core Audio to intercept audio output and apply the desired volume boost.
5. The boosted audio is then sent to the system's audio output for playback.
6. The user can control the volume directly from the application or the menu bar widget.

<p align="right">(<a href="#vol">back to top</a>)</p>

---------------------

<a name="io"></a>
## Basic I/O Details

### Input:
- User interaction with the application's sliders and buttons to control volume boost and other settings.


### Output:
- Boosted audio output to the system's audio playback.

&nbsp

### System/User Permissions and Requirements:
To manipulate audio output, *<ins>__volume-vault__</ins>* will need appropriate permissions to access the user's audio settings and intercept audio playback. 

Users will need to grant the necessary permissions during the application's first run. 
<ins>__*volume-vault*__</ins> should adhere to macOS security guidelines and handle permissions gracefully.

<p align="right">(<a href="#vol">back to top</a>)</p>

---------------------

<a name="use"></a>
## Usage

### Potential Use Cases and Applications:
- **<ins>Media Playback</ins>:** Enhance audio volume when watching movies, videos, or listening to music.
- **<ins>Video Conferencing</ins>:** Improve audio clarity during online meetings and conferences.
- **<ins>Accessibility</ins>:** Assist users with hearing impairments by increasing the volume as needed.
- **<ins>Noisy Environments</ins>:** Allow users to boost volume in loud or noisy surroundings.


### Prerequisites:


### Installation:


<p align="right">(<a href="#vol">back to top</a>)</p>

---------------------

<a name="feat"></a>
## Key Features 

- **<ins>Volume Boosting</ins>:** Amplify audio playback volume by up to 2000% beyond Apple's default limits.
- **<ins>Minimalistic UI</ins>:** A simple and user-friendly interface with essential controls.
- **<ins>Menu Bar Widget</ins>:** Run the application as a convenient menu bar drop-down widget.
- **<ins>Standalone Application</ins>:** Offer the option to use VolumeVault as a standalone application for easy access.
- **<ins>Customizability</ins>:** Allow users to fine-tune the volume boost level according to their preferences.

<p align="right">(<a href="#vol">back to top</a>)</p>

---------------------
<a name="give"></a>
## How and Why to Contribute

- **Contribution Guidelines:** Provide clear guidelines on how developers can contribute to *<ins>__volume-vault__</ins>*.
- **Open Source:** Consider making *<ins>__volume-vault__</ins>* an open-source project to foster community contributions.
- **Bug Reports and Feature Requests:** Encourage users to submit bug reports and suggest new features to improve the application.

<p align="right">(<a href="#vol">back to top</a>)</p>

---------------------
<a name="plus"></a>

## Potential Enhancements

1. **<ins>Equalizer</ins>:**
Implement an audio equalizer to provide users with further control over audio frequencies.
3. **<ins>Presets</ins>:**
Include preset configurations for different scenarios (e.g., movies, music, gaming) for quick adjustments.
6. **<ins>Audio Effects</ins>:**
Integrate audio effects like spatial audio or surround sound to enrich the audio experience.
8. **<ins>Dark Mode</ins>:**
Add support for macOS dark mode to enhance visual appeal and consistency with macOS aesthetics.

<p align="right">(<a href="#vol">back to top</a>)</p>

---------------------------

<a name="lic"></a>
<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#vol">back to top</a>)</p>

---------------------------
<a name="contact"></a>
<!-- CONTACT -->
## Contact

Your Name - [@lyndskg](https://twitter.com/lyndskg) - lyndsey.gu@gmail.com

Project Link: [https://github.com/your_username/repo_name](https://github.com/your_username/repo_name)

<p align="right">(<a href="#vol">back to top</a>)</p>

---------------------------
<a name="ack"></a>
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

<p align="right">(<a href="#vol">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/othneildrew/Best-README-Template.svg?style=for-the-badge
[contributors-url]: https://github.com/othneildrew/Best-README-Template/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/othneildrew/Best-README-Template.svg?style=for-the-badge
[forks-url]: https://github.com/othneildrew/Best-README-Template/network/members
[stars-shield]: https://img.shields.io/github/stars/othneildrew/Best-README-Template.svg?style=for-the-badge
[stars-url]: https://github.com/othneildrew/Best-README-Template/stargazers
[issues-shield]: https://img.shields.io/github/issues/othneildrew/Best-README-Template.svg?style=for-the-badge
[issues-url]: https://github.com/othneildrew/Best-README-Template/issues
[license-shield]: https://img.shields.io/github/license/othneildrew/Best-README-Template.svg?style=for-the-badge
[license-url]: https://github.com/othneildrew/Best-README-Template/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/othneildrew
[product-screenshot]: images/screenshot.png
[Next.js]: https://img.shields.io/badge/next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white
[Next-url]: https://nextjs.org/

