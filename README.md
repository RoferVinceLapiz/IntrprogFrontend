# Angular 21 Auth Boilerplate (Beginner Guide)

This project is a beginner-friendly Angular 21 boilerplate that demonstrates a complete authentication flow:

- Email sign up + email verification
- Login + Logout
- JWT auth header for API requests
- Refresh tokens (cookie-based) + auto-refresh before access token expiry
- Forgot password + reset password
- Role-based authorization (User & Admin)
- Admin area for account management
- Profile area for viewing/updating your own account

## Table of contents

- [1) Prerequisites](#1-prerequisites)
- [2) Run the app (real API)](#2-run-the-app-real-api)
- [3) Run the app (fake backend, no API)](#3-run-the-app-fake-backend-no-api)
- [4) Using the app (what to click)](#4-using-the-app-what-to-click)
- [5) How authentication works](#5-how-authentication-works)
- [6) Authorization (roles + route guards)](#6-authorization-roles--route-guards)
- [7) Project structure (quick tour)](#7-project-structure-quick-tour) 
- [8) Troubleshooting](#8-troubleshooting)

## 1) Prerequisites

- Node.js (LTS recommended) 
- npm (comes with Node.js) (Optional) Angular CLI:
- `npm i -g @angular/cli`


## 2) Run the app (real API)
By default this project is set up to call a real API at:
http://localhost:4000 (see 'src/environments/environment.ts`)
### Step 1: install packages
From the project root (where `package.json' is):
**bash
npm install
### Step 2: start your backend API
Start an API that implements the /accounts/* endpoints described in the [How authentication works] (#5-how-authentication-works) section.
The frontend expects the API to be available at http://localhost:4000 by default.
### Step 3: start Angular
bash
npm start
This runs `ng serve --open and should open the app in your browser.

# IPT 2026 Frontend

Angular 21 Authentication Frontend with JWT, Role-Based Access Control and Email Verification.

## Live App
https://ipt-2026-frontend-rollo.onrender.com

## Setup Instructions
1. Clone the repo
2. Run `npm install`
3. Run `ng serve`

## Features
- Registration with email verification
- Login with JWT and Refresh Token
- Forgot/Reset Password
- Role-Based Access Control (Admin/User)
- Fake Backend for local testing (Stage A)
- Real Backend integration (Stage B)

## Tech Stack
- Angular 21
- Bootstrap
- JWT Authentication