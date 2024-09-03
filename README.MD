# WhoPaysWhat

## Overview

"WhoPaysWhat" is a web-based tool designed to help groups of people split expenses fairly. It calculates how much each person should either receive or pay to balance out the expenses among all participants.

## Features

### Entering Data

- **Add Participants**: Users can enter each participant's name and the amount they have paid.
- **Automatic Calculations**: The tool automatically calculates the balances and suggests transactions to balance out all payments.

### Balances

- Displays the difference each person should pay or receive to ensure all payments are balanced.

### Transactions

- Provides a minimal list of payments that should be made between participants to settle all balances.

### Sharing and Loading Data

- **Share Configuration**: Users can share their current expense configuration with others by copying the data from a modal.
- **Load Configuration**: Users can also load a shared configuration by pasting it into the modal and confirming the data load, which will overwrite the current session.

## Usage

### Accessing the Tool

Simply open the `index.html` file in a modern web browser to start using the application.

### Adding Data

Click on the "Add Person" button to add a new participant's payment information. Each entry requires a name and the amount paid.

### Sharing Data

Click on the "Share" button to open a modal that allows you to copy your current data or paste data shared with you.

### Loading Data

After pasting the shared data into the modal, click "Load Data" to update the application with the new data.

### Resetting Data

If you need to start over, click the "Reset All" button. Confirm when prompted to clear all existing data.

## Technical Details

- **Framework**: Bootstrap 5.3.3
- **Languages**: HTML, CSS, JavaScript

## Modals

### Help Modal

Provides detailed instructions and explanations about how the application functions.

### Share Modal

Allows users to either copy their current expense data or paste and load data shared from another session.

This README provides an overview and instructions for using the "WhoPaysWhat" application, making it accessible for new and returning users alike.
