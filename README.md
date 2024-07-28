# VendorView
VendorView is a comprehensive platform designed to empower street vendors by allowing them to create profiles, list products, and track their whereabouts. The project consists of a backend and frontend, each housed in separate repositories. This repository serves as the parent repository, which includes submodules for both the backend and frontend.

## Table of Contents
* [Overview](#overview)
* [Repositories](#repositories)
* [Setup](#setup)
* [Running the Applications](#running-the-applications)
  * [Backend](#backend)
  * [Frontend](#frontend)

## Overview
VendorView is built to provide a seamless experience for both vendors and customers. The backend is developed using FastAPI, with a PostgreSQL database and Redis for temporary data storage. The frontend is built with Next.js, TypeScript, ShadCN, Tailwind, and Jotai for state management.

## Repositories
The project consists of the following submodules:

### Backend: VendorView Backend
### Frontend: VendorView Frontend
## Setup
Clone the Parent Repository
To clone the parent repository along with its submodules, use the following commands:

```bash
Copy code
git clone --recurse-submodules https://github.com/your-username/vendorview-parent.git
cd vendorview-parent
If you have already cloned the repository without submodules, you can initialize and update them with:
```
```bash
Copy code
git submodule update --init --recursive
Setup Backend
Navigate to the backend directory and follow the Backend README for setup instructions.
```
### Setup Frontend
Navigate to the frontend directory and follow the Frontend README for setup instructions.

## Running the Applications
### Backend
To run the backend server, navigate to the backend directory and follow the instructions in the Backend README.

### Frontend
To run the frontend server, navigate to the frontend directory and follow the instructions in the Frontend README.