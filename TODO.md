# CowCare Flutter App Development TODO

## Phase 1: Project Setup
- [x] Create Flutter project with `flutter create cowcare`
- [x] Set up project structure (lib/, assets/, test/)
- [x] Add dependencies (Riverpod, Hive, fl_chart, etc.)
- [x] Configure themes and assets

## Phase 2: Architecture and Mock Backend
- [ ] Implement modular architecture (presentation/domain/data layers)
- [ ] Set up Riverpod providers
- [ ] Create mock backend server replicating API endpoints
- [ ] Implement local storage with Hive

## Phase 3: Authentication
- [x] Implement auth screens (Login, Register, Forgot Password)
- [x] Add role-based auth logic
- [ ] Integrate phone OTP option

## Phase 4: Core Screens
- [x] Onboarding screen with farm registration
- [x] Dashboard (Herd Overview) with summary cards and list
- [x] Map screen with cow pins and details
- [x] Cow Detail screen with vitals, charts, feed
- [x] Alerts screen with filtering and acknowledgment
- [x] Device Pairing screen with BLE/QR/manual
- [x] Settings screen with prefs and profile

## Phase 5: Realtime and Offline
- [ ] Implement WebSocket for realtime updates
- [x] Add offline caching for timeseries and actions (partial)
- [ ] Queue and sync user actions when offline

## Phase 6: Testing
- [ ] Unit tests for domain logic
- [ ] Widget tests for main screens (Dashboard, CowDetail, Alerts)

## Phase 7: CI/CD and Deliverables
- [x] Set up GitHub Actions for tests and builds
- [x] Create README with setup instructions
- [ ] Generate APK and iOS archive
- [x] Prepare mock data and screenshots

## Phase 8: Finalization
- [ ] Code review and optimization
- [ ] Ensure accessibility and themes
- [ ] Package repo as zip or provide GitHub link
