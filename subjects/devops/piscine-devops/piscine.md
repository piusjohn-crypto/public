# Piscine DevOps: Task Brief

## Mission

Complete a progressive DevOps training route, starting with shell fundamentals and ending with cloud infrastructure automation. Work through the tasks in numerical order. The linked exercise briefs are the authoritative source for each task's requirements, submission format, and audit instructions.

The Piscine focuses on practical command-line use, scripting, process and job management, backups, and infrastructure automation. It does not include the excluded core projects.

## Task Sequence

### Stage 0: Shell Entry

**Difficulty: 1/5**

Practice basic shell execution, environment variables, and exit status.

- **Task 00:** [hello-devops](./hello-devops/)
- **Task 01:** [set-env-vars](./set-env-vars/)
- **Task 02:** [bin-status](./bin-status/)

**Stage acceptance:** Run each solution from a clean shell and explain how environment variables and exit codes behave.

### Stage 1: Linux Tools and Scripting

**Difficulty: 2/5**

Use command-line tools to inspect files and automate small, well-defined tasks. Handle expected inputs and failures instead of relying on manual steps.

- **Task 03:** [better-cat](./better-cat/)
- **Task 04:** [count-files](./count-files/)
- **Task 05:** [find-files](./find-files/)
- **Task 06:** [master-the-ls](./master-the-ls/)
- **Task 07:** [env-format](./env-format/)
- **Task 08:** [auto-exec-bin](./auto-exec-bin/)

**Stage acceptance:** Demonstrate expected output, describe a failure case, and show how the solution reports or handles it.

### Stage 2: Processes and Scheduled Work

**Difficulty: 3/5**

Manage work that runs in the background or on a schedule. Practice process inspection, logs, and repeatable backups.

- **Task 09:** [in-back-ground](./in-back-ground/)
- **Task 10:** [auto-jobs](./auto-jobs/)
- **Task 11:** [backup_manager](./backup_manager/)

**Stage acceptance:** Start and stop background work safely, verify a scheduled task, and inspect logs and generated backups.

### Stage 3: Cloud Infrastructure Automation

**Difficulty: 4-5/5**

Apply the earlier skills to cloud deployment and infrastructure automation. Complete these advanced tasks only after the preceding stages.

- **Task 12:** [Serverless Payments Reminder](./serverless/)
- **Task 13:** [CloudPress](./cloud-press/)

**Stage acceptance:** Present the architecture, explain how it is provisioned and tested, identify its security boundaries, and show how to remove deployed resources.

## Working Rules

- Read each full exercise brief before implementation. Its requirements take precedence over this route.
- Keep a record of commands, decisions, and troubleshooting. Be prepared to explain your work during an audit.
- Never commit credentials, private keys, webhook URLs, or other secrets. Use placeholders in documentation and the exercise's approved secret mechanism.
- Before cloud work, set a budget alert, use the smallest practical resources, and destroy resources when finished. Verify that no billable resources remain.
- Do not use a tool or command in an audit unless you can explain what it does.

## Completion

Complete Tasks 00-11 and pass their exercise checks and audits to finish the core Piscine. Tasks 12-13 are advanced extensions that may require a cloud account and incur charges; follow the cost controls before attempting them.