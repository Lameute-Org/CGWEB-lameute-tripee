# Project Setup Guide

This project consists of two main submodules:
- Frontend: Flutter application
- Backend: Spring Boot application

Each submodule is stored in its own repository. Follow the instructions below to clone the main repository with both submodules and set them up on your machine.

## Prerequisites
- Git: Ensure Git is installed.
- Flutter: For frontend development. 
- Java & Spring Boot: For backend development. 

## Cloning the Project
   ## A. Methode 1
1. Clone the Main Repository  
   Clone the main repository, including the submodules:

      ``git clone --recurse-submodules https://github.com/Lameute-Org/CGWEB-lameute-tripee.git``
   

2. Then update each module with command :

   git submodule update --remote --merge

   ## B. Methode 2
1. Clone the Main Repository  
   Clone the main repository using the command :

      git clone https://github.com/Lameute-Org/CGWEB-lameute-tripee.git
   

2. Then add all repo submodules using the command :

   git submodule update --init

3. Then update each module with command :

   git submodule update --remote
   
Each submodule can now be accessed and set up individually.

## Submodule Structure

### Frontend: Flutter Application

- Location: CGWEB-lameute-tripee/flutter-frontend
- Navigate to the frontend folder:

          cd CGWEB-lameute-tripee/flutter-frontend/Tripee
  

### Backend: Spring Boot Application

- Location: CGWEB-lameute-tripee/spring-boot-backend
- Navigate to the backend folder and it's services :

          cd CGWEB-lameute-tripee/spring-boot-backend/tripee/services
    
