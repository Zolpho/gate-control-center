# GCC Development Activity

Gate Control Center is developed in a private source repository. This public archive mirrors the private `main` development history using **commit dates and reviewed commit titles only**.

It intentionally does **not** publish source code, commit hashes, branches, authors, email addresses, diffs, private repository links, credentials, or operational secrets.

**Coverage:** 418 published commits from **August 1, 2026** through **October 24, 2026**.

Entries are listed chronologically, from the beginning of the project.

## August 2026

### August 1, 2026

- Initial Gate bot dashboard
- Ignore local account credentials
- Add multi-account Gate bot monitoring
- Configure Python application import path
- Report collector task health correctly
- Add GitHub Pages frontend deployment
- Expose backend on internal proxy network
- Connect GitHub Pages to live Gate API
### August 2, 2026

- Add account-scoped action authentication
- Fix account unlock dialog and login errors
- Avoid empty CSS class token for zero metrics
- Add EQTY DAO dashboard footer
- Fix Gate bot onboarding API permissions
- Document Gate subaccount onboarding
- Document Gate subaccount onboarding
- Add self-service dashboard password changes
- Compact dashboard header controls
- Allow entrypoint to secure writable user file
- Add private subaccount balance panel
- Link private balance documentation
- Add account-scoped Gate deposit addresses
- Backup DB script fixed
- Persist Gate deposit history
- Move private account data to Wallet tab
- Improve bot position values and price formatting
- Fix quote value formatter variable
- Align Spot Grid PnL metrics with Gate
- Compact bot overview table
- Show Spot Grid trigger waiting state
- Add waiting state to portfolio status
### August 6, 2026

- Improve portfolio chart readability
### August 8, 2026

- Add separate Gate bot control credentials
- Add Gate bot control and spot grid prepare API
- Add Spot Grid bot control UI
- Add safe Spot Grid simulation mode
- Add Bot Control activity audit view
- Add audited Bot Stop simulation workflow
- Add Bot Control request reconciliation
- Add Bot Control operation locking
- Add reconciliation-aware Bot Control lock resolution
- Add Gate Bot Control client methods and audit tests
- Add Bot Control needs attention queue
- Add Bot Control needs attention frontend
- Add persistent Bot Control rate limiting
- Add Bot Control audit export
- Add Bot Control concurrency and crash recovery tests
- Recover abandoned Bot Control requests on startup
- Add live Bot Control execution safety gate
- Add Bot Control live safety acceptance tests
- Add Bot Control operations and emergency runbook
- Harden Bot Stop live mode confirmation
- Make Bot Stop results persistent in UI
- Reset Bot Control request dialog scroll position
- Harden Spot Grid Create live workflow
- Display terminal bot status over stale Gate status
- Prune expired Bot Control cooldown locks
- Add Gate bot stop return estimate
- Show bot stop return estimate in confirmation
- Polish bot stop return confirmation
- Polish bot stop strategy summary
- Make bot stop confirmation scrollable
- Add spacing inside bot stop dialog
- Polish Bot Control request details
- Polish Bot Control request spacing
- Harden collector and add attention review workflow
### August 9, 2026

- Add read-only Treasury foundation
- Use dedicated Treasury secret mount
- Provision Treasury credential at container startup
- Add simulated Treasury transfer workflow
- Harden Treasury transfer simulation
- Add Treasury live transfer safety foundation
- Add Treasury transfer execution and reconciliation
- Report effective Treasury transfer enablement
- Harden Treasury transfer submission errors
- Harden Treasury transfer operations
- Add Treasury operations dashboard
- Show Treasury operation types
- Add Treasury economic ownership ledger
- Show Treasury economic ownership
- Fix Treasury ownership request IDs
- Polish Treasury ownership UI
### August 15, 2026

- Add read-only Treasury withdrawal capabilities
- Add read-only Treasury withdrawal preflight
- Fix Treasury capability liquidity wiring
- Add Treasury withdrawal destination registry
- Bind Treasury withdrawal preflight to approved destinations
- Harden SQLite concurrency for Treasury writes
- Add withdrawal request audit foundation
- Add withdrawal reservation workflow
- Preserve withdrawal amount precision on recheck
- Harden Treasury decimal persistence
- Extract reusable Treasury transfer execution
- Add withdrawal JIT preparation foundation
- Add withdrawal JIT execution workflow
- Add post-JIT hold-on-main lifecycle
### August 16, 2026

