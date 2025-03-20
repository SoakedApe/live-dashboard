# Changelog

## [1.1.0] - 2025-03-20
- Add daily P&L chart with strategy breakdown
- Add equity curve chart to main dashboard
- Switch DB_PATH to environment variable (was hardcoded)

## [1.0.1] - 2025-01-05
- Fix session authentication timeout
- Add `equity` table to schema for NAV tracking

## [1.0.0] - 2024-09-01
- Initial release: Flask dashboard with trade log, open positions, daily summary
- SQLite schema with trades, equity, daily_summary tables
- Basic HTTP auth
