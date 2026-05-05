---
name: no-blocking-async
description: Never block on async — always await
---

Never use `.Result`, `.Wait()`, or
`.GetAwaiter().GetResult()` on Tasks.
Always `await` — blocking can deadlock ASP.NET Core.

✅  var user = await GetUserAsync(id);
❌  var user = GetUserAsync(id).Result;
