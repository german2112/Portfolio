# Case Study: API Development for Automated Restocking System
# Project Overview
In this project, I worked as a Backend Engineer to develop an automated restocking API aimed at optimizing inventory management across multiple retail stores selling glasses. The project leveraged Java 11, Spring Boot, MySQL, and AWS Lambda to create a dynamic restocking system that minimized delays in inventory replenishment and improved the efficiency of stock allocation among stores.

# Problem Statement
The existing restocking system was inefficient, as it processed restock requests without considering stock levels, urgency, or store proximity. This often resulted in longer replenishment times and increased logistical costs due to non-optimal stock allocations. The goal was to automate and streamline the process, ensuring that restock requests were fulfilled quickly and strategically.

# Objectives & Goals
Optimize Restocking Efficiency: Minimize response times for restock requests by intelligently prioritizing stock sources.
Reduce Operational Costs: Ensure optimal allocation of stock from nearby sources to reduce logistics and handling costs.
Enhance User Experience: Simplify the restock ordering process for store staff with a user-friendly interface that displays the best stock sources.
# Approach & Methodology
To achieve the project’s goals, I designed and implemented an API with the following features:

Dynamic Restocking Priority: The API dynamically prioritized restocking based on a combination of urgency, stock levels, and proximity to reduce time and logistical resources.
Proximity-Based Inventory Allocation: Using MySQL and AWS Lambda, the system identified nearby stores with available stock to fulfill restock requests quickly and efficiently.
One-Click Restock Orders: For ease of use, store workers could view optimal restock options and place orders with a single click, streamlining the workflow.
# Challenges & Solutions
Challenge: Balancing multiple criteria (urgency, stock levels, proximity) to determine optimal stock sources.
Solution: I implemented a prioritization algorithm within the API that evaluated all factors, scoring and ranking stock sources to identify the best options for each restock request.
Challenge: Ensuring real-time inventory updates across multiple stores.
Solution: Leveraged AWS Lambda for efficient data processing and real-time inventory synchronization, ensuring that stock levels were always up-to-date.
# Results & Impact
Improved Restocking Time: Reduced the average restocking time by 50%, resulting in faster inventory turnover and fewer stockouts.
Cost Savings: Optimized stock allocation, reducing operational costs by approximately 30% due to reduced transportation and handling needs.
Enhanced User Experience: Streamlined the ordering process for store workers, increasing user satisfaction and reducing the manual effort required.
# Lessons Learned & Reflections
This project taught me the importance of prioritization algorithms in optimizing resource allocation and demonstrated the effectiveness of microservices (via AWS Lambda) in handling real-time data processing. Additionally, this experience strengthened my skills in API development, dynamic data processing, and database optimization with MySQL.