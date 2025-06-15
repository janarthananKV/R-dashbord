# R-Dashboard: Game Sales Analysis

R-Dashboard is an interactive and customizable dashboard application built using R and [Shiny](https://shiny.rstudio.com/), focused on analyzing and visualizing game sales data. This dashboard enables users to explore game sales trends, performance by region, platform statistics, genre breakdowns, and more in real time, empowering users to uncover actionable insights from gaming industry data.

## Features

- **User-Friendly Interface**: Intuitive dashboard layout for all levels of users.
- **Game Sales Insights**: Visualize sales data by year, platform, genre, region, and publisher.
- **Interactive Visualizations**: Dynamic charts, graphs, and tables powered by R’s visualization libraries.
- **Customizable Widgets**: Add or remove widgets to focus on specific analytics needs.
- **Real-Time Data Updates**: Live data loading and visualization with Shiny’s reactivity.
- **Multiple Data Sources**: Import game sales data from CSV, Excel, or databases.
  
## Tech Stack

- **Language**: R
- **Web Framework**: Shiny
- **Visualization**: ggplot2, plotly, DT (DataTables)
- **UI/Theming**: shinydashboard
- **Data Handling**: readr, dplyr, tidyr

## Getting Started

### Prerequisites

- [R](https://cran.r-project.org/) (version 4.0 or higher recommended)
- [RStudio](https://www.rstudio.com/) (optional, but recommended)

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/janarthananKV/R-dashbord.git
   cd R-dashbord
   ```

2. **Install required R packages:**
   Open R or RStudio and run:
   ```r
   install.packages(c("shiny", "ggplot2", "plotly", "DT", "dplyr", "tidyr", "readr", "shinydashboard"))
   # Add any additional packages as required by your app
   ```

3. **Run the application:**
   In R or RStudio, set the working directory to the project folder and run:
   ```r
   shiny::runApp()
   ```

## Usage

- Launch the app as described above.
- Explore sales trends by year, platform, genre, region, publisher, and more.
- Interact with filters, selectors, and widgets to analyze specific segments.

## Contributing

1. Fork the repository.
2. Create your feature branch (`git checkout -b feature/my-feature`).
3. Commit your changes (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature/my-feature`).
5. Open a Pull Request.

## Contributors

- [Janarthanan](https://github.com/janarthananKV)
- [Vishal](https://github.com/vishals25)

## Contact

For questions, suggestions, or support, please open an issue or contact the maintainer at <janakrishnancse@gmail.com>.

---
