# 🍽️ Digital Menu & Restaurant Feedback System

A web-based system that lets restaurant customers open the menu by scanning a **QR Code**, browse and order, and submit **ratings, reviews, and complaints**, while giving management a dashboard to control the menu and analyze feedback in real time.

> Academic project – Systems Analysis & Design.

---

## 📑 Table of Contents

- [Project Status](#-project-status)
- [System Request](#-system-request)
- [Feasibility Study](#-feasibility-study)
- [Project Plan](#-project-plan)
  - [Activities](#activities)
  - [PERT Diagram](#pert-diagram)
  - [Gantt Chart](#gantt-chart)
- [System Analysis](#-system-analysis)
- [Interview Questions](#-interview-questions)
- [Web Form](#-web-form)
- [Team](#-team)

---

## 📌 Project Status

| Deliverable | Status |
|-------------|:------:|
| System Request | ✅ Done |
| Feasibility Study | ✅ Done |
| Project Plan (Activities, PERT, Gantt) | ✅ Done |
| System Analysis document (Word) | ✅ Done |
| Interview Questions with answers (Word) | ✅ Done |
| Web Form (Google Form, published) | ✅ Done |

---

## 📝 System Request

### Project Sponsor
- Restaurant Owner / Restaurant Management

### Business Need
- Improving customer service and the dining experience.
- Organizing menu management and ordering processes.
- Collecting and analyzing customer feedback to improve quality.

### Business Requirements
- Provide a **digital menu** that customers can access by scanning a QR Code.
- Allow customers to submit **ratings, reviews, and complaints** about food and service.
- Allow the admin to **add, edit, and delete** menu items, prices, and offers instantly.
- Generate **reports and statistics** on customer feedback and best-selling items.
- Send **notifications** to management about negative reviews or complaints.

### Business Value
- Increase the number of customers.
- Increase the restaurant's profits by at least **15%**.
- Reduce printed menu costs and improve customer satisfaction.
- Reduce complaints.

### Special Issues
- The project budget should not exceed **$3,000**.
- The system should be delivered within **three months**.

---

## ✅ Feasibility Study

### Technical Feasibility
1. Availability of required technologies (Web / Mobile frameworks).
2. Ability to use QR Codes to display the menu.
3. Support for all devices.
4. Admin dashboard to manage the menu and customer feedback.
5. Ability to secure data.

### Economic Feasibility

| Item | Amount |
|------|-------:|
| Development costs | $5,000 |
| Annual operating costs | $1,200 |
| Annual benefits | $4,000 |

### Organizational Feasibility
1. Management can monitor sales and feedback reports easily.
2. Easy to use: scan a QR Code, then browse, order, and rate.
3. Employees will receive training to manage the system database.

---

## 📅 Project Plan

### Activities

| Activity | Description        | Predecessors | Duration |
|:--------:|--------------------|:------------:|:--------:|
| A | System Request      | –       | 2 |
| B | Feasibility Study   | –       | 4 |
| C | Methodology         | B       | 2 |
| D | Time Estimation     | A, C    | 3 |
| E | Task Identification | C       | 2 |
| F | PERT Chart          | C       | 5 |
| G | Gantt Chart         | D, E, F | 2 |

**Critical path:** B → C → F → G (total duration = **13**)

### PERT Diagram

| Activity | Duration | Earliest Start | Earliest Finish | Latest Start | Latest Finish | Slack | Critical |
|:--------:|:--------:|:--------------:|:---------------:|:------------:|:-------------:|:-----:|:--------:|
| A | 2 | 0  | 2  | 6  | 8  | 6 | – |
| B | 4 | 0  | 4  | 0  | 4  | 0 | ✅ |
| C | 2 | 4  | 6  | 4  | 6  | 0 | ✅ |
| D | 3 | 6  | 9  | 8  | 11 | 2 | – |
| E | 2 | 6  | 8  | 9  | 11 | 3 | – |
| F | 5 | 6  | 11 | 6  | 11 | 0 | ✅ |
| G | 2 | 11 | 13 | 11 | 13 | 0 | ✅ |

### Gantt Chart

Each ■ represents one time unit.

```
Time unit  1  2  3  4  5  6  7  8  9  10 11 12 13
A          ■  ■  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·
B          ■  ■  ■  ■  ·  ·  ·  ·  ·  ·  ·  ·  ·
C          ·  ·  ·  ·  ■  ■  ·  ·  ·  ·  ·  ·  ·
D          ·  ·  ·  ·  ·  ·  ■  ■  ■  ·  ·  ·  ·
E          ·  ·  ·  ·  ·  ·  ■  ■  ·  ·  ·  ·  ·
F          ·  ·  ·  ·  ·  ·  ■  ■  ■  ■  ■  ·  ·
G          ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ■  ■
```

---

## 🔍 System Analysis

Documented in the Word file **`1_System_Analysis.docx`**.

### 1. Current State of the System
The restaurant currently relies on printed paper menus, and waiters take orders by hand and pass them to the kitchen. Customer feedback is collected only verbally or through a paper comment card, so it is slow to reach management and is rarely recorded or analyzed.

### 2. System Goals
- **Digital menu:** let customers open the menu instantly by scanning a QR Code and place their orders from their own phones.
- **Feedback collection:** let customers submit ratings, reviews, and complaints about the food and the service.
- **Easy management:** let the admin add, edit, and delete menu items, prices, and offers at any time, and view reports on feedback and best-selling items.

### 3. Interviewee Opinions
- **Waiters:** the system will make their work easier because orders reach the kitchen directly, with fewer mistakes and less running between tables.
- **Kitchen staff:** clear, written orders will reduce misunderstandings and wasted food.
- **Cashier:** ordering and billing will be faster and more accurate.
- **Manager / Owner:** sales are expected to increase, printing costs for menus will drop, and customer complaints will be easier to track and solve.

### 4. Interviewee Feelings
- **Excitement:** most staff feel positive because the system will make service faster and easier, and customers will enjoy a modern experience.
- **Worry about jobs:** some waiters fear that the system will reduce the need for their role.
- **Fear of change:** some older employees are afraid they will not be able to learn the new technology quickly.
- **Fear of negative reviews:** some staff feel nervous that customers' complaints will be visible to management and could be used to judge their performance.

---

## 🎤 Interview Questions

Documented in the Word file **`2_Interview_Questions_With_Answers.docx`**.

### 1. Open-Ended Questions

**Q1. How does the restaurant currently take orders and present the menu to customers?**
> Customers get a printed paper menu, and the waiter writes the order by hand and carries it to the kitchen. Whenever a price or item changes, the menus have to be reprinted.

**Q2. What are the biggest problems you face in your daily work with the current process?**
> Orders are sometimes delayed or misunderstood because of handwriting, waiters spend a lot of time running between tables and the kitchen, and printed menus quickly become outdated.

**Q3. How do you currently collect and handle customer complaints and feedback?**
> Mostly verbally: customers tell the waiter or the manager. There is a paper comment card, but it is rarely used, and nothing is recorded or analyzed, so it is hard to follow up on complaints.

**Q4. What features would you like to see in the new digital menu system?**
> A QR Code menu with photos and prices, sending orders directly to the kitchen, instant updates for prices and offers, reports on best-selling items, and a notification to management when a customer leaves a negative review.

**Q5. How do you think the new system will change the way you work?**
> It should make the work faster and easier, with fewer mistakes and less running around. We will need some training at the beginning, but sales and customer satisfaction should improve.

### 2. Closed-Ended / Bipolar Questions

| # | Question | Options | Answer |
|:-:|----------|---------|--------|
| 1 | Do you currently face delays in delivering orders to the kitchen? | Yes / No | **Yes** |
| 2 | Do you own a smartphone that you can use to work with the system? | Yes / No | **Yes** |
| 3 | Would you prefer customers to place their orders themselves through the QR Code menu? | Yes / No | **Yes** |
| 4 | How often do customers complain about the service? | Daily / Weekly / Monthly / Rarely or Never | **Weekly** |
| 5 | How comfortable are you with using new technology at work? | Very comfortable / Comfortable / Neutral / Uncomfortable / Very uncomfortable | **Comfortable** |

---

## 🌐 Web Form

The customer feedback form was built with Google Forms and is published here:

👉 **[Open the Customer Feedback form](https://docs.google.com/forms/d/e/1FAIpQLScIYUBgbUE0AwIeHon2Uey97s2IWkf_6RFQqpIW-CQvCWz6OA/viewform?usp=publish-editor)**

Customers reach it by scanning the restaurant's **QR Code**.

### Section 1: Open-Ended Questions *(Paragraph)*

1. What did you like most about your visit today?
2. What could we do to improve your dining experience?
3. Please describe any problem or complaint you had (food, service, or cleanliness).
4. What dishes or offers would you like to see added to the menu?
5. Any other comments or suggestions for the management?

### Section 2: Closed-Ended Questions *(Required)*

| # | Question | Type | Options |
|:-:|----------|------|---------|
| 1 | How would you rate the food overall? | Linear scale | 1 to 5 (1 = Poor, 5 = Excellent) |
| 2 | How would you rate the service? | Linear scale | 1 to 5 (1 = Poor, 5 = Excellent) |
| 3 | Was the digital menu easy to use? | Multiple choice | Yes / No |
| 4 | Was your order delivered on time? | Multiple choice | Yes / No |
| 5 | Would you recommend our restaurant to a friend? | Multiple choice | Yes / Maybe / No |

---

## 👥 Team

| Name | Student ID |
|------|:----------:|
| Mohamed Mostafa Badr | 1202540906 |
| Mahmoud Ashraf Abdelaziz | 1202540918 |
| Mohamed Sameh Mohamed Rashad | 1202540867 |

---
