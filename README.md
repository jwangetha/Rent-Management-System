# Rent-Management-System
Creating a Rent Management System for Landlords
# Rent Management System

This project is a comprehensive Rent Management System designed to help landlords and property managers track tenants, rent payments, penalties, invoices, room occupancy, and balances owed.

## Features

- **Tenant Details Management:** Store and update tenant information such as name, contact details, and room assigned.
- **Rent Tracking:** Record rent due dates, payment status, and amounts paid.
- **Penalty Calculation:** Automatically apply a 10% penalty for late payments.
- **Invoice Generation:** Generate detailed invoices for each tenant.
- **Room Occupancy Status:** Monitor whether rooms are occupied or vacant.
- **Balance Tracking:** Keep track of outstanding balances for each tenant.

## Getting Started

### Prerequisites

- Python 3.x
- SQLite3 (or any preferred database)

### Installation

1. Clone the repository:

```bash
git clone https://github.com/yourusername/rent-management-system.git
cd rent-management-system
```

2. Install required packages:

```bash
pip install -r requirements.txt
```

### Usage

- Run the main application:

```bash
python main.py
```

- Follow the prompts to add tenants, record payments, generate invoices, and view occupancy statuses.

## Data Model Overview

- **Tenants:** ID, Name, Contact, Room Number, Occupancy Status
- **Rent Payments:** Tenant ID, Due Date, Payment Date, Amount, Penalty Applied
- **Rooms:** Room Number, Status (Occupied/Vacant)
- **Invoices:** Invoice ID, Tenant ID, Amount, Date, Penalty, Total Due

## Penalty Logic

- If a rent payment is made after the due date, a 10% penalty is added to the overdue amount.

## License

This project is licensed under the MIT License.

## Contact

For questions or contributions, please contact [jwangetha@gmail.com].

---
Still under construction.
