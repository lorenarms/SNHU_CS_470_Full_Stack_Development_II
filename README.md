<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->
<a name="readme-top"></a>
<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Don't forget to give the project a star!
*** Thanks again! Now go create something AMAZING! :D
-->



<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]



<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/lorenarms/SNHU_CS_470_Full_Stack_Development_II">
    <img src="https://angular.io/assets/images/logos/angular/angular.svg" alt="Logo" width="210">
  </a>

  <h3 align="center">CS 470: Full Stack Development II</h3>

  <p align="center">
    Lawrence Artl III
    <br />
    <a href="https://github.com/lorenarms/SNHU_CS_470_Full_Stack_Development_II/tree/main/writeups/Docs"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="http://bucket-burydbultrimilog.s3-website-us-east-1.amazonaws.com/">View Demo</a>
    ·
    <a href="https://github.com/lorenarms/SNHU_CS_470_Full_Stack_Development_II/issues">Report Bug</a>
    ·
    <a href="https://github.com/lorenarms/SNHU_CS_470_Full_Stack_Development_II/issues">Request Feature</a>
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#about-the-course">About The Course</a></li>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
        <li><a href="#how-i-developed-the-project">How I Developed The Project</a></li>
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


<!-- ABOUT THE COURSE -->
## About The Course
<h3>
Course Prerequisites
</h3>

- [x] <a href="https://github.com/lorenarms/SNHU_CS_465_Full-Stack-Development-I">CS 465</a> 

<h3>
Course Description
</h3>
<p>students will develop a full stack application that runs in the cloud. Through the application of cloud-based development principles and best practices, students will take their software stack from Full Stack Development I and utilize frameworks to build the cloud architecture upon which the software stack application will run. In addition, students will demonstrate their career readiness by articulating highly technical content to various audiences and in various formats. This course is the second in a two-course sequence.
</p>
<p>
This course covers the following competencies, which represent the knowledge and skills relevant to your field:

- [x] CS-40430: Apply cloud-based development principles and best practices in application development
- [x] CS-40431: Develop applications that run on cloud-based frameworks
- [x] CS-40432: Defend design decisions to a variety of audiences and in a variety of formats

</p>



<!-- ABOUT THE PROJECT -->
## About The Project
<div align = "center">
  <h3>AWS Web Application</h3>
  <img src="https://github.com/lorenarms/SNHU_CS_470_Full_Stack_Development_II/blob/main/images/main_page.png" alt="Main" width="500"><p></p>
