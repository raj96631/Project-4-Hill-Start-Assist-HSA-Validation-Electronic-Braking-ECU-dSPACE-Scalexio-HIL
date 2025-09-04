# Hill Start Assist (HSA) Validation – Electronic Braking ECU | dSPACE Scalexio HIL

## Project Description
Validated **Hill Start Assist (HSA)** functionality using the **Electronic Braking ECU (EBCU)** on a **dSPACE Scalexio HIL test bench**.  
The project focused on **standstill scenarios, braking logic, and safety compliance**. Robustness was ensured through **automated test execution, fault injection, and system-level validations**.

## Tools & Technologies Used
- **dSPACE Scalexio HIL** (ConfigurationDesk, ControlDesk, AutomationDesk)
- **Python** (automation scripts for HIL testing)
- **JIRA, DOORS, RQM** (requirements, defect tracking, traceability)
- **CANalyzer** (signal monitoring & debugging)
- **CAPL scripting** (CAN communication)
- **Microsoft Excel/Word** (test case design & reporting)

##  Folder Structure
```plaintext
Hill_Start_Assist_HIL_Validation/
│── README.md                # Project overview & guide
│── LICENSE                  # License information
│
├── documents/               # Requirements, design docs, reports
│   ├── requirements.docx
│
├── testcases_and_execution/ # Test cases & execution results
│   ├── HIL_Test_Cases_with_result.xlsx
│
├── scripts/                 # Automation scripts (Python, CAPL)
│   ├── example_script.py
│   └── placeholder_CAPL_script.capl
│
├── assets/                  # Diagrams, logos, supporting files
│   ├── system_architecture.png
│   └── block_diagram_placeholder.png
│
└── screenshots/             # Screenshots of execution results
    ├── test_execution_sample.png
    └── hil_environment_snapshot.png


 How to Run/Test the Project
Clone the repository:

bash
Copy code
git clone https://github.com/your-username/Hill_Start_Assist_HIL_Validation.git
Navigate to the scripts/ folder and run automation scripts (example in Python):

bash
Copy code
python example_script.py
Open testcases_and_execution/HIL_Test_Cases_with_result.xlsx to review executed test cases.

Use documents/ for requirement mapping and reports.

Screenshots of results are in /screenshots.



 Example Test Case Format
Test Case ID	Requirement ID	Pre-Condition	Steps	Expected Result	Status
TC_HSA_001	RQ_HSA_001	Vehicle on slope, brake applied	Release brake pedal	Vehicle holds position for 2s	Pass


📜 License
This project is licensed under the MIT License – see the LICENSE file for details.# Project-4-Hill-Start-Assist-HSA-Validation-Electronic-Braking-ECU-dSPACE-Scalexio-HIL