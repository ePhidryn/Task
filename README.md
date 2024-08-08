# TruffleHog Test Repository

This is a test repository for the TruffleHog security scanner. It contains a variety of files and code samples with intentionally planted secrets and sensitive information to be used for testing the capabilities of TruffleHog.

## Overview

The repository contains the following types of files and test cases:

1. **API Keys and Tokens**
   - `test_api_key.txt`: Contains a simple API key.
   - `test_high_entropy.txt`: Contains a high-entropy string that should be detected as a potential secret.
   - `config.ini`: Contains a password in a configuration file.
   - `false_positive.txt`: Contains a string that should not be detected as a secret.

2. **Git Repository History**
   - The repository has a history of commits with various changes, including the introduction and removal of secrets.

## Usage

To use this test repository with TruffleHog, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/trufflehog-test-repo.git
