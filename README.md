# Solar-Powered-Wi-Fi-Hotspot

## **1. Problem Statement**  
In India, people in rural areas lack reliable access to the internet due to inadequate infrastructure and frequent power outages. 
This digital divide limits opportunities for education, healthcare, and communication. 
There is a critical need for a cost-effective, sustainable solution to provide internet connectivity in such regions, especially during emergencies or in areas without access to grid electricity.


## **2. Solution**  
A **solar-powered Wi-Fi hotspot** system that uses renewable energy to provide reliable internet connectivity in underserved areas. 
The solution is portable, affordable, and scalable, combining solar panels with a router powered by stored solar energy. 
Key features include:  
1. **Energy Independence**: Operates entirely on solar power with battery backup.  
2. **Internet Connectivity**: Leverages 4G/5G or satellite networks for internet access.  
3. **Portability and Durability**: Lightweight, compact, and weatherproof design for deployment in remote and challenging environments.  
4. **Cost-Effective Access**: Suitable for schools, healthcare centers, disaster zones, and community hubs.  


## **3. Tech Stack**  

### **Hardware**:  
- **Solar Power System**:  
  - Monocrystalline solar panels (100W).  
  - Lithium-ion battery (12V, 40Ah).  
  - MPPT charge controller for efficient energy management.  
- **Wi-Fi Hotspot Device**:  
  - Portable 4G/5G router (e.g., TP-Link or JioFi).  
  - High-gain antenna for extended range.   
- **Casing**: Weatherproof and ruggedized casing for durability.  

### **Software**:  
- **Operating System**:
  OpenWrt for router customization. OpenWrt (from open wireless router) is an open-source project for embedded operating systems based on Linux, primarily used on embedded devices to route network traffic.  
- **User Interface**:  
  - Mobile/Web App: Built with **React Native** (mobile) and **Vue.js** (web).  
  - Backend: Python/Node.js for data management and API integration.  
- **Cloud Integration**: Firebase or AWS IoT Core for remote monitoring and diagnostics.  
- **Data Optimization**: Compression and QoS tools to optimize bandwidth usage.  


## **4. Timeline**  

| **Phase**               | **Tasks**                                                                    | **Duration**     |  
|-------------------------|------------------------------------------------------------------------------|------------------|   
| **Phase 1: Prototype**  | Assemble hardware components, configure software, and test functionality.    | 1 Month          |  
| **Phase 2: Pilot Test** | Deploy prototype in a small scale, monitor performance and feedback.         | 2 Weeks          |  
| **Phase 3: Iteration**  | Refine design based on feedback, optimize costs, and improve efficiency.     | 1 Week           |  
| **Phase 5: Deployment** | Scale to 2-3 additional sites, integrate the software aspects and deployment.| 1 Week           |  


### **5. Cost Estimation**  

#### **MVP Costs**:
| **Component**                   | **Cost (INR)** |  
|---------------------------------|----------------|  
| 50W Monocrystalline Panel	      | ₹3,000         |  
| Lithium-ion Battery (12V, 40Ah) | ₹3,000         |  
| MPPT Charge Controller(10 A)    | ₹2,500         |  
| 4G Router : JioFi Device        | ₹2,000         |  
| Casing and Miscellaneous        | ₹1,500         |  
| **Total Hardware**              | **₹12,000**    | 
