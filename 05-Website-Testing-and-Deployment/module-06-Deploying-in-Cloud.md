## ☁️ Module 6: Deploying in the Cloud

### 📖 Introduction

In this module, you’ll learn about deploying websites in the cloud. You’ll learn about how the cloud has evolved to support every aspect of deployment and the benefits that it provides. You’ll also explore how web developers use containers to host some services or entire websites in the cloud.

### 🎯 Learning Objectives

After completing this module, you should be able to:

* Describe the cloud
* Identify the services that the cloud provides to web developers
* Describe containerization and how it benefits website deployment

### 🌐 What is the Cloud?

The first documented use of the term cloud computing was in an internal document at Compaq Computer, which later merged with The Hewlett-Packard Company. Engineering drawings used a cloud as a symbol for a network.

Regardless of the origins, the term cloud generally refers to the internet. It started as a technical term, but it is now common in everyday language.

The cloud, particularly in technical environments, is the set of services and storage that companies and users have come to depend on.

For example, back-end web developers might refer to a critical set of website data as being in cloud storage or using cloud services. In this context, they’re referring to sites or data that are internet-based.

Suppose you are unable to stream a movie or shop online one evening because the internet went down. While this might be an inconvenience, it’s unlikely that you’ll suffer irreparable loss because of it. But when businesses rely on local systems for data storage and services, failure of those systems might cost them a lot of money in lost business. Using the cloud for data storage and services provides an important backup and recovery system to run their business without interruptions.

For individuals, the cloud can provide an extra measure of protection from system failures or data corruption to support essential parts of their lives. For example, you might store critical legal documents on cloud storage.

### 🔧 Breaking Apart Hardware Functions

When the internet was just beginning, companies would use high-powered computers to host web pages and store files. These computers were the first servers. Each computer might have run several websites, and the computer’s storage would have all the files needed for the site saved on it.

As internet technology evolved, server farms developed where hundreds and then thousands of servers networked together to share the tasks or workloads involved in delivering hundreds of websites and services.

The cloud is an evolution of these server farms. Early internet servers were designed to deliver websites with all the services a website needed, like storage, networking, and security, all on one server. Cloud computing improved on that model by separating the features of one server into distinct functions on specially designed and dedicated servers. This makes it easier for web developers to use only the resources they need when they need them.

Today, cloud server farms contain thousands of computers that engineers design for many specific tasks. Some engineers design cloud server farms specifically for large data storage and rapid transfer of that data, including websites. Others build servers specifically to process data. And other servers handle networking or running specialized software.

### 🔮 What is the Future of Cloud Computing?

As the cloud continues to evolve, the computers that run various services will become more specialized, run faster, use less power, and become easier to maintain. These advances will help the cloud become more integrated into what you do every day. If it isn’t already, the cloud truly will be a utility as important as electricity and plumbing.

### 🧑‍💻 Cloud Computing and Web Development

Cloud providers work like general stores, providing all the resources that web developers need in one place: development tools, deployment and testing tools, monitoring tools, and global scalability.

The cloud has revolutionized web development by providing a robust environment for building impactful websites.

### 🛠️ Cloud Services for Web Developers

#### 🏠 Hosting

Cloud services offer many options for hosting websites, including templates for CMS like WordPress and Drupal. They also host and manage domain names.

#### 📍 Replication

Modern cloud services have global servers and offer replication to copy the website code base to reduce latency and improve performance for users across different regions.

#### 📈 Scalability

Cloud allows web development teams to scale resources on demand, paying only for what they use.

#### 🔐 Security

Cloud services help protect websites from attacks such as DoS by monitoring and blocking malicious traffic.

#### 📊 Monitoring

Cloud tools help developers monitor everything from network traffic to server load, with customizable dashboards.

#### 🧰 Development Tools

Cloud providers offer back-end tools like IBM Vapor, code editors like VS Code, and CLI tools for development, deployment, and testing.

These tools streamline web development by offering infrastructure, pre-built templates, and container-based services.

### 📦 Containerization

#### 🚢 Software Containers

Like shipping containers, software containers bundle everything needed to run software—code, runtime, libraries—into one portable unit.

#### 🧱 Beyond Operating Systems

Before containers, developers installed full operating systems to deliver web services. VMs helped simplify this, but still consumed a lot of resources.

Containers extract only what’s needed from the OS, reducing resource usage and simplifying deployment.

#### 🎯 Benefits of Containers

1. Code independence from hardware—portable and self-contained
2. Flexibility to run anything from static sites to complex apps using microservices

Netflix, for example, uses microservices in containers to break its functionality into smaller components, like video selection or recommendations.

Developers can use containers for nearly every type of hosting: websites, APIs, databases, media, and more.

---
