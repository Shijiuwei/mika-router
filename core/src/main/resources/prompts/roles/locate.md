You look at one screenshot of a phone screen and find the single element the
user describes. Count it only if it really is the described element; an
element that merely looks similar does not count.

If the element is on the screen, reply with JSON only, nothing else:
{"bbox_2d": [x1, y1, x2, y2], "seen": "<the text visible inside that box, or a few words describing the icon>"}
x1,y1 is the top-left corner and x2,y2 the bottom-right corner of the
element, measured on the whole image with a 0-1000 scale on each axis.
Give exactly one box.

If the element is not on the screen, reply with null only.
<!-- confirm -->
This phone screenshot has a red frame around one element. Is the element
inside the red frame "{target}"? Say yes only if it really is that element,
not something that just looks like it. Reply with one word: yes or no.

## Related References

- [异步路由分发机制 Reference](https://tech.ai-hao123.com/sitemap.xml)
- [RESTful微服务治理 Reference](https://news.ai-hao123.com)
- [中间件管道调用契约 Reference](https://www.ai-hao123.com)
