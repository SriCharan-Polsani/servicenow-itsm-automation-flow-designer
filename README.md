# Incident & Request Automation – ServiceNow Flow Designer Project

## 📌 Overview  
This project automates the routing, approval, and notification processes for **Incident** and **Service Request** tasks using **ServiceNow Flow Designer**.  
It reduces manual effort, speeds up response time, and improves SLA performance.

---

## 🎯 Problem Statement  
IT support teams spend significant time:  
- Manually routing tickets  
- Requesting approvals  
- Sending notifications  
- Tracking SLA progress  

This leads to delays and SLA breaches.

---

## ✅ Solution  
A fully automated Flow Designer workflow that:  
- Identifies assignment group based on category/subcategory  
- Sends approval tasks automatically  
- Triggers multi-level notifications  
- Escalates when SLA is about to breach  
- Logs all actions in Work Notes  

---

## 🛠️ Technologies Used  
- ServiceNow Flow Designer  
- ServiceNow ITSM (Incident, Request)  
- SLA Engine  
- Email & In-app Notifications  
- Assignment Rules  

---

## 🔄 Workflow Design (High-Level)  
1. User submits an **Incident** or **Request** in the ServiceNow portal  
2. Flow Designer trigger runs on record creation  
3. Category / Subcategory are checked to determine the correct **Assignment Group**  
4. If approval is required, an **Approval Task** is generated and routed to the approver  
5. Notifications are sent to:
   - The end user  
   - The assignment group  
6. SLAs are monitored and if thresholds are breached, **escalation logic** reassigns or notifies leads  
7. Work notes are updated automatically with key actions taken by the flow  

---

## ⭐ Key Features  
- Auto-assignment of tickets based on routing rules  
- Automated approvals using Flow Designer actions  
- SLA-based monitoring and escalation  
- Multi-channel notifications (email / in-app)  
- Automatic work note updates for better ticket history  

---

## 🚀 Impact  
- Reduced manual routing and approvals  
- Faster response and resolution times  
- Better SLA compliance  
- Improved visibility into ticket lifecycle  

---

## 📈 Future Enhancements  
- Integrate with **Active Directory** for automated access provisioning  
- Add dashboards for automation success & failure rates  
- Use Predictive Intelligence for automatic ticket categorization  
