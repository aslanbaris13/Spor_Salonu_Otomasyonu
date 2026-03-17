# Fitness Center Automation System 🏋️

> **Member management desktop application built with C# and N-Tier Architecture**

![C#](https://img.shields.io/badge/C%23-239120?style=flat&logo=c-sharp&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-512BD4?style=flat&logo=dotnet&logoColor=white)
![Access](https://img.shields.io/badge/MS_Access-A4373A?style=flat&logo=microsoft-access&logoColor=white)
![Status](https://img.shields.io/badge/Status-Archived-gray?style=flat)

---

## Overview

A Windows desktop automation system for managing fitness center member operations — registration, updates, and tracking — built following N-Tier (Layered) Architecture principles.

> 🗂️ **Archived academic project.**

---

## Features

- 👤 **Member Management** — Add, update, and remove member records
- 📄 **PDF Export** — Generate membership forms via iTextSharp
- 📊 **Graphical Analysis** — Visualize occupancy and registration trends with ZedGraph
- 🔒 **Data Security** — BouncyCastle integration for cryptographic operations
- 🏗️ **Layered Architecture** — Clean separation of Presentation, Business, DataAccess, and Entity layers

---

## Tech Stack

| Layer | Technology |
|---|---|
| Language | C# |
| UI Framework | Windows Forms |
| Database | MS Access (OleDb) |
| Architecture | N-Tier (Layered) |
| PDF Generation | iTextSharp |
| Charts | ZedGraph |
| Cryptography | BouncyCastle |

---

## Project Structure

```
BusinessLayer/      → Business logic and validation
DataAccessLayer/    → Database CRUD operations
EntityLayer/        → Database entity classes
Fitness_Club/       → WinForms UI
```

---

## Setup

```bash
git clone https://github.com/aslanbaris13/Spor_Salonu_Otomasyonu.git
```
Open `Fitness_Club.sln` in Visual Studio and run.
