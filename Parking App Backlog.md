1. Product Backlog 1.1 

Login & Authentication 

PBI-101 : As a user/operator, I want to log in using my email/username and password so that I can access my respective application dashboard. PBI-102 : I as a new user want to create an account using my email, vehicle information and phone number, and be able to book a parking spot. 

PBI-103: As a user/operator I want to reset my forgotten password by using a secure email link so that I am able to get back into my account. 

PBI-104 : When logging into my account, as a user/operator, I would like to be asked for multi-factor authentication so that my account is more secure.

 PBI-105 : When I log off from an active session I want to ensure that it is secure and that it ends on all devices that are open.
 
 1.2 UI for Operator and User
 
PBI-201 (User UI): Interactive Map & Search View for parking near you, parking rates and real time availability pins.

PBI-202 (User UI): Garage Detail Screen with Spot Visual Map, hours and pricing tiers.

PBI-203 (User UI): Reservation, users can select their dates, time slots, and specific spots.

PBI-204 (User UI): Digital Pass & QR Code Screen for parking pass activation.

PBI-205 (User UI): Active Session Screen with a remaining parking time countdown, and the "Extend Session" button.

PBI-206 (User UI): User Profile & Vehicle Management Screen to manage personal data and license plates & preferred payment methods.

PBI-207 (User UI): Reservation History UI: user will be able to see past, active and upcoming reservation history, with ability to download the receipts.

PBI-208 (User UI): Payment Gateway Checkout UI with credit/debit card, apple pay and google pay input.

Operator UI:

PBI-209 (Operator UI): Operator Live Dashboard with real-time total occupancy, revenue today and entry/exit activity.

PBI-210 (Operator UI): Interactive Layout & Spot Management UI - graphically view, block/unblock or reserve specific spot.

PBI-211 (Operator UI): Rate Management UI, to set up dynamic pricing, peak hours, daily maximums and special event flat rate.

PBI-212 (Operator UI) Garage Profile & Facility Settings UI to configure operational hours, contact and total number of spots.

 PBI-213 Portal for manual override of entry/exit gate for vehicle operators to allow for vehicle access or to clear plate errors.

PBI-214 (Operator UI): Active Violations & Overstay Monitor UI shows the flag statements of unpaid/in overstayed vehicles.

PBI-215 (Operator Staff & Role Management UI): Operator Staff & Role Management UI to create different levels of access to gate for shift to gate guards & managers. 

1.3 Backend Processes for Operator and User User-Facing Backend Processes

PBI-301 (User Backend): Real Time Reservation Engine to temporarily reserve a selected spot for 10 minutes during checkout to avoid double reserving. 

PBI-302 (User Backend): Automated Payment & Settlement Microservice that integrates with Stripe/PayPal APIs to carry out pre-authorizations and charges. 

PBI-303 (User Backend): QR Code/Digital Ticket Generator with Automation which creates signed and time-decaying validation tokens after successful payment. 

PBI-304 (User Backend): Push & SMS Notification Service for reservation confirmation, 15 minutes expiration and extension remind. 

PBI-305 (User Backend): Dynamic Parking Fee Calculation Engine which will analyze the duration, base rates, time-of-day fee, and promo codes. 

PBI-306 (User Backend): Processing additional charges and updating the duration of parking as per user demand; Auto Parking Session Extension Handler functionality added. 

PBI-307 (User Backend): User Refund & Cancellation Workflow processing automated refunds based on cancellation policy rules.

Operator-Facing Backend Processes:

PBI-309 (Operator Backend):Occupancy Tracking Engine synchronizing physical sensor/gate triggers with the database spot availability. 

PBI-310 (Operator Backend): Automated Overstay Detection for vehicles that overstay. 

PBI-311 (Operator Backend): Automated Dynamic Pricing Algorithm rate changes according to the current booking rates. 



