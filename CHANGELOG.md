# Changelog

## [v0.5.0](https://github.com/runapi-ai/fish-audio/releases/tag/v0.5.0) - 2026-10-15

### Breaking
- Fish s1, s2-pro and s2.1-pro temporary cloning accepts at most one HTTPS audio URL with its exact transcript and cannot be combined with voice_id.
  Migration: Upload local or Base64 audio through POST /api/v1/files, pass the returned URL in references[0].audio with exact text, keep one sample and remove voice_id. Ensure the URL remains valid while queued and read. Choose voice_id alone for an existing voice.


## [v0.4.1](https://github.com/runapi-ai/fish-audio/releases/tag/v0.4.1) - 2026-09-04

### Changed
- Document terminal responses, 202 acceptance, and Task Result continuation for supported capabilities.


## [v0.4.0](https://github.com/runapi-ai/fish-audio/releases/tag/v0.4.0) - 2026-08-21

### Added
- Document account-owned voice creation, list and get workflows, readiness checks, and speech reuse.


## [v0.3.0](https://github.com/runapi-ai/fish-audio/releases/tag/v0.3.0) - 2026-08-17

### Added
- Document account-owned voice creation, list and get workflows, readiness checks, and speech reuse.


## [v0.2.2](https://github.com/runapi-ai/fish-audio/releases/tag/v0.2.2) - 2026-08-12

### Changed
- Generate the fish-audio skill from the shared RunAPI recipe with contract-discovered request rules and task behavior, direct local media inputs, complete result verification, and bounded recovery.


## [v0.2.1](https://github.com/runapi-ai/fish-audio/releases/tag/v0.2.1) - 2026-08-10

### Changed
- Complete marketplace distribution for the RunAPI Fish Audio skill.


## [v0.2.0](https://github.com/runapi-ai/fish-audio/releases/tag/v0.2.0) - 2026-08-07

### Added
- Add s2.1-pro guidance for managed MP3 and WAV speech generation.


## [v0.1.1](https://github.com/runapi-ai/fish-audio/releases/tag/v0.1.1) - 2026-07-21

### Added
- Document inline reference audio and exact transcript inputs for one-request voice matching.


## [v0.1.0](https://github.com/runapi-ai/fish-audio/releases/tag/v0.1.0) - 2026-07-20

### Added
- Add guided synchronous speech generation examples for s1 and s2-pro.
