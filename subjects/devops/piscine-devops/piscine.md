# Piscine DevOps: Task Brief

## Mission

Complete a progressive DevOps training route, starting with shell fundamentals and ending with cloud infrastructure automation. Work through the tasks in numerical order. The linked exercise briefs are the authoritative source for each task's requirements, submission format, and audit instructions.

The Piscine focuses on practical command-line use, scripting, process and job management, backups, and infrastructure automation. All the tasks in the DevOps folder belong to the Piscine, except these core projects:

1. Deep-In-Net
2. Deep-In-System
3. Crud-Master
4. Play-With-Containers
5. Orchestrator
6. Cloud-Design
7. Code-Keeper

The remaining DevOps tasks are ordered below by increasing difficulty.

## Stage 0: Foundation

- [hello-devops](./hello-devops/)
- [set-env-vars](./set-env-vars/)
- [bin-status](./bin-status/)
- [read-file](./read-file/)
- [read_file](./read_file/)
- [write-file](./write-file/)
- [write_file](./write_file/)
- [input-redirection](./input-redirection/)
- [append-output](./append-output/)
- [technical-file](./technical-file/)
- [details](./details/)
- [dir-info](./dir-info/)

## Stage 1: Shell, Files, and Data Handling

- [better-cat](./better-cat/)
- [count-files](./count-files/)
- [find-files](./find-files/)
- [master-the-ls](./master-the-ls/)
- [env-format](./env-format/)
- [auto-exec-bin](./auto-exec-bin/)
- [file-struct](./file-struct/)
- [file-details](./file-details/)
- [file-checker](./file-checker/)
- [file-researcher](./file-researcher/)
- [json-researcher](./json-researcher/)
- [find-files-extension](./find-files-extension/)
- [credentials-searches](./credentials-searches/)
- [credentials_searches](./credentials_searches/)
- [custom-ls](./custom-ls/)
- [custom-calendar](./custom-calendar/)
- [custom_calendar](./custom_calendar/)
- [string-processing](./string-processing/)
- [string-tokenizer-count](./string-tokenizer-count/)
- [string_tokenizer_count](./string_tokenizer_count/)
- [change-struct](./change-struct/)
- [object-to-json](./object-to-json/)
- [object_to_json](./object_to_json/)
- [set-internal-vars](./set-internal-vars/)
- [check-user](./check-user/)
- [comparator](./comparator/)
- [division](./division/)
- [grades](./grades/)
- [largest](./largest/)
- [greatest-of-all](./greatest-of-all/)
- [shopping](./shopping/)
- [easy-conditions](./easy-conditions/)
- [easy-perm](./easy-perm/)
- [easy-perm-checkpoint](./easy-perm-checkpoint/)
- [hard-conditions](./hard-conditions/)
- [hard-perm](./hard-perm/)
- [env-format-checkpoint](./env-format-checkpoint/)
- [plus](./plus/)
- [plus-checkpoint](./plus-checkpoint/)

## Stage 2: Automation and System Work

- [in-back-ground](./in-back-ground/)
- [auto-jobs](./auto-jobs/)
- [backup_manager](./backup_manager/)
- [skip-lines](./skip-lines/)
- [skip-secrets](./skip-secrets/)
- [skip_secrets](./skip_secrets/)
- [merge-two](./merge-two/)
- [merge_two](./merge_two/)
- [left](./left/)
- [right](./right/)
- [head-and-tail](./head-and-tail/)
- [in-the-dark](./in-the-dark/)
- [burial](./burial/)
- [punishment](./punishment/)
- [clean-the-list](./clean-the-list/)
- [clean_the_list](./clean_the_list/)
- [job-regist](./job-regist/)
- [array-selector](./array-selector/)
- [flex-function](./flex-function/)
- [flex_function](./flex_function/)
- [remake](./remake/)
- [candidates-checker](./candidates-checker/)
- [candidates_checker](./candidates_checker/)
- [road-to-ccp](./road-to-ccp/)
- [road-to-dofd](./road-to-dofd/)
- [calculator](./calculator/)

## Stage 3: Advanced DevOps

- [serverless](./serverless/)
- [cloud-press](./cloud-press/)
- [cloud-kube](./cloud-kube/)
- [easy-cloud](./easy-cloud/)
- [joker-num](./joker-num/)
- [hello-python](./hello-python/)
- [hello_python](./hello_python/)
- [strange-files](./strange-files/)
- [concat-string](./concat-string/)
- [concat_string](./concat_string/)
- [numerical-operations](./numerical-operations/)
- [numerical_operations](./numerical_operations/)
- [numerical-operations-the-return](./numerical-operations-the-return/)
- [numerical_operations_the_return](./numerical_operations_the_return/)
- [cl-camp3](./cl-camp3/)
- [cl-camp3-checkpoint](./cl-camp3-checkpoint/)
- [cl-camp6](./cl-camp6/)
- [cl-camp6-checkpoint](./cl-camp6-checkpoint/)
- [cl-camp8](./cl-camp8/)
- [cl-camp8-checkpoint](./cl-camp8-checkpoint/)

## Working Rules

- Read each full exercise brief before implementation. Its requirements take precedence over this route.
- Keep a record of commands, decisions, and troubleshooting. Be prepared to explain your work during an audit.
- Never commit credentials, private keys, webhook URLs, or other secrets. Use placeholders in documentation and the exercise's approved secret mechanism.
- Before cloud work, set a budget alert, use the smallest practical resources, and destroy resources when finished. Verify that no billable resources remain.
- Do not use a tool or command in an audit unless you can explain what it does.

## Completion

Complete the Piscine tasks in order and pass their exercise checks and audits to finish the DevOps route. The seven excluded projects are not part of the Piscine track.

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