# SSPA Project GitHub Organization

Welcome to the SSPA (Smart Plant Automation) project GitHub organization! This organization is dedicated to the development and collaboration of various repositories that collectively form the SSPA project. Below is an overview of the repositories within this organization:

## Repositories

### 1. RxSPA
- **Description:** This repository contains the code for the microcontroller master (RxSPA) responsible for polling data from the slave microcontroller.
- **Purpose:** Facilitates communication between master and slave, enabling the transfer of data essential for the SSPA project.

### 2. ADCSPA
- **Description:** Here lies the code for the microcontroller slave (ADCSPA), which reads sensor data from the meteorological station and lysimeter. Additionally, it can execute irrigation tasks for plant care.
- **Purpose:** Enables the slave microcontroller to gather data from various sensors and perform crucial tasks like irrigation based on the received information.

### 3. Utils
- **Description:** This repository houses common functions and utilities used by both RxSPA and ADCSPA. The code is packaged as a library and is published on PlatformIO Hub.
- **Purpose:** Provides a shared set of functionalities for both master and slave microcontrollers, enhancing code modularity and maintainability.

### 4. SPA-Backend
- **Description:** The API code responsible for inserting and selecting data into the database from the microcontroller master (RxSPA).
- **Purpose:** Facilitates the interaction between the master microcontroller and the database, ensuring seamless data management for the SSPA project.

### 5. 3DModels
- **Description:** Storehouse for 3D models in STL format, designed for 3D printers. These models are related to the physical components of the SSPA project.
- **Purpose:** Provides a centralized location for 3D printable models essential for constructing physical components related to the SSPA project.

### 6. Eagle Board
- **Description:** Repository containing 3D models for the boards designed using Eagle software.
- **Purpose:** Holds the electronic board designs in a format compatible with Eagle, offering a resource for visualizing and fabricating the necessary electronic components for the SSPA project.

## Contribution Guidelines
We encourage and welcome contributions from the community. Please follow the guidelines outlined in each repository's `CONTRIBUTING.md` file to ensure a smooth collaboration process.

Feel free to explore each repository to understand their specific functionalities and contributions to the overall SSPA project. Thank you for being part of our community! If you have any questions or suggestions, don't hesitate to reach out.

Happy coding! 🌱✨
