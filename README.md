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
  <a href="https://github.com/cmash93/caffeine-and-coding">
    <img src="public/images/logo.png" alt="Logo" width="180" height="180">
  </a>

<h1 style="font-size:35px;" align="center">(caffeine &amp;&amp; coding)</h1>

  <p align="center" style="font-size:18px;">
    Caffeine &amp;&amp; Coding is a CMS style blog that gears towards conversations about coding, tech, and the like. Whether you would like to share your most recent coding epiphany or just a game review, Caffeine &amp;&amp; Coding can serve as an open and inviting space to just talk tech!
    <br />
    <a href="https://github.com/cmash93/caffeine-and-coding"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://desolate-dusk-37866.herokuapp.com/" target="blank" >Live Website</a>
        ·
    <a href="https://github.com/cmash93/caffeine-and-coding/issues">Report Bug</a>
    ·
    <a href="https://github.com/cmash93/caffeine-and-coding/issues">Request Feature</a>
  </p>
</div>

<!-- TABLE OF CONTENTS -->

<!-- ABOUT THE PROJECT -->

## Built With

- [![Node][node.js]][node-url]
- [![Express][express]][express-url]
- [![Sequelize][sequelize]][sequelize-url]
- [![MYSQL][mysql]][mysql-url]
- [![Handlebars][handlebars]][handlebars-url]
- [![Bootstrap][bootstrap.com]][bootstrap-url]

<!-- GETTING STARTED -->

## Prerequisites

- npm
  ```sh
  npm install npm@latest -g
  ```

## Installation

1. Clone the repo
   ```sh
   git clone https://github.com/cmash93/caffeine-and-coding.git
   ```
2. Install NPM packages
   ```sh
   npm i
   ```
3. Access MYSQL to create the database
   ```sh
   mysql -u <username> -p
   ```
   ```sh
   SOURCE db/schema.sql
   ```
4. Access prepopulate data from seeds.<br>
 <i><b>Note:</b> the seed data is for visual reference only. You will not be able to sign in with this data due to the use of bcrypt.</i>
   ```sh
   npm run seed
   ```
5. Start the server
   ```sh
   npm start
   ```

<!-- USAGE EXAMPLES -->

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

<!-- LICENSE -->

## License

Distributed under the MIT License.

<!-- CONTACT -->

## Contact

Courtney Ashley Farzam - cmash93@outlook.com

Project Link: [https://github.com/cmash93/caffeine-and-coding](https://github.com/cmash93/caffeine-and-coding)

<!-- ACKNOWLEDGMENTS -->

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->

[contributors-shield]: https://img.shields.io/github/contributors/cmash93/E-Commerce-Back-End.svg?style=for-the-badge
[contributors-url]: https://github.com/cmash93/E-Commerce-Back-End/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/cmash93/E-Commerce-Back-End.svg?style=for-the-badge
[forks-url]: https://github.com/cmash93/E-Commerce-Back-End/network/members
[stars-shield]: https://img.shields.io/github/stars/cmash93/E-Commerce-Back-End.svg?style=for-the-badge
[stars-url]: https://github.com/cmash93/E-Commerce-Back-End/stargazers
[issues-shield]: https://img.shields.io/github/issues/cmash93/E-Commerce-Back-End.svg?style=for-the-badge
[issues-url]: https://github.com/cmash93/E-Commerce-Back-End/issues
[license-shield]: https://img.shields.io/github/license/cmash93/E-Commerce-Back-End.svg?style=for-the-badge
[license-url]: https://github.com/cmash93/E-Commerce-Back-End/blob/main/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/courtneyashleyfarzam
[product-screenshot]: images/screenshot.png
[node.js]: https://img.shields.io/badge/node.js-000000?style=for-the-badge&logo=nodedotjs&logoColor=white
[node-url]: https://nodejs.org/en/
[react.js]: https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB
[react-url]: https://reactjs.org/
[vue.js]: https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D
[vue-url]: https://vuejs.org/
[angular.io]: https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white
[angular-url]: https://angular.io/
[svelte.dev]: https://img.shields.io/badge/Svelte-4A4A55?style=for-the-badge&logo=svelte&logoColor=FF3E00
[svelte-url]: https://svelte.dev/
[laravel.com]: https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white
[laravel-url]: https://laravel.com
[bootstrap.com]: https://img.shields.io/badge/Bootstrap-2A52BE?style=for-the-badge&logo=bootstrap&logoColor=white
[bootstrap-url]: https://getbootstrap.com
[jquery.com]: https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white
[jquery-url]: https://jquery.com
[sequelize]: https://img.shields.io/badge/sequelize-2FC21D?style=for-the-badge&logo=sequelize&logoColor=white
[sequelize-url]: https://sequelize.org/
[express]: https://img.shields.io/badge/express-563D7C?style=for-the-badge&logo=express&logoColor=white
[express-url]: https://expressjs.com/
[mysql]: https://img.shields.io/badge/mysql-DD0031?style=for-the-badge&logo=mysql&logoColor=white
[mysql-url]: https://www.mysql.com/
[handlebars]: https://img.shields.io/badge/Handlebars-ffffff?style=for-the-badge&logo=bootstrap&logoColor=black
[handlebars-url]: https://handlebarsjs.com/
