# VirtualWorks Task 5 – ICSR Processing

## Overview
This project demonstrates an end-to-end Individual Case Safety Report (ICSR) workflow using a completely simulated case. The workflow follows the tutorial's sequence: triage, data entry, quality review, medical review and submission.

## Simulated Case
**Case ID:** VW-T5-001

A 45-year-old female with osteoarthritis was treated with diclofenac 50 mg tablets for acute musculoskeletal pain. She subsequently developed melena associated with upper gastrointestinal bleeding and was hospitalized. Diclofenac was discontinued and the event resolved following treatment.

## Key Assessments
- **Triage:** Valid simulated ICSR
- **ADR:** Upper gastrointestinal bleeding (melena)
- **Seriousness:** Serious – hospitalization
- **Severity:** Severe
- **Dechallenge:** Positive
- **Causality:** Probable
- **Reporting category:** 15-day

## Workflow
### 1. Triage
The case represents an identifiable patient, identifiable reporter, suspect medicinal product and adverse event.

### 2. Data Entry
Patient, reporter, product, event, medical history, medication, dates, outcome and assessment information are organized as structured ICSR data.

### 3. Quality Review
The structured data and narrative are checked for completeness, accuracy and internal consistency.

### 4. Medical Review
The simulated case is reviewed for seriousness, medical plausibility and causality. The causality assessment is **probable**, based on the constructed chronology, known association, positive dechallenge and absence of a stronger alternative explanation within the simulated case.

### 5. Submission
Hospitalization is used as the seriousness criterion, placing the case in the **15-day reporting category** described in the tutorial.

## Severity vs. Seriousness
These concepts are deliberately kept separate:
- **Seriousness:** Serious – hospitalization
- **Severity:** Severe

The tutorial discusses seriousness and reporting timelines but does not provide a separate severity grading scale or a specific causality scale. Those classifications are therefore explicitly educational choices for this simulated case.

## Files
- `VirtualWorks_Task_05_ICSR_Simulated_Case.pdf`
- `VirtualWorks_Task_05_ICSR_Simulated_Case.xlsx`
- `README.md`

## Disclaimer
This is a fictional case created solely for educational and internship-project purposes. No real patient data, real safety report or real regulatory submission is involved.
