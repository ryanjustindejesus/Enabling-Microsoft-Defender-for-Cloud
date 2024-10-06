<h1>Enabling Microsoft Defender for Cloud</h1>

- <b>This tutorial outlines the configuration of Microsoft Defender for Cloud</b>

<h2>Environments and Technologies Used</h2>

- <b>Microsoft Azure</b> 
- <b>Azure Active Directory</b>

<h2>Operating Systems</h2>

- <b>Windows 10</b>


<h2>Configuration Steps</h2>

![image](https://github.com/user-attachments/assets/88c44155-ae89-47db-8e1c-1f14fabd3514)
- <b>Navigate to Microsoft Defender for Cloud</b>
- <b>Click Environment settings</b>
- <b>Edit settings for LAW-Cyber-Lab-01</b>

![image](https://github.com/user-attachments/assets/ba56e4bd-6422-488b-b200-1fbbd7161bd7)
- <b>Turn on Servers and SQL servers on machines and save</b>

![image](https://github.com/user-attachments/assets/5a5b6445-7112-46e8-a9c3-2d63a2431193)
- <b>Click "Data collection" then select "All Events"</b>

![image](https://github.com/user-attachments/assets/873cce07-ebf2-4cdd-a3b9-c3a6aaa6fbe5)
- <b>Edit settings for Azure Subscription"</b>
- <b>Turn on Servers, Databases, Storage, and Key Vault</b>

![image](https://github.com/user-attachments/assets/eb3dbaba-c919-428b-97d7-e33cf6c3cd44)
- <b>Click settings under Monitoring coverage for Servers</b>
- <b>Click edit configuration for Log Analytics agent/Azure Monitor agent</b>

![image](https://github.com/user-attachments/assets/bc8cad7f-54d5-484c-9005-5f87ef9d42d8)
- <b>Select Azure Monitor Agent (Preview)</b>
- <b>Custom Workspace: LAW-Cyber-Lab-01</b>
- <b>Click apply and continue</b>

![image](https://github.com/user-attachments/assets/bcb0edfe-f939-458b-9344-d48130638449)
- <b>Click "Continuous export"</b>
- <b>Click Log Analytics workspace</b>
- <b>Select Security recommendations: All recommendations selected</b>
- <b>Recommendation severity: Low, Medium, High</b>
- <b>Include security findings: Yes</b>
- <b>Secure score: Overall score, Control score</b>
- <b>Security alerts: Low, Medium, High, informational</b>
- <b>Regulatory compliance: No selected standards</b>

![image](https://github.com/user-attachments/assets/ee09484c-2cbb-49e5-af4a-8d52c13a2465)
- <b>Select Subscription: Azure Subscription 1</b>
- <b>Select target workspace: LAW-Cyber-Lab-01</b>



