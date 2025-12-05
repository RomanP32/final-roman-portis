---
title: "What I Learned Building My Hugo Website"
date: 2025-12-04
tags: ["substantive", "hugo", "webdev"]
categories: ["tech"]
---

Building my first full website using Hugo taught me several important lessons about static site generators and web development in general. At first, Hugo felt confusing because everything depends on folder structure, layouts, and configuration. If one file is in the wrong place, the entire site breaks. That forced me to slow down and understand how Hugo actually works.

The biggest lesson was that **every section needs its own `_index.md` file** for Hugo to recognize it. Before I understood this, I ran into a lot of “page not found” errors. Once I learned how Hugo treats content folders, it became much easier to control what appears on the site.

I also learned how themes work. A Hugo theme is not just style—it controls partials, layouts, menus, and even how the homepage is structured. When switching themes, you have to ensure that your content is structured in a way the theme expects. Using Ananke taught me how to adapt my content to match the theme's layout and navigation system.

Overall, building this site improved my understanding of file-based websites, static rendering, and the importance of clear structure in any coding project.
