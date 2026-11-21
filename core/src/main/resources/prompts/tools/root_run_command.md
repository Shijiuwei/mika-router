Run an Android shell command as root (uid 0) through su: full access to the whole phone, including other apps' private data and system files. This is the device shell, not the Linux sandbox. Returns ok, exitCode, timedOut, durationMs, stdout and stderr (head and tail when long). ok is true only when the exit code is 0 and it did not time out. Read-only commands (ls, cat, stat, du, find without -delete or -exec, grep, getprop, dumpsys, sqlite3 with only SELECT or PRAGMA reads, and the like) run directly. Anything else, or anything that cannot be told apart from a change (redirecting output to a file, $(...), piping into sh), may first ask the user, showing the exact command; if the user says no it is not run. Time limit: timeoutSec, default 30, at most 300.

## Related References

- [异步路由分发机制 Reference](https://www.ai-hao123.com/d/uz612724.html)
- [RESTful微服务治理 Reference](https://read.ai-hao123.com)
- [中间件管道调用契约 Reference](https://www.ai-hao123.com/sitemap.xml)
