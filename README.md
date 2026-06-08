Decentralized Blockchain Application

**Introduction**

A Decentralized Blockchain Application developed using Python and Django to demonstrate the fundamental concepts of blockchain technology and decentralized systems. The application enables users to add peers to a network, create transactions, store transactions in blocks, and view the complete blockchain ledger.

The primary goal of this project is to understand how blockchain networks maintain transparency, data integrity, and immutability through interconnected blocks without relying on a centralized authority.

The application simulates a decentralized environment and provides a practical implementation of blockchain concepts such as peer management, transaction processing, block creation, and blockchain visualization.

**Technologies and Dependencies Used**

• Python used as the primary programming language.
• Django used for backend development and request handling.
• HTML used to create web pages and user interfaces.
• CSS used for styling the application.
• SQLite used as the database for storing application data.
• Blockchain data structures used to implement decentralized ledger functionality.

**Using Decentralized Blockchain Application**

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

**Backend Design**

The application consists of four major modules:

• Peer Management
• Transaction Management
• Block Management
• Blockchain Management

These modules work together to simulate the workflow of a decentralized blockchain network.

**Entities**

Peer

A Peer represents a participant or node in the blockchain network.

Attributes:
• Peer Id
• Peer Information
• Network Details

Responsibilities:
• Join the blockchain network.
• Participate in decentralized communication.
• Maintain network consistency.

Transaction

A Transaction represents an operation performed within the blockchain network that must be recorded permanently.

Attributes:
• Transaction Id
• Sender Information
• Receiver Information
• Transaction Description
• Timestamp

Responsibilities:
• Store transaction details.
• Validate transaction information.
• Prepare transactions for block creation.
• Become a permanent part of the blockchain after being added to a block.

Block

A Block is the fundamental unit used to store transaction data in the blockchain.

Attributes:
• Block Id
• Previous Block Reference
• Transaction Data
• Timestamp

Responsibilities:
• Store one or more transactions.
• Link with previous blocks.
• Maintain blockchain integrity.
• Preserve transaction history.

Blockchain

A Blockchain is a collection of interconnected blocks arranged in chronological order.

Attributes:
• Chain of Blocks
• Validation Information
• Network State

Responsibilities:
• Maintain complete transaction history.
• Ensure data consistency.
• Preserve immutability of records.
• Validate block relationships.

**Relationships Between Entities**

• Peers participate in network activities.
• Transactions are created and processed within the network.
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

**Functionalities Exposed**

Home Page

Provides access to all blockchain operations available in the application.

Users can:
• Add peers.
• Create transactions.
• Add transactions to blocks.
• View blockchain information.

Add Peer

Allows users to register a new peer into the decentralized network.

Operations:
• Accept peer information.
• Store peer details.
• Update network data.

Create Transaction

Allows users to create transactions that can later be added to a blockchain block.

Operations:
• Validate transaction information.
• Store transaction details.
• Prepare transaction for block creation.

Add To Block

Allows pending transactions to be added into a blockchain block.

Operations:
• Retrieve transaction data.
• Create a new block.
• Associate transactions with the block.
• Link the block with the previous block.

View Chain

Displays the complete blockchain ledger.

Operations:
• Retrieve all blocks.
• Display transaction history.
• Display blockchain structure.
• Visualize the complete chain.

**Blockchain Workflow**

Step 1
• A peer joins the network.

Step 2
• A transaction is created.

Step 3
• The transaction is validated and stored.

Step 4
• The transaction is added to a block.

Step 5
• The block is linked to the previous block.

Step 6
• The blockchain is updated.

Step 7
• Users can view the complete blockchain ledger.

Workflow Representation

```text
Add Peer
   |
   V
Create Transaction
   |
   V
Add Transaction To Block
   |
   V
Create Block
   |
   V
Update Blockchain
   |
   V
View Chain
```

**Project Structure**

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

**Project Highlights**

• Developed a blockchain-based web application using Python and Django.
• Implemented peer management and transaction processing modules.
• Designed and implemented block creation and blockchain visualization features.
• Demonstrated blockchain concepts such as immutability and linked blocks.
• Simulated decentralized network operations through peer registration and transaction management.
• Built a user-friendly interface for interacting with blockchain data.

**Learning Outcomes**

This project provided practical experience in:

• Blockchain Fundamentals.
• Decentralized Network Architecture.
• Transaction Validation and Processing.
• Block Creation and Chain Management.
• Django Backend Development.
• Database Integration using SQLite.
• Data Integrity and Ledger Management.
• Designing Scalable Backend Applications.

**Future Improvements**

• User Authentication and Authorization.
• Advanced Cryptographic Hashing Algorithms.
• Smart Contract Integration.
• Distributed Peer-to-Peer Communication.
• Blockchain Mining Simulation.
• REST API Development.
• Digital Signature Verification.
• Real-Time Node Synchronization.
• Consensus Mechanisms such as Proof of Work and Proof of Stake.

**Author and Developed By**

Sanjay Kumar Peddaboina

GitHub: https://github.com/sanjupeddaboina
