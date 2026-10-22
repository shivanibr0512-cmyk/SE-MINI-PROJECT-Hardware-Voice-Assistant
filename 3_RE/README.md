# Requirements Engineering (RE)

## 1. Functional Requirements (FR)

- **FR-01:** The system shall capture voice input through a connected microphone.
- **FR-02:** The system shall recognize predefined multimedia voice commands.
- **FR-03:** The system shall start media playback when the user says "Play".
- **FR-04:** The system shall pause media playback when the user says "Pause".
- **FR-05:** The system shall resume playback when the user says "Resume".
- **FR-06:** The system shall increase volume when the user says "Volume Up".
- **FR-07:** The system shall decrease volume when the user says "Volume Down".
- **FR-08:** The system shall move to the next media item when the user says "Next".
- **FR-09:** The system shall move to the previous media item when the user says "Previous".
- **FR-10:** The system shall reject unsupported commands.
- **FR-11:** The system shall provide an appropriate error indication when an operation cannot be processed.

## 2. Non-Functional Requirements (NFR)

- **NFR-01 — Performance:** The system should process voice commands promptly.
- **NFR-02 — Usability:** Voice commands should be simple and easy to understand.
- **NFR-03 — Reliability:** Recognized commands should trigger the correct operation.
- **NFR-04 — Security:** Commands must be validated before execution.
- **NFR-05 — Maintainability:** Voice recognition, command processing and multimedia control should use separate modules.
- **NFR-06 — Portability:** The software design should support the selected compatible hardware platform.

## 3. Requirements Traceability Matrix (RTM)

| Requirement ID | Requirement | Related Test Case |
|---|---|---|
| FR-01 | Voice input | TC-01 |
| FR-02 | Command recognition | TC-01 |
| FR-03 | Play media | TC-02 |
| FR-04 | Pause media | TC-03 |
| FR-05 | Resume media | TC-04 |
| FR-06 | Increase volume | TC-05 |
| FR-07 | Decrease volume | TC-06 |
| FR-08 | Next media | TC-07 |
| FR-09 | Previous media | TC-08 |
| FR-10 | Invalid command handling | To be added |
| FR-11 | Error handling | To be added |

*Note: The RTM will be updated as additional test cases are prepared.*
