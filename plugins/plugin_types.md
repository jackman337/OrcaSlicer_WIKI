# Plugin Types

A plugin can provide one or more features. Expand a plugin row to see its plugin capabilities.

![local_plugin_activated_capabilities](https://github.com/OrcaSlicer/OrcaSlicer_WIKI/blob/main/images/plugins/local-plugin-activated-capabilities.png?raw=true)

## Script

Script plugins are run manually from the Plugins window.

1. Open **File** > **Plugins**.
2. Expand the plugin.
3. Find the script feature.
4. Click the **Run** button.

![script_plugin_run_result](https://github.com/OrcaSlicer/OrcaSlicer_WIKI/blob/main/images/plugins/script-plugin-run-result.png?raw=true)

## Post-processing

Post-processing plugins are selected from a process profile and run as part of the slicing/export workflow.

1. Go to **Prepare**.
2. Open the process settings.
3. Go to **Others**.
4. Find **Post-processing Plugin**.
5. Click the **+** button.

![post_processing_setting_empty](https://github.com/OrcaSlicer/OrcaSlicer_WIKI/blob/main/images/plugins/post-processing-setting-empty.png?raw=true)

Choose a post-processing plugin from the list and click **OK**.

![select_post_processing_plugin](https://github.com/OrcaSlicer/OrcaSlicer_WIKI/blob/main/images/plugins/select-post-processing-plugin.png?raw=true)

The selected plugin appears under **Post-processing Plugin**. It will be used when you slice or export with that process profile.

![post_processing_plugin_selected](https://github.com/OrcaSlicer/OrcaSlicer_WIKI/blob/main/images/plugins/post-processing-plugin-selected.png?raw=true)

## Printer Connection

Printer connection plugins add printer communication features. After activating a printer connection plugin, OrcaSlicer uses it where printer connection options are available. This is still WIP.

If the plugin has its own setup instructions, check the **Description** or **Diagnostics** tab in the Plugins window.
