# FurEverCarePlatform - Pet Store Management System

Welcome to **FurEverCarePlatform**, a comprehensive pet store management system designed to streamline pet shop operations and provide an excellent experience for both users and administrators. This monorepo integrates three key components of the system, each hosted in separate repositories as Git submodules.

## Project Overview

FurEverCarePlatform consists of three main modules:

1. **[FurEverCarePlatform.Shop](https://github.com/tuanpnt17/FurEverCarePlatform.Shop)**  
   - **Description**: The front-end shop interface for customers to browse and purchase pet products and services.  
   - **Tech Stack**: React, Vite, TypeScript, Ant Design (to be confirmed).  
   - **Location**: `./shop`

2. **[FurEverCarePlatform.Management](https://github.com/nguyentttse180432/FurEverCarePlatform.Managerment)**  
   - **Description**: The management dashboard for shop owners and admins to handle pet inventory, orders, and user management.  
   - **Tech Stack**: React, Vite, TypeScript (to be confirmed).  
   - **Location**: `./management`

3. **[FurEverCarePlatform (Backend)](https://github.com/Datdater/FurEverCarePlatform)**  
   - **Description**: The backend web service providing APIs for both the shop and management modules.  
   - **Tech Stack**: To be confirmed (e.g., Node.js, Spring Boot, etc.).  
   - **Location**: `./backend`

## Getting Started

### Prerequisites
- Git
- Node.js (for front-end modules)
- Backend DotNet runtime

### Clone the Repository
To clone this monorepo with all submodules:
```bash
git clone --recurse-submodules https://github.com/tuanpnt17/FurEverCarePlatform.git
cd FurEverCarePlatform