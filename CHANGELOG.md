## Version 1.1.12

### v1.1.12 (October 08, 2026)
- Fix Xcode's build errors and warnings
- Update Xcode breakpoints
- Command search: localize the trailing type tags
- Fix the second review's findings: partial probes, accent text, badge contrast
- Project timeline rows get padding inside their hover fill
- Secrets tab: Import and Add secret are matching pill buttons
- Fix the review findings: probes, Claude card, Dependency Tools, themes
- Themes set the status colors; Color Blind Safe and Low Glare themes
- Menu Remove rows hover with the destructive button's red wash
- Health checks run the added dependency tools (pip, Bundler, Cargo, Go)
- Dependency Tools run in the terminal dock; chips keep their height on hover
- New filter: the empty chip bar button reads "Add filter"
- Add ten 21st.dev community themes
- Dependency Tools: run commands, add built-ins and custom tools
- AI Commit shows its token use and estimated cost
- Claude Code card: logo, update check, and Claude's own model menu
- Lock page scrolling while a menu is open; thin thumb in scrolling menus
- Open menus follow their trigger when the page scrolls
- Fix the Bedrock review findings: push protects web/app uploads, moves read the copy
- Linked theme and plugin repos on Bedrock sites (web/app)
- Fix the second audit's findings: sync and backup sheets, projects table, focus layers
- Restore a server's code from its backup
- Focus ring preview shows its rings (keyboard-only rings never appear in a preview)
- Fix the review findings: Bedrock push and WooCommerce, Open With, Herd import, keyboard edge cases
- Context-menu key, Dock / Finder Open With, Herd sites at onboarding, Bedrock WordPress
- Keyboard navigation for right-click menus
- Focus ring on the menu row the keys are on; command search result ring
- Keyboard-only focus rings, Return presses the focused control, Tab in menus; drawn checkboxes
- One focus ring for every control; flat switches; command search and picker polish
- Fix the uncovered-areas audit: release script, health probes, pipe stalls, secrets at rest, workspace UI
- Fix the audit's unverified findings: sheet lists, Clone from SSH, WordPress pull, build runner, menus
- WordPress site title and admin login in the wizard; drop a folder on Projects to import it
- Keyboard navigation for the Filter, Display and bulk Actions menus; keep-awake for agent runs; dev server log cap
- Build features on the uncalled APIs; keep the tab when switching projects; accent focus rings
- Remove the 55 stale string catalog entries
- Wire the uncalled SSH, update-all and archive actions; finish font tokens
- Add missing previews, fix crash-report diagnostics, purpose strings and acknowledgements
- Sweep the audit's design-token gaps
- Polish the audit's low-severity UI gaps; add shortcut hints, row Sync menu and Dock completion count
- Fix the audit's low-severity correctness and safety gaps
- Fix the audit's medium-severity gaps and translate the new strings
- Fix the audit's high-severity gaps
- Lift toasts above the bulk bar and refresh the Modified list
- Keep menus inside the app and give them Emil-style motion
- Keep the Projects back link where the heading sits
- Stack toasts like cards and list them on hover
- Show focus on every hand-built input
- Animate every reveal toggle's slash the same way
- Fade the command search results at the top and bottom
- Put section-level empty states in a dashed outline
- Give EmptyState one look everywhere
- Give Agents rows their hover fill
- Use the compact buttons in every sheet
- Fix three issues in the linked repo and WordPress wizard work
- Mention WordPress installs and linked themes and plugins in the README
- Add plugins and several themes to the New Project wizard
- Stop Push from skipping every src folder in the site
- Support a linked plugin in Pull and Push
- Update the README's Requirements and Releasing sections
- Refresh the README's feature list
- Skip working folders and AGENTS.md when pushing
- Use one red on dark, and a red error toast icon
- Make Create Another keep the project and start clean
- Match dark-mode amber, blue and red to the status chips too
- Keep .env lines on one line and scroll the card sideways
- Delete the Activity empty state's unused subtitle strings
- Drop the subtitle from the Activity empty state
- Match dark-mode greens to the status chips' label green
- Cap floating menus and scroll the overflow
- Fail a theme pull when the theme isn't on the server
- Build the Ready screen's checklist from the real steps
- Keep a copied theme in its own repo when cloning from SSH
- Match the wizard's build and result buttons to its step footers
- Point AGENTS.md at CLAUDE.md and remove the zenflow task docs
- Translate the stack editor tabs and the deploy auto label
- Drop GitHub Actions and Web Preview from the Pro feature list
- Open Settings' info hints in the app's own panel
- Keep the token breakdown counting while it's open
- Toggle the token breakdown instead of showing it on hover
- Show the token breakdown in a tooltip, not a popover
- Give the token breakdown an info affordance
- Break the run's token count down on hover
- Drop the duplicate status from the agent run header
- Say how much of an agent run's token count was cached
- Re-sort the String Catalog the way Xcode writes it
- Translate the system proxy warning
- Mark a standalone time with a clock glyph
- Warn when a system proxy swallows local .test links
- Bring back the scroll edge fade as an alpha mask
- Remove the dead Fix with AI sheet and the Anthropic API key provider
- Fix actor-isolation warnings in the dependency scanner
- Rewrite CLAUDE.md to describe the app as it is now
- Remove dead code: unused features, orphaned views and types, and their strings
- Clear the String Catalog warnings: drop stale keys, format percentages
- Update the Claude and Codex model lists
- Keep a version's release notes when release.sh re-runs it

---

## Version 1.1.11

### v1.1.11 (September 21, 2026)
- Translate StackMe into Spanish, French, German, Italian, Brazilian Portuguese, Russian, Japanese, Korean and Simplified Chinese, with separate interface and AI reply language settings
- Add a Tools page for the CLI tools StackMe drives, with installed versions and one-click updates
- Add a Dependencies tab showing each project's toolchain and package versions
- Save unfinished projects and stacks as drafts
- Run Astro dev servers from StackMe with permanent .test links, and flag servers started outside StackMe with a one-click take over
- Redesign the Ports dev-server cards with live HMR status and recent servers
- Rebuild the New filter dialog as Linear-style chips that open straight into the field picker
- Flag projects whose folder or git remote went stale, with a fix button for every blocked state
- Add hover states to workspace lists and the backups calendar, and use plain Stacks icons
- Give every clickable URL the same link style and a pointing-hand cursor
- Make status chips readable in dark mode and fix the scroll fade masks
- Redesign the DMG installer window
- Fix new-project builds hanging when a tool reads the terminal, and fix Tailwind v4 setup in the React and TALL stacks
- Build with Xcode 27

---

## Version 1.1.10

### v1.1.10 (September 08, 2026)
- Give the certificate lock the status palette
- Drop the scheme from the projects table domain
- Show TLS certificate expiry on the projects table
- Fix the collapsed GitHub import sheet
- Grow the shell around the onboarding card's own center
- Swap onboarding for the shell in place, with no window animation

---

## Version 1.1.9

### v1.1.9 (September 04, 2026)
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