- Add external withdrawal execution foundation
- Add audited external withdrawal submission service
- Add external withdrawal API orchestration
- Classify and audit withdrawal submission errors
- Add audited withdrawal orphan resolution service
- Add super-admin withdrawal orphan resolution API
- Show treasury ownership to custodians
- Clarify treasury custody liability view
- Allow custodians to inspect transfer requests
### August 19, 2026

- Require Gate address eligibility for withdrawals
- Require verified Gate address for API withdrawals
- Support Gate address book withdrawal policy
- Settle completed Gate withdrawals
- Reject withdrawals below post-fee minimum
- Clarify withdrawal settlement replay semantics
- Add safe Treasury withdrawal preparation UI
- Add Treasury withdrawal reserve and confirm UI
- Add Treasury withdrawal JIT preparation UI
- Show read-only Treasury JIT execution preview
- Add Treasury JIT execute and reconcile UI
- Add Treasury external withdrawal execute and reconcile UI
- Add Treasury withdrawal settlement UI
- Show definitive Gate evidence for withdrawal settlement
- Fix Treasury health and lifecycle messaging
### August 20, 2026

- Use same-origin frontend API in Docker
- Add dashboard user ownership transfers
### August 21, 2026

- Add account-scoped Gate user transfers
- Fix user transfer frontend event bindings
- Improve user transfer review UI
- Polish user transfer review interface
- Guard completed user transfers in UI
- Add read-only trading market API
- Add read-only spot trading market console
- Fix Trading tab visibility
- Enhance trading order book and recent trades
- Match Gate top-20 order book depth ratio
- Add volume and expand trading order book
- Add limit order preflight engine
- Add interactive limit order preview ticket
- Persist limit order percentage selection
- Polish limit order allocation controls
- Add spot trading safety foundation
- Stage isolated spot trading credentials
- Add spot order audit and locking primitives
- Add read-only spot order reconciliation
- Add isolated spot order write boundary
- Add guarded spot order execution coordinator
- Expose guarded spot order execution API
- Add spot order execution readiness UI
- Wire guarded spot order execution UI
- Add spot order cancellation foundation
- Add guarded spot order cancellation coordinator
- Expose guarded spot order cancellation API
- Add spot order cancellation readiness UI
- Add read-only spot cancellation reconciliation
- Wire guarded spot order cancellation UI
- Tighten spot cancellation state semantics
- Treat Gate rate limits as ambiguous writes
- Expose effective Spot order state
### August 22, 2026

- Add read-only Spot open orders
- Add durable Spot recent orders
- Add persistent Spot orders UI
- Polish persistent Spot order IDs
- Add persistent Spot order cancellation
- Add durable Spot trading recovery
- Add Spot cancellation rate limiting
- Polish persistent Spot orders UI
- Use full-width Spot order tables
- Add guarded Spot order amendment foundation and reconciliation
- Add read-only Spot order amendment visibility
- Add durable Spot amendment recovery identity
- Add guarded Spot order price amendment UI
- Add manual Spot order amendment reconciliation UI
- Allow cancellation after completed Spot amendments
- Harden Spot cancellation recovery after Gate not-found
- Show account-wide Spot orders
- Document Bot Control safe defaults
- Make Bot Control live policy account-aware
- Add local bot archive
- Fix local bot archive persistence
### August 23, 2026

- Polish global dashboard UI
- Polish Overview dashboard
- Polish Bots dashboard
- Polish Trading dashboard
- Refine Trading dashboard controls
- Refine Trading account scope
- Keep Trading order book visible
- Add Bot Control activity pagination
- Polish Bot Control dashboard
- Finalize Bot Control workflow
- Refine Bot Control final layout
- Polish Alerts dashboard
- Add alert incident persistence foundation
- Use alert incident lifecycle evaluation
- Add alert incident read and acknowledge API
- Show alert incidents and recovery history
- Color active incident count by state
- Use alert incidents on overview
- Compact shared account selector
- Widen compact account selector
- Polish wallet balance and deposit views
- Use bot terminology in wallet balances
- Add depth to wallet balance cards
- Compact Treasury wallet workspace
- Simplify Treasury status indicators
- Polish Treasury transfer workflow
- Polish Treasury transfer form
- Finalize Treasury transfer workflow UI
- Isolate Treasury state across account sessions
- Isolate Bot Control and Trading sessions
- Fix Trading session reset login crash
- Polish Treasury withdrawal preparation UI
### August 29, 2026

