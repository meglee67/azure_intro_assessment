# Storage
## Azure Blob Storage
A cloud-based storage solution, optimized for storing massive amount of unstructured data. Unstructued data being data that doesn't adhere to a particular data model or definition, such as text or binary data.
Blob storage is designed for things like storing files to distributed access, streaming video and audio, serving images or documents directly to a browser, etc. Blob storage offers 3 types of blobs:
1. Block Blobs: Meant to store large binary or text data, block blobs are made up of blocks of data that can be managed individually
2. Page Blobs: These store random access files and virtual hard drive files which serve was disks for Azure Virtual Machines.
3. Append Blobs: Append blobs are optimized for append operations, making them suitable for scenarios like logging, where data is continuously added.

In terms of Python usage, objects stored in Blob Storage can be accessed via various Azure tools or an Azure Storage client library. These client libraries come in various languages, including Python. Through this you can do things like authenticate to Azure and authorize access to blob data, create a container, upload and list blobs in a container, download blobs and delete a container. 

## Azure Confidential Ledger
Azure confidental ledger (ACL) is a new and secure service for managing senstitive data records. ACL uses the Azure Confidental Computing platform and the Confidential Consortium Framework to provide a tamper-protected solution. Integrity of files are maintained through a consensus-based blockchain.
Examples of data that can be stored are:
1. Records relating to business transactions, such as money transfers
2. Updates to trusted assets, such as core applications or contracts
3. Admin and control changes, like granting access permissions
4. Operational IT and security events

Using Python you can do things like create a control plane client library, which allows you to perform operations on ledgers such as creation, modification, deletions, and getting the details of a specific ledger. Once a ledger exists, you can interact with it using a data plane client library, which will allow you to do things like retrieve messages you wrote to the ledger and see the latest transaction committed to the ledger.

# Compute
## Azure Virtual Desktop

## Azure Functions

# Database Services
## Azure Database for MySQL

## Azure Database Migration Service