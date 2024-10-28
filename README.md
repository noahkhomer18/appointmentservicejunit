# appointmentservicejunit
Appointment Service
This project is a Java application that manages appointments using an Appointment class and an AppointmentService class, with unit tests to ensure functionality and validation.

Files
Appointment.java: Defines the Appointment class, which includes:

appointmentId: A unique ID with a maximum of 10 characters.
appointmentDate: A date that must be in the future.
description: A description limited to 50 characters.
The class enforces validation rules to prevent invalid appointments.
AppointmentService.java: Provides services for managing appointments, including:

addAppointment(): Adds an appointment with a unique ID.
deleteAppointment(): Removes an appointment by ID.
getAppointment(): Retrieves an appointment by ID.
AppointmentServiceTest.java: Contains JUnit tests for AppointmentService, testing:

Adding appointments and ensuring no duplicate IDs.
Deleting appointments and handling non-existent IDs.
AppointmentTest.java: Contains JUnit tests for Appointment, covering:

Creation of valid appointments.
Validation rules for appointmentId, appointmentDate, and description.
Running Tests
Run AppointmentServiceTest.java and AppointmentTest.java with JUnit to ensure functionality and validation rules work as expected.

