<div align="center">

# RESQNET

### Offline Emergency Communication & Bluetooth Mesh Network

**Offline-first emergency communication designed for situations where conventional network connectivity is unavailable or disrupted.**

</div>

---

## About RESQNET

RESQNET is an offline-first emergency communication platform designed to support communication when conventional Internet connectivity is unavailable or disrupted.

RESQNET uses **Bluetooth Low Energy (BLE)**, **store-and-forward communication**, and **multi-hop message relay** to allow nearby RESQNET devices to exchange emergency information.

The platform is designed for emergency and disaster-response scenarios where conventional communication infrastructure may be unavailable, unreliable, or disrupted.

---

## Key Features

- Emergency SOS broadcasting
- Emergency Alert creation and distribution
- Request Help
- Volunteer Network
- Offline emergency communication
- Bluetooth Low Energy communication
- Multi-hop message relay
- Store-and-forward messaging
- Private messaging
- Community Centre broadcasts
- Missing-person reporting
- Safe-location sharing
- Offline maps
- Contact exchange
- Message encryption and authentication
- Duplicate-message protection
- Message TTL and expiry controls

---

# Application Preview

## Dashboard

<p align="center">
  <img src="screenshots/Screenshot_20260921_144844.jpg.jpeg" width="240" alt="RESQNET Dashboard">
  &nbsp;&nbsp;
  <img src="screenshots/Screenshot_20260921_144841.jpg.jpeg" width="240" alt="RESQNET Dashboard">
  &nbsp;&nbsp;
  <img src="screenshots/Screenshot_20260921_144847.jpg.jpeg" width="240" alt="RESQNET Dashboard">
</p>

<p align="center">
  <b>Emergency Dashboard & Core RESQNET Features</b>
</p>

---

## Emergency Alerts

RESQNET enables users to create and distribute emergency alerts through participating devices.

<p align="center">
  <img src="screenshots/WhatsApp%20Image%202026-09-21%20at%2019.13.48%20(1).jpeg" width="230" alt="RESQNET Emergency Alert">
  &nbsp;
  <img src="screenshots/WhatsApp%20Image%202026-09-21%20at%2019.13.48.jpeg" width="230" alt="RESQNET Emergency Alert">
  &nbsp;
  <img src="screenshots/WhatsApp%20Image%202026-09-21%20at%2019.13.47%20(2).jpeg" width="230" alt="RESQNET Emergency Alert">
</p>

---

## SOS Emergency Broadcasting

The SOS feature is designed to distribute emergency information across reachable RESQNET devices.

<p align="center">
  <img src="screenshots/WhatsApp%20Image%202026-09-21%20at%2019.08.15%20(1).jpeg" width="230" alt="RESQNET SOS">
  &nbsp;
  <img src="screenshots/WhatsApp%20Image%202026-09-21%20at%2019.08.15.jpeg" width="230" alt="RESQNET SOS">
  &nbsp;
  <img src="screenshots/WhatsApp%20Image%202026-09-21%20at%2019.08.14%20(1).jpeg" width="230" alt="RESQNET SOS">
</p>

---

## Request Help

Users can create help requests containing information needed by nearby participants and volunteers.

<p align="center">
  <img src="screenshots/1000275566.jpg.jpeg" width="240" alt="RESQNET Request Help">
  &nbsp;&nbsp;
  <img src="screenshots/1000275743.jpg.jpeg" width="240" alt="RESQNET Request Help">
  &nbsp;&nbsp;
  <img src="screenshots/1000275570.jpg.jpeg" width="240" alt="RESQNET Request Help">
</p>

---

## Volunteer Network

RESQNET includes functionality for coordinating volunteers and emergency assistance.

<p align="center">
  <img src="screenshots/1000275576.jpg.jpeg" width="250" alt="RESQNET Volunteer Network">
  &nbsp;&nbsp;
  <img src="screenshots/1000275722.jpg.jpeg" width="250" alt="RESQNET Volunteer Network">
</p>

---

## Community Centre

The Community Centre provides a shared space for distributing community information across participating RESQNET devices.

<p align="center">
  <img src="screenshots/WhatsApp%20Image%202026-09-21%20at%2019.12.09.jpeg" width="250" alt="RESQNET Community Centre">
  &nbsp;&nbsp;
  <img src="screenshots/WhatsApp%20Image%202026-09-21%20at%2019.12.08.jpeg" width="250" alt="RESQNET Community Centre">
</p>

---

## Missing Person Reporting

Missing-person information can be created and distributed through the RESQNET communication network.

