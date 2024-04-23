# hackathlonF5_marketplace
<h1>startUpCommunity</h1>

![1e2645b96bc33f257d77cea4d99a6d2d](https://user-images.githubusercontent.com/114645883/221011831-0dff3969-b7db-4d7b-af22-2ec5194f05ed.png)

<p> You are in front of the Hackathon 2023 final project. We are very happy to reach this point of training development thanks to our respective guides. We know, we have the ability to face this small but intense challenge: constant communication with our team, organizing tasks using agile scrum, strengthening our knowledge to refactor and document new tools. We thank our sponsor, CaixaBank, for this academic challenge. Our development team is made up of our Product Owner Ainhoa, Scrum Judit and, although in fact we all act as developers, our developers Georgette, Carlos, Ana, Bryan, Caren, Natalia and Alba. Our goal is to create a new product according to our client's requirements. <p>
  
<h2>1. MVP client's requirements:</h2>
<ul>
 <li> To create a marketplace </li>
<li> To create adds and publish them.</li>
<li> User as visitor</li>
<li> Clients must pay for advertising their services</li>
<li> Contact client-user </li>
</ul>

We offer as a scalable projec:
1.A marketplace in which the objective will be to create a community of developers who want to start a startup and need collaborators.
2. The theme of the startup projects will be exclusive to specific themes that we believe could improve our future. Climate anxiety, the ghost of Nazism, classism and sexism and the big lie of unlimited economic growth are leading us to deep unease, and we believe that through technological means we can help our environment a little to stop being hostile.
3. This platform is focused on junior technological or development profiles who want to contribute something valuable by joining together in this startup community. You will be able to access the profile of colleagues, see their concerns and skills in the IT area and, if you want to develop a common theme, click on your favorites. If there is a match they can then get in touch.

![73322dd86f7b8e28e2b70142a3c954e9](https://user-images.githubusercontent.com/114645883/221011982-27967cc4-1387-4987-aad3-806f5d47c519.png)

<h2>2. User stories:</h2>
<ul>
<li>As an user, I want to access all the views to be able to find out about all the content on the platform. </li>
<li>As an user, I want an intuitive and simple design to move between the different screens.</li>
<li>As an user, I want to access advertiser information to check if there is a project that I like.</li>
<li>As an user, I want a favorites list so I can get in touch with them if I finally want to participate in a project.</li>
<li>As an user, I want to access the posts of the announcers.</li>
<li>As a user, I want to be able to be identified equally as a user-client to benefit from the horizontality of the app and search for colleagues.</li>
</ul>


## 3. Team Members

| Name | Role | GitHub |
| :--- | :---: | :---: | 
| Judit Calvet |  Scrum Master | https://github.com/Judit-Calvet | 
| Aihnoa Cala | Product Owner | https://github.com/acalabustos | 
| Carlos Sanchez  | Developer | https://github.com/Holapueblodev | 
| Ana Delgado | Developer | https://github.com/anadelccc | 
| Georgette Palomo | Developer| https://github.com/georgette949 | 
| Alba Rus  | Developer| https://github.com/Albaric0que | 



<h2>5. Final Design</h2> 
<div style="heigth:auto; display:flex; flex-wrap:wrap; justify-content:center; padding:1rem">

![Mockup (1)](https://user-images.githubusercontent.com/114645883/221018815-95c1c4e6-3d78-4cf4-87dd-b1c1ed8a4a92.png)

</div>


<h2>6. Stacks</h2>
<ul>
<li>HTML5</li>
<li>CSS3</li>
<li>JavaScript</li>
<li>PHP 8.1.10</li>
<li>Laravel</li>
<li>Boostrap 5</li>
<li>DrawSQL</li>
<li>MySQL</li>
</ul>

<h2>7. Required:</h2>
<li>Composer & Laravel Installed</li>
<li>XAMPP/LAMPP Installed</li>
<li>NPM Installed</li>
<li>MySQL</li>
<li>PHP</li>
<li>PHP Artisan Serve</li>

<h2>8. How to install this project:</h2>

You will need a text editor and perform the following steps:

1. Clone the project
```bash
  git clone https://github.com/Holapueblodev/hackathlonF5_marketplace
```

2. Go to the project directory
```bash
  cd (nombre carpeta aquí)
```

3. Create a MySQL database named "marketplace"

4. Locate .env.example in the project and once there change the database name that comes by default for our database name (laravel for springfieldelementaryschool). After that, remove .example from the file name so its new name will be .env

5. Install dependencies
```bash
  npm install
```
```bash
  composer install
```

6. Activate the server and keep this terminal open
```bash
  npm run dev
```

7. Run the PHP server and keep this terminal open
```bash
  php artisan serve
```

8. Import database
```bash
  php artisan migrate:fresh --seed
```

***

 <h2>9. Tests</h2>

To run the php tests, execute the following command:
```bash
  php artisan test
```
<img width="259" alt="Screenshot test" src="public/css/img/phpTest.png">


To run the vendor tests, execute the following command:
```bash
  vendor/bin/phpunit
```
<img width="259" alt="Screenshot test" src="public/css/img/vendorTest.png">


<h2>10. Methodology:</h2>
<ul>
<li>Mob programming.</li>
<li>Pair programming.</li>
<li>Agile with SCRUM</li>
<li>TDD</li> 
</ul>
