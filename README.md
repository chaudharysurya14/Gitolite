# Gitolite Server Setup

## 📘 Overview
**Gitolite** is a server-side tool for managing Git repositories over SSH. It enables fine-grained access control, allowing administrators to define who can read, write, or manage each repository — all through SSH key authentication. Gitolite is lightweight, secure, and ideal for managing multiple users and projects on a single server.

---

## ⚙️ Prerequisites
- **CentOS 7 / RHEL / Ubuntu** (Linux environment)
- **Git** installed
- **Perl** (with `Data::Dumper` module)
- SSH access to the server

---

## 🧰 Installation Steps

### 1️⃣ Create a dedicated Git user
```bash
sudo adduser git
sudo passwd git
