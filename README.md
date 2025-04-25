
# 🏢 Office Network Deployment Project  
*A 7-room office network infrastructure designed and deployed from scratch*  

## 📋 Project Overview  
**Organization**: Malonic Aluminium & Glass  
**Location**: Harare Zimbabwe  
**Duration**: 1 week (Jan 2019)  
**Cost Savings**: £500+ by repurposing existing equipment  

## 🌟 Key Achievements  
- ✅ **Full Infrastructure Deployment**: Designed and physically installed network from ground up  
- 🚀 **28 Network Ports**: Installed 4 Cat6 ports per room across 7 rooms  
- 📡 **Wi-Fi Optimization**: Eliminated all dead zones using strategic AP placement  
- 💰 **Cost Efficiency**: Repurposed spare TP-Link Archer C7 as access point  
- ⏱️ **Zero Downtime**: Supported 20+ devices with uninterrupted connectivity  

## 🔧 Technical Specifications  
 
### Network Diagram (7-Room Office Deployment)
```mermaid
%%{init: {'theme': 'forest', 'fontFamily': 'Segoe UI', 'gantt': {'barHeight': 20}}}%%
graph TD
    A[🛜 ISP Modem<br>192.168.1.1] -->|🔷 Cat6 Main Feed| B[🖥️ 24-Port Switch<br>192.168.1.2]
    B --> C[🚪 Room 1<br>📌 Ports 1-4<br>192.168.1.10-13]
    B --> D[🚪 Room 2<br>📌 Ports 5-8<br>192.168.1.14-17]
    B --> E[🚪 Room 3<br>📌 Ports 9-12<br>192.168.1.18-21]
    B --> F[🚪 Room 4<br>📌 Ports 13-16<br>192.168.1.22-25]
    B --> G[🚪 Room 5<br>📌 Ports 17-20<br>192.168.1.26-29]
    B --> H[🚪 Room 6<br>📌 Ports 21-24<br>192.168.1.30-33]
    H --> I[📶 TP-Link AP<br>192.168.1.33]
    
    style A fill:#FF6B6B,stroke:#CC0000,color:white,stroke-width:2px
    style B fill:#4ECDC4,stroke:#1A7F78,color:black,stroke-width:2px
    style C,D,E,F,G,H fill:#FFD166,stroke:#CC9C00,stroke-width:1.5px
    style I fill:#A5DD9B,stroke:#5C9E5D,stroke-width:2px
    
    linkStyle default fill:none,stroke:#888,stroke-width:2px
    linkStyle 0 stroke:#FF6B6B,stroke-width:3px
