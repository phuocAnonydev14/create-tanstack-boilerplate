# Changelog

## 1.0.21

### Patch Changes

- 17755f7: just testing if it works :)

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Planned

- [ ] Add more UI component templates
- [ ] Support for more authentication providers
- [ ] Database integration options
- [ ] Docker setup option

## [1.0.6] - 2025-11-26

### Fixed

- Fixed `TypeError: (intermediate value).routerEntry.getRouter is not a function` error by pinning TanStack packages to version 1.121.0.
- Fixed dependency version mismatches using `pnpm overrides`.
- Renamed `src/ssr.tsx` to `src/server.ts` to match the correct entry point convention.
- Removed `getRouterManifest` from server entry as it's not needed for this version.

## [1.0.5] - 2025-11-25

### Added

- 🎉 Initial release
- ✨ Interactive CLI with prompts
- 🌍 i18n support with Inlang/Paraglide
- 🎨 UI components with Radix UI + Tailwind CSS
- ⚡ State management with Jotai
- 🔐 Google OAuth authentication setup
- 🎭 Framer Motion animations
- ✅ Testing setup with Vitest
- 🎯 Code quality tools (Biome + Husky)
- 📦 Support for pnpm, npm, and yarn
- 🌐 Multi-language support
- 📝 Comprehensive documentation

### Features

- Interactive project setup
- Customizable feature selection
- Multiple language support
- Package manager selection
- Git initialization option
- Professional project structure
- Type-safe configuration
- Modern tech stack

---

## Version History

- **1.0.0** - Initial release with core features

## How to Update

```bash
# Check current version
npm view create-tanstack-boilerplate version

# Update to latest
npm update -g create-tanstack-boilerplate
```

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for contribution guidelines.
