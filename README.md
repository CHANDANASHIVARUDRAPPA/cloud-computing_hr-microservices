HR SERVICES SYSTEM - README

This project demonstrates the integration of multiple microservices as part of our HR Services System. It includes modular functionalities for student welfare, faculty leave, faculty exits, job portal services, and hostel management.

MICROSERVICES INTEGRATED:
Student Welfare Microservice

Handles counseling appointments, wellness programs, and resource management.
Flask-based, integrated via internal API routing.
Faculty Leave Management Microservice

Enables faculty to apply for leaves and view leave status.
Uses Flask, connected through RESTful endpoints.
Faculty Exit and Feedback Microservice

Records faculty resignations and collects feedback.
Modular Flask service communicating with other parts via API.
Job Portal Microservice

Allows candidates to apply for jobs, upload resumes, and track application status.
Flask microservice accessible through its own admin and user dashboards.
Student Hostel Management Microservice

Handles hostel registrations, room allocations, attendance, mess menu, and housekeeping data.
Built with Flask and SQLite, integrated into the main project structure.
Each microservice runs independently with its own Flask server, and all are integrated using Docker Compose, allowing the services to communicate seamlessly through internal networking.
