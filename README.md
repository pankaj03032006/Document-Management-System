# OpenDocMan

[![License](https://img.shields.io/badge/license-GPLv2-blue.svg)](LICENSE.txt)
[![PHP Version](https://img.shields.io/badge/PHP-8.2+-777bb4.svg)](https://php.net)
[![MySQL Version](https://img.shields.io/badge/MySQL-8.0+-orange.svg)](https://mysql.com)
[![MariaDB Version](https://img.shields.io/badge/MariaDB-10.0+-blue.svg)](https://mariadb.org)

**OpenDocMan** is a free, web-based document management system (DMS) written in PHP. It is designed to comply with ISO 17025 and OIE standards for document management, offering fine-grained access control, automated installation and upgrades, and a robust review process.

---

##  Features

-   **Upload & Manage** – Upload files directly via your web browser.
-   **Access Control** – Fine-grained control based on department or individual user permissions.
-   **Revision Tracking** – Keep a complete history of document revisions.
-   **Review Workflow** – Optional review process for all new and updated files.
-   **Simple Deployment** – Automatic installer and Docker support.
-   **Modern Tech Stack** – Built for PHP 8.2 and MySQL 8.0+ / MariaDB 10.0+.

---

##  Quick Start (Docker - Recommended)

The fastest way to get started is with Docker, which includes automatic password generation and environment validation.

### 1. Generate Environment Configuration

Run the interactive setup script to create a `.env` file with secure passwords:

```bash
./generate-env-secrets.sh