<!-- [![Product Name Screen Shot][product-screenshot]](https://example.com)-->
</div>

<p>
  During this course we explored the use of containers for development of a web application. Starting with Docker and Docker compose, a simple application was developed that made use of Angular for a front end, node.js for the backend, and MongoDB to store data locally. 
  
  Eventually the application was moved to the cloud, taking advantage of Amazon's Web Service environment including DynamoDB and Lambda functions to handle data streams and user interaction. 
 
This project involved a lot of problem solving and debugging as the AWS environment is very particular in how interactions between the Lambda functions and the API are implemented. Since problem solving is my forte, I thouroughly enjoyed very aspect of this build. Check out the final product with the link above!
</p>

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- BUILT WITH -->
### Built With

This project used the following frameworks, and will require them to run on your machine. See the <a href="#installation">installation</a> section for more information.

[![Angular][Angular.io]][Angular-url]

[![Node][Node.js]][Node-url]

[![Express][Express.js]][Express-url]

[![Mongodb][Mongodb]][Mongodb-url]

[![Docker][Docker]][Docker-url]

[![DynamoDB][DynamoDB]][DynamoDB-url]

[![AWS][AWS]][AWS-url]


<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- DEVLOPMENT OF THE PROJECT -->
### How I Developed The Project

  <p>
This project followed several guides to get the containers set up on a local machine, and more guides to access and set up the AWS environment. Development took about seven weeks, and made use of pre-built Angular application found <a href="https://github.com/AngularTemplates/learn-angular-from-scratch-step-by-step">here</a>. The API for this project is also pre-built and can be found <a href="https://github.com/AngularTemplates/learn-how-to-build-a-mean-stack-application">here</a>.
</p>
<p>
My approach to solving the above problem (and all others in any other aspect of my life) is methodical and logical. I typically know the limitations and abilites of the tools I am using to solve the problem, and using a one-step-at-a-time method helps me to work efficiently. I rarely have the problem in missing the "forest for the trees"; in fact, I'm very good at stepping back from the details and seeing the big picture for what it is, and then stepping back into the details with an understanding of how they effect the overall problem / solution.
</p>

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- GETTING STARTED -->
## Getting Started

To install and run the local instance of this application on your own machine, you'll need to install Docker Desktop (Windows). You will also need to be running an IDE such as Visual Studio Code or similar.

### Prerequisites

Start by ensuring you have npm installed on your machine.

  ```sh
  npm install npm@latest -g
  ```
  
Get Docker Desktop <a href="https://www.docker.com/products/docker-desktop/">here</a>.

### Installation

To install and run the application, follow the instructions below.

1. Follow the <a href="https://github.com/lorenarms/SNHU_CS_470_Full_Stack_Development_II/blob/main/writeups/Guides/CS%20470%20Module%20One%20Assignment%20-%20Docker%20Containers%20Guide.pdf">guide</a> to get Docker Desktop installed and running.
2. Follow the next <a href="">guide</a> to fork and install the "Learn Angular from Scratch" (lafs) repos. You will containerize both repos.
3. Follow the last <a href="https://github.com/lorenarms/SNHU_CS_470_Full_Stack_Development_II/blob/main/writeups/Guides/CS%20470%20Module%20Two%20Assignment%20-%20Docker%20Compose%20Guide.pdf">guide</a> to create a network of containers using Docker Compose.

4. Open a web browser and navigate to "http://localhost:3000" to access the API
5. Open another browser tab / window and navigate to "http://localhost:4200" to access the backend


<!-- USAGE EXAMPLES -->
## Usage

<h3>Front-end Customer Facing Website</h3>
<p>The front end of the website can be accessed <a href="http://bucket-burydbultrimilog.s3-website-us-east-1.amazonaws.com/">here</a> </p>
<p>The website is a mock-up of a study page that allows users to select a topic and then add questions to that topic. Selecting the topic will bring up the question page for that topic. Users can add questions and delete questions. Selecting a question allows users to add answers that question.</p>

<table>
    <tr>
        <th>Question List</th>
        <th>Adding a Question</th>    
    </tr>
    <tr>
        <td><img src="https://github.com/lorenarms/SNHU_CS_470_Full_Stack_Development_II/blob/main/images/questions.png" alt="[question list page]" style="height:300px;"></td>
        <td><img src="https://github.com/lorenarms/SNHU_CS_470_Full_Stack_Development_II/blob/main/images/adding%20a%20question.png" alt="[adding a question]" style="height:300px;"></td>
    </tr>
        
</table>

<h3>Backend SPA (using Angular, Express, node.js, and MongoDB)</h3>
<p>The backend uses the AWS environment to serve the front end website as well as store data in DynamoDB. The data is accessed via Lambda functions through the Amazon API Gateway. The entire front end is stored in the Amazon S3 Bucket environment, as shown in the below image.</p>

<table>
    <tr>
        <th>S3 Bucket</th>
        <th>API Gateway</th>     
    </tr>
    <tr>
        <td><img src="https://github.com/lorenarms/SNHU_CS_470_Full_Stack_Development_II/blob/main/images/S3Bucket.png" alt="[bucket]" style="height:auto;"></td>
        <td><img src="https://github.com/lorenarms/SNHU_CS_470_Full_Stack_Development_II/blob/main/images/APIGateway.png" alt="[gateway]" style="height:auto;"></td>
   </tr>
</table>

<table>
    <tr>
        <th>DynamoDB Questions Table</th>
        <th>Lambda Function Sample</th>
   </tr>
    <tr>
        <td><img src="https://github.com/lorenarms/SNHU_CS_470_Full_Stack_Development_II/blob/main/images/dynamoDBQuestions.png" alt="[dynamo]" style="height:auto;"></td>
        <td><img src="https://github.com/lorenarms/SNHU_CS_470_Full_Stack_Development_II/blob/main/images/upsertLambdaFunction.png" alt="[lambda]" style="height:auto;"></td>
   </tr>
</table>

<p>
  In order to test the application before migrating to the AWS cloud, a set of containers were configured using Docker Compose. These containers ran in tandem on a local machine, as illustrated below (Docker Desktop, "lafs-web" and "lafs-api"). MongoDB stands in for Dynamo, and the container front end is accessable through local host port 4000.
</p>

<table>
    <tr>
        <th>Docker Compose Project Running Locally</th>
    </tr>
    <tr>
        <td><img src="https://github.com/lorenarms/SNHU_CS_470_Full_Stack_Development_II/blob/main/images/dockerComposeRunning.png" alt="[docker]" style="height:auto;"></td>
    </tr>
</table>

_For more information, please refer to the [Guides](https://github.com/lorenarms/SNHU_CS_470_Full_Stack_Development_II/tree/main/writeups/Guides)_

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ROADMAP -->
## Roadmap

- [x] Include guides
- [x] Compile screenshots
- [x] Link to documentation
- [x] Add final README

See the [open issues](https://github.com/lorenarms/SNHU_CS_470_Full_Stack_Development_II/issues) for a full list of proposed features (and known issues).

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTRIBUTING -->
## Contributing

I'm always open to collaborate with other great coders! If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- LICENSE -->
## License

Currently there is no license for this application, it is free to use by anyone who needs it. Please consider letting me know if it was helpful at all, or any additions you can propose (see the <a href="#contributing">contributing</a> section)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

<p>Check out my <a href="https://www.youtube.com/channel/UCGtp8PRHgPCQHYoSxbMST8A" target="_blank">YouTube channel</a> for more videos about coding projects I've done.</p>
<p>Also, check out my <a href="http://artllj.com" target="_blank">Personal Website</a> for more information about me, and my <a href="https://www.linkedin.com/in/lorenarms95/" target="_blank">LinkedIn</a> to see if I'd be a good fit for your team. </p>
<h3>Thanks for stopping by!</h3>
<img src="https://github.com/lorenarms/SNHU_CS_370_Emerging_Trends_in_CS/blob/main/images/profile.png" alt="[picture of me]" style="width:100px;">
<p>much love
-L
</p>


<p align="right">(<a href="#readme-top">back to top</a>)</p>


  

<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

* [Choose an Open Source License](https://choosealicense.com)
* [GitHub Emoji Cheat Sheet](https://www.webpagefx.com/tools/emoji-cheat-sheet)
* [Malven's Flexbox Cheatsheet](https://flexbox.malven.co/)
* [Malven's Grid Cheatsheet](https://grid.malven.co/)
* [Img Shields](https://shields.io)
* [GitHub Pages](https://pages.github.com)
* [Font Awesome](https://fontawesome.com)
* [React Icons](https://react-icons.github.io/react-icons/search)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/lorenarms/SNHU_CS_470_Full_Stack_Development_II.svg?style=for-the-badge
[contributors-url]: https://github.com/lorenarms/SNHU_CS_470_Full_Stack_Development_II/graphs/contributors
  
[forks-shield]: https://img.shields.io/github/forks/lorenarms/SNHU_CS_470_Full_Stack_Development_II.svg?style=for-the-badge
                
[forks-url]: https://github.com/lorenarms/SNHU_CS_470_Full_Stack_Development_II/network/members
  
[stars-shield]: https://img.shields.io/github/stars/lorenarms/SNHU_CS_470_Full_Stack_Development_II.svg?style=for-the-badge
[stars-url]: https://github.com/lorenarms/SNHU_CS_470_Full_Stack_Development_II/stargazers
  
[issues-shield]: https://img.shields.io/github/issues/lorenarms/SNHU_CS_470_Full_Stack_Development_II.svg?style=for-the-badge
[issues-url]: https://github.com/lorenarms/SNHU_CS_470_Full_Stack_Development_II/issues
  
[license-shield]: https://img.shields.io/github/license/lorenarms/SNHU_CS_470_Full_Stack_Development_II.svg?style=for-the-badge
[license-url]: https://github.com/lorenarms/SNHU_CS_470_Full_Stack_Development_II/blob/master/LICENSE.txt
  
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=0077FF
[linkedin-url]: https://linkedin.com/in/lorenarms95

[product-screenshot]: images/main_page.png

[Node.js]: https://img.shields.io/badge/node.js-002200?style=for-the-badge&logo=nextdotjs&logoColor=green
[Node-url]: https://nodejs.org/en/
[Express.js]: https://img.shields.io/badge/Express-FFFFFF?style=for-the-badge&logo=express&logoColor=222222
[Express-url]: https://expressjs.com/
[Mongodb]: https://img.shields.io/badge/mongodb-003300?style=for-the-badge&logo=mongodb&logoColor=11FF11
[Mongodb-url]: https://www.mongodb.com/
[Angular.io]: https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white
[Angular-url]: https://angular.io/
[DynamoDB-url]: https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/Introduction.html
[DynamoDB]: https://img.shields.io/badge/amazon_dynamodb-ccac00?style=for-the-badge&logo=amazondynamodb&logoColor=000000
[AWS]: https://img.shields.io/badge/amazon_aws-ccac00?style=for-the-badge&logo=amazonaws&logoColor=000000
[AWS-url]: https://aws.amazon.com/
[Docker]: https://img.shields.io/badge/docker-3232FF?style=for-the-badge&logo=docker&logoColor=ffffff
[Docker-url]: https://www.docker.com/

