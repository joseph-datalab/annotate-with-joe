# Object Interaction Video Annotation

## Project Overview

This project demonstrates my approach to identifying and annotating human-object interactions in video data for AI and machine learning applications.

The task involves reviewing video footage, identifying relevant actions, determining accurate start and end points, and assigning the appropriate labels according to annotation guidelines.

## Annotation Tasks

For this project, I focus on:

- Identifying human-object interactions
- Detecting when an action begins and ends
- Creating accurate temporal segments
- Assigning action labels
- Reviewing frame-level transitions
- Identifying invalid or ambiguous actions
- Performing quality checks before finalizing annotations

## Example Annotation Structure

| Start Time | End Time | Action |
|---|---|---|
| 00:02.10 | 00:04.35 | Pick up object |
| 00:04.35 | 00:07.20 | Interact with object |
| 00:07.20 | 00:09.40 | Put down object |

> The examples above demonstrate the annotation format. Actual labels and boundaries depend on the project's annotation guidelines.

## Quality Control

Before completing an annotation, I check:

- Whether the correct action was identified
- Whether the segment starts at the correct frame
- Whether the segment ends when the action changes
- Whether the correct label was assigned
- Whether any relevant actions were missed
- Whether the annotation follows the project guidelines

## Tools

This type of annotation can be completed using tools such as:

- Supervisely
- CVAT
- Label Studio
- Labelbox

## Sample

Visual annotation examples and screenshots are provided in this project to demonstrate the workflow.
