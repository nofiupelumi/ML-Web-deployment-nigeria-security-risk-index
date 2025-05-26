# Nigeria Security Risk Index Dashboard (2018-2024)

## Repository Name: nigeria-security-risk-index

## Overview
This repository hosts the Nigeria Security Risk Index Dashboard, a comprehensive data visualization and analysis tool that presents security incident data from 2018-2024 across Nigeria's six geopolitical zones. The dashboard provides stakeholders with actionable intelligence for security planning, risk mitigation, and policy development.

![Nigeria Security Risk Index Dashboard](https://ddftrtwy.gensparkspace.com/)
https://ddftrtwy.gensparkspace.com/
## Features
- **Interactive Data Visualization**: Dynamic charts and maps displaying security trends
- **Regional Risk Analysis**: Comparative assessment of security challenges across Nigeria's geopolitical zones
- **Incident Type Classification**: Detailed breakdown of security incidents by category and impact
- **Temporal Analysis**: Year-by-year and seasonal security trend visualization
- **Perpetrator Group Tracking**: Evolution of armed groups and their tactical approaches
- **Future Risk Projections**: Scenario analysis with probability assessments for 2024-2026
- **Strategic Recommendations**: Evidence-based guidance for policy, operations, and private sector

## Technology Stack
- HTML5/CSS3 with Tailwind CSS framework for responsive design
- Chart.js for data visualization components
- Font Awesome for iconography
- Responsive design optimized for desktop and tablet viewing
- PDF export functionality for offline documentation

## Dataset
The dashboard is powered by a comprehensive dataset of 25,945 security incidents recorded between 2018-2024, including:
- Geographical distribution across 36 states and FCT
- Categorization by risk factor and indicator
- Casualty figures (73,266 fatalities recorded)
- Perpetrator attribution where available
- Temporal patterns and trends
- Weapon types and attack methodologies

## Key Findings
- 160.8% increase in security incidents from 2018 to 2024
- 41% decrease in fatalities during the same period
- North East has highest risk score (14.0) despite having lowest incident count
- Homicide (28.2%), kidnapping (11.0%), and transportation accidents (10.2%) are the most common risk indicators
- Bandit groups have overtaken Boko Haram/ISWAP as most active perpetrators (35% vs 30% of attributed incidents)

## Installation & Usage
1. Clone the repository:
   ```
   git clone https://github.com/nofiupelumi/ML-Web-deployment-nigeria-security-risk-index.git
   ```
2. Open the `index.html` file in a modern web browser
3. For development:
   - Ensure Node.js is installed
   - Install dependencies: `npm install`
   - Run local server: `npm run dev`

## Structure
```
nigeria-security-risk-index/
├── index.html              # Main dashboard HTML
├── assets/
│   ├── css/                # Stylesheet files
│   │   └── main.css        # Custom styling beyond Tailwind
│   ├── js/                 # JavaScript files
│   │   ├── charts.js       # Chart configuration and data
│   │   └── main.js         # Dashboard functionality
│   └── img/                # Static images and icons
├── data/                   # Dataset files
│   └── security-data.json  # Processed incident data
└── docs/                   # Documentation
    └── methodology.md      # Data collection and analysis methodology
```

## Future Development
- [ ] Add interactive filtering by year, region, and incident type
- [ ] Implement district/local government area level analysis
- [ ] Create API endpoints for data access by third-party applications
- [ ] Develop predictive analytics module for enhanced risk forecasting
- [ ] Add multilingual support (English, Hausa, Yoruba, Igbo)
- [ ] Incorporate real-time data updates via a backend API

## Contributing
Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch: `git checkout -b feature/amazing-feature`
3. Commit your changes: `git commit -m 'Add some amazing feature'`
4. Push to the branch: `git push origin feature/amazing-feature`
5. Open a Pull Request

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Citation
If you use this dashboard or dataset in your research or publications, please cite as:
```
Risk Control. (2024). Nigeria Security Risk Index: Premium Security Analysis 2018-2024.
Retrieved from https://github.com/nofiupelumi/ML-Web-deployment-nigeria-security-risk-index
```

## Acknowledgements
- Data collection partners across Nigeria's 36 states
- Security analysts and researchers who contributed to the methodology
- Chart.js and Tailwind CSS communities for open-source tools
- All stakeholders working toward a more secure Nigeria

## Contact
For inquiries, please contact: info@nigeriariskindex.com

---

**Disclaimer**: This security risk analysis is provided for informational purposes only. While every effort has been made to ensure accuracy, the security landscape is dynamic and subject to rapid change. Users should verify critical information and use this dashboard as one of multiple intelligence sources for decision-making.
