# CrypytoMark README
=====================

## Project Overview
CryptoMark is a single-page application that allows users to track their accounts and transactions. The application provides features to create multiple accounts, set transactions like deposits, withdrawals, and transfers between accounts.

## Features
### Accounts
* Create multiple accounts
* View account summaries

### Transactions
* Set transactions like deposits, withdrawals, and transfers between accounts
* Filter transactions by account, category, and transaction type

## Setup
### Backend
1. Change directory to `/backend`
2. Install dependencies with `npm i`
3. Run Express server with `npm run dev`

## API Endpoints
### Accounts
* `GET /accounts`: Get all accounts
* `POST /accounts`: Save a new account

### Transactions
* `GET /transactions`: Get all transactions
* `POST /transactions`: Save a new transaction

### Categories
* `GET /categories`: Get all categories
* `POST /categories`: Save a new category

## Tools
* jQuery

