
# Hotel Booking Analytics — 2025

This repository contains an end to end analytics project built on the Hotel_bookings_final.csv dataset. The work covers data cleaning, exploratory analysis, visualizations, insight generation, and a stakeholder ready report and presentation.

Project goal
Analyze booking completion, cancellations, pricing, and customer behavior to reduce cancellations, improve guest experience, and increase profitability.

Repository structure
hotel-booking-analysis/
│
├── dashboard/                      # exported dashboard PDF and live link preview
├── presentation/                   # Hotel_booking_Presentation.pptx
├── python/                         # notebooks and scripts
│   └── Hotel_booking.ipynb
├── outputs/                        # exported charts and images (png)
├── report/                         # final PDF report
├── data/                           # Hotel_bookings_final.csv
└── README.md                       # this file

Tools and technologies
- Python: pandas, numpy, matplotlib
- Jupyter Notebook for analysis
- Reporting: PowerPoint and PDF
- Visualization exports: PNG
- Git and GitHub for version control and sharing

Key deliverables
- Cleaned dataset and derived tables saved as CSV in python/outputs
- Notebook: python/Hotel_booking.ipynb with cleaning, analysis, and plotting code
- Visualizations: outputs/*.png
- Presentation: presentation/Hotel_booking_Presentation.pptx
- Final report: report/Hotel_Booking_Analytics_Report.pdf

Quick setup and running instructions
1. clone the repository
2. place the dataset at data/Hotel_bookings_final.csv
3. create a Python environment and install dependencies
   pip install pandas numpy matplotlib jupyter
4. open the notebook
   jupyter notebook python/Hotel_booking.ipynb
5. run the notebook cells to reproduce analyses and regenerate charts

What the notebook does
- loads and profiles the raw dataset
- cleans timestamps and categorical fields
- engineers features: stay_length, lead_time, booking_month, booking_channel
- computes aggregates: booking volumes, cancellation rates, avg price per night
- generates and saves charts to outputs/

Key insights
- confirmed booking rate around 72 percent
- cancellations around 20 percent, refunds processed in a high share of cancelled bookings
- web is the dominant channel, but Android and iOS together form nearly half of confirmed bookings
- standard rooms and mid range hotels drive the bulk of volume and cancellations
- coupon usage is limited, indicating potential for targeted loyalty programs

Primary recommendations
- introduce targeted non refundable options and incentives for long lead bookings
- build loyalty programs to convert one time customers into repeat customers
- prioritize channel investments toward higher net revenue channels while improving web UX
- test dynamic pricing in peak months and shift blanket discounts to value added offers

Contact
Gurdeep Singh
gurdeepsingehre@gmail.com
+91 95578 46089

License
This repository is for internal analysis and demonstration. Check with stakeholders before public sharing.
