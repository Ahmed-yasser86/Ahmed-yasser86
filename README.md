
```markdown
## Ahmed Yasser - Software Engineer

<div align="center">
  <a href="https://www.linkedin.com/in/ahmed-yasser-212b5b28b/" target="_blank">
    <img src="https://img.shields.io/static/v1?message=LinkedIn&logo=linkedin&label=&color=0077B5&logoColor=white&labelColor=&style=for-the-badge" height="25" alt="linkedin logo"  />
  </a>
  <a href="ahmedyassermonet@gmail.com" target="_blank">
    <img src="https://img.shields.io/static/v1?message=Gmail&logo=gmail&label=&color=D14836&logoColor=white&labelColor=&style=for-the-badge" height="25" alt="gmail logo"  />
  </a>
  <a href="https://wa.me/00201023131109" target="_blank">
    <img src="https://img.shields.io/static/v1?message=Whatsapp&logo=whatsapp&label=&color=25D366&logoColor=white&labelColor=&style=for-the-badge" height="25" alt="whatsapp logo"  />
  </a>
</div>

###

<h1 align="center">👋 Hey there, I'm Ahmed Yasser</h1>

###

<h3 align="center">Software Engineer | BIS Student (GPA: 3.97/4.0)</h3>

###

<div align="center">
  <img src="https://visitor-badge.laobi.icu/badge?page_id=Ahmedrix.Ahmedrix" />
  <img src="https://img.shields.io/github/followers/Ahmedrix?style=social" />
</div>

---

## 🚀 About Me

I'm a Software Engineer and Business Information Systems student passionate about building **efficient, scalable, and well-structured software solutions** from the ground up. I don't just use technologies — I understand how they work and architect systems that can handle thousands of users.

🔹 **What drives me:**
- Designing and optimizing backend systems
- Building distributed architectures with zero third-party dependencies
- Solving complex problems with clean, maintainable code
- Bridging theory with practice through system analysis and architecture

🌍 **Beyond coding:** I have a deep appreciation for history, philosophy, and languages. I'm fluent in Arabic and English, currently learning Chinese. I also enjoy classical music, football, and exploring art and cultural heritage.

---

## 💡 Featured Project: Ahmedrix Educational Ecosystem

<div align="center">
  
  ### **⚡ Built From Scratch — 13 Docker Containers — 1 Developer ⚡**
  
</div>

A complete learning platform where teachers can:
- 📺 **Live stream** to thousands of students
- 💬 **Real-time chat** with message history
- 🤝 **One-on-one video calls** (private sessions)
- 📚 **Manage courses** and student enrollments

**The twist?** No third-party APIs, no plug-and-play services. Just clean code and solid architecture.

```mermaid
flowchart TB
    User["👤 Users"] --> LB1["🚦 Chat LB"]
    User --> LB2["🚦 Video LB"]
    User --> API["🎯 .NET 9 API"]
    User --> WebRTC["📞 Signaling Server<br/>(WebRTC)"]
    
    subgraph Chat["💬 Chat Cluster"]
        LB1 --> C1["Node α"] & C2["Node β"] & C3["Node γ"]
        C1 <--> Redis["📨 Redis Backplane"]
        C2 <--> Redis
        C3 <--> Redis
    end
    
    subgraph Video["📺 Video Cluster"]
        LB2 --> V1["NMS 1"] & V2["NMS 2"] & V3["NMS 3"]
    end
    
    subgraph OneOnOne["🤝 One-on-One Video"]
        WebRTC --> Signal["Peer Connection"]
        Signal --> P2P["Direct P2P Video<br/>Teacher ⇄ Student"]
    end
    
    API --> DB[("🗄️ SQL Server")]
    Chat --> API
    Video --> API
    WebRTC --> API
    
    style OneOnOne fill:#e1f5fe,stroke:#01579b
    style P2P fill:#fff9c4,stroke:#fbc02d
```

---

## 🛠️ Technical Arsenal

### **Backend Development**
<div align="left">
  <img src="https://img.shields.io/badge/.NET%209-512BD4?style=for-the-badge&logo=dotnet&logoColor=white" />
  <img src="https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=csharp&logoColor=white" />
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=cplusplus&logoColor=white" />
</div>

### **Databases & Caching**
<div align="left">
  <img src="https://img.shields.io/badge/SQL%20Server-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white" />
  <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white" />
  <img src="https://img.shields.io/badge/EF%20Core-512BD4?style=for-the-badge&logo=dotnet&logoColor=white" />
  <img src="https://img.shields.io/badge/ADO.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white" />
</div>

### **DevOps & Containerization**
<div align="left">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker%20Compose-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/HAProxy-2A2A2A?style=for-the-badge&logo=haproxy&logoColor=white" />
  <img src="https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white" />
</div>

### **Real-Time & Web Technologies**
<div align="left">
  <img src="https://img.shields.io/badge/WebRTC-333333?style=for-the-badge&logo=webrtc&logoColor=white" />
  <img src="https://img.shields.io/badge/Socket.io-010101?style=for-the-badge&logo=socketdotio&logoColor=white" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
  <img src="https://img.shields.io/badge/WebSockets-010101?style=for-the-badge&logo=socketdotio&logoColor=white" />
  <img src="https://img.shields.io/badge/RTMP-00D8FF?style=for-the-badge&logo=adobe&logoColor=black" />
  <img src="https://img.shields.io/badge/HLS-FF6C37?style=for-the-badge&logo=apple&logoColor=white" />
</div>

### **Tools & IDEs**
<div align="left">
  <img src="https://img.shields.io/badge/Visual%20Studio-5C2D91?style=for-the-badge&logo=visualstudio&logoColor=white" />
  <img src="https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white" />
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" />
  <img src="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white" />
</div>

---

## 📊 GitHub Analytics

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Ahmedrix&show_icons=true&theme=radical" height="150" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Ahmedrix&layout=compact&theme=radical" height="150" />
</div>

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Ahmedrix&theme=radical" />
</div>

---

## 🏆 Key Achievements

- ✅ Built a **distributed educational platform** with 13 Docker containers — single-handedly
- ✅ Implemented **WebRTC one-on-one video** with zero server bandwidth for media
- ✅ Designed **auto-scaling chat cluster** with Redis backplane synchronization
- ✅ Created **load-balanced video streaming** supporting 900+ concurrent viewers
- ✅ Architected **RTMP/HLS streaming cluster** with HAProxy failover
- ✅ Maintained **3.97 GPA** while building production-ready systems

---

## 📫 Let's Connect

I'm always open to collaborating on impactful projects or discussing software architecture!

<div align="center">
  <a href="https://www.linkedin.com/in/ahmed-yasser-212b5b28b/">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="mailto:ahmedyassermonet@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
  <a href="https://wa.me/00201023131109">
    <img src="https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" />
  </a>
</div>

---

<div align="center">
  
  ### ⚡ **"Centralize control, distribute the work, keep it simple."** ⚡
  
  *— Ahmed Yasser, Solo Architect & Developer*
  
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=100&section=footer"/>
  
</div>
```

---
