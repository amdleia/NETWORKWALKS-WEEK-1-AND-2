# Cybersecurity Internship – Weeks 1 & 2

## ⭐ Overview ⭐

For my first two weeks of my cybersecurity internship with **NETWORKWALKS**, I focused on getting my Kali Linux environment set up and then using it for a hands-on footprinting and reconnaissance exercise.

It was a good way to get started because I got to work with the environment and tools myself instead of only learning about them in theory.

---

# 🗓️ Week 1 – Kali Linux Setup

For Week 1, I focused on getting my **Kali Linux environment** ready for the practical tasks.

### 💻 What I Worked On

* Set up Kali Linux as my cybersecurity testing machine.
* Configured the network using **NAT Network**.
* Set the network subnet to **10.0.0.0/24**.
* Configured Kali Linux with the required IP address **10.0.0.2/24**.
* Enabled clipboard and file drag-and-drop.
* Set up the shared **`/downloads`** folder.
* Made sure Kali Linux had full internet access.
* Tested the setup to make sure everything was working properly.

### 💡 What I Learned

Week 1 helped me understand the basics of setting up a cybersecurity lab and gave me more practice with **IP addresses, subnets, and network configuration**.

It was also useful to get comfortable with Kali Linux before moving on to the practical exercises.

---

# 🔎 Week 2 – Footprinting & Reconnaissance

For Week 2, I moved on to a hands-on **footprinting and reconnaissance** exercise.

For this exercise, **NetworkWalks assigned Microsoft (`microsoft.com`) as the target**. The goal was to learn how publicly available information can be collected during the early stages of a cybersecurity assessment.

### 🛠️ Tools I Used

* 🐧 **Kali Linux**
* 🔎 **theHarvester**
* 🌐 **Baidu** – used as a theHarvester source
* 📡 **nslookup**
* 🔍 **WHOIS**
* 🌐 **curl -I**
* 🕵️ **WhatWeb**
* 🛡️ **wafw00f**

### 🔍 What I Worked On

During the exercise, I:

* Used **theHarvester** with Baidu to gather publicly available information.
* Ran another theHarvester search using **all available sources**.
* Looked for information such as email addresses, sub-domains, and hosts.
* Used **nslookup** to explore DNS-related information.
* Used **WHOIS** to look at publicly available domain information.
* Used **curl -I** to view HTTP response headers.
* Used **WhatWeb** to identify technologies associated with the website.
* Used **wafw00f** to check for information about a possible Web Application Firewall.
* Took screenshots of my commands and results as evidence.

### 💡 What I Learned

This exercise helped me understand how much information can be found through **publicly available sources** without directly accessing a company's internal systems.

I also became more comfortable using the Kali Linux Terminal and got a better understanding of what each reconnaissance tool is used for.

---

# 📸 Evidence

Screenshots of my practical work and tool results are included in this repository to document the activities I completed during Weeks 1 and 2.

---

# ⚠️ Scope

The Week 2 exercise focused on **footprinting, reconnaissance, and publicly available information**.

**No active exploitation was performed during this exercise.**
