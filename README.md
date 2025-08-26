# Velora-Hotel-Bookings
This Power BI dashboard analyzes hotel reservation data to help executives monitor booking trends, customer behavior, and revenue performance. The dataset includes 5,000+ bookings spanning September to November 2024, with details such as booking dates, stay dates, loyalty levels, booking channels, and pricing.


📊 Key Metrics
Five core KPIs were calculated using DAX:

Booking Count – Total number of reservations

Cancellation % – Ratio of canceled bookings to total bookings

Total Revenue – Sum of room rate × number of nights

Room Nights – Total nights booked across all reservations

Average Room Rate – Revenue divided by room nights

🧠 Data Preparation
Performed in Power Query:

Calculated derived columns:

Revenue = Room Rate × Nights

Lead Time = Stay Date - Booking Date

Day of Week and Day Name from Stay Date

Bucketed lead time into categories:

Before 1 week

1–2 weeks

2–4 weeks

More than 4 weeks

Sorted weekday names using a numeric column to ensure correct visual order

📈 Visualizations
The dashboard includes:

Booking Trend Over Time

Line chart showing daily booking volume

Date slicer to filter meaningful time windows

Weekday vs Weekend Analysis

Column chart showing bookings by day of week

Custom sorting and optional conditional formatting

Loyalty Program Breakdown

Bar chart showing bookings by loyalty level

Styled with custom colors and background image

Booking Lead Time Buckets

Column chart showing how far in advance customers book

Reveals impulsive vs planned booking behavior

Booking Channel vs Loyalty Matrix

Matrix visual showing bookings by channel and loyalty level

Optimized layout with readable fonts and no scrollbars

🎨 Design Enhancements
Custom theme with brand colors and fonts

Canvas background for professional layout

Rounded corners and consistent padding for visual polish

Format Painter used for consistent styling across visuals

🧰 Tools & Techniques
Power BI Desktop (latest version)

Power Query for data transformation

DAX for KPI calculations

Matrix, line, column, and bar charts

Slicer for dynamic filtering

PowerPoint used to create custom background images
