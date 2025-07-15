# The AWS Shared Responsibility Model

## 🔐 Overview

The **AWS Shared Responsibility Model** defines the split of security and compliance duties between AWS and the customer. It ensures both parties understand their roles in maintaining a secure and operational cloud environment.

---

## 🧠 Who’s Responsible for Security?

> **Answer: Both AWS and the customer.**

This model works much like owning a house:
- **AWS** (the builder) ensures the house has strong walls and secure doors.
- **You**, the customer, are responsible for locking the door.

---

## 🔒 Security _of_ the Cloud (AWS Responsibility)

AWS is responsible for securing the **infrastructure** that powers the cloud:

- **Physical Layer**  
  - Data center security (e.g., locks, surveillance, access controls).
- **Network Layer**  
  - Secure connectivity and network traffic control.
- **Hypervisor Layer**  
  - Isolation between customer workloads using virtualization.

In short, AWS handles all underlying **hardware and foundational services**.

---

## 🔐 Security _in_ the Cloud (Customer Responsibility)

As a customer, you are responsible for everything **you put in the cloud**:

- **Operating System (OS)**  
  - Patch management  
  - Account configuration  
  - Access credentials

- **Applications**  
  - Securing your application logic and services.

- **Data**  
  - Who has access  
  - How it's encrypted  
  - Where it's stored

### Example:
- You alone have the encryption keys.
- AWS doesn’t have a "backdoor" to access your OS or data.
- Like a construction company not keeping your house key—**you manage access**.

---

## ⚖️ Shared Responsibilities (Service Dependent)

Responsibility may **shift** depending on the AWS service used. For example:

| Component                      | Responsibility |
|-------------------------------|----------------|
| Server-side encryption        | Shared         |
| Network traffic protection    | Shared         |
| OS and firewall configuration | Customer       |
| Platform/application management | Varies by service |

As you explore AWS services, you’ll encounter specific breakdowns of who manages what.

---

## 📌 Summary Table

| Component                     | Responsibility     |
|------------------------------|--------------------|
| **Infrastructure (hardware, software, networking)** | AWS |
| **Facilities and data center security**             | AWS |
| **Data, applications, OS**                          | Customer |
| **Identity and access management**                  | Customer |
| **Encryption (client-side)**                        | Customer |
| **Encryption (server-side)**                        | Shared |
| **Network/firewall config**                         | Customer |

---

## ✅ Final Reminder

> - **AWS** secures **the cloud**  
> - **You** secure what you put **in the cloud**

A successful AWS environment relies on understanding and respecting this division of responsibility.
