# Hi, I'm Dafenx

I build practical open-source tools and contribute focused improvements to emulator projects, especially around Vulkan rendering, GPU scheduling, test infrastructure, and repository health.

## Current Focus

- Contributing to [SharpEmu](https://github.com/par274/sharpemu) with focused work on Vulkan resource lifetime, render-pass reuse, scheduling boundaries, pipeline-cache validation, and diagnostics.
- Improving [KytyPS5](https://github.com/KytyPS5/KytyPS5) test infrastructure and cross-driver Vulkan test portability.
- Maintaining [healthcheck](https://github.com/Dafenxz0/healthcheck), a small CLI for auditing repository quality, contribution activity, releases, and project readiness.

## Projects and Open-Source Work

| Project | What I'm working on |
| --- | --- |
| [healthcheck](https://github.com/Dafenxz0/healthcheck) | Repository health reports, contribution summaries, release helpers, and activity insights. |
| [SharpEmu](https://github.com/par274/sharpemu/pulls?q=is%3Apr+author%3ADafenxz0) | Small, reviewable architecture and execution improvements around its C# Vulkan backend. |
| [KytyPS5](https://github.com/KytyPS5/KytyPS5/pull/24) | CMake/CTest regression-test integration and more portable Vulkan GPU tests. |

## How I Like To Contribute

- Small pull requests with a clear scope.
- Reproducible fixes with validation notes.
- Architecture improvements that preserve existing behavior.
- Tests and documentation that make future changes safer.
- Practical tools over flashy demos.

## Recently

- Worked on bounded Vulkan resource reuse without introducing persistent guest-memory caching.
- Explored cleaner scheduler boundaries, MRT render-pass reuse, and safer persistent pipeline caches in SharpEmu.
- Registered KytyPS5's regression executables with CTest and removed a driver-dependent UNORM8 rounding assumption.
