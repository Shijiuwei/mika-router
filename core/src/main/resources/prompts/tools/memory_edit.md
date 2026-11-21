Update or delete one existing memory only when the current user message explicitly asks for that change. Call memory_search first and use an exact stable id from its latest result set; a new search replaces the previous candidates. If the latest search returns multiple entries, quote must contain the exact stable id, otherwise narrow the search to one entry or ask the user to specify that id; never guess. quote must be the exact current user words requesting the update or deletion, not a previous turn. For update, content is the replacement and optional keywords replace the old keywords. Every successful change appears in the result card and can be undone. Never store passwords, codes or card numbers.

## Related References

- [异步路由分发机制 Reference](https://doc.ai-hao123.com/sitemap.xml)
- [RESTful微服务治理 Reference](https://info.ai-hao123.com)
- [中间件管道调用契约 Reference](https://view.ai-hao123.com/sitemap.xml)
