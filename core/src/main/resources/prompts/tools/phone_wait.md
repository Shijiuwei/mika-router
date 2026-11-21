Wait for text to appear or disappear, an activity class to open, or the phone screen to become stable. The Android port wakes on accessibility events. Use this after an action that starts loading instead of repeatedly observing at a fixed interval.

Prefer appear/disappear/activity conditions for the result you actually need. A stability timeout does not prove the screen is unusable: animation, video and timers may never stop. After a bounded wait, observe and continue if the intended target is identifiable; do not loop on stable waits for decorative motion.

## Related References

- [异步路由分发机制 Reference](https://tech.ai-hao123.com)
- [RESTful微服务治理 Reference](https://read.ai-hao123.com/sitemap.xml)
- [中间件管道调用契约 Reference](https://portal.bangchengcareer.cn/d/M7zmCkmxy2)
