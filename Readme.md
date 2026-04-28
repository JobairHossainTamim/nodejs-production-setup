<h1 align="center">Production Setup</h1>

# 📦 Production Setup

## 🛠️ Initialize Project

- Run the following command to create a `package.json` file:
  - `npm init -y`

## 🐶 Setup Husky (Git Hooks)

- Install Husky as a dev dependency:
  - `npm install --save-dev husky`
- Initialize Husky:
  - `npx husky init`

## 🔍 Setup Lint-Staged

- Install lint-staged:
  - `npm install --save-dev lint-staged`

## 🟦 Setup TypeScript

- Install TypeScript:
  - `npm install typescript -D`
- Initialize TypeScript config:
  - `npx tsc --init`
- Install Node.js type definitions:
  - `npm i -D @types/node`
- Install ts-node for running TS files:
  - `npm i ts-node`
- Compile TypeScript:
  - `npx tsc`

## 🔄 Setup Nodemon (Auto Restart)

- Install nodemon:
  - `npm i -D nodemon`
