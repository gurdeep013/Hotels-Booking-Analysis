# Hotels Booking Analytics — 2025

This repository contains an end-to-end analytics project built on the Hotel_bookings_final.csv dataset. The work covers data cleaning, exploratory analysis, visualizations, insight generation, and a stakeholder-ready report and presentation.

## Project Goal
Analyze booking completion, cancellations, pricing, and customer behavior to reduce cancellations, improve guest experience, and increase profitability.

## Repository Structure
```
hotel-booking-analysis/
│
├── dashboard/                      # Exported dashboard PDF and live link preview
├── presentation/                   # Hotel_booking_Presentation.pptx
├── python/                         # Notebooks and scripts
│   └── Hotel_booking.ipynb
├── outputs/                        # Exported charts and images (PNG)
├── report/                         # Final PDF report
├── data/                           # Hotel_bookings_final.csv
└── README.md                       # This file
```

## Tools and Technologies
- **Python**: pandas, numpy, matplotlib
- **Jupyter Notebook** for analysis
- **Reporting**: PowerPoint and PDF
- **Visualization exports**: PNG
- **Git and GitHub** for version control and sharing

## Key Deliverables
- Cleaned dataset and derived tables saved as CSV in `python/outputs`
- Notebook: `python/Hotel_booking.ipynb` with cleaning, analysis, and plotting code
- Visualizations: `outputs/*.png`
- Presentation: `presentation/Hotel_booking_Presentation.pptx`
- Final report: `report/Hotel_Booking_Analytics_Report.pdf`

## Quick Setup and Running Instructions

1. Clone the repository
2. Place the dataset at `data/Hotel_bookings_final.csv`
3. Create a Python environment and install dependencies:
```bash
   pip install pandas numpy matplotlib jupyter
```
4. Open the notebook:
```bash
   jupyter notebook python/Hotel_booking.ipynb
```
5. Run the notebook cells to reproduce analyses and regenerate charts

## What the Notebook Does
- Loads and profiles the raw dataset
- Cleans timestamps and categorical fields
- Engineers features: stay_length, lead_time, booking_month, booking_channel
- Computes aggregates: booking volumes, cancellation rates, avg price per night
- Generates and saves charts to `outputs/`

## Key Insights
- Confirmed booking rate around **72%**
- Cancellations around **20%**, refunds processed in a high share of cancelled bookings
- **Web is the dominant channel**, but Android and iOS together form nearly half of confirmed bookings
- Standard rooms and mid-range hotels drive the bulk of volume and cancellations
- Coupon usage is limited, indicating potential for targeted loyalty programs

## Primary Recommendations
- Introduce targeted non-refundable options and incentives for long lead bookings
- Build loyalty programs to convert one-time customers into repeat customers
- Prioritize channel investments toward higher net revenue channels while improving web UX
- Test dynamic pricing in peak months and shift blanket discounts to value-added offers

## Contact
**Gurdeep Singh**  
gurdeepsingehre@gmail.com  
+91 95578 46089
https://gurdeepsingh.space

## License
This repository is for internal analysis and demonstration. Check with stakeholders before public sharing.
