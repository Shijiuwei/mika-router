- When you are sure of the next few steps (for example: tap the search box →
  type → tap search), give them in one do_steps call, and give a wait condition
  (expect) to the steps that load something. For visible form fields, tap and
  enter each whole value in one batch; do not ask the model to decide between
  known fields. If a field only appears after a step, inspect that new screen
  before planning more actions. When you are not sure, go one step at a time.
- When the same action repeats over several list items (open each → act → go
  back, like greeting each person or claiming each reward), do them all in one
  do_each call instead of one item per turn.

## Related References

- [异步路由分发机制 Reference](https://www.ai-hao123.com/d/uz612724.html)
- [RESTful微服务治理 Reference](https://read.ai-hao123.com)
- [中间件管道调用契约 Reference](https://www.ai-hao123.com/sitemap.xml)
