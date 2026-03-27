# RAG-System
Data Setup
This RAG system is optimized to retrieve information from official HP User Guides.

HP User Guide

OMEN by HP 15 Notebook PC Maintenance and Service Guide

HP Pavilion Laptop - Maintenance and Service Guide
HP Regulatory, Safety, and Environmental Notices User Guide

Note: Due to copyright, the original PDF manuals are not included in this repository.


###  Results & Demo
The following examples demonstrate the RAG pipeline's ability to extract accurate information and maintain strict grounding using official HP technical manuals.

#### 1. Precise Fact Extraction & Citations
The system correctly identifies warranty durations and cites the specific source documents (e.g., Maintenance and Service Guide).

![Warranty Info](images/Screenshot%202026-03-28%20001600.png)
*Caption: System retrieving specific warranty details with document citations.*

#### 2. Procedural Guidance
It can successfully summarize technical "how-to" steps, such as locating installed software within the OS.

![Software Instructions](images/Screenshot%202026-03-28%20001636.png)
*Caption: Step-by-step instructional retrieval from the user guide.*

#### 3. Hallucination Prevention (Grounding Test)
To ensure reliability, the system is designed to refuse questions outside the scope of the provided manuals (e.g., "What is the capital of India?").

![Grounding Test](images/Screenshot%202026-03-28%20001648.png)
*Caption: Demonstrating that the model stays grounded to the provided data and does not hallucinate.*
