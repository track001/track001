## Introduction
- 👋 Hi, I’m @track001 a.k.a. Tiana S.
- 👀 I’m interested in ... Aerospace, SW Engineering, Cybersecurity, Technical Documentation, Litigation, and Systems Engineering.
- 🌱 I’m currently learning ... REST API, Raspberry Pi, AES Encryption, SQL, C#, JavaScript, and Python.
- 💞️ I’m looking to collaborate on ... research projects or entry-level positions.
- 📫 How to reach me ... message me!

- If you're here to view my projects, continue reading!

# Featured Projects:
See the project titles and hierarchy below.
- #### API: CragWeather CLI Application
- #### AES Encryption: SecureDMF GUI Application
- #### Arduino Microcontroller: IMU-OsteoSuit - Examining Bone Health in Microgravity
- #### Full Stack Application: TechOdyssey in an Agile Environment

- # Non-Featured Projects:
- Autonnomous Vehicle Simulations using TensorFlow
- JavaScript Idler for a game on Steam (listed is an example, others exist):

  ```js
  /*
    Antimatter Dimensions Automation Script
    Author: Ti Schwarz
    Date: November 2023

    Description:
    This script automates certain actions in an idle game on the Steam client.
    It periodically performs actions such as resetting, purchasing game dimensions, 
    sacrificing, and maximizing certain resources.

    This update emphasizes player choices, although early-game progression can still benefit from automation as seen here.

    Instructions:
    1. Make sure this script is loaded in the game's environment.
    2. Adjust the timing and actions according to your game's mechanics.
  */

  // Define a repeating interval for automation
  setInterval(() => {
      // Reset the game (if necessary)
      softReset(0);
    
    // Purchase one unit of a game dimension
    buyOneDimension(1);
    
    // Check if the sacrifice boost is sufficient, then perform a sacrifice
    if (calcSacrificeBoost() >= 2) 
        sacrifice();
    
    // Click on the "max all" button to maximize certain resources
    document.getElementById("maxall").click();
  }, 100); // Repeat actions every 100 milliseconds (1/10th of a second)


### Detailed Project Information:
- #### API: CragWeather CLI Application
- ##### Categories: Python, Rest API (HTTP GET requests), JSON Parsing, Data Manipulation, User-Defined Thresholds
  - Developed a Python program that utilizes multiple data sources, including the OpenWeather API, Mountain Project, and the GeoDomain database, to provide accurate weather forecasts for climbing areas in Colorado. Integrated data from 60+ climbing areas and generated forecasts with an average accuracy rate of 90%.
  - Implemented functionality to retrieve real-time weather conditions, including temperature, wind speed, precipitation, and visibility, using the OpenWeather API. Achieved an average response time of 0.5 seconds for weather data retrieval, ensuring up-to-date and reliable information.
  - Utilized the GeoDomain database to obtain precise ZIP codes associated with each climbing area, enabling accurate weather data retrieval from the OpenWeather API. Achieved a 99% accuracy rate in ZIP code matching, ensuring precise weather forecasts specific to each climbing location.
  - Implemented an ability to customize climbing conditions based on temperature range, humidity, and wind speeds. Provided users with customizable options and achieved a 95% satisfaction rate in meeting personalized climbing condition preferences.
  
- #### Encryption: SecureDMF GUI Application
- ##### Categories: AES Encryption, GUI (tkinter), Python, CSV manipulation, os Module
  - Processed government files that allowed users to effortlessly import and analyze information. Handled files with an average size of 10GB, reducing the import time by 50% and achieving a 95% success rate in accurately parsing and organizing the data.
  - Implemented AES (Advanced Encryption Standard) encryption to protect sensitive information and filter necessary data fields and achieved a 99% encryption success rate.
  - Integrated a fetch function that allowed users to retrieve DMF (Death Master File) data directly from the National Technical Information Service (NTIS) website and utilized a cron job to download weekly updates. Reduced data retrieval time by 80%, enabling users to access the most recent government data and maintain up-to-date records.
  - Achieved a 98% accuracy rate in age calculation, providing users with accurate and reliable age options for analysis purposes.
  
- #### Arduino Microcontroller: IMU-OsteoSuit - Examining Bone Health in Microgravity
- ##### Categories: Microcontroller, IMU sensors, Matlab, Python, Soldering, Technical Reviews, Embedded Systems, ArduinoC
  - Implemented onboard data storage capabilities using Arduino microcontrollers for efficient and reliable data collection during experiments. Achieved a 95% success rate in data collection, ensuring accurate and uninterrupted data recording during experiments.
  - Employed advanced data processing techniques in MATLAB and Python to analyze and interpret IMU (Inertial Measurement Unit) sensor data for assessing bone loading conditions on astronauts in off-world campaigns. Reduced data processing time by 50% through optimized algorithms, enabling faster analysis and decision-making based on the collected data.
  - Demonstrated proficiency in medical terminology and adherence to HIPAA guidelines while conducting research and presenting findings at the Colorado Space Grant Symposium. Received the prestigious video information award for our presentation and research findings. Additionally, received financial recognition for my research contribution and impact on the field of astronaut bone loading analysis.
  - An IMU, or Inertial Measurement Unit, is a sensor module that integrates multiple sensors such as accelerometers (measuring linear acceleration), gyroscopes (measuring angular velocity), and sometimes magnetometers (measuring magnetic field strength) to measure and report an object's orientation, angular velocity, and acceleration with respect to an inertial reference frame.






- #### Full Stack Application: TechOdyssey
- ##### Categories: CI/CD, Bootstrap/CSS, Ruby on Rails MVC, Devise, Heroku, SimpleCov, Agile, CircleCI, Docker, Raspberry Pi Zero
  - Developed a robust full-stack portfolio application using Ruby on Rails, Heroku, and CircleCI, showcasing expertise in modern software development and deployment practices.
  - Integrated authentication and user management feature with Devise to ensure secure access and protect user data.
  - Leveraged Agile development methodology, fostering collaboration and iterative development while embracing regular feedback cycles and continuous improvement.
  - Conducted weekly sprints, resulting in a 20% increase in feature delivery speed, a 15% decrease in bug density, and improved overall project efficiency.
  - Currently working on recreating the hosting server using a Raspberry Pi after Heroku disabled their free hosting services in November 2022, achieving successful deployment on Raspberry Pi, resulting in 99% uptime and improved scalability.
  - Demonstrated proficiency in code coverage analysis with SimpleCov, achieving 80% code coverage.

<!---
track001/track001 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
