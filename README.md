# Booking-Parking-System
A smart campus parking concept for BINUS University that lets students and staff book a parking spot in advance and see live spot availability, so they spend less time circling the parking area and less time stuck in congestion around campus.

The Problem
Parking space at campus is limited while the number of students, lecturers, and staff grows every year. Between 07:00 and 17:00 the situation is worst, and it leads to three connected problems:
- Limited parking space. Capacity stays the same while the number of vehicles keeps growing.
- Traffic congestion. Drivers who can't find a spot park outside designated areas or keep circling, which blocks the parking area and nearby roads.
- Wasted time. Users need multiple round trips to find a spot, causing delays to classes and other academic activities.

The Solution
A hybrid parking system that supports two kinds of users at once:
Booking users reserve a spot through the app (up to 48 hours in advance), receive a digital QR code, and are verified on arrival.
Walk-in users can still park the old way in any free spot.

How the system works
- Reservation: The user opens the app. The system checks that the user has a class or work schedule on campus that day, and only then allows booking. The user picks a spot, enters vehicle data, and receives a QR code. The spot's LED turns from green to blue.
- Arrival and detection: An AI camera reads the license plate when the vehicle enters the spot and compares it with the booked data. A mismatch triggers a warning notification.
- Attendance confirmation: The user scans the QR code at the scanner on the parking pole. If the QR code and the plate match, the LED turns red and the booking is marked Confirmed.
- Finished parking: An ultrasonic sensor detects the vehicle leaving, the LED returns to green, and the spot becomes available again.

UI Design
The Figma prototype covers the full user journey:
- Splash screen and onboarding slides
- Location permission, sign up and sign in
- Main map page with nearby parking
- Pick-a-slot screen by floor
- iBooking form and booking details
- Processing and success states
- Digital parking ticket with QR code
- Admin dashboard with system performance report

My Contribution
- Analyzed the parking problem and defined the system requirements
- Modeled the system with a Use Case Diagram and Class Diagram
- Designed the screens in Figma as part of the project design work
