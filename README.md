# GoPhish Phishing Awareness Lab

## Project Overview
This project demonstrates a controlled phishing awareness simulation conducted in a secure lab environment using **GoPhish**. The objective was to understand common phishing techniques, analyze user interaction, and explore defensive strategies that organizations can use to reduce social engineering risk.

⚠️ **Ethical Notice:**  
This lab was performed using isolated infrastructure and test accounts only. No real users, credentials, or external targets were involved.

---

## Lab Architecture

<p align="center">
  <img src="Architecture.png" width="600">
</p>

### Environment Components
1. Deployed a locally hosted GoPhish server to manage phishing simulation campaigns.  
2. Configured a test SMTP sending profile to safely distribute simulated phishing emails.  
3. Hosted a controlled landing page to capture interaction metrics.  
4. Analyzed campaign data through the GoPhish dashboard to evaluate behavioral risk.  

---

## Campaign Dashboard

<p align="center">
  <img src="CampaignDashboard.png"width="700">
</p>

The GoPhish dashboard provided centralized visibility into campaign performance, enabling monitoring of email delivery, opens, clicks, and overall engagement.

---

## Email Template Example

<p align="center">
  <img src="EmailTemplate.png" width="700">
</p>

A realistic email scenario was created to replicate common phishing tactics such as urgency and account verification prompts.

---

## Landing Page Simulation

<p align="center">
  <img src="LandingPage.png" width="700">
</p>

The landing page was hosted within the lab to safely track user interaction after link clicks without collecting sensitive information.

---

## Campaign Results

<p align="center">
  <img src="CampaignResults.png" width="700">
</p>

Metrics collected from the simulation helped illustrate how phishing attacks succeed and reinforced the importance of user awareness training.

---

## Tools & Technologies
- GoPhish  
- Linux  
- SMTP Configuration  
- HTTP/HTTPS  
- Networking Fundamentals  
- Security Awareness Practices  

---

## Skills Demonstrated
- Phishing attack simulation in a controlled environment  
- Security-focused infrastructure setup  
- Social engineering risk analysis  
- Technical documentation  
- Threat awareness and defensive thinking  

---

## Key Takeaways
- Users are more likely to engage with emails that create urgency.
- Sender domain verification is critical in identifying phishing attempts.
- Security awareness training significantly reduces organizational risk.

---

## Future Improvements
- Deploy the lab using Docker for portability  
- Integrate logs with a SIEM for alert simulation  
- Create multiple phishing scenarios for behavioral comparison  
- Implement defensive email filtering rules  

---

## Author
**Damian Chevalier**  
Cybersecurity Enthusiast | Aspiring SOC Analyst

