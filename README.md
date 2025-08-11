# 🏦 BankX – Modular Banking Tech Suite

BankX is a comprehensive backend system simulating core banking operations, loan processing, digital wallet functionality, fraud detection, and secure authentication. Built with microservices architecture and modern DevOps practices, it’s designed to showcase enterprise-grade banking workflows.

---

## 🚀 Features

- 🔐 **Authentication Service**: Secure login, 2FA, session management
- 🧾 **Account Service**: Customer onboarding, KYC, account types
- 💸 **Transaction Service**: Deposits, withdrawals, transfers, ledger updates
- 🏦 **Loan Service**: Loan application, credit scoring, approval workflow
- 👛 **Wallet Service**: P2P transfers, transaction history, daily limits
- ⚠️ **Fraud Detection**: Real-time anomaly detection using Kafka Streams
- 📣 **Notification Service**: OTPs, loan status alerts via email/SMS
- 📜 **Audit Service**: Tracks all user actions and system events
- 🌐 **API Gateway**: Centralized routing, rate limiting, and security
- 🔄 **CI/CD Pipeline**: Automated testing, Docker builds, and deployment

---

## 🧰 Tech Stack

| Layer         | Technologies |
|---------------|--------------|
| Backend       | Java, Spring Boot, JPA |
| Messaging     | Kafka, Redis |
| Security      | Spring Security, JWT, JobRunr |
| Storage       | PostgreSQL, Elasticsearch |
| DevOps        | Docker, GitHub Actions |
| Monitoring    | ELK Stack (Elasticsearch, Logstash, Kibana) |

---

## 🛠️ Setup Instructions

```bash
# Clone the repo
git clone https://github.com/your-username/BankX.git
cd BankX

# Run services using Docker Compose
docker-compose up --build
