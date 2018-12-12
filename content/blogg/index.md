---
views:
    main:
        template: anax/v2/article/default
        data:
            class: blog

    byline: false
    block-about: false
    article-toc: false

    blog-list:
        region: main
        template: anax/v2/blog-list/default
        sort: 2
        data:
            dateFormat: j F Y
            meta:
                type: toc
                orderby: publishTime
                orderorder: desc

    blog-toc:
        region: sidebar-right
        template: anax/v2/blog-toc/default
        sort: 2
        data:
            meta:
                type: copy
                view: blog-list

---
Dagens Bild
===========================

I denna blogg lägger jag upp dagens bild varje dag. Det är bilder med varierande motiv som visas upp på olika vis. OBS. Det läggs inte upp bilder varje dag då det blir oftast en "liten" fördröjning i schemat då det finns alltid något som kommer upp. Men snart blir det förbättring!
