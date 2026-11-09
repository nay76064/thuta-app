# Web workspace boundaries

- This workspace is the public React web client. Keep API persistence and authorization in `../api`; call its HTTP interface rather than importing server internals.
- Stack: TypeScript, React, Vite, and shadcn/ui. The selected shadcn preset is `b7CINFsdU`.
- Follow repository-level architecture and security requirements in [../AGENTS.md](../AGENTS.md). Product behavior is specified in [../SPEC.md](../SPEC.md).
- Keep interfaces responsive and accessible, including keyboard access, semantic controls, visible focus, and meaningful image alternatives.
- Keep `README.md` user-facing and `CLAUDE.md` as a pointer to the repository guidance.