<p align="center">
  <img src="screenshots/1000275574.jpg.jpeg" width="240" alt="RESQNET Missing Person Report">
  &nbsp;&nbsp;
  <img src="screenshots/1000275710.jpg.jpeg" width="240" alt="RESQNET Missing Person Report">
  &nbsp;&nbsp;
  <img src="screenshots/1000275572.jpg.jpeg" width="240" alt="RESQNET Missing Person Report">
</p>

---

## Safe Locations

RESQNET allows important locations such as shelters, hospitals, police stations, relief camps, safe zones, and other emergency resources to be shared.

<p align="center">
  <img src="screenshots/WhatsApp%20Image%202026-09-21%20at%2019.06.42.jpeg" width="250" alt="RESQNET Safe Locations">
  &nbsp;&nbsp;
  <img src="screenshots/WhatsApp%20Image%202026-09-21%20at%2019.06.41.jpeg" width="250" alt="RESQNET Safe Locations">
</p>

---

## Contact Exchange

RESQNET provides contact exchange functionality for connecting participating users.

<p align="center">
  <img src="screenshots/WhatsApp%20Image%202026-09-21%20at%2019.10.20.jpeg" width="220" alt="RESQNET Contacts">
  &nbsp;
  <img src="screenshots/WhatsApp%20Image%202026-09-21%20at%2019.10.19%20(2).jpeg" width="220" alt="RESQNET Contacts">
  &nbsp;
  <img src="screenshots/WhatsApp%20Image%202026-09-21%20at%2019.10.19%20(1).jpeg" width="220" alt="RESQNET Contacts">
</p>

---

# How RESQNET Works

A RESQNET device can exchange emergency information with nearby RESQNET devices using Bluetooth Low Energy.

Messages can be stored and relayed between participating devices, allowing information to travel beyond the direct Bluetooth range of the originating device when suitable relay devices are available.

<div align="center">

### Multi-Hop Communication

**Device A → Device B → Device C → Device D**

</div>

Conceptually:

<pre>
Emergency Message
        |
        v
  RESQNET Device A
        |
       BLE
        v
  RESQNET Device B
        |
   Store & Forward
        |
       BLE
        v
  RESQNET Device C
        |
       BLE
        v
  RESQNET Device D
</pre>

Each participating device can help relay eligible messages through the network while duplicate-message protection, message expiry, and TTL controls help manage message propagation.

---

# Technology

RESQNET is currently developed using **Flutter** with native Android integration for Bluetooth Low Energy communication.

The application follows an **offline-first architecture**.

### Core Technologies

<table>
  <tr>
    <td><b>Application Framework</b></td>
    <td>Flutter / Dart</td>
  </tr>
  <tr>
    <td><b>Platform</b></td>
    <td>Android</td>
  </tr>
  <tr>
    <td><b>Communication</b></td>
    <td>Bluetooth Low Energy (BLE)</td>
  </tr>
  <tr>
    <td><b>Communication Model</b></td>
    <td>Store-and-Forward / Multi-Hop Relay</td>
  </tr>
  <tr>
    <td><b>Architecture</b></td>
    <td>Offline-First</td>
  </tr>
  <tr>
    <td><b>Local Data</b></td>
    <td>On-device persistent storage</td>
  </tr>
  <tr>
    <td><b>Security</b></td>
    <td>Application-level encryption and authentication</td>
  </tr>
</table>

---

# Security

RESQNET incorporates application-level cryptographic mechanisms designed to protect:

- Message confidentiality
- Message integrity
- Message authenticity
- Local cryptographic material
- Communication between participating RESQNET devices

Additional communication controls include:

- Unique message identification
- Duplicate-message protection
- Message TTL controls
- Message expiry
- Controlled store-and-forward propagation

Detailed cryptographic implementation, private key material, signing credentials, and internal security mechanisms are intentionally not published in this repository.

---

# Use Cases

RESQNET is intended for communication scenarios where conventional network infrastructure may be unavailable or unreliable, including:

- Disaster-response environments
- Emergency communication
- Network outage scenarios
- Remote or infrastructure-limited environments
- Community emergency coordination
- Volunteer coordination
- Missing-person information distribution
- Emergency resource and safe-location sharing

---

# Source Code

> **RESQNET is proprietary software.**

This repository is maintained as a **public product showcase and documentation repository**.

The production source code, BLE communication implementation, cryptographic implementation, signing credentials, internal application components, and other proprietary implementation details are **not publicly distributed through this repository**.

---

# Project Status

RESQNET is currently under active development, testing, and validation.

Features and interfaces shown in this repository may evolve as development continues.

---

<div align="center">

## IntProSec Private Limited

**RESQNET — Offline Emergency Communication**

© 2026 IntProSec Private Limited. All rights reserved.

</div>