### Description
What changes and why. Name the components touched (`api/app-api`, `portal`, `custom-visuals/<visual>`, `automation`, ...).

### Checklist
- [ ] Builds and tests pass for the affected components (`pnpm exec turbo run typecheck lint test --affected`; `dotnet test` for a .NET solution)
- [ ] Created tests which fail without the change (if possible)
- [ ] Contracts that must stay in sync are changed together and generated clients are regenerated, not hand-edited (`AGENTS.md` section 4)
- [ ] `docs/` and `README.md` updated when a folder, schema, queue, auth flow or deployable changed
