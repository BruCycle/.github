
<h1 align="center"> :bike: BrüCycle :bike: </h1>
<h2 align="center">:beers: Burn It To Earn It. :beers:</h2>
<div align="center">
  <img src="https://media.giphy.com/media/VEyS5blLoyMCQ1HvOb/giphy.gif">
  <br>
  <h4> What could make biking even more fun, you ask? Beer, of course!</h4>
</div>

<br>
<br>

BrüCycle was developed as a way for you to alleviate those symptoms. You will track your biking exercise data via [Strava](https://www.strava.com), and the number of beers that you have earned during said exercise. You will accumulate beers in your Beer "Bru" Bank based on the amount of miles and calories burned in bicycle rides you've completed. 

:beer: [Learning Goals](#learning-goals)
<br>
:beer: [Project Overview](#project-overview)
<br>
:beer: [Planning](#planning)
<br>
:beer: [Tech Stack](#tech-stack)
<br>
:beer: [Deployment](#deployment)
<br>
:beer: [Contributors](#contributors)
<br>

### Learning Goals
Back end
  -
  - Consume two or more external APIs 
  - Create a project with a separate frontend and backend
  - Code follows DRY and SRP design
  
 Front End
  -
  - Use an external OAuth provider to authenticate users 
  - Professional quality HTML and CSS, color palette is pleasing and suitable to the target audience
  - Application works in multiple browsers (Chrome, Safari, Firefox, etc)

### Project Overview

[Backend repo](https://github.com/BruCycle/brucycle_be)
<br>
[Frontend repo](https://github.com/BruCycle/brucycle_fe)

### Setup/Installation Guide
- Fork this repository
- Clone your fork
- From the command line, install gems and set up your DB:
  - ```bundle```
- APIs used
  -  Please follow the link to get your ``client id`` and ```client secret``` used later: https://www.strava.com/settings/api
  - ```bundle exec figaro install```
  - Go to ```config/application.yml```
  - Name your API keys from Strava ```strava_client_id``` and ```strava_client_secret``` respectfully
- Run ```rails db:{create,migrate}```
- Run the test suite with ```bundle exec rspec.```


<br>

### Planning
Database Design
<br>
  ![BruCycle_DB](https://user-images.githubusercontent.com/103780823/211390915-8ba95209-28ba-4c64-8aa6-24038cb32eee.png)
  <br>
Miro Planning board
<br>
  <img width="1497" alt="Screenshot 2023-01-11 at 10 06 14 AM" src="https://user-images.githubusercontent.com/108167041/211884129-d20d44af-179a-492a-b3a3-268329ceb022.png">
<br>
[Miro BruBoard](https://miro.com/app/board/uXjVP1oyu60=/#tpicker-content)
### Tech Stack
![rubyonrails](https://img.shields.io/badge/rubyonrails-6.0.6-000000?style=for-the-badge&logo=rubyonrails&logoColor=red)
<br>
![ruby](https://img.shields.io/badge/ruby-2.7.4-000000?style=for-the-badge&logo=ruby&logoColor=red)
<br>
![json](https://img.shields.io/badge/json-000000?style=for-the-badge&logo=json&logoColor=white)
<br>
![postgresql](https://img.shields.io/badge/postgresql-000000?style=for-the-badge&logo=postgresql&logoColor=light-blue)
<br> 
![Bootstrap](https://img.shields.io/badge/bootstrap-000000?style=for-the-badge&logo=bootstrap&logoColor=white)
<br> 
![Heroku](https://img.shields.io/badge/heroku-000000.svg?style=for-the-badge&logo=heroku&logoColor=%23430098)
<br>
![HTML5](https://img.shields.io/badge/html5-000000.svg?style=for-the-badge&logo=html5&logoColor=23E34F26)
<br>
![Markdown](https://img.shields.io/badge/markdown-000000.svg?style=for-the-badge&logo=markdown&logoColor=white)
<br>
![Miro](https://img.shields.io/badge/Miro-000000?style=for-the-badge&logo=Miro&logoColor=yellow)
<br>
 

### Deployment
[Brücycle Website](https://brucycle-fe.herokuapp.com/)

### Contributors

<table>
  <tr>
    <th>Sean Culliton</th>
    <th>Ashley Turner</th>
    <th>Kristen Nestler</th>
    <th>James White</th>
    <th>Naomi Yocum</th>
    <th>Mike Dao<br>(Project Manager)</th>
  </tr>
  <tr>
    <td><img src="https://avatars.githubusercontent.com/u/108320490?s=120&v=4"></td>
    <td><img src="https://avatars.githubusercontent.com/u/105073232?s=120&v=4"></td>
    <td><img src="https://avatars.githubusercontent.com/u/103780823?s=120&v=4"></td>
    <td><img src="https://avatars.githubusercontent.com/u/108167041?s=120&v=4"></td>
    <td><img src="https://avatars.githubusercontent.com/u/102825498?s=120&v=4"></td>
    <td><img src="https://avatars.githubusercontent.com/u/3011748?s=120&v=4"></td>
  </tr>
 
  <tr>
    <td>
       <a href="https://github.com/smculliton" rel="nofollow noreferrer">
          <img src="https://i.stack.imgur.com/tskMh.png" alt="github"> Github
      </a><br>
        <a href="https://www.linkedin.com/in/seanculliton" rel="nofollow noreferrer">
          <img src="https://i.stack.imgur.com/gVE0j.png" alt="linkedin"> LinkedIn
      </a>
    </td>
    <td>
      <a href="https://github.com/ashuhleyt"  rel="nofollow noreferrer">
          <img src="https://i.stack.imgur.com/tskMh.png" alt="github"> Github
        </a><br>
      <a href="https://www.linkedin.com/in/ashuhleyt/" rel="nofollow noreferrer">
    <img src="https://i.stack.imgur.com/gVE0j.png" alt="linkedin"> LinkedIn
        </a>
    </td>
    <td>
      <a href="https://github.com/knestler" rel="nofollow noreferrer">
          <img src="https://i.stack.imgur.com/tskMh.png" alt="github"> Github
        </a><br>
      <a href="https://www.linkedin.com/in/kristen-nestler/ rel="nofollow noreferrer">
    <img src="https://i.stack.imgur.com/gVE0j.png" alt="linkedin"> LinkedIn
        </a>
    </td>
    <td>
      <a href="https://github.com/James-E-White"  rel="nofollow noreferrer">
          <img src="https://i.stack.imgur.com/tskMh.png" alt="github"> Github
        </a><br>
      <a href="https://www.linkedin.com/in/james-ed-wh/" rel="nofollow noreferrer">
    <img src="https://i.stack.imgur.com/gVE0j.png" alt="linkedin"> LinkedIn
        </a>
    </td>
    <td>
      <a href="https://github.com/naomiyocum" rel="nofollow noreferrer">
          <img src="https://i.stack.imgur.com/tskMh.png" alt="github"> Github
        </a><br>
      <a href="https://www.linkedin.com/in/naomiyocum/" rel="nofollow noreferrer">
    <img src="https://i.stack.imgur.com/gVE0j.png" alt="linkedin"> LinkedIn
        </a>
    </td>
    <td>
      <a href="https://github.com/mikedao" rel="nofollow noreferrer">
          <img src="https://i.stack.imgur.com/tskMh.png" alt="github"> Github
            </a><br>
            <a href="https://www.linkedin.com/in/michaeldao/" rel="nofollow noreferrer">
    <img src="https://i.stack.imgur.com/gVE0j.png" alt="linkedin"> LinkedIn                                                         
        </a><br>
    </td>
  </tr>
</table>
