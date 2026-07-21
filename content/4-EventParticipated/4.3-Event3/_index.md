---
title: "Event 3"
date: 2026-06-13
weight: 3
chapter: false
pre: " <b> 4.3. </b> "
---

# Summary Report: “FCAJ Community Day”

### Event Objectives

- Gain practical insight into building a scalable URL shortening service on AWS.
- Understand the journey from learning AWS fundamentals to becoming an AWS community contributor.
- Learn what DevOps engineers really do in real-world projects.
- Explore the role of data analytics engineers in multinational companies and the skills needed for career growth.

### Speakers

- **Đinh Trung Kiên**
- **Nguyễn Minh Thọ**
- **Danh Hoàng Hiếu Nghị**
- **Dat Pham**
- **Cường Nguyễn**

### Key Highlights

#### 1. Scalable URL Shortening Service on AWS

The first session introduced a scalable URL shortening service built on AWS. The speakers explained that a simple URL shortener is easy to deploy and inexpensive, but it can also suffer from security issues, read latency, single points of failure, and poor scalability. The proposed architecture used Amazon CloudFront, Amazon WAF, and Amazon Amplify at the frontend, while the backend relied on Amazon ECS, Amazon ElastiCache, and DynamoDB. A Key Generation Service pre-generated short codes and pushed them into Redis using LPUSH, while the create flow used RPOP to retrieve a code and store the mapping in DynamoDB. The forward flow checked Redis first, and only went to DynamoDB when a cache miss occurred.

#### 2. From First Cloud AI Journey to AWS Partner

Another important session shared the journey from curiosity to becoming an AWS partner and community builder. The speaker described an eight-step path: student curiosity, first cloud journey, workshops and community, hands-on labs, school projects, portfolio building, AWS partner growth, and sharing knowledge with future learners. The talk also introduced the First Cloud AI Journey program, the AWS Student Builder Group, events and badges, and the AWS Community Builder program. This session was inspiring because it showed that learning AWS is not only about technical knowledge but also about building a network, gaining experience, and contributing back to the community.

#### 3. What does a DevOps Engineer really do?

The DevOps session explained that DevOps is much broader than just writing CI/CD pipelines or managing Docker and Kubernetes. It involves collaboration, automation, infrastructure management, security, monitoring, and incident handling. The presentation highlighted common hiring expectations, common misconceptions, and the reality of daily work, including supporting developers, troubleshooting production issues, handling alerts, investigating costs, and clarifying ownership. It also emphasized the importance of understanding Linux, networking, programming, Git, CI/CD, containers, and how applications are built, tested, deployed, and monitored.

#### 4. Data Analytics Engineer in a multinational company

The final session focused on the role of a Data Analytics Engineer in a multinational environment. The speakers explained that the job varies depending on the domain, business model, and team structure. In companies such as Kamereo and Colgate-Palmolive, the role includes building daily, weekly, and monthly reports, creating dashboards, detecting anomalies, analyzing business performance, and supporting digital transformation. The session also emphasized essential skills such as critical thinking, communication, storytelling with data, and problem-solving. In terms of career growth, the speakers introduced a development model from follower and learner to problem solver, system thinker, and eventually a leader who helps shape strategy and guide others.

### Key Takeaways

- A good system design must balance functionality, performance, security, and scalability.
- Cloud architecture becomes more effective when read and write paths are optimized separately.
- AWS community programs can provide both technical growth and long-term professional opportunities.
- DevOps is not just about tools; it is also about ownership, collaboration, and reliability.
- Data analytics work is not only about numbers but also about turning data into meaningful decisions and action.

### Applying to Work

- Apply the idea of separating read and write paths when designing new systems.
- Use caching and edge services such as CloudFront and WAF to improve performance and security.
- Continue learning AWS through hands-on labs, projects, and community activities.
- Build stronger DevOps habits around automation, monitoring, and troubleshooting.
- Improve data communication skills so that technical insights can be understood and used by business teams.

### Event Experience

This event was valuable because it covered several important areas of modern software engineering in one place. I learned not only about system architecture and AWS services, but also about career development, community building, DevOps culture, and the role of data analytics in business. The combination of technical depth and practical experience made the event both inspiring and useful for my future learning.

#### Lessons Learned

- Good architecture is not only about making things work, but also about making them scalable and resilient.
- Continuous learning and hands-on practice are essential for growth in cloud, DevOps, and data roles.
- Building a career requires both technical ability and soft skills such as communication, problem-solving, and teamwork.

#### Some memorable moments

{{< figure src="/images/30-5.jpg" title="Figure 1. A memorable moment from the technical sharing session" width="80%" >}}

