# Select tools by evidence need

| Need | Preferred method | Boundary |
| --- | --- | --- |
| Recover your own application | Repository, deployment artifacts, backups, source maps | Browser reconstruction cannot restore private server files |
| Understand layout and navigation | Supported browser inspection and screenshots | Capture multiple states and viewports |
| Trace complicated delivered JavaScript | REA bundle analysis and available source | Minified names, dynamic imports and absent maps leave uncertainty |
| Understand API behavior | Authorized actions plus permitted traffic inspection or supplied HAR | Observe actual request/response shapes; protect tokens and personal data |
| Compare original and rebuild | Matched scenarios, assertions and screenshot comparisons | Pixel similarity alone does not prove functionality |
| Analyze Electron or native modules | REA application inspection; native provider if necessary | Do not require native tooling for a normal website |

## REA adapter

Use official upstream https://github.com/morluto/rea and https://rea.tools for current capability and installation guidance. Verify release availability: documentation on the main branch may describe features absent from an installed release. Read installed help rather than hardcoding flags from memory.

Relevant documented capability families include page inspection, bundle analysis, session observation, script export, screenshots, capture comparison, and separate scenario workflows. Passive observation and action-driving scenarios have different effects. Do not assume a passive observer navigates or clicks. Verify which observations include bodies versus metadata or shapes.

When local setup is requested, inspect the host and existing agent registration first, explain proposed configuration changes, follow current official setup, then check capabilities. Do not imply a local MCP installation automatically becomes usable in this hosted conversation. Browser attachments require the appropriate locally reachable endpoint and target; respect environment browser policies. Keep debug listeners on loopback and use a dedicated investigation profile.

Analysis may run locally while the AI provider still receives tool results. Never describe the entire workflow as private/offline unless the model and every tool actually operate that way.
