# Automated Timetable Generator

## Overview

Creating a timetable for educational institutions can be a challenging and error-prone task, especially when done manually. This project aims to help administrators by automating the process using AI agents. The system will generate schedules that meet a variety of constraints, making the start of each academic year smoother and more efficient.

## Features

1. **Natural Language Input**: Users can input requirements in natural language or a predefined format, and the system will generate a schedule that meets all the criteria.
2. **Manual Adjustments**: Users can manually adjust the generated schedule to better fit their needs.
3. **Dynamic Updates**: The system allows for updates and changes throughout the academic year without causing regressions.
4. **Stateful Interaction**: Users can ask questions about the schedule at any time, and the system will provide relevant answers, maintaining the context of the conversation.

## Example Constraints

- 8 student batches, each with 20 students.
- 5 subjects to be taught.
- 10 available teachers (with possible overlaps in subject expertise).
- 5 classrooms in the institute.

## Usage

1. **Input Requirements**: Provide the system with your scheduling requirements using natural language or a predefined format.
2. **Generate Schedule**: The system generates a schedule that meets all the provided constraints.
3. **Adjust Schedule**: Manually make adjustments to the generated schedule if needed.
4. **Update Schedule**: If there are changes during the academic year, explain them to the system, and it will update the schedule accordingly.
5. **Query Schedule**: Ask questions about the schedule at any point, and the system will provide relevant answers while maintaining context.

## How to Get Started

1. **Clone the Repository**: 
   ```bash
   git clone https://github.com/yourusername/automated-timetable-generator.git
   ```
2. **Install Dependencies**:
   ```bash
   cd automated-timetable-generator
   pip install -r requirements.txt
   ```
3. **Run the Application**:
   ```bash
   python main.py
   ```

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE.md) file for more details.

## Contact

If you have any questions or feedback, please open an issue on GitHub or reach out to me at mnvsk97@gmail.com
