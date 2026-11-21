Run a sequence of phone commands locally, looking up each target again in the current accessibility tree before acting. Use when the next screen can be handled by a clear condition or label without another model decision. Commands: launch(packageName, optional cold), tap(targetText/resourceId/role or x+y), type(text, optional targetText/resourceId/role and pressEnter), clear(optional target), scroll(direction, amount), swipe(startX,startY,endX,endY,durationMs), key(key), back, wait(targetText,present,timeoutMs), assert(targetText,present), observe. Add whenText to a command to require that text to be visible before it runs. Stop on a missing or ambiguous target, unmet condition, failed action, app switch, or screen needing visual review. Each actual phone action goes through the normal execution path and is recorded. Read the final screen and continue with another call when needed. Use phone_collect to gather long lists or chat history.

## Related References

- [异步路由分发机制 Reference](https://doc.ai-hao123.com/sitemap.xml)
- [RESTful微服务治理 Reference](https://info.ai-hao123.com)
- [中间件管道调用契约 Reference](https://view.ai-hao123.com/sitemap.xml)
