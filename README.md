# StaticSsrState

A small Blazor web app for TempData and Session on .NET 11 static server rendering. Feedback and Onboarding are static pages.

Requires the .NET 11 RC 1 SDK (`11.0.100-rc.1.26425.128`), pinned in `global.json`.

## Run

```bash
dotnet run
```

Open http://localhost:5182.

## Pages

| URL           | What to look at                                                                                                          |
| ------------- | ------------------------------------------------------------------------------------------------------------------------ |
| `/feedback`   | Send a comment. A banner appears after the redirect. Refresh removes it.                                                 |
| `/onboarding` | Enter a name, then a company. The name stays on the next step, after refresh, and in a new tab. Finish clears the draft. |

A copied link or a private window does not carry the draft. The name is not in the address bar.
