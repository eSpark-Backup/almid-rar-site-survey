# AlMidrar_SiteSurvey
## Introduction 
The purpose of this networking site survey was to assess the current network infrastructure and performance of the Al-Midrar to identify potential areas for improvement. The survey was conducted by the Fizan, Shah Meer and Kashif on Friday 21 July 2023.
## Objectives
The primary objectives of the networking site survey were as follows:
- Evaluate the existing network topology, equipment, services and configurations.
- Identify network performance issues and bottlenecks.
- Recommend improvements to enhance the overall network efficiency, cost and reliability.

## Methodology
- [Done] Initial Consultation: Discussions with the IT team to understand the current network setup, challenges faced, and objectives.
- [Done] Physical Inspection: On-site examination of the networking equipment, cabling, and network rooms.
- [Planed for next visit] Network Performance Testing: Utilizing specialized software to analyze network speed, latency, and throughput.
- [Planed for next visit] User Interviews: Obtaining feedback from employees regarding their network experience and pain points.
## Current Setup and Network Infrastructure
- Buildings : 3 | Floors : 5 | Rooms : 25 
- Network Topology: Mesh Wifi
- Network Equipment: 
  - Wifi Routers : 13 (4*30mbps+9*30mbps = 430 mbps)
- Network Configuration: Default
- List of clients : (Total 210+1) 
  - Smartphones(Wifi) : 92
  - Laptops/PC(Wifi) : 92
  - CCTV Cameras(Wifi) : 26
  - Attendance Machine(unknown interface) : 1 
## Findings
1. All clients are connected via Wifi
2. 13 Internet connections
3. No Bandwidth policy is configured
4. Data is stored in local PCs
## Recommendations
- Shift all Laptop/Pc and CCTV from wifi to wired network
- Use central storage for data commaon data and sharing intead of cloud
- Implement Quality of Service (QoS) policies to prioritize critical applications during periods of high traffic.
- Implement load balancing policy  
- Reduce no of internet connections from 13 to 4-5 and upgrade bandwidth plans
- Use 
### Benefits of Wired Network Conversion
- Enhanced Network Performance: Wired connections generally provide faster and more reliable data transfer compared to wireless.
- Reduced Interference: Eliminating Wi-Fi signals reduces potential interference issues in crowded or congested environments.
- Enhanced Security: Wired networks offer a higher level of security compared to wireless, as they are not susceptible to unauthorized access via Wi-Fi hacking.
## Challenges and Considerations
- Disruptions during Installation: The conversion process may cause temporary disruptions to network services while cabling and equipment are installed.
- Cost: Converting to a wired network may involve significant upfront costs for cabling, switches, and other hardware.
- Physical Constraints: The physical layout of the office may present challenges in running cables to certain areas.
## Proposed Solutions
### 01 Convert with existing Internet connection
- Unmanaged network switches will be added with each router
- All Laptop/PC and CCTV cams will be conrverted into wired network
### 02 Restructured whole Infrastructure
- 4-5 internet connections shall provides internet intead of 13
- 5 Managed switches shall be installed on each floor of 
- Load balancwer shall be installed on building # 1 with 3 different internet connections 
- All managed switches (i.e 4) of building # 1 and 2 shall be connected with a load balancer
- 20-25 Wifi Routers shall be installed on each room to provide smartphones(92+)  
- Building # 3 shall be connected without load balancer because thier are only 4 users 
- 
## Conclusion
The networking site survey indicates that converting the Wi-Fi-based network at ALMidrar to a wired network is a viable option. The transition offers significant benefits in terms of network performance, reliability, and security. However, careful planning, resource allocation, and coordination with the IT team will be necessary to ensure a successful and smooth conversion process.