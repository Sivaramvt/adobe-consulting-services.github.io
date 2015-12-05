---
published: false
---

# Http Cache framework
## Purpose
HttpCache provides a most effective way to improve performance of an application by caching the full output of a http request and then bypassing the request processing entirely on each subsequent requests. 

### Features
- Caches anonymous and authenticated requests.
- Supports caching personalized requests.
	- Group based caching provided OOTB.
    - Mechanism exposed to plugin custom logic for handling personalized requests. 
- Super flexible cache configs tied to URIs supported. 
	- Allows extending cache configs.
    - Allows multiple cache configs.
- Developer hook exposed to plugin custom rules on key cache handling events such as
	- On request receive.
    - On response cache
    - On response deliver
    - On cache invalidate
- Provides mechanism to plugin custom cache keys.
- Pluggable cache persistece model.
	- In-MEM impplementation provided OOTB
    - Allows multiple cache stores to co-exist.
- Invalidation mechanism based on JCR paths and Sling jobs.
	- Sample JCR change event handler based invalidation supplied.
    - In-Mem cache store supports TTL.
- Provdies powerful instrumentation based on JMX mbeans.

    




Enter text in [Markdown](http://daringfireball.net/projects/markdown/). Use the toolbar above, or click the **?** button for formatting help.
