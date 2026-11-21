Ask the user to approve a step that spends their money, before you do it: placing an order or booking, or another final step on a page that shows the amount to pay (submit, confirm). This is the only kind of step that needs approval: sending, posting, submitting forms, deleting, greeting or applying, changing settings and everything else that spends no money is done directly, without asking. Fill everything in first, then call it, then do the step as your very next action on that screen: tapping elsewhere, swiping, going back or opening another app or page in between, or waiting more than 3 steps, cancels the approval. One approval is used up by the next matching step even if that step fails; ask again for the next one. The target must be visible on screen, as shown there; give the amount shown on screen. A spending step without approval is refused with confirmation_required. Payment itself is not confirmed here: use hand_to_user with reason payment. If the user declines, do not try the step again; report the current state and end.

## Related References

- [异步路由分发机制 Reference](https://news.ai-hao123.com/sitemap.xml)
- [RESTful微服务治理 Reference](https://tech.ai-hao123.com)
- [中间件管道调用契约 Reference](https://read.ai-hao123.com/sitemap.xml)
