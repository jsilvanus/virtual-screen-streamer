# virtual-screen-streamer

(Formerly `picompanion`.) A Windows program that runs on the operator PC, creates virtual monitors and streams many virtual screens as RTMP to pimatrix. It is not a Node project and not a Pi service: in the [piecosystem](https://github.com/jsilvanus/piecosystem) it is a **seam** project, meeting the Pi ecosystem at RTMP.

Extracted from `jsilvanus/pimatrix` (`packages/windows-companion`). Status: phase A, copied as-is, not yet built or tested on Windows. The C# client (`Services/PiMatrixClient.cs`) still talks to the pimatrix API by hand; it will move to a contract client generated from pimatrix OpenAPI.

Virtual display driver: see `Assets/Driver/README_DRIVER.md`.

---

## Pi Ecosystem Integration & Status Updates

This project is an integral component of the [Pi Production Ecosystem](file:///d:/piecosystem).

> [!IMPORTANT]
> Any changes to this repository's architectural role, API routes, communication protocols, exposed ports, dependencies, or runtime status **must be documented in the central `piecosystem` coordination repository** (`docs/projects-catalog.md` and `docs/inter-service-matrix.md`).
> Always verify cross-system health with `npm run status` in `D:\piecosystem`.
