# API-based Weapon Detection Alert System

A real-time weapon detection system that leverages machine learning to identify potential threats and enhance safety protocols. This application, built with Flask, integrates an API-based model to detect weapons in video feeds and sends alerts with annotated images to security personnel.

## Features

- **Real-time Detection**  
  - Utilizes a machine learning model API to detect weapons in real-time within monitored areas.
  - Automatically processes video frames to identify and label any detected weapons.

- **Automated Email Alerts**  
  - Upon detection, annotated images are sent to designated security personnel via email.
  - Provides instant notifications to ensure swift responses to potential threats.

- **Enhanced Safety Protocol**  
  - Acts as both a deterrent and a detection tool for improved security and threat management.
  - Can be used in various environments, such as public spaces, corporate offices, and more.

- **Scalable Architecture**  
  - Built with Flask to enable flexible API extension and seamless integration with other monitoring and security systems.
  - Designed to be scalable, allowing further enhancements and additions.

## Tech Stack

- **Backend**: Flask
- **Machine Learning Model**: API-based weapon detection model
- **Notifications**: Email alerts with annotated images
- **Deployment**: Scalable architecture for integration with security systems

## Getting Started

1. **Clone the repository**  
   ```bash
   git clone https://github.com/yourusername/weapon-detection-alert-system.git
   cd weapon-detection-alert-system
   ```

2. **Install dependencies**  
   ```bash
   pip install -r requirements.txt
   ```

3. **Configure API and Email Settings**  
   - Update the `config.py` file with the API credentials for the weapon detection model.
   - Configure email settings for sending alerts.

4. **Run the Application**  
   ```bash
   flask run
   ```

## Usage

- The system will monitor video feeds and detect weapons in real-time.
- Alerts with annotated images are sent via email to specified personnel when a weapon is detected.
