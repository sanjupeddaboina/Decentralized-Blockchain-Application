Decentralized Blockchain Application

Introduction

A Decentralized Blockchain Application developed using Python and Django to demonstrate the working principles of blockchain technology and decentralized networks. The application allows users to create transactions, add peers to a blockchain network, store transactions inside blocks, and view the complete blockchain ledger.

The primary objective of this project is to understand how blockchain systems maintain data integrity through chained blocks and decentralized data management without relying on a central authority.

The backend is designed using Django and implements blockchain concepts such as peer management, transaction management, block creation, and blockchain visualization.

Technologies and Dependencies Used

• Python used as the primary programming language.
• Django used to build the web application and manage backend operations.
• HTML used to create user interfaces.
• CSS used for styling web pages.
• SQLite used as the database for storing application data.
• Blockchain data structures used to implement decentralized ledger functionality.

Using Decentralized Blockchain Application

CLI -->

```bash
git clone https://github.com/sanjupeddaboina/Decentralized-Blockchain-Application.git
cd Decentralized-Blockchain-Application
pip install django
python manage.py runserver
```

Open Browser -->

```text
http://127.0.0.1:8000/
```

Backend Design

Main Components

The application consists of four major modules:

• Peer Management
• Transaction Management
• Block Management
• Blockchain Management

These modules work together to simulate a decentralized blockchain network.

Entities

Peer

A Peer represents a node participating in the blockchain network.

Attributes:

• Peer Id
• Peer Information
• Network Details

Responsibilities:

• Join the blockchain network.
• Participate in decentralized communication.
• Maintain blockchain consistency.

Transaction

A Transaction represents an activity performed by a user which needs to be recorded on the blockchain.

Attributes:

• Transaction Id
• Sender Information
• Receiver Information
• Transaction Description
• Timestamp

Responsibilities:

• Store transaction information.
• Validate transaction data.
• Wait for block creation.
• Become a permanent part of the blockchain once added to a block.

Block

A Block is the fundamental storage unit of the blockchain.

Attributes:

• Block Id
• Previous Block Reference
• Transaction Data
• Timestamp

Responsibilities:

• Store one or more transactions.
• Maintain linkage with previous blocks.
• Preserve blockchain integrity.

Blockchain

Blockchain is a collection of interconnected blocks arranged sequentially.

Attributes:

• Chain of Blocks
• Validation Information
• Network State

Responsibilities:

• Maintain complete transaction history.
• Ensure data integrity.
• Preserve immutability of records.

Relationships Between Entities

• Peer participates in blockchain operations.
• Transactions are created and managed within the network.
• Transactions are stored inside blocks.
• Blocks are linked together to form a blockchain.

Relationship Flow

```text
Peer
 |
Transaction
 |
Block
 |
Blockchain
```

Functionalities Exposed

Home Page

Provides navigation to all blockchain operations.

Users can:

• Add peers.
• Create transactions.
• Add transactions to blocks.
• View blockchain.

Add Peer

Allows users to register a peer into the decentralized network.

Operations:

• Accept peer details.
• Store peer information.
• Update network state.

Create Transaction

Allows users to create a blockchain transaction.

Operations:

• Validate transaction information.
• Store transaction details.
• Prepare transaction for block creation.

Add To Block

Allows pending transactions to be added into a blockchain block.

Operations:

• Retrieve transaction data.
• Create a block.
• Associate transactions with the block.
• Link the block with the previous block.

View Chain

Displays the complete blockchain ledger.

Operations:

• Retrieve all blocks.
• Display transaction history.
• Show blockchain structure.

Blockchain Workflow

Step 1: A peer joins the network.

Step 2: A transaction is created.

Step 3: The transaction is stored temporarily.

Step 4: The transaction is added into a block.

Step 5: The block is linked to the previous block.

Step 6: The blockchain is updated.

Step 7: Users can view the updated blockchain ledger.

Project Structure

```text
Decentralized-Blockchain-Application
│
├── BC
│   ├── Block.py
│   └── Blockchain.py
│
├── Blockchain
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
│
├── BlockchainApp
│   ├── templates
│   ├── static
│   ├── views.py
│   └── urls.py
│
├── manage.py
├── Screenshots.docx
└── README.md
```

Project Highlights

• Developed a Decentralized Blockchain Application using Python and Django.
• Implemented blockchain concepts such as transactions, blocks, and chain management.
• Designed modules for peer management, transaction processing, and blockchain visualization.
• Built a web-based interface for creating transactions and viewing blockchain data.
• Demonstrated blockchain data integrity through linked blocks and transaction history management.
• Simulated decentralized network operations through peer registration and transaction handling.

Learning Outcomes

This project provided practical experience in:

• Blockchain Fundamentals.
• Decentralized Network Architecture.
• Transaction Processing and Validation.
• Block Creation and Chain Management.
• Python Backend Development.
• Django Framework Development.
• Database Integration using SQLite.
• Data Integrity and Ledger Management.

Future Improvements

• User Authentication and Authorization.
• Advanced Cryptographic Hashing Algorithms.
• Smart Contract Integration.
• Distributed Peer-to-Peer Communication.
• Blockchain Mining and Proof-of-Work Simulation.
• REST API Development.
• Digital Signature Verification.
• Real-Time Node Synchronization.
• Consensus Algorithms.

Author and Developed By

Sanjay Kumar Peddaboina
