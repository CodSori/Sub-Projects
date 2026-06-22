# P&C-Centered Substation Logic and Troubleshooting Portfolio

## Project Purpose
Build a low-cost, technical portfolio that demonstrates developing competence in:
- Protection & Control (primary focus)
- Substation design literacy (adjacent competency)
- Field/utility realization and troubleshooting (practical competency)

This portfolio is meant to show disciplined technical growth, structured reasoning, and tangible evidence of my building competence within power delivery P&C.

## Project Design Principles
- Keep scope narrow and technically credible.
- Favor clarity over complexity.
- Show logic, traceability, and engineering judgment.
- Use free or already-available tools whenever possible.
- Create deliverables that can be discussed with others as either learning tools or proof of competency.

## Final Portfolio Structure
The portfolio will have five sections.

### Section 1: System Context and One-Line Overview
Purpose: Show understanding of the basic functional structure of a simple substation and relate primary equipment to secondary/protection functions.

#### Deliverables
1. A simplified one-line diagram of a substation
2. A component map with labels and short role descriptions.
3. A one-page narrative explaining power flow, switching points, sensing points, and protection/control relevance.

#### Desired content
A simplified arrangement such as:
- incoming line or source
- bus
- breakers
- disconnect switch(es)
- CTs
- PT/VTs
- lockout relays
- protective relay function block
- DC battery/control power source
- trip path destination

---

### Section 2: Breaker Control and Protection Logic
Purpose: Demonstrate P&C-centered reasoning through a simplified but realistic trip/close control package.

#### Deliverables
1. Simplified DC control schematic for breaker trip/close logic.
2. Logic block diagram or signal flow diagram.
3. Sequence of operation document.
4. Permissive/interlock matrix.
5. Short explanation of what causes:
   - breaker close
   - breaker trip
   - close block
   - lockout condition

#### Desireded logic elements
Include some combination of:
- close command path
- trip command path
- breaker auxiliary contacts
- trip coil / close coil
- relay trip output
- lockout relay action
- interlock or permissive condition
- alarm indication

#### Sequence of operation topics
Explain normal behavior and abnormal behavior, such as:
- normal breaker closing sequence
- protective trip sequence
- lockout operation sequence
- blocked close condition
- loss of control power effect

---

### Section 3: Print Tracing and Document Interpretation
Purpose: Show proficiency at reading prints methodically.

#### Deliverables
1. One annotated one-line.
2. One annotated control schematic.
3. One annotated simplified wiring/terminal diagram.
4. A print-tracing worksheet for each drawing.

#### Print-tracing worksheet template
For each print, answer:
1. What is the purpose of this drawing?
2. What are the sources on this drawing?
3. What are the outputs or end actions?
4. What permissives/interlocks appear in the path?
5. What assumptions would need field verification?
6. What are likely failure points or confusion points?

---

### Section 4: Troubleshooting and Field Realization Casebook
Purpose: Demonstrate practical engineering thinking based on commissioning, testing, isolation, and malfunction diagnosis.

#### Deliverables
Create 4 troubleshooting case studies. Each should be 1–2 pages.

#### Standard case format
For each case, include:
1. Symptom
2. Intended behavior
3. Possible causes
4. Most likely causes
5. Diagnostic path
6. Verification steps
7. Likely root cause
8. Corrective action
9. Lessons learned

#### Possible case topics
Use realistic cases such as:
1. Breaker fails to close after command
2. Protective relay issues trip output but breaker does not trip
3. Lockout relay operates and blocks reclosing/closing
4. Low control voltage causes unreliable motor or control operation

#### Optional fifth case
- mismatch between print expectation and field condition
- stale drawing revision vs actual installation
- isolation point misunderstood during troubleshooting

---

### Section 5: Simple Simulation and Logic Validation
Purpose: Add a lightweight analytical element without expensive software.

#### Deliverables
One of the following:

##### Option A: MATLAB logic/timing model
Create a MATLAB script or Simulink-style logic representation that models:
- breaker state transitions
- close permissives
- trip command dominance
- lockout latch behavior
- loss of control power effects

##### Option B: Excel logic truth tables and timing sheet
Create:
- logic matrix for breaker operation
- permissive/interlock truth table
- failure mode table
- simple timing/event sequence table

##### Option C: Both
Use Excel for logic tables and MATLAB for state transitions.

---

## Deliverable Sequence
Plan for building hypothetical substation layout:

### Stage 1: System definition
- choose one station context
- define included components
- create the simplified one-line
- write short role notes

### Stage 2: Control logic
- define normal operating intent
- draft close path logic
- draft trip path logic
- add lockout function
- write a sequence of operation

### Stage 3: Drawing interpretation
- annotate the one-line
- create one simplified control schematic
- create one simplified wiring/terminal view
- complete print-tracing worksheets

### Stage 4: Troubleshooting
- write 4 troubleshooting cases
- include root-cause reasoning
- connect cases back to drawings and logic

### Stage 5: Simulation/validation
- implement truth tables and/or MATLAB logic
- verify that your narrative matches your logic model
- adjust inconsistencies

### Stage 6: Final packaging
- create clean section dividers
- add short introductory explanation
- add a concluding page on lessons learned and future extension ideas


## Quality Standard
The portfolio should be:
- mid-range technicality but correct
- clean/neat
- logically consistent
- explicit with assumptions
- clearly labeled as a learning portfolio


## Stretch Goals
Only pursue these after the core project is complete.

- Add a second breaker bay and compare logic differences.
- Add a transformer protection variant.
- Add a small annunciation/alarm summary page.
- Add a commissioning checklist.
- Add a test procedure template.
- Add a revision log to mimic engineering document control.

## Definition of Success
The project is successful if, after completion, I can:
1. explain a simple substation bay and its control/protection relationships clearly
2. trace a trip or close path through a simplified drawing package
3. discuss likely failure points and diagnostic steps
4. show a professional artifact during networking or interviews


## Next Steps 
If all goals are met for 3 different substations, then a publicly available 
satellite image of a small, but real-world substation will be used as the basis 
for performing an expanded version of this project. The hypothetical prints and 
controls of a real-world substation will mark the start of Substation Projects 
version 2. This guideline is expected to be re-worked and expanded upon at the 
beginning of version 2.