- Add withdrawal recipient address book foundation
- Add authenticated withdrawal recipient API
- Link withdrawal recipients to destinations
- Add asset-first withdrawal preparation flow
- Polish withdrawal preparation layout and reset
- Add withdrawal recipient management
- Add withdrawal destination review
- Invalidate stale withdrawal preflight
- Clarify withdrawal preflight destination
- Fix no-JIT withdrawal readiness gate
- Harden withdrawal settlement action semantics
- Hide blocked withdrawal execution controls
- Correct withdrawal funding semantics
- Promote withdrawal Treasury workspace
- Clarify withdrawal funding state
- Harden and simplify withdrawal flow
- Polish withdrawal workspace
### August 30, 2026

- Polish withdrawal full-width layout
- Polish withdrawal preflight hierarchy
- Fix withdrawal preflight destination label
- Clarify historical Bot Control lock state
- Reset scroll on page navigation
- Reset scroll after browser reload
- Add contextual Wallet navigation
- Polish Wallet deposit and withdrawal UX
- Polish Wallet account, deposit and transfer UX
- Complete Wallet UX polish
- Complete Wallet UX refinement
- Refine Wallet interaction polish
- Finish Wallet UX polish

## September 2026

### September 2, 2026

- Optimize portfolio history queries
### September 6, 2026

- Add selectable Aurora interface
- Add Aurora Transfers presentation
- Add Aurora Bots presentation
- Add Aurora Bot details presentation
- Add Aurora Bot Control presentation
- Use production EQTY logo
- Add Aurora Treasury symbols and readability polish
- Add Aurora Trading presentation
- Polish Aurora Trading balance symbols
- Fix Aurora Trading tab visibility
- Polish Aurora live trading caution
- Add Aurora Alerts presentation
- Polish Aurora Alerts symbols and history
- Add Aurora System presentation
- Add Aurora Overview presentation
- Normalize Aurora semantic state colors
### September 12, 2026

- Polish Aurora topbar controls
- Refine Aurora topbar composition
- Adopt Aurora inset luminous controls
- Adopt Aurora soft 3D controls
- Refine Aurora satin 3D controls
- Refine Aurora compact premium controls
- Adopt Aurora inset-luminous controls
- Refine Aurora topbar hierarchy and inset controls
- Refine Aurora account-first inset controls
- Deepen Aurora inset controls and account readability
- Finalize Aurora recessed-light topbar physics
- Add derived out-of-range bot state
- Harden Bot Control live-write UX
- Fix Aurora Bot Details header scrolling
- Fix Aurora Bot Control dialog scrolling
- Fix Aurora Bot Control asset amount layout
- Fix Aurora Bot Control market symbol alignment
- Polish Aurora Bot Control live warning layout
- Add Aurora tablet wallet motion
- Fix Aurora tablet wallet geometry
- Fix Aurora tablet withdrawal stage flow
### September 13, 2026

- Remove duplicate Aurora deposit rules
- Remove redundant Aurora deposit declarations
- Remove final duplicate Aurora deposit declarations
- Remove duplicate Aurora withdrawal overflow
- Fix resilience test child import path
- Fix Aurora withdrawal request grid overflow
- Fix Aurora deposit final-phase grid overflow
- Fix Aurora withdrawal tablet route overlap
- Fix Aurora mobile withdrawal overflow
- Fix Aurora mobile withdrawal safety overflow
- Add per-account action policy foundation
- Add rootadmin account policy API
- Add Aurora rootadmin account permissions UI
- Enforce per-account policy on direct transfers
- Enforce per-account policy on withdrawals
- Enforce per-account policy on trading
- Correct account policy audit wording
- Fix account policy timestamps and UI copy
### September 19, 2026

- Make Trading capabilities policy-aware
- Use administrator wording for account policy UI
- Add manual Trading max-notional guard
- Add dashboard MFA authentication foundation
- Add Bearer authentication to protected API
- Add Bearer session logout endpoint
- Migrate dashboard browser authentication to Bearer
### September 20, 2026

- Add domain-neutral WebAuthn foundation
- Add internal WebAuthn passkey engine
- Add challenge-bound passkey ceremonies
- Integrate passkey MFA into login service
- Add authenticated passkey registration API
- Add password-passkey login API
- Add passkey management security controls
- Bind WebAuthn challenges to RP configuration
- Harden browser Bearer initialization cleanup
- Require password reauthentication for TOTP enrollment
- Add Security page TOTP enrollment flow
### September 22, 2026

- Fix frontend login startup after Security rollout
- Update Authenticator enrollment copy
- Harden TOTP recovery dialog against repeated Escape
- Add Docker log rotation
- Add active session management API
- Track active session client metadata
- Add read-only Active Sessions UI
### September 23, 2026

