# Introduction to AWS Global Infrastructure

## 🌍 Overview

AWS Global Infrastructure is a network of data centers and services distributed around the world. Its architecture is designed to support **high availability**, **fault tolerance**, and **low-latency access** for customers globally.

---

## ☕ Why High Availability Matters (A Coffee Shop Analogy)

Imagine a chain of coffee shops:

- One shop has a power failure (latte spilled on the register).
- That shop must close temporarily.
- But customers can still go to other nearby locations.
- The **business continues**, customers are served, and income flows.

This mirrors how AWS ensures **service availability** across multiple sites. One location going down doesn’t mean the whole system fails.

---

## 🔐 Key Concepts

### 🟢 High Availability

- Ensures **minimal downtime** for applications.
- If one component fails, others seamlessly take over.
- Keeps services running and accessible.

### 🔁 Fault Tolerance

- Goes beyond high availability.
- System continues operating even if **multiple components** fail.
- Resilience is built into **every layer** of the infrastructure.

---

## 🧱 Structure of AWS Global Infrastructure

### 🌎 AWS Regions

- A **Region** is a physical location in the world (e.g., Ohio, Paris, Tokyo).
- Each Region contains **at least three Availability Zones (AZs)**.
- Regions are geographically isolated to improve redundancy and latency.

### 🧩 Availability Zones (AZs)

- An AZ is a cluster of **one or more data centers**.
- Each AZ has **independent power, networking, and connectivity**.
- AZs are physically separated to reduce the impact of disasters.

---

## 🛠️ How It All Works Together

- AZs are isolated but interconnected with **low-latency networking**.
- Customers can **distribute resources** across AZs to increase availability.
- Example: if one AZ has an outage, services in another AZ continue operating.

---

## 📈 Multi-Region Architecture

- For **disaster recovery**, some businesses operate across multiple Regions.
- This provides **failover options** if an entire Region experiences problems.
- It’s a more advanced design strategy covered in later lessons.

---

## ✅ Summary

AWS Global Infrastructure enables:

- **Resilience** through isolated AZs
- **Availability** by distributing resources
- **Global reach** through strategically located Regions

By leveraging this infrastructure, AWS customers build robust, always-on applications—even in the face of disasters or spilled lattes.

