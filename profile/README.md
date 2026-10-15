## Hi there 👋 Welcome to Aimplan! 🎯

Aimplan adds planning to Power BI. Users type numbers, comments and workflow statuses straight into their reports through Aimplan custom visuals, and the data is written back to a database that feeds the same semantic model.

Since October 2026 everything we ship lives in one repository, [aimplan/aimplan](https://github.com/aimplan/aimplan). The earlier per-component repositories are archived and read-only; their history continues in the monorepo. Start with its README and the `docs/` folder.

### Sites

* [Administration portal](https://github.com/aimplan/aimplan/tree/main/portal) - portal.aimplan.com, where administrators design storage tables and manage scenarios, measures, users and processes

### Our visuals

* [Planning Grid](https://github.com/aimplan/aimplan/tree/main/custom-visuals/planning-grid) - Aimplan Planning & Reporting Visual
* [Input Grid](https://github.com/aimplan/aimplan/tree/main/custom-visuals/input-grid) - Aimplan Edit Table
* [Table Grid](https://github.com/aimplan/aimplan/tree/main/custom-visuals/table-grid) - Aimplan Data Input Table
* [Status Visual](https://github.com/aimplan/aimplan/tree/main/custom-visuals/status-visual) - Aimplan Status Visual
* [Comment Visual](https://github.com/aimplan/aimplan/tree/main/custom-visuals/comment-visual) - Aimplan Comment Visual

### Our APIs

| API                                                                                   | Summary                                                                                                                                |
|---------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------|
| [Hub API](https://github.com/aimplan/aimplan/tree/main/api/hub-api)                   | Which instances and users exist, instance membership, feature toggles.                                                                 |
| [App API](https://github.com/aimplan/aimplan/tree/main/api/app-api)                   | _Regional._ Each instance's data: storage tables, scenarios, measures, processes, write-back for the visuals, the AI Planning Designer and the MCP server. |
| [Demo sign-up API](https://github.com/aimplan/aimplan/tree/main/api/demo-signup-api)  | Azure Function behind the public demo and training sign-up.                                                                            |

### Also in the repository

Provisioning automation (`automation/`), demo Power BI projects (`demo/`), admin scripts (`notebooks/`) and support tooling (`support/`).
