# Ethernote

Open Smart Contract Template for Promissory Note DApp (Lump-Sum Repayment).

[![Join the chat at https://gitter.im/blocknotary/ethernote](https://badges.gitter.im/blocknotary/ethernote.svg)](https://gitter.im/blocknotary/ethernote?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

## How does it work?

High level worklfow diagram:
* A borrower fills the note details
* A lender fills the note detail
* Borrower and lender sign the note
* The note initializes a smart contract  
* Lender funds the note 
* Borrower paids the note in full 

![Workflow diagram](https://raw.githubusercontent.com/blocknotary/ethernote/master/design/workflow.png)

## Design

### Step 1

A borrower fills the note details

![Step 1](https://raw.githubusercontent.com/blocknotary/ethernote/master/design/cert_1.png)

### Step 2

A lender fills the note detail

![Step 2](https://raw.githubusercontent.com/blocknotary/ethernote/master/design/cert_2.png)

### Step 3

After the note is signed the note template is fixed and a footer added. On the right side of the note there is a history/timeline which is updated by changes in note and related smart contract.

![Step 3](https://raw.githubusercontent.com/blocknotary/ethernote/master/design/cert_3.png)


## Documents

Lump-Sum Repayment Promissory Note template:

https://docs.google.com/document/d/1MdvXL_PHxQREp1CU-PT3isyQQnTwbQl0hBtSnnM3bHs/edit?usp=sharing

## License

MIT

