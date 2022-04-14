---
title: 'Pre-rendering の形式'
date: '2022-04-14'
---

Next.jsでは2種類のPre-rendering方式をサポートしています。
- Static Generation（SSG）で、これはアプリケーションのHTMLの生成が1度だけ行われ、それがページリクエストのたびに再利用されます。
- Server-side Rendering（SSR）で、こちらはページリクエストのたびにHTMLが再生成されます。
Next.jsでは同じアプリケーション内でページごとにPre-rendering方式の選択が可能です。そのためSSGとSSRのハイブリッドな構成のアプリケーションも実装できます。