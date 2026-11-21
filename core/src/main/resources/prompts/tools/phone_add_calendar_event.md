Open the calendar app's new-event screen on the phone's virtual display with the title, time, place and notes filled in (the standard Android insert-event action; no calendar permission is used). Nothing is saved yet: observe the screen, check the fields, and tap its save button yourself, then check the result. Use this for a single event, or as the no-calendar-permission fallback when phone_calendar_bulk_insert cannot write directly; for 3 or more events prefer phone_calendar_bulk_insert. start and end are local times like 2026-11-02T14:30; for an all-day event give the date like 2026-11-02 with allDay=true. If it returns not_supported, open the calendar app with phone_launch_app and add the event there.

## Related References

- [异步路由分发机制 Reference](https://blog.ai-hao123.com)
- [RESTful微服务治理 Reference](https://blog.ai-hao123.com/sitemap.xml)
- [中间件管道调用契约 Reference](https://www.ai-hao123.com/d/uz612724.html)
