<div align="center">

# PureAuth

<img src="https://readme-typing-svg.demolab.com?font=Poppins&size=22&pause=1000&color=20D6C7&center=true&vCenter=true&width=650&height=40&lines=Authentication+Infrastructure+for+Modern+Software;Secure+Authentication+%26+Licensing;Built+for+Developers" alt="PureAuth tagline" />

<p>
  <a href="https://auth.purexit.online/">
    <img src="https://img.shields.io/badge/Website-PureAuth-20D6C7?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Website" />
  </a>
  <a href="https://discord.gg/v7vH2AyGfW">
    <img src="https://img.shields.io/badge/Discord-Community-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" />
  </a>
  <img src="https://img.shields.io/badge/Status-In%20Development-F59E0B?style=for-the-badge" alt="Development Status" />
</p>

<p>
  <strong>Secure authentication, licensing, and access management for modern applications.</strong>
</p>

</div>

---

### Contents

* [Features](#features)
* [Client SDKs](#client-sdks)
* [Developer Tools](#developer-tools)
* [Platform Status](#platform-status)
* [Connect](#connect)

---

## Features

* **Authentication** — Secure user authentication and session management.
* **License Management** — Create, activate, expire, revoke, and manage licenses.
* **User Management** — Manage users, permissions, subscriptions, and account access.
* **Device & HWID Controls** — Bind and manage authorized devices.
* **Developer API** — Integrate PureAuth directly into your own applications.
* **Webhooks** — Connect authentication events with your own services.
* **Application Management** — Manage multiple applications from one dashboard.
* **Audit Logs** — Keep track of important authentication and account activity.
* **Subscriptions** — Manage plans, expiration dates, and access levels.
* **Security Controls** — Rate limiting, session controls, and abuse prevention.

---

## Client SDKs

PureAuth is being built with developers in mind, providing simple integration across popular languages.

<div align="center">

|    Language    |       Status      |
| :------------: | :---------------: |
|     **C++**    | 🟡 In Development |
|     **C#**     | 🟡 In Development |
|   **Python**   | 🟡 In Development |
| **JavaScript** |     ⚪ Planned     |
|     **Go**     |     ⚪ Planned     |
|    **Rust**    |     ⚪ Planned     |

</div>

> SDK repositories will be published as they become ready.

---

## Developer Tools

```text
Application
     │
     ▼
 PureAuth API
     │
     ├── Authentication
     ├── License Validation
     ├── User Management
     ├── Device Binding
     └── Session Management
              │
              ▼
        Your Application
```

### Simple Integration

```cpp
PureAuth auth(APP_ID, APP_SECRET);

auto session = auth.login(username, password);

if (session.success) {
    // User authenticated
}
```

---

## Platform Status

<div align="center">

| Service        |     Status    |
| :------------- | :-----------: |
| Authentication |  🟡 Building  |
| Licensing      |  🟡 Building  |
| Developer API  |  🟡 Building  |
| Dashboard      |  🟡 Building  |
| SDKs           |  🟡 Building  |
| Documentation  |  🟡 Building  |
| Public Launch  | ⚪ Coming Soon |

</div>

PureAuth is currently under active development. More features, SDKs, documentation, and public releases will be announced as development progresses.

---

## Connect

<div align="center">

<a href="https://auth.purexit.online/">
<img src="https://img.shields.io/badge/Website-20D6C7?style=for-the-badge&logo=googlechrome&logoColor=white" />
</a>

<a href="https://discord.gg/v7vH2AyGfW">
<img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" />
</a>

</div>

---

<div align="center">

**PureAuth**

*Authentication infrastructure for modern software.*

Built with security, simplicity, and developers in mind.

</div>
