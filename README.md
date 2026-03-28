
---

#  `devops-project` README

```markdown
#  DevOps Project — CI/CD with Jenkins, Maven & Tomcat

![Java](https://img.shields.io/badge/Java-App-blue)
![Jenkins](https://img.shields.io/badge/Jenkins-CI%2FCD-red)
![Tomcat](https://img.shields.io/badge/Tomcat-Deployment-yellow)
![Maven](https://img.shields.io/badge/Maven-Build-orange)

A complete **CI/CD pipeline project** where a Java application is built, tested, and deployed to a Tomcat server using Jenkins.

---

##  Architecture
Developer → GitHub → Jenkins Pipeline → Maven Build → Tomcat Deployment


---

## Tools Used

- Java
- Jenkins
- Apache Tomcat
- Maven
- GitHub

---
##  Pipeline Stages

1. **Code Checkout**
2. **Build using Maven**
3. **Run Tests**
4. **Package Application**
5. **Deploy to Tomcat Server**

---

##  How to Run

### 1. Clone Repo
```bash
git clone https://github.com/nimeghala45/devops-project.git

2. Setup Jenkins
Configure pipeline job
Link GitHub repo
Add Jenkinsfile
3. Run Pipeline
Trigger build manually or via webhook

 Key Learnings
CI/CD fundamentals
Pipeline automation
Deployment strategies

Future Improvements
Docker containerization
Kubernetes deployment
Monitoring integration
