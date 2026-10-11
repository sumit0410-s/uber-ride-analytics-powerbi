# Uber Ride Analytics Dashboard | Power BI

An interactive Power BI dashboard for exploring ride-booking performance, revenue, distance, vehicle categories, customer and driver ratings, and trip outcomes.

## Dashboard Preview

> Add a screenshot of the **Overview** page here after publishing or taking a screenshot from Power BI Desktop.
>
> Save the image in your repository (for example, `images/dashboard-overview.png`) and replace this note with:
>
> `![Dashboard Overview](images/dashboard-overview.png)`

## Project Objectives

- Monitor booking volume and completed rides.
- Track revenue and booking value over time.
- Analyze total and average trip distance.
- Compare revenue across vehicle types.
- Explore pickup and drop-off location patterns.
- Review customer and driver ratings.
- Understand completed, cancelled, and incomplete rides.

## Dashboard Pages

### 1. Home
A landing page introducing the dashboard and providing navigation to the analysis.

### 2. Overview
An interactive overview page containing KPI cards, time-based charts, vehicle-type comparisons, location insights, and booking-status breakdowns.

## Key Metrics

The report includes visuals for the following metrics and dimensions:

| Metric / Dimension | Purpose |
|---|---|
| Revenue | Review revenue performance |
| Booking Value | Compare booking value across quarters |
| Completed Bookings | Monitor successful bookings and trends |
| Lost Bookings | Track bookings that were not completed |
| Total Distance | Measure distance covered across trips |
| Average Distance | Understand typical trip distance |
| Customer Rating | Review average customer ratings |
| Driver Rating | Review average driver ratings |
| Vehicle Type | Compare performance by vehicle category |
| Pickup Location | Identify prominent pickup locations |
| Drop Location | Identify prominent drop-off locations |
| Booking Status | Review completed, cancelled, and incomplete rides |
| Quarter / Date | Explore performance across time periods |

*Metric values depend on the data loaded into the Power BI report and any filters selected.*

## Interactivity

Use the report's slicers and visual interactions to explore the data. Available controls include vehicle-type and date/quarter-related filtering. Selecting a category in one visual may also filter or highlight related visuals.

## Tools & Technologies

- **Microsoft Power BI Desktop** — report design and interactive visualizations
- **Power Query** — data preparation, if used in the source model
- **DAX** — measures and calculations, where defined in the model

## Repository Contents

```text
.
├── README.md
├── Dashboard.pbix
└── images/
    └── dashboard-overview.png   # Optional screenshot to add
```

The screenshot and `images/` folder are optional. Keep `Dashboard.pbix` in the repository if you want others to download and open the report.

## How to Use

1. Download or clone this repository.
2. Open `Dashboard.pbix` using Microsoft Power BI Desktop.
3. If Power BI prompts for data-source access or credentials, configure the source as appropriate.
4. Refresh the data if the source is available and refresh is required.
5. Use the slicers and charts on the **Overview** page to explore the report.

## Data Notes

This repository README describes the report structure visible in the supplied `.pbix` file. The underlying dataset, source system, refresh credentials, and business definitions should be documented here if you plan to share the project publicly. Do not publish private or confidential data, credentials, or connection strings.

## Future Improvements

- Add a screenshot or GIF of the dashboard.
- Document the dataset source, columns, and data-cleaning steps.
- Explain the DAX definitions for key measures.
- Add a data dictionary and clarify the meaning of “lost,” “cancelled,” and “incomplete” bookings.
- Publish a read-only report link if sharing permissions and data sensitivity allow it.

## Author

SUMIT SHRIVASTAVA.
