# Retornos de Endpoints

---

```C#
        // GET: api/<TestController>
        [HttpGet]
        public ActionResult<IEnumerable<Blog>> Get()
        {
            var blogs = blogRepository.GetBlogs();
            return Ok(blogs);
        }
```
- Blogs es una lista de clases
