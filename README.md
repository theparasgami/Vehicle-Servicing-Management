![image](https://user-images.githubusercontent.com/76521428/136322672-09fb169c-555c-48fd-bdeb-5eb51aa40e94.png)

<h1 align="center"> Vehicle Servicing Management </h1>
Vehicle Service Management is a software application that aims to minimize the effort put in by companies to maintain their transactions and vehicle booking system. It manages all the transactions related to Customer profiling, Vehicle Service Bookings and Booking Details of the company. <br /> <br />
In this software, anyone with a legal email ID can be added to the system as a customer. Customers can use the software only after they are registered to the system. One of the important perks of registration is that customers can opt for email reminders.

## Technologies Used
![HTML5](https://img.shields.io/badge/-HTML5-white?color=ff6529&style=for-the-badge&logo=HTML5&logoColor=white&logoWidth=20)
![CSS3](https://img.shields.io/badge/-CSS3-orange?color=264DE4&style=for-the-badge&logo=CSS3&logoColor=white&logoWidth=20)
![Javascript](https://img.shields.io/badge/-javascript-white?style=for-the-badge&logo=javascript&logoColor=white&logoWidth=20&color=F1DB4E)
![EJS](https://img.shields.io/badge/-EJS-A81F50?style=for-the-badge&logo=EJS&logoColor=white&logoWidth=20)
![NodeJS](https://img.shields.io/badge/-Node-orange?color=8BBF3F&style=for-the-badge&logo=NODE&logoColor=white&logoWidth=20)
![Express](https://img.shields.io/badge/-Express-orange?color=8BBF3F&style=for-the-badge&logo=Express&logoColor=white&logoWidth=20)
![NPM](https://img.shields.io/badge/-NPM-brightgreen?color=DC2C34&style=for-the-badge&logo=NPM&logoColor=white&logoWidth=20)
![MYSQL](https://img.shields.io/badge/-mySQL-orange?color=4579A0&style=for-the-badge&logo=mysql&logoColor=white&logoWidth=20)


Here are the steps you need to do to run the project locally:

1. **Fork** this repo in your profile.
2. **Clone the forked repository** in your system, by using this command in your Git bash/Command Prompt. <br />
   Make sure you replace `<your-username>` with your Github username

   ```
   git clone https://github.com/<your-username>/Vehicle-Servicing-Management.git
   ```
  
3. Make a seperate **branch**, other than main, to make changes in this project.
   ```
   git branch <branch-name>
   ```
4. Start the XAMPP (Apache and MYSQL) server in your system and make a blank Database named `vsm`, using XAMPP.
5. In the project directory, go to `server` folder and run the following command in terminal: 
   ```
   npm install
   ``` 
   After all the node modules gets downloaded, run:
   ```
   npm start
   ```
6. This will start the project in `localhost` server at port `8000`. Write `localhost:8000` in your browser to see the UI of the project.   
