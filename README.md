# ReachInBox-Frontend

## Overview
This repository contains the code for Reachinbox frontend  App using React with Typescript for an assignment given by Reachinbox.

## Technologies Used ( Frontend )
  - Typescript
  - React
  - Tailwind css

## Deployment

The application is deployed on netlify and can be accessed [here](https://reachinbox-frontend.netlify.app/).


## Login Page

![Screenshot (344)](https://github.com/nithyapriya-din/REACHINBOX-TASK11/assets/128920395/fb0298f0-1fd2-4464-b5e2-8bde53838a7b)

## Landing Page

![Screenshot (346)](https://github.com/nithyapriya-din/REACHINBOX-TASK11/assets/128920395/09ff52fd-5880-454f-ae7d-7520b31a6ef7)

## Deshboard with Dark Mode
 
![Screenshot 2024-04-02 213745](https://github.com/nithyapriya-din/REACHINBOX-TASK11/assets/128920395/b507dfc6-bbd4-45ff-b115-296f5e7099d9)

## Dashboard with Light Mode

![Screenshot (355)](https://github.com/nithyapriya-din/REACHINBOX-TASK11/assets/128920395/8c2f6406-f4a1-408b-a556-255f80a18993)

## Delete Email 

![Screenshot (356)](https://github.com/nithyapriya-din/REACHINBOX-TASK11/assets/128920395/82fb7ea2-2a85-4365-a796-d0d8f89b9e20)



 # How to Run <br/>
 
   <h2>Installation</h2>
   
   Clone the repository:   ``` git clone https://github.com/nithyapriya-din/REACHINBOX-TASK11
   Navigate to the project directory:   ``` cd reachinbox ``` <br/>
   Install the dependencies:   ``` npm install ``` <br/>
   Start the development server:   ``` npm run start ``` <br/>
   Open your browser and visit:   ``` http://localhost:3000 ``` <br/>
   

   ## Features 
   
  - Authentication
  - Get Emails
  - Post (send) Email
  - Delete Email


   <h2>Endpoints</h2>
   <h3>All Emails</h3>
   <pre><code>GET {{baseurl}}/onebox/list </code></pre>

   <h3>All Emails from Onebox</h3>
   <pre><code>GET {{baseurl}}/onebox/messages/:thread_id </code></pre>

   <h3>Add Onebox Mail</h3>
   <pre><code>POST {{baseurl}}/onebox/reply/:thread_id </code></pre>

   <h3>Delete Email</h3>
   <pre><code>DELETE {{baseurl}}/onebox/messages/:thread_id </code></pre>

 
  
