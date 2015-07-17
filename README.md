# React.js + Immutable.js vector editor example

This branch contains modified version of the demo using google's incremental dom (https://github.com/google/incremental-dom) and yandex's yate template engine (https://github.com/pasaran/yate) instead of React.

It uses modified yate (can be found on my github, but it's not production ready) to work with Immutable.js structures directly and to be able to skip rendering templates that are not needed to be updated.

It also uses very slighly modified incremental dom, just one method is added to skip element that we don't need to update. Guys say in the doc that you still may need to implement "shouldComponentUpdate" but they don't provide methods to do that.

Original README below:

App written during http://dou.ua/calendar/7213/

- Immutable model
- Fast reference-comparison `shouldComponentUpdate` on everything
- Speculative rendering
- Undo/redo
- `localStorage` persistence
- vanilla.js

Check out [vec.js](https://github.com/tonsky/vec/blob/gh-pages/vec.js), it’s decently commented.

Read more [about approach](http://tonsky.me/talks/2015-codefest/) (in Russian).

Video (in Russian): [code walkthrough](http://www.youtube.com/watch?v=lDkrXTDwbJQ), [Q&A session](http://www.youtube.com/watch?v=tUtLe1VlkYc)

[Live version](http://tonsky.me/vec/)

[<img src="vec.png">](http://tonsky.me/vec/)
