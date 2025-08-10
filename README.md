# SystemKey-Discord-Webhook

A simple key-based authentication system that generates a unique code, sends it to a Discord webhook, and allows users to register or log in using this code.

## Overview

- The program generates a random authentication code (key).
- This key is sent to a configured Discord webhook for logging and monitoring.
- Users can register or log in to the program using the generated key.
- The system tracks each authentication attempt by logging device information and key usage.

## Features

- Generates unique authentication keys.
- Sends keys and login attempts to a Discord webhook.
- Allows user registration/login using the key.
- Logs device details such as username, HWID, IP address, etc.


## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/NoMoreLife-1/SystemKey-Discord-Webhook.git
