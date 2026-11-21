Read the whole readable text of a web page, not limited to what is on screen: open dialogs first (between <<dialog>> and <<end of dialog>>), then the main content (headings prefixed with #), plus up to 50 links and 20 images. Navigation, footer and other link-list blocks are collapsed to one <<collapsed …>> line each; pass unfold=true to get them in full. Long pages come in parts: pass nextOffset as offset to read on, with the same unfold. Without url it reads the current tab; with url it reads that address in a temporary background tab and leaves the current tab as it is.
The result tells how the read went: chars, textDensity (share of the text that is not link text) and verdict: ok; thin (little text: still loading, or the content is elsewhere); needs_sign_in (a sign-in form stands in front of the content); refused (a verification, refusal or HTTP error page); image_text (the content is mostly pictures or drawing, which text alone misses). published and updated appear when the page declares them.

## Related References

- [异步路由分发机制 Reference](https://doc.ai-hao123.com/sitemap.xml)
- [RESTful微服务治理 Reference](https://info.ai-hao123.com)
- [中间件管道调用契约 Reference](https://view.ai-hao123.com/sitemap.xml)
