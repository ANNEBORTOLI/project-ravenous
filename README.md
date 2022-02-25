<!-- PROJECT LOGO -->

![](/public/logoRavenous.png)
<br />

<p align="center">
  <h2 align="center">Ravenous Project</h2>

  <p align="center">
    A React app to search for restaurants using the Yelp API.
    <br />
  </p>
</p>

## :notebook_with_decorative_cover:Documentation

- [About the Project](#:memo:About-the-Project)
- [Technologies](#:wrench:Technologies)
- [Getting Started](#:memo:Getting-Started)
  - [Clone the Repository](#:pushpin:Clone-the-Repository)
  - [Install Packages](#:pushpin:Install-Packages)
  - [Configure Yelp API](#:pushpin:Configure-Yelp-API)
  - [Run API locally](#:pushpin:Run-API-locally)
- [Usage Example](#:art:Usage-Example)
- [Contact](#:princess:Contact)

<!-- ABOUT THE PROJECT -->

## :memo:About the Project

The Ravenous Project is a front-end application build with JavaScript and React, all with the goal of building a Yelp-like clone using the Yelp API to search for restaurants in your area.

## :wrench:Technologies

![](https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E)
![](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)

<!-- GETTING STARTED -->

## :memo:Getting Started

### :pushpin:Clone the Repository

```sh
   git clone https://github.com/ANNEBORTOLI/project-ravenous
```

### :pushpin:Install Packages

```sh
    npm install
```

### :pushpin:Configure Yelp API

- Create an Yelp account at https://www.yelp.com/;

- Once you login, create a new app using the menu to the left;

- Fill out the required fields for the app, and agree to the terms and conditions and create the app. You should see an “API Key” presented to you;

- Open **Yelp.js** that is inside of the **util** directory and store the string of your API Key from the Yelp API;

- CORS Restrictions:

Due to CORS restrictions your fetch() may not function correctly. To solve this problem just bypass this restriction with CORS Anywhere API.

- Visit **https://cors-anywhere.herokuapp.com/corsdem** and _“Request temporary access to the demo server”_;

- Go to **Yelp.js** file to see the CORS Anywhere URL prepended to the Ravenous URL path;

### :pushpin:Run API locally

```sh
    npm start
```

<!-- USAGE EXAMPLES -->

## :art:Usage Example

- A user may decide to search with a different sorting option: _"Best Match", “Highest Rated”, or “Most Reviewed”_. If not, the default search will be by best matches;

- Choose what kind of business and location your are looking for. These parameters represent the three pieces of information that is going to be sent to the Yelp API.

![Search Bar](/public/searchtOptions.png)

- The business list will be displayed;

![Businesses List](/public/businessesList.png)

<!-- CONTACT -->

## :princess:Contact

<a target="_blank" href="https://github.com/ANNEBORTOLI">
  <img align="left" alt="LinkdeIN" src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" />
</a>
<a target="_blank" href="https://www.linkedin.com/in/anne-bortoli">
  <img align="left" alt="LinkdeIN" src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" />
</a>
<a target="_blank" href="mailto:annebortoli@gmail.com">
  <img align="left" alt="Gmail" src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
</a>
