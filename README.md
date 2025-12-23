## Title of the Project
URL SHORTENER
## About
This project is a Full Stack URL Shortener Web Application developed using React JS, Tailwind CSS, and Supabase. The system allows users to convert long URLs into short, easy-to-share links. It includes user authentication, QR code generation, automatic redirection, and a user-specific dashboard to manage shortened URLs.
The application also provides an Admin Panel for monitoring and controlling all URLs created by different users. This project demonstrates the practical implementation of frontend, backend, authentication, and database integration in a real-world web application.

## Features
-> User Signup & Login Authentication</br>
-> Secure URL Shortening</br>
-> Redirection using short links</br>
-> QR Code Generation for each short URL</br>
-> User-wise Dashboard to view history</br>
-> Copy & Delete URLs</br>
-> Animated Modern UI</br>
-> Secure Database using Supabase</br>
-> Logout & Session Handling</br>

## Requirements
### Software Requirements
-> Node.js</br>
-> NPM</br>
-> VS Code / Any Code Editor</br>
-> Web Browser (Chrome / Edge)</br>
-> Supabase Account</br>
-> React 18+</br>
-> Tailwind CSS</br>

### Hardware Requirements
-> System with minimum 4GB RAM</br>
-> Internet Connection</br>
-> Any modern CPU</br>

## System Architecture
The architecture of the Secure URL Shortener Web Application is based on a Client–Server Model with cloud backend services (Supabase).</br>
1.The User accesses the application through a Web Browser.</br>
2.The Frontend (React JS + Tailwind CSS) handles:</br>
  -> User Interface</br>
  -> Form input</br>
  -> Authentication requests</br>
  -> Display of shortened URLs and dashboards</br>
3.The frontend communicates with Supabase Backend using REST APIs & SDK.</br>
4.Supabase provides:</br>
  -> Authentication Service (Login, Signup, Session)</br>
  -> Database Service (Store URLs, Users)</br>
5.When a user enters a long URL:</br>
  -> A short code is generated (NanoID).</br>
  -> The data is stored in the Supabase Database.</br>
6.When a short URL is accessed:</br>
  -> The Redirect Module fetches the original URL.</br>
  -> The user is redirected to the original website.</br>
7.The Admin Panel fetches all users’ URLs for monitoring and control.</br>

<img width="1024" height="1536" alt="image" src="https://github.com/user-attachments/assets/41d509e4-7032-4849-b7c3-3177d2c645d5" />

## Output

<!--Embed the Output picture at respective places as shown below as shown below-->
#### Output1 - LOGIN PAGE 

<img width="1470" height="923" alt="Screenshot 2025-11-30 at 7 04 45 PM" src="https://github.com/user-attachments/assets/8f5ed73f-f009-44c9-aa43-0100368241a4" />

#### Output2 - HOME PAGE 

<img width="1470" height="923" alt="Screenshot 2025-11-30 at 7 05 11 PM" src="https://github.com/user-attachments/assets/c3fea411-fc4d-47ee-a933-0e443f08e708" />

#### Output3 - DASHBOARD 

<img width="1470" height="925" alt="Screenshot 2025-11-30 at 7 06 46 PM" src="https://github.com/user-attachments/assets/3ff3db1a-9042-425d-8532-53e4668cbc84" />


## Results

Users can log in, shorten URLs, and generate QR codes successfully.</br>
Short URLs are stored and redirected correctly using Supabase</br>
Dashboard and logout features work properly.</br>
The application is responsive and user-friendly.</br>

## Impact

Makes long URLs easy to share.</br>
Improves user productivity and security.</br>
Demonstrates real-time full-stack web development.</br>
Project is scalable for real-world use.</br>

## Articles published / References

Supabase Documentation – https://supabase.com/docs</br>
React Official Documentation – https://react.dev</br>
Tailwind CSS Documentation – https://tailwindcss.com/docs</br>
NanoID Documentation – https://github.com/ai/nanoid</br>
QRCode Generator Library – https://www.npmjs.com/package/qrcode</br>
MDN Web Docs – https://developer.mozilla.org</br>



