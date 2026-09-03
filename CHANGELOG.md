## Version 1.1.9

### v1.1.9 (September 03, 2026)
- Logs tab, remote .env pull, Laravel pull toggles, clone cache excludes
- Add type-to-filter to floating menu pickers
- Cap oversized os_log payloads, title-bar project breadcrumb switcher
- Fix tooltips floating off their anchors (NSHostingView panel resize)
- Remove commented-out code from ToastNotification
- Surface GitHub secret import in the environment sheet, drop dead Secrets views
- Fix shellWithTimeout burning its full timeout on every command
- Speed up Ports scrolling and WP URL rewrite, quiet the backup scheduler
- Add Opus 5, fix stale tooltip positioning, warn on retired models
- Gate unavailable runtimes in the wizard; confirm remote runbook runs
- MVP hardening: store safety, backup honesty, deletion opt-ins, crash reporting
- Clone from SSH wizard: copy picker, resilient builds, minimize to toast
- SSH keys, jump hosts, and per-environment runbook commands
- Clone from SSH: type-aware database clone (files + DB)
- Add "Copy from a server" project-creation source (rsync over SSH)
- App sheets morph on ANY growth, not just animated triggers
- Env sheet tab rule runs edge-to-edge; tabs sit inset on it
- Remove the resize blur-to-mask on app sheet content
- App sheets center in the whole window again
- Sheet resize with intent: fully-damped morph + blur-to-mask
- Env sheet: tabs sit under the title; UnderlineTabBar gains showsBorder
- Env sheet: breathe above the tabs, single rule below them
- Env sheet auto-heights per tab
- Tab bar: never wrap titles; tighter spacing + wider env sheet
- Extract UnderlineTabBar; env modal adopts the detail page's tab style
- Env form: primary-color section icons; SSH Test Connection always visible
- Env modal: Git tab (icon-git) splits branch/remote out of General
- Tab out the environment config modal
- Detail header gear opens the selected environment's config
- Show detected project identity (Statamic/Astro) everywhere, not just the table
- Menu bar: stack logos on Recent Projects
- Settings form: bump bottom clearance to Spacing.xxxl
- Settings form: Spacing.xxl clearance under the last section
- Fix sidebar-toggle shimmer on the Agents run list
- Ports: kill button next to PIDs in the listening table
- Filter icon popover: color picker inside, edit support, hug fix
- Built-in filters render as plain colored dots, not icons
- Fix mispositioned hover tooltip on health trend-chart history dots
- Filter icon picker: status-dot default, more dev icons, icon+color in front of name
- Filters: single custom-color field + icons
- Add parsing unit tests; harden ls preamble skip against bracket prose
- Harden container CLI: timeouts + failure-is-not-empty run-state
- Surface partial DB-import failures as an amber warning toast
- Hard-disable CloudKit sync, remove dead command-menu code
- Agent apply/harvest fixes, dependency update UX, health drill-downs, RAM + settings cleanup
- Health day-tick strip + inline panel, agent permission tiers and apply hardening, Badge sweep, Fable 5
- Health column redesign, agent speed tuning, and settings centering fix
- Route View/Help menus, remove window-tab items, settle traffic lights after resize
- Terminal dock entry point, Codex verify, real health probes, remote code backup
- Backup restore round-trip + backups honesty pass; commit WIP pivot work
- AppSheet auto-height, backups calendar, container php serving
- Container serving model, concurrency cleanup, and workspace polish
- Add per-row copy to the .env file view
- Move container runtime config to Settings; add logs viewer + AI diagnosis
- Keep backup row "1 month ago" age on one line
- Verify scheduled backups: due-logic tests + DEBUG scheduler trace
- Extract a shared SectionHeader component
- Make Filter/Display header toggles fully tappable
- Forward TOC-rail scroll-wheel events into the Settings form
- Traffic-light nudge: deterministic flip-safe positioning, documented resize limit
- Capture code + media in manual full backups
- Stream container image-pull progress into the status line
- Add Run Migrations bulk action + databaseMigrated emitter
- Wire backup Download to a real .zip export
- Add dedicated ImportDirectoryView for bulk import
- Apple Container deletion cleanup + image-pull UX; pivot checkpoint
- Full-width workspace dividers + stack-card New project + backup restore wiring
- Make appSheet backdrop a window drag handle + seal title-bar clicks
- Fix title-bar buttons dragging the window + add AccentButtonStyle
- Rebuild project detail page (env-centric) + DRY pass + container 1.0
- Add custom AppSheet overlay for app-matching modal sheets
- Dedupe Views: shared backup-sheet bits, status pill, timeline row, ActionBar
- Extract Activity timeline + Backups tab into value-input views
- gitignore the local Apple SwiftUI skills export
- SwiftUI render-path optimizations + the-pivot WIP checkpoint
- Enhance workspace views by enabling fade mask in ScrollViewWithThinIndicator for improved user experience and adding workspaceContentWidth extension for consistent layout across multiple views. Updated WorkspaceCommandSearch to include utility commands in search results, ensuring comprehensive command access.
- Enable fade mask in ScrollViewWithThinIndicator for AddEnvironmentSheet and EditEnvironmentSheet to enhance user experience.
- Update BackupScheduleSheet and WorkspaceBackupScheduleSheet to enable fade mask in ScrollViewWithThinIndicator; refactor selectedEnvironment closure in WorkspaceNewBackupSheet for improved readability.
- Add workspace session memory and title bar cluster width management
- Enhance SpacingSystem and TypographySystem with new animations and typography adjustments
- Add @MainActor annotations to RuntimeProvider methods for improved concurrency handling
- Workspace shell goes permanent: delete classic UI, monochrome button system, Stacks list redesign
- Ports destination, global Backups modals, tabbed project detail, slim projects table
- Health column sparkline + hover popover, dependency/health probes, polish
- Workspace shell: title-bar toolbars, Health column + popover, Backups redesign
- Rework project creation, logging, and projects workspace UI
- Rework project creation flow, add SwiftTerm build runtime, redesign projects table
- Settings: long-form searchable view with category drill-down; search polish
- Workspace shell: notifications, inline command search, projects table; container served-URL health
- Editor split button, Herd dev-server run-state, settings polish
- Observable run-state store + title-bar project command menu
- Add multi-runtime seam + Apple Container runtime (per-project)
- Add project-scoped AI agent runs (Agents surface)
- Embedded terminal: SwiftTerm dock with tabs + rename (pivot Phase 3)
- Workspace sidebar active-row fill + FloatingMenu corner radius (pivot Phase 3)
- Workspace shell polish: gradient New Project in the panel, traffic-light + spacing tweaks (pivot Phase 3)
- Workspace shell window chrome: hidden title bar + opaque themed shell (pivot Phase 3)
- Workspace shell UI polish: terminal in content column, width cap, flat UserButton (pivot Phase 3)
- Add resizable bottom terminal dock with persisted height (pivot Phase 3)
- Day-group the global Activity feed (pivot Phase 3 polish)
- Reconcile project detail to the feed styling (pivot Phase 3)
- Add Projects table for the workspace shell (pivot Phase 3)
- Add workspace-shell toolbar controls: editor picker + theme + terminal (pivot Phase 3)
- Redesign workspace sidebar: destinations + project quick-list + user (pivot Phase 3)
- Wire more activity emitters + persist rail destination (pivot Phase 3 polish)
- Wire the workspace nav rail into ContentView (pivot Phase 3)
- Add nav rail foundations + global Activity/Snapshots feeds (pivot Phase 3)
- Surface project commands in the command palette (pivot Phase 3)
- Add project-centric detail page behind a feature flag (pivot Phase 3)
- Add ProjectWorkspace + coordinators (pivot Phase 2)
- Add RuntimeProvider seam over Herd (pivot Phase 1)
- Add auto-backup scheduler
- Toast pill redesign + neutral gray selection across sidebar and menus (#13)
- WordPress DB sync hardening, spinner standardization, ContentView extraction
- Centralize the shared Herd tool-path list
- Remove dead OverviewTabView leftovers
- Remove dead ProjectDetailSidebar struct and orphaned sync methods
- Remove dead quick-actions cluster from ContentView
- Consolidate sync option cards into one card + accessory
- Consolidate icon views behind a shared AssetIcon
- Prune dead design-system tokens
- Remove dead FileSyncService methods
- Delete dead EnvironmentStatusCard and its OverviewTabView cluster
- Remove the unshipped database Migration feature
- Delete dead GitStatusBar.swift
- Remove deprecated sync git methods and stale Laravel helper
- Remove orphan view and preference-key types
- Remove dead orphan types and unused ProgressiveBlur
- Add UI mockups and reference screenshots
- Add color theme system and AI fix session
- Add a model stat-bar flyout to the Intelligence picker
- Stream the AI fix investigation as a live transcript
- Add a propose-and-review flow to Fix with AI
- Await ShellService.run in the project inspector
- Fix stack card vanishing when dropped on itself
- Stop sidebar rows shrinking on press
- Drop the stack chip from project cards and list rows
- Run Claude Code headlessly to apply error fixes
- Warn on incomplete selection checkboxes and fix the selected chevron
- Expand CLAUDE.md release and signing docs, dedupe a gating note

---

## Version 1.1.8

### v1.1.8 (May 24, 2026)
- Make the JS error panel actions auto-width
- Clarify the JavaScript errors panel and inline its actions
- Flatten sidebar rows and add press feedback
- Tighten menus and share one sidebar row
- Accent the active provider indicator in Intelligence settings
- Fix version stamping and the Sparkle download URL in the release flow

---

## Version 1.1.7

### v1.1.7 (May 24, 2026)
- Match the accent to the system color across the app
- Switch menus, tooltips, and popups to thin material
- Light-mode shell, vibrant menus, and system-matching accent fills
- Extend the droplet path chip to more path readouts
- Add Intelligence settings pane and agent handoff for AI fixes
- Add droplet path hover chip and inline icon button feedback
- Error→AI Phase 2: in-app Claude fix bridge for JS errors
- Error→editor/AI Phase 1: open JS errors in editor via ErrorContextResolver
- Error→editor/AI Phase 0: ErrorContext resolver + richer JS capture
- UI consistency pass: menus, sheets, underline fields, interactive tooltips
- Card quick-actions fly-out submenus, inspector redesign, UX polish
- Backups tab dashboard redesign, schedule sheet, WP backup PATH fix
- Backups redesign, project morph, tooltip delay, WP sync fix
- Secrets matrix, Backups tab, status diff stats, Laravel installer fix
- Secrets panel cleanup, env picker sliding pill, tooltip dismiss fix
- Pro feature gating, tooltip system, dynamic pricing, and UX polish (#12)
- Pro feature gating, tooltip system, dynamic pricing, and UX polish (#11)
- Sign Debug builds with Developer ID Application to keep TCC grants
- Remove redundant dark-mode-only previews across the codebase
- Overview tab cleanup: footers, progress toast, previews, dead helper
- Apply fade mask to Stacks grid and drop dark-mode preview
- Harden ScrollViewWithThinIndicator against native scrollbars
- Project creation wizard overhaul, sync reliability, and UX polish
- Sparkline chart, sidebar accordions, About redesign, release tooling, and UI polish
- Fix sparkline recording one entry per refresh instead of multiple

---

## Version 1.1.6

### v1.1.6 (April 04, 2026)
- Bug fixes and improvements

---

## Version 1.1.5

### v1.1.5 (April 04, 2026)
- Bug fixes and improvements

---

## Version 1.1.3

### v1.1.3 (April 04, 2026)
- Fix release script for major.minor.build versioning

---

## Version ..2

### v..2 (April 04, 2026)
- Bug fixes and improvements

---

## Version 1.1.1

### Build  (April 04, 2026)
- Use unified version display in About and Onboarding views
- Fix menu bar icon, settings window, build warnings, and add project rename
- Unify accordion animations with shared Animations.accordion token
- Add dynamic card size slider, refine grid spacing, and UI polish
- Add Sparkle auto-updates, version display, and toolbar UI refinements
- Add granular access control permissions, fix onboarding UI, and Tahoe+ breadcrumb insets
- Redesign project overview, fix plugin updates, add crash reporter (#8)
- Add project groups with sidebar navigation, icon picker, and drag-drop
- Add Tahoe+ toolbar button insets and remove focus rings from toolbar buttons
- Enhance FileSyncService and SyncOptionsSheet for improved WordPress sync functionality
- Fix WordPress theme sync: broken symlink handling and sidebar action stubs
- Enhance project management features and UI improvements
- Fix plugins toolbar, menu bar actions, and Tahoe+ proportional breadcrumbs
- Fix menu bar actions, Tahoe+ pill tabs/breadcrumbs, and MySQL import
- Add Tahoe+ adaptive pill radius, fix accent color system, and UI improvements

---

## Version 1.0

### Build 2 (April 03, 2026)
- Onboarding wizard with step-by-step setup
- Local (Flywheel) environment detection
- Fixed Herd crash on app launch
- Fixed Restart button sizing in web preview

