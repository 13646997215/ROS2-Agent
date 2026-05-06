# ROS2-Agent Benchmark Report

## Overall
- passed: True
- score: 1.0 / 1.0

## Sections

### workspace_demo
- passed: True
- score: 1.0 / 1.0
- matched: demo_nodes, ament_python, build_workspace
- missing: (none)

### workspace_next_step
- passed: True
- score: 1.0 / 1.0
- matched: recommended_next_step=build_workspace
- missing: (none)

### build_failure_demo
- passed: True
- score: 1.0 / 1.0
- matched: bad_pkg, compile/cpp, retry_failed_packages
- missing: (none)

### build_failure_next_actions
- passed: True
- score: 1.0 / 1.0
- matched: retry_failed_packages
- missing: (none)

### runtime_graph_demo
- passed: True
- score: 1.0 / 1.0
- matched: qos_incompatibility, sensor_data_not_reaching_consumer
- missing: (none)

### runtime_graph_next_actions
- passed: True
- score: 1.0 / 1.0
- matched: align_qos_profiles, verify_scan_subscriber_runtime
- missing: (none)

### runtime_health_demo
- passed: True
- score: 1.0 / 1.0
- matched: controller_activation_failure, hardware_interface_export_issue, tf_staleness
- missing: (none)

### runtime_health_next_actions
- passed: True
- score: 1.0 / 1.0
- matched: inspect_controller_manager_logs, verify_hardware_interface_exports, inspect_tf_publishers
- missing: (none)
