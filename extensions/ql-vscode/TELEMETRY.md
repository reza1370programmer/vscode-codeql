# Telemetry in the CodeQL extension for VS Code

If you specifically opt-in to permit GitHub to do so, GitHub will collect usage data and metrics for the purposes of helping the core developers to improve the CodeQL extension for VS Code. This data will not be shared with any parties outside of GitHub. IP addresses and installation IDs will be retained for a maximum of 30 days. Anonymous data will be retained for a maximum of 180 days.

## Why do you collect data?

GitHub collects aggregated, anonymous usage data and metrics to help us improve CodeQL for VS Code. IP addresses and installation IDs are collected only to ensure that anonymous data is not duplicated during aggregation.

## What data is collected

If you opt in, GitHub collects the following information related to the usage of the extension. The data collected are:

- The identifiers of any CodeQL-related [VS Code commands](https://code.visualstudio.com/docs/getstarted/tips-and-tricks#_command-palette) that are run
- For each command: the timestamp, time taken, and whether or not the command completed successfully
- VS Code and extension version
- Randomly generated GUID that uniquely identifies a CodeQL extension installation. (Discarded before aggregation.)
- IP address of the client sending the telemetry data. (Discarded before aggregation.)
- Whether or not the `codeQL.canary` setting is enabled and set to `true`

## How long will data be retained?

IP address and GUIDs will be retained for a maximum of 30 days. Anonymous, aggregated data that includes command identifiers, run times, and timestamps will be retained for a maximum of 180 days.

## Who will have access to this data?

IP address and GUIDs will only be available to the core developers of CodeQL. Aggregated data will be available to GitHub employees.

## What data is **NOT** collected?

We only collect the minimal amount of data we need to answer the questions about how our users are experiencing this product. To that end, we do not collect the following information:

- No GitHub user ID
- No CodeQL database names or contents
- No contents of CodeQL queries
- No filesystem paths.

## How do I disable telemetry reporting?

When telemetry collection is disabled, no data will be sent to GitHub servers.

You can disable telemetry collection by setting `codeQL.telemetry.enableTelemetry` to `false` in [your settings](https://code.visualstudio.com/docs/getstarted/settings#_settings-editor). Telemetry collection is _disabled_ by default.

Additionally, telemetry collection will be disabled if the global `telemetry.enableTelemetry` setting is set to `false`. For more information on global telemetry collection, see [Microsoft’s documentation](https://code.visualstudio.com/docs/supporting/faq#_how-to-disable-telemetry-reporting).

## More information

See GitHub's [Privacy Statement](https://docs.github.com/en/free-pro-team@latest/github/site-policy/github-privacy-statement) and [Terms of Service](https://docs.github.com/en/free-pro-team@latest/github/site-policy/github-terms-of-service) for more information.
