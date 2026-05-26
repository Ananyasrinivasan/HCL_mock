# HCL_mock
Hotel Booking &amp; Guest Analytics Integration System 
This project is a simple hospitality management ETL solution built using Informatica Intelligent Cloud Services (IICS), Oracle Database, and Power BI.

The main goal of the project is to process hospitality data such as guest details, hotel information, reservations, and billing records while applying business validations and generating useful reports.

The project focuses on implementing real ETL concepts like:

Data validation
Incremental loading
Duplicate checking
Reject handling
Alert generation
Workflow automation
Tools & Technologies Used
Informatica IICS
Oracle SQL
Power BI
Flat Files (for reject handling)
Source Tables

The following source tables were used:

HR_GUEST
HR_HOTEL
HR_RESERVATION
HR_BILLING
Target Tables

Processed data is loaded into:

GUEST_MASTER
HOTEL_MASTER
RESERVATION_FACT
BILLING_FACT
BOOKING_ALERT

Mapping Tasks

The following mapping tasks were created:

mt_Load_Guest
mt_Load_Hotel
mt_Load_Reservation
mt_Load_Billing
Taskflow

A task flow was created to automate the execution of all mappings.

Taskflow Name
tf_Hospitality_ETL
Execution Order
mt_Load_Guest
↓
mt_Load_Hotel
↓
mt_Load_Reservation
↓
mt_Load_Billing

✅ Expression Transformation
✅ Filter Transformation
✅ Lookup Transformation
✅ Router Transformation
✅ Aggregator Transformation
✅ Incremental Loading
✅ Reject Handling
✅ Alert Logic
✅ Taskflow Automation
✅ Power BI Reporting

Conclusion

This project demonstrates an end-to-end ETL workflow for the hospitality domain using Informatica IICS. It includes real-time business validations, data quality checks, incremental loading, workflow automation, and reporting integration with Power BI.
