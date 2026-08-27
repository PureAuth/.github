<div align="center">

# PureAuth

### Authentication infrastructure for modern software.

Secure authentication, licensing, user management, and
device control — built for developers.

<p>
  <a href="https://auth.purexit.online/">
    <img src="https://img.shields.io/badge/Website-20D6C7?style=for-the-badge&logo=googlechrome&logoColor=white">
  </a>
  <a href="https://discord.gg/v7vH2AyGfW">
    <img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white">
  </a>
  <img src="https://img.shields.io/badge/Status-In%20Development-F59E0B?style=for-the-badge">
</p>

</div>

---

## What is PureAuth?

PureAuth is a developer-focused authentication and licensing
platform designed to make application security simple.

Manage applications, users, licenses, devices, sessions and
access from a single platform.

---

## Platform

<table>
<tr>
<td width="50%">

### Authentication

Secure application authentication,
sessions and account management.

</td>
<td width="50%">

### Licensing

Create, activate, expire and revoke
licenses with flexible controls.

</td>
</tr>

<tr>
<td width="50%">

### Device Control

HWID binding and device management
for authorized users.

</td>
<td width="50%">

### Developer API

Integrate PureAuth directly into
your application using our API.

</td>
</tr>

<tr>
<td width="50%">

### Application Management

Manage multiple applications from
one centralized dashboard.

</td>
<td width="50%">

### Security

Sessions, rate limits, bans, logs
and abuse prevention.

</td>
</tr>
</table>

---

## Developer Experience

Built to integrate into the software
you already use.

| Language | Status |
|:---:|:---:|
| C++ | 🟡 In Development |
| C# | 🟡 In Development |
| Python | 🟡 In Development |
| JavaScript | ⚪ Planned |
| Go | ⚪ Planned |
| Rust | ⚪ Planned |

More SDKs will be released as PureAuth develops.

---

## How It Works

```text
        Your Application
               │
               ▼
        ┌─────────────┐
        │  PureAuth   │
        │     API     │
        └──────┬──────┘
               │
       ┌───────┼────────┐
       ▼       ▼        ▼
   Auth     License   Device
   Check    Check     Check
       │       │        │
       └───────┼────────┘
               ▼
          Access Granted
