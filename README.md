# job-portal-sc
# JobPortal Smart Contract

This is a Solidity smart contract that serves as a foundation for a decentralized job portal. It allows users to register, post job opportunities, and interact with the system for employment-related activities. The contract is designed to operate on the Ethereum blockchain.

---

## Features

1. **User Registration**:
   - Users can register by providing personal details such as:
     - First name
     - Last name
     - Phone number
     - Address
     - Aadhar number (or similar unique ID)
     - Password
     - User type (e.g., employer, job seeker)

2. **Job Posting**:
   - Employers can add jobs with the following details:
     - Job ID
     - Job name
     - Location
     - Duration
     - Wage
     - Contact person
     - Contact details

3. **Data Storage**:
   - Data is organized into two main structures:
     - `user`: Stores user information.
     - `jobpool`: Stores job-related information.

4. **Potential Expansions**:
   - The contract can be extended to include features like:
     - Job application process
     - User authentication
     - Enhanced security measures
     - Payment functionalities for wages

---

## Prerequisites

- **Solidity Version**: `^0.8.26`
- **Ethereum Development Environment**:
  - [Remix IDE](https://remix.ethereum.org/) for development and testing.
  - [Truffle](https://trufflesuite.com/) or [Hardhat](https://hardhat.org/) for local development.
- A compatible Ethereum wallet like [MetaMask](https://metamask.io/).

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/JobPortal.git
   cd JobPortal
