1. Product Backlog 1.1 

Login & Authentication 

PBI-102: As a user/operator, I want to log in with my email/username and my password, so that I can access my application dashboard. PBI-102 : I as a new user want to create an account using my email, vehicle information and phone number, and be able to book a parking spot. 

PBI-103: As a user/operator I want to reset my forgotten password by using a secure email link so that I am able to get back into my account. 

PBI-104 : As a user/operator, I want to be prompted for a second factor of authentication (FFA) when logging into my account, to make my account more secure.

 PBI-105 : I want to make sure when I log off from a session that it's secure and that it logs off from all active devices.

 
 1.2 UI for Operator and User

 
PBI-201 (User UI): Interactive Map & Search View for parking near you, parking rates and real time availability pins.

Hours and pricing tiers on the Garage Detail Screen with Spot Visual Map. (PBI-202 User UI)

PBI-203 (User UI): Reservation allows users to choose their dates, time slots and specific user spots.

PBI-204 (User UI): Digital Pass & QR Code for parking pass activation screen.

PBI-205 (User UI): Active Session Screen with a remaining parking time countdown, and the "Extend Session" button.

PBI-206 (User UI): User Profile & Vehicle Management Screen to manage personal data and License Plate & Preferred Payment Methods.

PBI-207 (User UI): UI for Reservation History: user will be able to view past, current and future Reservation History — with the option to download the receipts.

PBI-208 (User UI): Payment Gateway Checkout UI with Credit/Debit card, apple pay and google pay input.


Operator UI:

PBI-209 (Operator UI): Operator Live Dashboard, current total occupancy, revenue for the day and entry/exit activity.

PBI-210 (Operator UI): Interactive Layout & Spot Management UI - graphically view, block/unblock or reserve specific spot.

PBI-211 (Operator UI): Rate Management UI, to set up dynamic pricing, peak hours, daily maximums and special event flat rate.

PBI-212 (Operator UI) Garage Profile & Facility Settings UI to set operational hours, contact and total number of spots.

 PBI-213 Portal for manual override of entry/exit gate for vehicle operators to gain access to vehicle or to clear a plate error.

PBI-214 (Operator UI): Active Violations & Overstay Monitor UI shows the flag statements of unpaid/in overstayed vehicles.

PBI-215 (Operator Staff & Role Management UI): Operator Staff & Role Management UI to set various levels of access to gate for shift to gate guards & managers. 

1.3 Backend Processes for Operator and User User-Facing Backend Processes

PBI-301 (User Backend): Real Time Reservation Engine to temporarily reserve a selected spot for 10 minutes when checkout to prevent double reserving. 

PBI-302 (User Backend): Automated Payment & Settlement Microservice, connecting to Stripe/PayPal API to perform pre-authorizations and charges. 

PBI-303 (User Backend): QR Code/Digital Ticket Generator with Automation which creates signed and time-decaying validation tokens after successful payment. 

PBI-304 (User Backend): Push & SMS Notification service for Reservation confirmation, 15 minutes expired and extended reminder. 

PBI-305 (User Backend): Dynamic Parking Fee Calculation Engine which will process the base rate, time-of-day fee, promotion codes and duration. 

PBI-306 (User Backend): Additional charges and duration of parking is processed as per user needs; Auto Parking Session Extension Handler functionality added. 

PBI-307 (User Backend): User Refund & Cancellation Workflow is automated to process refunds based on cancellation policy rules.


Operator-Facing Backend Processes:

PBI-309 (Operator Backend):Occupancy Tracking Engine is synchronizing physical sensor/gate triggers and the database spot availability. 

PBI-310 (Operator Backend): Overstay detection for vehicles that overstay, automated. 

PBI-311 (Operator Backend): Automated Dynamic Pricing Algorithm rate changes according to the current booking rates. 

Operator and User User Reporting: 

PBI-401 (User Report): Personal Spending Summary Report including monthly/annual parking expenditures graphs and categories.  

PBI-402 (User Report): TaxReady Receipt Exporter to export the official parking receipts.  

PBI-403 (User Report): Environmental Impact, time spent and estimated saving of carbon use by using EVs.  


Operator Reporting: 

PBI-404 (Operator Report): Real-Time vs. Historical Occupancy Heatmap Report for analysis of peak hours, peak days and turn-away rates.  

PBI-405 (Operator Report): Revenue Breakdown & Financial Report: classifies the revenues according to the type of spot, time and payment method.  

PBI-406 (Operator Report)Overstay & Violation Report - Uncollected fees, frequent violation areas, manual overrides of operator.  

PBI-407 (Operator Report): Customer retention & utilization analytics, with recurring drivers and one-time visitors.  

Multi-Garage Comparison Report (Operator Report) enables the management to compare the performance of a facility with another.  

PBI-409 (Operator Report): Provides operators with an end of day summary balance sheet in PDF format via email report daily.  Financial Reconciliation & Export Tool. 

PBI-410 (Operator Report): CSV/Excel files mapped for accounting software (e.g., QuickBooks) financial reconciliation. 


