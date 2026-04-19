# Server-Side Request Forgery (SSRF) Interactive Learning Lab

## Overview

This project is a browser-based interactive lab designed to help learners understand Server-Side Request Forgery (SSRF) through visual simulations and hands-on scenarios.

The lab focuses on how servers make outbound requests, how attackers manipulate these requests to access unintended resources, and how SSRF can be used to reach internal systems that are normally not accessible from the outside.

All concepts are demonstrated in a safe and controlled environment for educational purposes.

## Objectives

* Explain how servers make HTTP requests to external resources
* Demonstrate how user-controlled input can influence server-side requests
* Show how SSRF vulnerabilities occur
* Visualize access to internal networks and services
* Provide interactive simulations of SSRF attack flow
* Teach practical prevention techniques

## Features

* Interactive URL input and server request simulation
* Visualization of request flow (attacker → server → target)
* Internal network diagram simulation (localhost, private IPs, cloud metadata)
* Demonstration of how internal resources are accessed
* Simulated SSRF attack scenarios
* Explanation of filter bypass techniques

## Covered Concepts

* Server-side request behavior
* Difference between client-side and server-side requests
* SSRF vulnerability logic
* Internal vs external network access
* Common SSRF targets:

  * Localhost (127.0.0.1)
  * Private networks (192.168.x.x, 10.x.x.x)
  * Cloud metadata endpoints (169.254.169.254)
* SSRF attack flow (step-by-step)
* Basic filter bypass concepts
* Prevention techniques:

  * Input validation
  * Allowlisting domains
  * Blocking internal network access

## How It Works

The lab is structured into progressive sections:

1. Request Flow
   Demonstrates how servers fetch resources based on user input

2. Attack Simulation
   Shows how attackers manipulate URLs to access unintended targets

3. Network Visualization
   Displays how internal systems are reached through SSRF

4. Impact
   Demonstrates potential consequences such as internal data exposure

5. Prevention
   Explains how proper validation and restrictions prevent SSRF

## Usage

This is a static web application and does not require installation.

To run the project:

* Download or clone the repository
* Open the main HTML file (e.g., `index.html`) in any modern web browser

No additional setup or dependencies are required.

## Important Note

This project is intended strictly for educational purposes.

All attack scenarios are simulated using mock data and controlled logic. The application does not perform real attacks and should not be used against real systems.

## Learning Use Cases

* Cybersecurity training sessions
* Classroom demonstrations
* Self-paced learning
* Web security fundamentals

## Future Improvements

* Advanced SSRF scenarios (blind SSRF, filter bypass techniques)
* Integration with real-world testing workflows
* Enhanced internal network visualization
* Expanded challenge-based exercises

## Contribution

Contributions are welcome. Suggestions for improving simulations, adding new scenarios, or enhancing learning flow are encouraged.


