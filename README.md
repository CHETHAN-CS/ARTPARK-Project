<div id="top"></div>
<!--

-->



<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://www.artpark.in/">
    <img src="images/artparklogo.png" alt="Logo" width="400" height="100">
  </a>

  <h2 align="center">Innovation Grant Program</h2>

  <p align="center">
    The program invites highly motivated and talented faculty members, along with their under-graduate and post-graduate students, to apply for research projects in the areas of Artificial Intelligence, Robotics and Autonomous Systems
    <br />
    <a href="https://www.artpark.in/innoProgramme" target="_blank"><strong>Know More About the Program »</strong></a>
    <br />
    <h3 align="center">Project Title: Traffic Voilaton Detection using CCTV cameras</h3>
    <br />
    <h3 align="center">DONE BY</h3>
    <h4> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; CHETHAN S &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; PRAJWAL K &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;NEHAL CHAKRAVARTY &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;SHIVARAJ B KAREGERA <h4>
    <h5>RV College of Engineering &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;RV College of Engineering &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; RV College of Engineering &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; RV College of Engineering <h5>
    <br />
    <h3 align="center">Under the Guidence Of</h3>
    <h4> Dr. Ramakanth Kumar <h4>
    <h5> Head Of the Department, Dept. of CSE, RVCE <h5>
  <!--
    <a href="PROFILE URL">CHETHAN S</a>
    ·
    <a href="PROFILE URL">PRAJWAL K</a>
    ·
    <a href="PROFILE URL">NEHAL CHAKRAVARTY</a>
    .
    <a href="PROFILE URL">SHIVARAJ BK</a>
   -->
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details open>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
      <ul>
        <li><a href="#hardware-requirements">Hardware Requirements</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#Jetson-Nano-Setup">Jetson Nano Setup</a></li>
        <li><a href="#download-the-source-code">Download the Source-Code</a></li>
        <li><a href="#prerequisites">Prerequisites</a></li>
      </ul>
    </li>
    <li><a href="#run">RUN</a></li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project


To ensure safety measures on roads of India, the identification of traffic rule violators is highly desirable but challenging job due to numerous difficulties such as occlusion, illumination, etc. In this project we propose an end-to-end framework for detection of violations and notifying violators. The creation of automatic detection systems for traffic rules violations on signal jumping, speed limit cross, riding two-wheeler without helmet is necessary to improve and manage road safety in the country.

To perform such autonomous system, we propose machine learning models which are trained by custom datasets obtained over the internet, wherein the images are caught by CCTV cameras. Every machine learning model that is proposed is trained to detect a particular violation. To train the models google colab platform was utilized for training and evaluation purposes.

The results obtained from the system proposed is that it’s able to detect the vehicles successfully and if any violations such as not wearing helmet, red light signal jumping, and one way violation is being detected by different models successfully. Lot of scope is present in the field of traffic monitoring and deep learning integration. Models can be trained with more data to increase confidentiality score and accuracy score. Developing an autonomous system which could detect violation and notify the commuters and the traffic policing department in real time is the direction for future work. 

To make the project standalone, we have used NVIDIA jetson nano. We have deployed the software into the jetson nano and connected it with IP camera. Hence, we have developed a complete product.

<p align="right">(<a href="#top">back to top</a>)</p>


### Built With

This section should list any major frameworks/libraries used to bootstrap your project. Leave any add-ons/plugins for the acknowledgements section. Here are a few examples.

* [Python](https://www.python.org/)
* [OpenCV](https://opencv.org/)
* [MobileNet](https://github.com/chuanqi305/MobileNet-SSD/)
* [Haar-Cascade](https://github.com/CHETHAN-CS/vehicle_detection_using_haarcascade/)

<p align="right">(<a href="#top">back to top</a>)</p>

### Hardware Requirements

The hardware requirements in this project are as follows

* [IP Camera](https://en.wikipedia.org/wiki/IP_camera/)
* [NVIDIA Jetson Nano](https://developer.nvidia.com/embedded/jetson-nano-developer-kit/)
* [Display Monitor](https://en.wikipedia.org/wiki/Computer_monitor/)
* [Keyboard](https://en.wikipedia.org/wiki/Computer_keyboard)
* [Mouse](https://en.wikipedia.org/wiki/Computer_mouse/)
* [Power Adapter](https://forums.developer.nvidia.com/t/power-supply-considerations-for-jetson-nano-developer-kit/71637/)

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- GETTING STARTED -->
## Getting Started

Follow the guidelines/steps given Below to Install and RUN the project on Normal PC using ANACONDA.

### Install Anaconda
Install Anaconda and create an environment with python 3.6. Follow these guidlines for more info.

For installantion guide: https://docs.anaconda.com/anaconda/install/windows/

For managing environments: https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html#creating-an-environment-with-commands

-----------------------------------------------------------------------------------------------------------------------------------------------------------------

Follow the guidelines/steps given Below to Install and RUN the project on NVIDIA Jetson Nano.

### Jetson-Nano-Setup
In order to RUN the project in Jetson nano you need to do initial Setup for Jetson nano. Follow the instructions given in the NVIDIA Jeson nano Installation manual.
Follow this Link to access the manual and proceed with the setup.(Choose appropriate w.r.t the RAM size of your jetson Nano).

For 2GB Jetson Nano: https://developer.nvidia.com/embedded/learn/get-started-jetson-nano-2gb-devkit

For 4GB Jetson Nano: https://developer.nvidia.com/embedded/learn/get-started-jetson-nano-devkit

### Download the Source-Code
Once you are ready with the jetson nano setup switch it ON and download the source code of the project from below link.

Follow this link for source code: https://drive.google.com/drive/folders/1DMh4dKm2AypiDYFfHEzXlm_ja28lmOjg?usp=sharing
      
Then Unzip the code and keep it in any directory.

### Prerequisites

The commands to install all the prerequisites are kept in a single script file(requirements.sh). So, Need to install them seperately. Just run the script file by opening the terminal.
 
* First GOTO your project directory using 'cd' command.
  Example: ```
           cd "Path to project directory"
             ```
      
* Commands to run the script file
  ```sh
  chmod a+x requirements.sh
  ```

  ```sh
  ./requirements.sh
  ```

## RUN

To run the different usecases (Line cross detection/Parking Detection/Wrong way detection/Helmet detection) Run the below commands:

1. Go to project directory (If you are not in)
2. To RUN Line cross detection
   ```sh
   python "command to run code -Need to update"
   ```
3. To RUN Parking Detection
   ```sh
   python "command to run code -Need to update"
   ```
4. To RUN Wrong way detection
   ```sh
   python "command to run code -Need to update"
   ```
5. To RUN Helmet Detection code
   ```sh
   python "command to run code -Need to update"
   ```
<p align="right">(<a href="#top">back to top</a>)</p>



<!-- USAGE EXAMPLES -->
## Usage

NEED TO UPDATE

<p align="right">(<a href="#top">back to top</a>)</p>


<!-- CONTACT -->
## Contact

CHETHAN S  - chethans.cs18@rvce.edu.in
      
PRAJWAL K -prajwalk.cs18@rvce.edu.in
      
SHIVARAJ BK  - shivarajbk.cs18@rvce.edu.in
      
NEHAL CHAKRAVARTY  - nehalchakravarty.cs18@rvce.edu.in

Project Link: [TVD-Gdrive](https://drive.google.com/drive/folders/1DMh4dKm2AypiDYFfHEzXlm_ja28lmOjg?usp=sharing)

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

Need to Update....


<p align="right">(<a href="#top">back to top</a>)</p>

