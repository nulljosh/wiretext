# Wiretext Roadmap

## From Apps.pdf (imported 2026-07-12)
- [ ] Sim verification skipped (usage raincheck) — rebuilt ios/web fresh (`npm run build:ios`), regenerated Xcode project, xcodebuild build succeeds, resource-folder wiring in project.yml and BundleSchemeHandler both correct (no obvious static bug found). Blank white screen needs an actual sim launch to diagnose (can't repro headlessly) — still open
- [ ] Ship iOS: blocked — no ASC app record for com.nulljosh.wiretext; register app first (asc-app-create-ui skill, browser automation, confirm first), then `asc workflow run ship-ios`
