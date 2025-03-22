# AI-Health-Care

## 💡 Introduction

**Problem Statement**:  Every year, millions of people face life-threatening emergencies due to the unavailability of blood, with many struggling to find immediate blood donors when time is critical. The lack of a streamlined platform for connecting blood donors and recipients exacerbates this issue, resulting in delays that could cost lives.

**Solution**:  The Blood Donation App is designed to address this critical challenge by connecting blood donors with those in need in real-time. Our app ensures that users can quickly find compatible blood donors in their area, making blood donation more accessible and efficient. Through features like emergency alerts, a live donor map, and a health tracker, the app empowers individuals and communities to contribute to life-saving causes. By fostering a network of donors and creating an easy-to-use platform, we aim to reduce the gap in blood availability, saving lives when it matters the most.
With real-time notifications, instant matching, and a supportive community, the Blood Donation App promotes a safer, healthier society by ensuring that blood is always available when needed.


✨ Features
🔹 User-Friendly Interface – Simple and easy-to-use design.

🔹 Live Blood Availability Map – See nearby donors in real time.

🔹 AI-Powered Chatbot – Get instant answers & support.

🔹 Emergency Mode – Notify donors in urgent situations.

🔹 Health Tracker – Keep track of your donation history.

🔹 Community & Recognition – Earn badges and rewards for donating.


## Intro To AI-Health-Care Video

