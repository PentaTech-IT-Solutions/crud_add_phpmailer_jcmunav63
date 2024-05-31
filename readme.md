**Project's name: CRUD Add PHPMailer**

<a name="readme-top"></a>
<div align="center">
    <img src="/logo_jcm_md.png" alt="main-logo" width="500"  height="auto" />
  <br/>
  <h3><b>CRUD Add PHPMailer</b></h3>
</div>

📗 Table of Contents <a name="table_of-contents"></a>

- [📗 Table of Contents](#table-of-contents)
- [📖 About project ](#about-project)
  - [🛠 Built With ](#-built-with-)
    - [Tech Stack ](#tech-stack-)
    - [Key Features ](#key-features-)
  - [💻 Getting Started ](#-getting-started-)
    - [Prerequisites](#prerequisites)
    - [Setup](#setup)
    - [Install](#install)
    - [Usage](#usage)
  - [👥 Author ](#-author-)
  - [🙏 Acknowledgments ](#-acknowledgments-)
  - [📝 License ](#-license-)

## 📖 About project - CRUD Add PHPMailer<a name="about-project"></a>

This CRUD Project application is a PHP project to create a simple CRUD Web Application for users management. In this project we are adding the email sending functionality using the PHPMailer library. This project uses PHP version 8.2.12, MariaDB database server version 10.4.32, and two external libraries called domPDF and PHPMailer. This project is part of the Pentatech IT Solutions PHP Internship program.


## 🛠 Built With <a name="built-with"></a>

### Tech Stack <a name="tech-stack"></a>

  <ul>
    <li><a href="https://www.apachefriends.org/download.html">XAMPP</a></li>
    <li><a href="https://www.php.net/downloads.php">PHP v 8.2.12</a></li>
    <li><a href="https://mariadb.org/download/">MariaDB v 10.4.32</a></li>
  </ul>

### Key Features <a name="key-features"></a>
- **Login and Signup forms, with session management, developed in the first project.**
- **Team users dashboard, including name, position, email, photo, and details. All CRUD operations were implemented in the second project.**
- **Team users list and user deatils PDF report, using the domPDF library, implemented in the third projec.**
- **Email creation and sending usinf¿g the PHPMailer library. This is the fourth project.**


<p align="right">(<a href="#readme-top">back to top</a>)</p>

## 💻 Getting Started <a name="getting-started"></a>

To get a local copy up and running, follow these steps.

### Prerequisites

In order to run this project you need:

[Install XAMPP](https://www.apachefriends.org/download.html)

Prerequisites: XAMPP application, including Apache web server, PHP (version 8), and MySQL DB server or MariaDB server. You can use a code editor like Visual Studio Code...

### Setup
Clone the crud_add_phpmailer_jcmunav63 repo. You can clone this project inside of XAMPP's public folder called htdocs (in Windows C:\xampp\htdocs).

```sh
  cd C:\xampp\htdocs
  git clone https://github.com/PentaTech-IT-Solutions/crud_add_phpmailer_jcmunav63
```

### Install

This project requires the following dependencies: the PHP interpreter, the Apache Web Server, a MySQL or MariaDB database server, the dependency manager Composer, and the third-party libraries called domPDF and PHPMailer. The first three components are bundled into XAMPP application (for Windows or Linux). Other similar software applications are WAMP (for Windows), LAMP (for Linux), and MAMP (for Mac). The Composer, the domPDF, and the PHPMailer components are installed using a command terminal.


### Database

Create a database using the url "localhost/phpmyadmin" in the browser. The PHPMyAdmin application will open to manage the database server.

You can use the file database/team_management.sql using the import tab of the PHPMyAdmin application. It contains all the information to set up the database to start using it.

The SQL file will create the tables and it will insert some example data. Otherwise, you can also use PHPMyAdmin's graphic interface to create the database and the tables.

The suggested tables to use are...
- A users table (it will contain 6 columns, id, username, fullname, email, password, phonenumber).
- A teams table (it will contain 3 columns, id, name, description).
- A members table, (it will include 8 columns, id, teams_id, first_name, last_name, position, department, about, image_url).


### Usage

To run the project, use the browser to enter the following path...

http://localhost/crud_add_phpmailer/index.php

In this home page you will find two links to enter the application, the signup.php form page, if you are not registered yet, or the login.php form page, if you are already registered.
   http://localhost/crud_add_phpmailer/signup.php

   http://localhost/crud_add_phpmailer/login.php

See the images of these two forms below.

<div align="center">
  <img src="/assets/images/signup_form.PNG" alt="Sign up" width="500"  height="auto" />
  <br/>
  <img src="/assets/images/login_form.PNG" alt="Sign up" width="500"  height="auto" />
</div>

After logging in, the user is redirected to a Team members' Dashboard. Here, the user can Create, Read, Update, or Delete (CRUD) a team member.

<div align="center">
  <img src="/assets/images/dashboard.PNG" alt="Sign up" width="600"  height="auto" />
</div>

Here's the form used to Create or Update a team member...

<div align="center">
  <img src="/assets/images/member_form.PNG" alt="Sign up" width="600"  height="auto" />
</div>

And there's also an option to create a new Team, using the following form. The Read, Update, or Delete operations for Teams are also implemented.

<div align="center">
  <img src="/assets/images/team_form.PNG" alt="Sign up" width="350"  height="auto" />
</div>

In the previous project, we added the generation of two PDF reports to export the html content. the first one is the list of members that is displayed in the dashboard, and the second one is a specific details page, selected from the last name's link in the dashboard. The exported file is shown in the dashboard, as a pdf file, and it has a download or a print option for the user.

Here are some example images for these two reports...

  - Members list page (dashboard):
<div align="center">
  <img src="/assets/images/members_list.PNG" alt="Sign up" width="550"  height="auto" /><br />
  <img src="/assets/images/members_list_pdf.PNG" alt="Sign up" width="650"  height="auto" />
</div>

  - Member details page:
<div align="center">
  <img src="/assets/images/member_details.PNG" alt="Sign up" width="550"  height="auto" /><br />
  <img src="/assets/images/member_details_pdf.PNG" alt="Sign up" width="650"  height="auto" />
</div>


<p align="right">(<a href="#readme-top">back to top</a>)</p>


## 👥 Author <a name="author"></a>

👤 **Juan Carlos Muñoz**

- GitHub: [@jcmunav63](https://github.com/jcmunav63)
- Twitter: [@jcmunav63](https://twitter.com/jcmunav63)
- LinkedIn: [@juan-carlos-muñoz](https://www.linkedin.com/in/juan-carlos-mu%C3%B1oz-fullstackdev/)

<p align="right">(<a href="#readme-top">back to top</a>)</p>


## 🙏 Acknowledgments <a name="acknowledgements"></a>

* I would like to acknowledge all the support and help from PentaTech-IT-Solutions.

<p align="right">(<a href="#readme-top">back to top</a>)</p>


## 📝 License <a name="license"></a>

This project is [MIT](./LICENSE) licensed.

<p align="right">(<a href="#readme-top">back to top</a>)</p>
