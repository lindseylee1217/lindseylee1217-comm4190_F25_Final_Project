# Milestone 5 — App Workflow Development & Testing

## Overview
This folder captures how the Looking Glass workflow was prototyped and tested, including prompt orchestration, data handling, and iteration notes. Each notebook implements a complete workflow with routing logic, mermaid diagrams, and comprehensive testing against usage scenarios.

## Contents
- Workflow notebooks  
  - `HG_Milestone_5.ipynb` — Workflow implementation with 3-route classification (analyze/companion/growth) and 5 test cases  
  - `LL_Milestone_5.ipynb` — Workflow implementation with 3-route classification (talk_therapy/goal_setting/trajectory_analysis) and MS2 scenario testing
- Sample data  
  - `sample_data/` text cases used to validate workflow behavior

## Workflow Features

Both notebooks implement complete LLM workflows with:

### Routing Logic
- **HG_Milestone_5**: Routes to `analyze` (pattern analysis), `companion` (empathetic support), or `growth` (historical tracking)
- **LL_Milestone_5**: Routes to `talk_therapy`, `goal_setting`, or `trajectory_analysis`

### Visual Diagrams
- Mermaid.js flowcharts showing complete workflow structure
- Router nodes, agent nodes, and output nodes clearly defined
- Subgraph organization for different workflow paths

### Testing & Validation
- **HG_Milestone_5**: 5 comprehensive test cases covering standard journals, safety checks, minimal content, off-topic inputs, and work-focused entries
- **LL_Milestone_5**: Direct testing of MS2 usage scenarios (trajectory analysis for student growth, talk therapy for emotional support)

## How to use
1. Open the notebooks to review workflow design, mermaid diagrams, prompt chaining, and evaluation notes.  
2. Run cells with `sample_data/` files to observe reflection outputs and adjust prompts.  
3. Review test outputs to see how workflows handle different input types and scenarios.
4. Use these notebooks as a template for extending the workflow to new journaling datasets.

## Notes
- Notebooks include saved outputs for quick reading.  
- Feel free to duplicate and modify notebooks to test alternative prompt strategies.
- Workflows are implemented using LangGraph/LangChain patterns as discussed in class.

---

[← Back to Main README](../README.md)