- Add Active Sessions revocation controls
- Add IP restriction foundation
- Add IP restriction configuration API
- Add IP restriction recovery API
- Add Aurora IP restriction controls
- Normalize Aurora IP restriction checkbox
- Fix Aurora IP checkbox box model
- Add IP restriction enforcement decision
- Enforce dashboard IP restrictions
- Preserve dashboard session across refresh
- Make IP policy editor enforcement aware
- Isolate tests from production IP arm
- Polish Classic Security interface
- Polish Classic Security form fields
- Share Wallet account permissions across interfaces
- Polish Classic Wallet account permissions
- Add Infinity Grid creation foundation
- Add Infinity Grid prepare API
- Add Infinity Grid preview UI
- Clarify Infinity Grid profit percentage
- Add shared Bot Control market context
- Align Bot Control cache tests with M4.2
- Harden Infinity Grid validation
- Cover Infinity Grid prepare validation
- Expose Infinity Grid validation guidance

## October 2026

### October 1, 2026

- Generalize Infinity Grid create safety foundation
- Add gated Infinity Grid create route
- Add gated Infinity Grid create UI
- Expose Infinity Grid create configuration provenance
- Refine Bot Control UI clarity
- Guard annualized APR for short runtimes
- Release Bot Control locks after Gate rejection
- Align Infinite Grid with Gate native model
- Polish Infinity Grid review display
### October 2, 2026

- Add cumulative grid earnings chart
- Add optimized cumulative return chart
- Fix portfolio history gaps and polish overview chart
### October 3, 2026

- Require Bearer sessions for state-changing operations
- Add public EQTYDAO donation API
- Serialize public donation trust publication
### October 4, 2026

- Add public donation UI and Aurora mobile fixes
- Add Aurora donation presentation
- Unify Classic mobile controls
- Add Bots mobile strategy cards
- Require controlled donation trust bootstrap
### October 8, 2026

- Add full-catalog donation trust bootstrap
### October 10, 2026

- Add donation ledger persistence foundation
- Add public donation ledger API
- Add external donation intent correlation
- Add public donation intent workflow
- Wire public donation intent tracking
- Fix Aurora Donate responsive layout
- Polish Aurora Donate mobile layout
- Add explicit internal donation materialization
- Add donor attribution capability
- Add donor attribution UI
- Polish Aurora donation tablet layout
- Add public donation ledger UI
### October 11, 2026

- Fix Infinity Grid floor preflight
- Require Infinity Grid floor below market
- Add Infinity Grid configuration guide
- M4.21 add native bot activity trades
- M4.22 enable Spot Grid native trades
### October 15, 2026

- M4.24 add demo identity session foundation
- M4.24 add isolated demo bearer foundation
- M4.24 add first demo presentation shell
- M4.24 add isolated demo wallet store
- M4.24 add demo wallet read routing
### October 17, 2026

- M4.24 add demo wallet presentation
- M4.24 add demo wallet ownership and transfers
- M4.24 add demo wallet withdrawals
- M4.24 add isolated demo trading
- M4.24 use Gate public market data in demo trading
### October 18, 2026

- M4.24 clarify Demo market data presentation
- M4.25 add Bot Control strategy workspace
- M4.25 compact Bot Control operations
- M4.26 add Demo Bot Control
- M4.26 polish Demo Bot Control presentation
- M4.26 clear Demo state on account lock
- M4.27 expose reviewed Demo auxiliary surfaces
- M4.28 polish Aurora sidebar icons
- M4.28 refine sidebar navigation
- M4.29 add ownership return accounting foundation
- M4.29 materialize ownership returns after transfer success
- M4.30 scope Wallet records to selected account
- M4.30 fix Transfer audit records subtitle
- M4.31 label explicit Treasury donations
- M4.31 align Treasury detail dialogs with Aurora
- M4.31 allow Demo to view public bot Trades
### October 19, 2026

- Replace MIT license with proprietary EQTY DAO license
### October 21, 2026

- Fix Demo trading preview public-read validation
- Fix Demo trading execution result validation
- Fix Demo trading execution status presentation
- Improve shared trading cancellation confirmation UX
### October 22, 2026

- Align Wallet transfer confirmation styling
- Use single confirmation for withdrawal lifecycle
### October 24, 2026

- Clarify withdrawal lifecycle progress
- Prioritize withdrawal lifecycle in request detail
- Place withdrawal confirm action with authorization
- Default dashboard to Aurora and compact interface selector

---

This is a public development-activity mirror, not a source-code release.
