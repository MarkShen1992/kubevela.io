---
title: vela workflow
---

Operate application delivery workflow.

### Synopsis

Operate the Workflow during Application Delivery. Note that workflow command is both valid for Application Workflow and WorkflowRun(expect for [restart, rollout] command, they're only valid for Application Workflow). The command will try to find the Application first, if not found, it will try to find WorkflowRun. You can also specify the resource type by using --type flag.

### Options

```
  -h, --help   help for workflow
```

### Options inherited from parent commands

```
  -y, --yes   Assume yes for all user prompts
```

### SEE ALSO


* [vela workflow debug](vela_workflow_debug)	 - Debug workflow steps
* [vela workflow logs](vela_workflow_logs)	 - Tail logs for workflow steps
* [vela workflow restart](vela_workflow_restart)	 - Restart an application workflow.
* [vela workflow resume](vela_workflow_resume)	 - Resume a suspend application workflow.
* [vela workflow rollback](vela_workflow_rollback)	 - Rollback an application workflow to the latest revision.
* [vela workflow suspend](vela_workflow_suspend)	 - Suspend an application workflow.
* [vela workflow terminate](vela_workflow_terminate)	 - Terminate an workflow.

#### Go Back to [CLI Commands](vela) Homepage.


###### Auto generated by [spf13/cobra script in KubeVela](https://github.com/kubevela/kubevela/tree/master/hack/docgen).
