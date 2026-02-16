# Bolt's Journal - Critical Learnings

## 2026-05-18 - [Static Site Performance]
**Learning:** For static sites with minimal content, the biggest performance wins come from resource hints (prefetching/preloading) and modern CSS properties like `content-visibility`. Broken links can also prevent prefetching from working correctly.
**Action:** Always verify links before adding prefetch hints and consider `content-visibility` for repetitive section-based layouts.
