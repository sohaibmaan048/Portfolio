---
title: "DBMS in Action: Creating a Tech Gadgets Table 🗄️💻"
date: 2026-05-03 10:00:00 +0500
categories: [Education, University Life]
tags: [DBMS, SQL, Database, Student Life]
image:
  path: /assets/posts/p2.jpg
description: "A deep dive into DBMS lab after the Eid break: designing a structured table for tech gadgets with 10 attributes."
---

Returning to university after the Eid break meant switching gears from a relaxed “home mode” to full-on “study mode” 🔄. My first DBMS lab task after the break was both practical and creative: designing a database table for tech gadgets. At first glance, it seemed simple—10 features and 5 to 6 records—but as I dug in, I realized this was a real test of planning, logic, and attention to detail.

## The Table Structure: 10 Key Features 📝

```sql
-- Creating the Tech Gadgets table with professional data types
CREATE TABLE TechGadgets (
    gadget_id INT PRIMARY KEY,           -- Unique identifier
    gadget_name VARCHAR(50) NOT NULL,    -- Name of device
    brand VARCHAR(50),                   -- Manufacturer
    category VARCHAR(50),                -- Type of gadget
    purchase_year INT,                   -- Year bought
    price_usd DECIMAL(10, 2),            -- Cost in USD
    battery_life_hours INT,              -- Battery life
    connectivity VARCHAR(50),            -- Wi-Fi/5G/Bluetooth
    operating_system VARCHAR(50),        -- Software
    rating DECIMAL(2, 1)                 -- User rating out of 5
);
```
![The Structure of the Table](/assets/in_post/pic1.jpg)

Choosing data types for each attribute was an important step. For example, the price needed a decimal type to allow accurate calculations, while battery life required integers for easy comparisons. Using `gadget_id` as a **Primary Key** ensured each record was unique and easy to reference.

## Populating the Table: 5–6 Realistic Records 🖊️

I then added sample gadgets to test the table, including:
* **Smartphones** 📱 like Galaxy S22 and iPhone 14
* **Laptops** 💻 such as MacBook Air and ThinkPad X1
* **Smartwatches** ⌚ like Galaxy Watch 5
* **Tablets** 📟 like iPad Pro
![The Data for the Table](/assets/in_post/pic2.jpg)
![TABLE](/assets/in_post/pic3.jpg)
![TABLE Shown in localhost database](/assets/in_post/pic4.jpg)

Even with just 5–6 records, keeping data consistency and accuracy was essential. Attributes like brand, category, battery life, and OS had to match the type of gadget, while the ratings and prices had to feel realistic. This exercise reminded me that even a small dataset requires thoughtful planning.

## Lessons Learned: Beyond Just Theory 📚

This lab reinforced several important DBMS principles:

* ✅ **Data Integrity:** Proper constraints prevent invalid data from entering the table.
* ✅ **Logical Structure:** Each column has a clear purpose and relates to others.
* ✅ **Practical Application:** Even small details like units for battery life matter.
* ✅ **Confidence Boost:** Completing the table after a break refreshed my skills.

## The Bigger Picture: Preparing for Challenges Ahead 🚀

Tasks like this show that complex systems are built on simple foundations. Every advanced query or report depends on a strong, logical table structure. With midterms approaching, I plan to:

1. Focus on more hands-on DBMS exercises 🔧
2. Explore constraints, relationships, and queries in depth 🕵️‍♂️
3. Keep practicing structured table design to improve efficiency ⚡

Designing this tech gadgets table was a small but meaningful step in my DBMS journey. It reminded me that practical experience strengthens understanding far more than theory alone. I’m excited to continue building these skills and tackle larger, more complex database projects in the future 💪.
