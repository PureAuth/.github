<div align="center">

# PureAuth

### Authentication infrastructure for modern software

Secure authentication, licensing, user management, and device control — built for developers.

<p>
  <a href="https://auth.purexit.online/">
    <img src="https://img.shields.io/badge/Website-20D6C7?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Website" />
  </a>
  <a href="https://auth.purexit.online/docs">
    <img src="https://img.shields.io/badge/Docs-4D7CFF?style=for-the-badge&logo=readthedocs&logoColor=white" alt="Docs" />
  </a>
  <a href="https://discord.gg/v7vH2AyGfW">
    <img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" />
  </a>
  <img src="https://img.shields.io/badge/Status-Live-22C55E?style=for-the-badge" alt="Status" />
</p>

</div>

---

## What is PureAuth?

PureAuth is a developer-focused authentication and licensing platform. Manage applications, users, licenses, devices, sessions, and access from one dashboard — with every access decision enforced on the server.

**Panel:** [auth.purexit.online](https://auth.purexit.online) · **API:** `https://api.purexit.online`

---

## Platform

| | |
|:---|:---|
| **Authentication** | Secure app auth, sessions, and account management |
| **Licensing** | Create, activate, expire, and revoke licenses |
| **Device control** | HWID binding and device management |
| **Developer API** | HMAC-signed Client API for native integrations |
| **Applications** | Multiple apps from one centralized dashboard |
| **Security** | Sessions, rate limits, bans, logs, abuse prevention |

---

## Official SDKs

Shared flow: **Init → Login / Register → Validate**

| Language | Repository | Status |
|:---|:---|:---|
| Python | [PureAuth-Python-Example](https://github.com/PureAuth/PureAuth-Python-Example) | Available |
| C++ | [PureAuth-CPP-Example](https://github.com/PureAuth/PureAuth-CPP-Example) | Available |
| C# | [PureAuth-CSharp-Example](https://github.com/PureAuth/PureAuth-CSharp-Example) | Available |
| Go | [PureAuth-Go-Example](https://github.com/PureAuth/PureAuth-Go-Example) | Available |
| JavaScript | [PureAuth-JavaScript-Example](https://github.com/PureAuth/PureAuth-JavaScript-Example) | Available |
| PHP | [PureAuth-PHP-Example](https://github.com/PureAuth/PureAuth-PHP-Example) | Available |

---

## How it works

```text
        Your Application
               |
               v
        +---------------+
        |   PureAuth    |
        |     API       |
        +---------------+
               |
     +---------+---------+
     |         |         |
     v         v         v
   Auth     License    Device
   Check     Check      Check
     |         |         |
     +---------+---------+
               |
               v
         Access Granted
```

---

## Links

- Website: [auth.purexit.online](https://auth.purexit.online)
- Documentation: [auth.purexit.online/docs](https://auth.purexit.online/docs)
- Discord: [Join the community](https://discord.gg/v7vH2AyGfW)

<p align="center">
  <sub>© PureAuth · Built for developers who ship protected software.</sub>
</p>
