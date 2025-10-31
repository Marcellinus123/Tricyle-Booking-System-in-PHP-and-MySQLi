```markdown
# Tricycle Booking System in PHP & MySQLi  
A campus-based digital ride scheduling and logistics management platform designed specifically for **CKT-UTAS students and on-campus residents**. This system serves as a modern alternative to traditional campus tricycle booking arrangements by offering a seamless, transparent, and automated approach to requesting and dispatching tricycles (“Motor King/Pragyia”) for transportation and delivery purposes within the CKT-UTAS campus.

It modernizes student mobility on campus by giving residents an easy way to request rides, track requests, communicate with riders, and ensure fair pricing, time management, and safe transportation around the university environment.

---

## System Overview
The platform provides a web-based interface that streamlines the entire tricycle booking process, removing manual calling, waiting, and negotiation at stand points. It is tailored for campus life needs and allows:

- Students to request tricycle services anytime within allowed campus hours
- Tricycle riders to manage, accept, and complete bookings
- Admins to monitor operations, ensure smooth service delivery, and manage platform users

Designed using **PHP**, **MySQLi**, **HTML5**, **CSS3**, and **JavaScript**, the system focuses on efficiency, simplicity, and real-time task updates to enhance the commuting experience on campus.

---

## Core Features

### Student / Resident
- Registration & secure login (restricted to CKT-UTAS residents only)
- Profile management with student ID verification
- Ability to request tricycle service based on:
  - Pickup location (hostel, lecture block, faculties, library, etc.)
  - Drop-off destination within campus
  - Purpose (ride or goods delivery)
- Real-time ride request dashboard
- Ride cost estimation depending on route or delivery load
- View and track assigned rider details
- Notification when rider accepts the booking
- Ride status updates (pending → accepted → in transit → completed)
- Ability to confirm ride completion
- History of past rides and receipts
- Complaint/feedback submission for service improvement

### Tricycle Driver / Rider
- Account login with admin approval for authenticity
- Dashboard displaying all booking requests
- Ability to accept or decline requests
- Real-time booking updates
- Trip completion marking once service is delivered
- View ride history and earnings summary
- Profile settings (vehicle details, contact information)
- Notification for every new booking assigned/available

### Administrator
- Full control panel for system management
- User management (approve students & driver accounts)
- Monitor all ride requests and statuses
- Assign drivers if rider does not auto-accept
- Manage campus pickup and drop-off points
- View financial and booking reports
- Handle user complaints & feedback
- Maintain service rules, pricing, and availability schedules
- Ability to disable driver/students violating rules

---

## System Workflow

1. Student signs in using university student credentials
2. Student submits a booking request with destination details
3. System calculates estimated cost/distance
4. Riders get notified and can accept the ride
5. Admin auto-assigns if no rider responds
6. Student receives assigned driver information
7. Tricycle driver picks up student or goods
8. Student & driver mark ride as completed
9. System records fare, time, and logs report

This workflow ensures fairness, order, transparency, and smooth transportation across campus.

---

## Target Users

- CKT-UTAS Students staying on campus or nearby hostels
- Verified campus tricycle riders (registered)
- University transportation unit administrators

> Note: System is **restricted** to CKT-UTAS community — prevents outsiders from booking.

---

## Technology Stack
| Technology | Purpose |
|-----------|--------|
| PHP | Backend server logic |
| MySQLi | Database & secure data transactions |
| HTML5 / CSS3 | Frontend UI structure & styling |
| JavaScript | UI interactions, dynamic updates |
| AJAX | Smooth request/response management |
| Session Authentication | Secure login control |
| PHP Mailer (optional) | Notifications & alerts |

---

## Key Objectives
- Modernize CKT-UTAS transportation system
- Reduce stress and queueing at tricycle stations
- Provide transparency in pricing and service flow
- Improve student safety & ride accountability
- Promote digital transformation in campus logistics
- Offer convenience and time-saving booking

---

## Possible Future Enhancements

- GPS tracking for live ride navigation
- Mobile application (Android/iOS)
- Payment integration (Momo/Voucher)
- Emergency button for student safety
- Advanced fare calculation using campus distance mapping
- Driver ratings & review system
- Multi-language support (English, local languages)

---

## Why This System Matters
Transportation inside campuses can be challenging without organization and technology. This booking system bridges that gap by digitizing campus mobility while prioritizing student experience, security, and convenience. With structured registration, booking logs, and admin oversight, the system empowers students and supports a more efficient transportation culture within CKT-UTAS.

It also opens future opportunities like delivery requests for groceries, documents, and school projects, ensuring the tricycle system evolves to match modern campus life.

---

### This is not just a ride-booking script — it is a **campus-mobility digital solution** built specifically for CKT-UTAS to serve students responsibly, securely, and conveniently.

```
