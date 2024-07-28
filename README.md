# DOCTOR-CARE-SYSTEM
Blockchain-Based Healthcare Management System
Objective:
The primary goal of this project is to ensure secure and reliable storage of healthcare data, specifically tracking the doctor responsible for treating a patient. This system helps in identifying the correct doctor in case of any discrepancies or issues in patient care.

# Components:

# Doctor.sol:

Description: This smart contract manages doctor details.
Functionality:
Add and manage doctor credentials.
Verify the identity and credentials of doctors.

# Hospital.sol:

Description: This smart contract handles hospital information and transactions.
Functionality:
Register and manage hospital details.
Facilitate transactions between hospitals and other entities in the system.
Patient.sol:

Description: This smart contract manages patient details.
Functionality:
Add and manage patient information.
Ensure patient data is securely stored and accessible.

# Record.sol:

Description: This smart contract handles patient records.
Functionality:
Store patient medical records securely.
Track and manage the doctor responsible for each patient’s treatment.

# HealthcareSystem.sol:

Description: This overarching smart contract coordinates interactions between doctors, hospitals, and patients.
Functionality:
Ensure secure and seamless transactions across the healthcare network.
Maintain a decentralized and tamper-proof ledger of all healthcare activities.


# Key Features:

# Secure Data Storage:

Patient records and doctor details are stored on the blockchain, ensuring data integrity and security.
Encryption techniques ensure that sensitive information remains confidential.

# Reliable Doctor Identification:

Each patient's treatment is linked to a specific doctor, recorded on the blockchain.
In case of any issues or disputes, the system can accurately identify the responsible doctor.

# Transparency and Accountability:

Blockchain’s immutable ledger provides a transparent record of all transactions.
Enhances accountability by ensuring that all actions are recorded and cannot be altered.

# Decentralized Access:

Decentralized system removes the need for a central authority, reducing the risk of single points of failure.
Patients, doctors, and hospitals can interact directly through smart contracts.

# Audit Trail:

Comprehensive audit trail for all healthcare interactions.
Facilitates audits and compliance checks by providing a clear history of all transactions.

# Hospital Transaction Example:

A hospital initiates a transaction to add a new patient record.
The transaction includes details about the patient and the doctor assigned to the case.
The smart contract verifies the doctor’s credentials and securely stores the patient record.
The blockchain ledger is updated with the new transaction, ensuring it is immutable and transparent.
