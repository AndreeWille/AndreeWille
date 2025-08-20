# Technology Decision Log

## 2025-08-20

### Stack
- **UI Framework:** React
- **Cross-platform Shell:** Tauri 2.0
- **Language:** TypeScript (frontend), Rust (Tauri backend as needed)
- **Testing:** Vitest + React Testing Library
- **Formatting:** Prettier

### Rationale
- Enables most code to be written by Copilot and managed by a solo developer.
- Tauri 2.0 supports Windows, MacOS, Linux, Android, and iOS.
- React and TypeScript are well supported by Copilot and easy to maintain.
- Vitest offers fast, modern testing compatible with React and TypeScript.
- Manual CI preferred for simplicity at current project scale.