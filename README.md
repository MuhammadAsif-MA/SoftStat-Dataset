# SoftStat-Dataset
The SoftStat dataset is a custom dataset developed for research in resource allocation within software project management. This dataset combines three unique datasets—Resource Pool, Allocations, and Project Details—to capture the relationships between resources, tasks, and projects. SoftStat is designed to model domain-specific constraints such as skill-task alignment, budget compliance, and temporal urgency.

This repository contains the SoftStat dataset and provides tools for utilizing it in research and experiments related to software project management and resource allocation.

# Dataset Overview
SoftStat unifies the following three datasets:

Resource Pool: This dataset describes the available resources, including the capabilities and skill sets of individual resources in the project.

Allocations: This dataset captures the task assignments to resources, providing insights into the allocation of resources to specific tasks within the project.

Project Details: This dataset includes key information about the projects, such as budget constraints, project timelines, and other critical project-specific details.

The datasets are designed to provide complete coverage of domain-specific relationships and enable the modeling of constraints that are crucial for effective software project management.

# Key Attributes
Skill-Task Alignment: Ensures that the right resources with the appropriate skills are assigned to the corresponding tasks.
Budget Compliance: Assists in tracking whether the resources are allocated within the predefined project budgets.
Temporal Urgency: Models the time-based constraints and urgency of task completion within a project’s timeline.
# Files Included
resource_pool.csv: Dataset containing the details of available resources and their skill sets.
allocations.csv: Dataset describing the task assignments and the resources allocated to each task.
project_details.csv: Dataset with project-level information such as budgets, deadlines, and constraints.
# Usage
This dataset is intended for researchers and practitioners in the field of software project management. You can use this dataset for studies related to resource allocation, project management optimization, and constraint-based modeling.
