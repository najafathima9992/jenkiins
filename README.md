# Jenkins CI/CD Pipeline for Automated Web Deployment

This project demonstrates a simple CI/CD pipeline using **Jenkins**, **GitHub**, **AWS EC2**, and **Apache** to automatically deploy a static web application.

## Project Overview

The goal of this project is to eliminate manual deployment and ensure that every code update is automatically reflected in the live application.

Whenever code is pushed to the GitHub repository, Jenkins pulls the latest changes and deploys them to the web server directory hosted on an AWS EC2 instance.

## Architecture

Developer → GitHub Repository → Jenkins Pipeline → AWS EC2 → Apache Web Server

## Tools Used

- Jenkins
- GitHub
- AWS EC2
- Apache HTTP Server
- Git
- Linux

## Features

- Detects code changes from GitHub
- Automates deployment to live server
- Reduces manual effort
- Ensures faster and more consistent releases

## Project Structure

```bash
.
├── index.html
└── Jenkinsfile
