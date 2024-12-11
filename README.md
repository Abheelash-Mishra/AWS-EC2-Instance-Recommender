# AWS EC2 Instance Recommender

A tool designed to recommend the most efficient AWS EC2 instance types based on specific user workloads and sustainability goals. This project prioritizes cost-effectiveness and resource efficiency while considering proximity to AWS green data centers for environmental sustainability.

## Features
- **Dynamic Instance Recommendations:** Selects optimal EC2 instances for general, memory-intensive, or compute-intensive tasks.
- **Sustainability Focus:** Recommends AWS green data centers to minimize carbon footprint.
- **Cost-Performance Optimization:** Matches user workloads with EC2 instance types that maximize value while minimizing costs.
- **Customizable Workload Parameters:** Input task details for precise recommendations.
- **Comprehensive Instance Filtering:** Evaluates and ranks instances based on workload-specific attributes.

## Project Workflow
- **User Input:** Enter task details to determine the type of workload (general, memory-intensive, or compute-intensive).
- **Task Categorization:** Computing utilization intensity are categorized using predefined mappings.
- **Instance Selection:** Based on user inputs, a dynamic algorithm filters and ranks EC2 instances using a scoring formula.
- **Recommendation Output:** Displays the optimal EC2 instance types and their details, including the closest green data centers.

## Contributing
Contributions are welcome! Feel free to submit a pull request or raise an issue for discussion.

## License
This project is licensed under Apache 2.0.

## Acknowledgments
- Inspired by sustainable development goals to create eco-friendly computing solutions.
- Built as part of a solo developer project to explore efficient resource allocation in cloud computing.
