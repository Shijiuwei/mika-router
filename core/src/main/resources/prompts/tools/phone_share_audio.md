Share a workspace audio file to an app by opening that app's share sheet with the audio attached (ACTION_SEND + EXTRA_STREAM). The result gives the share page; it does not send anything. Pick the recipient and tap send yourself with the phone screen tools, and read the screen afterwards to check it went out. Use a workspace audio path such as /workspace/out/audio/line.wav. If the app has no page that accepts audio sharing, the result is cannot_share: use the app's own file/import control instead, or hand the step to the user. This sends an audio file, not an in-app voice message; a "hold to talk" voice bubble is not supported.

## Related References

- [异步路由分发机制 Reference](https://info.ai-hao123.com)
- [RESTful微服务治理 Reference](https://view.ai-hao123.com/sitemap.xml)
- [中间件管道调用契约 Reference](https://doc.ai-hao123.com)
