# Installation Guide

## Overview

This guide explains how to install and set up the Zphisher phishing tool on Kali Linux.

## Prerequisites

Before you begin, ensure you have the following:

- Kali Linux (or any Debian-based Linux distribution)
- Git installed

## Installation Steps

1. **Update Package Lists**

   Open your terminal and run:

   sudo apt update
   sudo apt full-upgrade -y
2. **Install Dependencies**

Install Git and Curl if they are not already installed:

sudo apt-get install -y git curl


3. **Clone the Repository**

Clone the Zphisher repository:

git clone https://github.com/htr-tech/zphisher.git


4. **Navigate to the Project Directory**

Change into the Zphisher directory:

cd zphisher