[![Intro To SpoonShare](https://i.imghippo.com/files/fTnl6839vIo.png)
](https://youtu.be/fagBxXos7xE?si=9cu-mIE4HgC6I54P)


### Our Target SDG Goals 🎯

<p align="center">
<img src="https://i.imghippo.com/files/gwb2810TZU.png" alt="" border="0">
<img src="https://i.imghippo.com/files/yCxJ4815BpM.png" alt="" border="0">
<img src="https://i.imghippo.com/files/c2364JZ.png" alt="" border="0">
</p>
AI-Health-Care App is a life-saving Android app designed to revolutionize how we connect blood donors with those in urgent need. Our mission is to eliminate the delays in blood availability, ensuring that every life is protected in critical moments. By fostering a community of regular donors and providing real-time access to blood resources, we aim to make blood donations seamless, efficient, and impactful. Join us in supporting UN Sustainable Development Goal 3 (Good Health and Well-being) by 2030. Together, we can build a world where no one has to wait for blood when every second counts.



## 🛠️ Technologies Used
💻 Flutter – For a seamless cross-platform experience.

📱 Android Studio – Android app development.

☁️ Firebase – User authentication & database management.

🌍 Google Cloud – Secure and scalable cloud storage.

🤖 Google AI Studio – AI-powered chatbot integration.

🔗 Google IDX – Efficient coding environment.

🎨 Figma – UI/UX design for a smooth experience.




📊 Flow Diagram
Here’s a simple overview of how the app works:

🚀 How to Contribute?
We welcome contributors! Follow these steps to get started:
1️⃣ Fork the repository 📂
2️⃣ Clone it to your local machine 🖥️
3️⃣ Make changes (fix a bug, add features) ✏️
4️⃣ Commit & Push 🚀
5️⃣ Create a Pull Request and we’ll review it ✅

❤️ Join Us & Save Lives!
Blood donation is an act of kindness that can save millions of lives. Be a part of this mission and make a difference today!





*Architectural Diagram Explanation for Blood Donation App*  
The architecture of the *Blood Donation App* is designed to ensure seamless interaction between users, secure data management, and real-time updates. The system follows a *multi-layered architecture*, including:  

1️⃣ *User Interface (UI) Layer*  
   - Built with *Flutter*, providing a smooth, cross-platform experience for Android and iOS users.  
   - Designed using *Figma* to ensure an intuitive and user-friendly interface.  
   - Includes key screens like *Home, Find Donors, Emergency Requests, Profile, Chat, and Notifications*.  

2️⃣ *Application Layer (Business Logic)*  
   - Handles *user authentication, **real-time notifications, and **data processing*.  
   - Implements *AI Chatbot* (Google AI Studio) for instant assistance.  
   - Manages the *blood request and donor matching logic*.  

3️⃣ *Database & Backend Layer*  
   - *Firebase Authentication*: Manages user login and verification.  
   - *Firebase Firestore*: Stores donor details, blood requests, and user history securely.  
   - *Google Cloud Functions*: Handles automated background tasks (e.g., sending alerts, matching donors).  

4️⃣ *AI & Real-Time Features*  
   - *Google AI Studio*: Powers chatbot for donor inquiries and guidance.  
   - *Google Maps API*: Enables real-time donor location tracking and blood bank mapping.  
   - *Emergency Mode System: Instantly alerts nearby donors in **urgent cases*.  

5️⃣ *Deployment & Hosting*  
   - *Google Cloud Storage*: Secures medical reports and donor details.  
   - *Google IDX*: Provides a cloud-based development environment for collaboration.  
   - *Firebase Hosting*: Ensures fast and reliable hosting for web-based features.  

---

### *Data Flow in the System*  
1. *User Registration/Login* → Secured via *Firebase Authentication*.  
2. *Search for Blood or Donors* → AI chatbot or manual search.  
3. *Blood Request Sent* → System matches the best donors nearby.  
4. *Emergency Mode Activated (if needed)* → Nearby donors get instant alerts.  
5. *Donor Accepts Request* → Secure chat/call initiated.  
6. *Blood Donation Completed* → Records updated in Firebase Firestore.  
7. *Rewards & Recognition* → System updates donor profile.

## 🛳 User Guide

### Overview
<table style="width: 100%;">
  <tr>
    <td align="center" width="25%">
    <img src="https://i.imghippo.com/files/HlC1305tfw.png" width="120" alt="Converted Image">
    <br>
      <b>Splash Screen</b><br>
      Displays the AI-Health-Care logo upon app launch.
   </td>

     
   <td align="center" width="25%">
       <img src="https://i.imghippo.com/files/FKq7834kgU.png"  width="120" alt="Converted Image"><br>
      <b>Onboarding Screen</b><br>
      Awareness about blood donation.
    </td>

    
 <td align="center" width="25%">
     <img src="https://i.imghippo.com/files/PMcz6399G.png"   width="120" alt="Converted Image">
    <br>
      <b>Log In or Sign Up.</b><br>
User can log in to access their account. Don't have an account? Sign up here.
    </td>

    
 <td align="center" width="25%">
     <img src="https://i.imghippo.com/files/ggW6545fYo.png"  width="120" alt="Converted Image"><br>
      <b>Log in Screen</b><br>
     Login with your email or continue with Google.
    </td>
   
   </tr>
 <td align="center" width="25%">
     <img src="https://i.imghippo.com/files/pEmj1419HjI.png"   width="120" alt="Converted Image"><br>   
  <b>Sign up Screen.</b><br>
     Create an account with your email or sign up using Google.
    </td>

    
 <td align="center" width="25%">
    <img src="https://i.imghippo.com/files/cIbD6268tM.png"   width="120" alt="Converted Image"><br>
 <b>User Information Screen.</b><br>
     Next, add your information to get started.

   
 <td align="center" width="25%">
   <img src="https://i.imghippo.com/files/motL6704SLM.png"    width="120" alt="Converted Image"> <br>
 <b>Home Screen</b><br>
     Lists nearby blood donation centers where blood is available for those in need.</td>
    
    
   <td align="center" width="25%">
 <img src="https://i.imghippo.com/files/jbvi7664Aw.png"   width="120" alt="Converted Image"><br>
       <b>Chatbot Screen</b><br>
    Get instant assistance! Ask questions and learn how to use the app easily.</td>
</table>



# Hello, We are SquadVision
## 🤝 Contributors
We are a team from Deogiri Institute of Engineering And Management Studies Chh. Sambhajinagar and Core Team Members of the  AI-Health-Care Team [GDSC DIEMS](https://gdsc.community.dev/deogiri-institute-of-engineering-and-management-studies-aurangabad/)


     

