# Software Requirements Specification (SRS)

## 1. Requirement Review and Improvement

---

### Requirement 1 (Original)
"The system should be user-friendly."

#### Problems:
-  Not clear
-  Not measurable
-  Not testable
-  Ambiguous

#### Improved Requirement:
The system shall allow a new user to complete account registration within 3 minutes without external assistance.

---

### Requirement 2 (Original)
"The system shall store student records safely."

#### Problems:
-  Not specific
-  Not measurable
-  Ambiguous ("safely")

#### Improved Requirement:
The system shall store student records in an encrypted database using AES-256 encryption and restrict access to authorized users only.

---

### Requirement 3 (Original)
"The system should load quickly."

#### Problems:
- ❌ Not measurable
- ❌ Not testable
- ❌ Ambiguous ("quickly")

#### Improved Requirement:
The system shall load the dashboard page within 2 seconds under normal network conditions (minimum 10 Mbps connection).

---

### Requirement 4 (Original)
"The system shall allow users to register, login, and manage their profile."

#### Problems:
- ❌ Not atomic (multiple requirements combined)
- ❌ Not detailed

#### Improved Requirements:

4.1 The system shall allow users to register using email and password.

4.2 The system shall allow registered users to log in using valid credentials.

4.3 The system shall allow logged-in users to update their profile information including name and password.

---

### Requirement 5 (Original)
"The system shall send notifications."

#### Problems:
-  Not specific
-  Not clear what type of notifications
-  Not measurable

#### Improved Requirement:
The system shall send email notifications to users within 1 minute after successful registration or password reset request.