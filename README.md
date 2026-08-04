# G02_log

Structured runtime diagnostics for the GO2 Hesai ROS 2 project.

Each uploaded run is stored under `sessions/<session-id>/` and may contain:

- JSONL lifecycle and health events
- CSV topic-rate summaries
- Text environment and parameter snapshots
- Markdown analysis reports

This repository is for compact diagnostics only. Point-cloud maps, rosbag
recordings, core dumps, and other large binary artifacts must be transferred by
SCP and stored outside Git under `D:\GO2_Data` on the analysis computer.

The collector and analyzer source live in the `GO2_Hesai` repository under
`tools/` so runtime behavior is versioned with the robot software.
