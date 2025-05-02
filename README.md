# AWS Cognito with Amplify - Setup Guide

This guide will help you integrate AWS Cognito authentication into a Vite + React app using AWS Amplify.

---

## ⚙️ Prerequisites

- Node.js installed
- An AWS Account
- AWS CLI configured

---

## 🚀 Quick CLI Commands

```bash
npm install -g @aws-amplify/cli

amplify configure

npm create vite@latest aws-cognito-amplify
cd aws-cognito-amplify
npm install

amplify init
amplify add auth
amplify push

npm install aws-amplify @aws-amplify/ui-react
