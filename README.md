# Lights, Camera, Returns

![Lights, Camera, Returns Power BI dashboard](assets/dashboard-preview.png)

## What really makes a movie successful?

What makes a movie successful depends on how success is defined. This Power BI data story compares three distinct measures of success:

- **Commercial scale** — how much revenue a film generates.
- **Investment efficiency** — how effectively its reported budget converts into revenue.
- **Audience approval** — how viewers rate the film.

The analysis uses the supplied movie dataset to show why a single definition of “success” can be misleading.

## Key takeaway

Larger budgets generally align with higher revenue, but outcomes vary widely. Bigger spending does not consistently produce better audience ratings, and films budgeted below **$1 million** generated the strongest typical revenue multiple among eligible films.

## Analytical approach

Initial data profiling revealed incomplete and potentially misleading financial records. To create a more reliable core analytical sample, a film was included only when it had:

- A reported budget greater than zero.
- Reported revenue greater than zero.
- At least 100 audience votes.

This produced approximately **7,000 eligible films**, representing **9.8% of the full dataset**.

## What the report explores

- The relationship between reported budget and revenue.
- Median revenue generated per $1 of reported budget across budget bands.
- Median audience ratings across budget bands.
- Sample coverage, methodology, and analytical limitations.
- Interactive tooltips that provide additional context without overcrowding the main report page.

## Important limitations

- Reported profit and ROI exclude marketing and distribution costs.
- Inflation adjustments are unavailable.
- Budget and revenue values depend on the completeness and accuracy of the supplied dataset.
- The filtered analytical sample improves comparability but does not represent every film in the source data.

## Accessibility and design

The report includes accessible labels, alt text, strong colour contrast, an intentional reading order, and interactive tooltips. The layout is designed to communicate the main conclusion first while keeping the underlying method and limitations visible.

## Project file

The Power BI report is available as [`Lights Camera Returns - Qasim Ali.pbix`](Lights%20Camera%20Returns%20-%20Qasim%20Ali.pbix).

Because the file is approximately 299 MB, it is stored using **Git Large File Storage (Git LFS)**. Install Git LFS before cloning the repository to download the complete report file.

## Open the report

1. Install [Git LFS](https://git-lfs.com/) and Microsoft Power BI Desktop.
2. Clone this repository.
3. Open `Lights Camera Returns - Qasim Ali.pbix` in Power BI Desktop.

## Tools used

- Microsoft Power BI
- Power Query
- DAX
- Git and Git LFS

