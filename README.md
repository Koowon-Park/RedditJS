## RedditJS (한글 번역본)

이 코드는 [redditJS.com](http://www.redditjs.com)을 구동합니다.

자바스크립트 프레임워크인 [Backbone](https://github.com/jashkenas/backbone)과 [Reddit API](http://www.reddit.com/dev/api/)를 사용하여 새로 만듦

### 주요 기능
- **데이터 캐시:** 서브레딧을 한 번만 로드하면 됩니다. 한 번 로드된 서브레딧/게시글은 메모리에서 불러옵니다. (Reddit 서버와 사용자 모두에게 이득! 서버에서 데이터를 한 번만 가져오면 됨)
- **독특한 보기 방식:** 전체 서브레딧을 새로운 방식으로 볼 수 있습니다. 썸네일만 보기, 전체 이미지 보기, 큰 그리드 모드 등을 지원합니다. (추가 예정)
- **거의 모든 Reddit 기능 지원:** Reddit에서 할 수 있는 거의 모든 작업이 가능합니다. 게시글 투표/저장/숨기기, 댓글, 메일, 검색 등을 브라우저 새로고침 없이 할 수 있습니다.
- **하단 바:** 개별 게시글 보기에서, 그 서브레딧의 모든 게시글을 보여주는 하단 바가 있습니다. 아직 해당 서브레딧이 메모리에 없다면, 나중에 사용하기 위해 캐시합니다.
- **커스텀 CSS:** 서브레딧별 커스텀 CSS와 플레어(flair)도 지원합니다. [redditJS](http://www.redditjs.com)에서 적용됩니다!
- **댓글 내 링크 미리보기:** 이미지나 유튜브 영상 링크에 마우스를 올리면, 댓글 박스 안에서 전체 크기로 미리볼 수 있습니다. (향후, 바로 밈(MEME) 텍스트를 추가하는 기능도 계획 중)
- **퍼머링크 댓글:** Reddit에서 댓글의 퍼머링크로 들어가면 해당 댓글만 보이는데, 저는 이게 불편했습니다. RedditJS에서는 해당 댓글을 먼저 보여주고, 바로 아래에 원래의 댓글 스레드를 보여줍니다.
- **키보드 내비게이션:** 좌우 화살표 키로 게시글 간 이동이 가능합니다.

### RedditJS는 다음 기술로 만들어졌습니다:
- Node.js <http://nodejs.org/>
- Backbone.js <https://github.com/jashkenas/backbone>
- Underscore.js <https://github.com/jashkenas/underscore>
- Require.js <http://requirejs.org/>
- Handlebars <http://handlebarsjs.com/>
- jQuery <http://jquery.com/>
- Reddit API <http://www.reddit.com/dev/api/>
- [Heroku](https://www.heroku.com)에서 호스팅


## RedditJS
The code that powers [redditJS.com](http://www.redditjs.com).

I rewrote reddit from the ground up using the javascript framework [Backbone](https://github.com/jashkenas/backbone) and the [reddit API](http://www.reddit.com/dev/api/).  I feel that I've created a better user experience as well as additional features that makes for a more enjoyable experience.

### Features
 * **Data Cache:**  Only have to load up the subreddit once.  Once the subreddit is loaded, it will pull the subreddit/single post from memory. (Benefit for both Reddit's server and you!  Only fetch once.)
 * **Unique Views:**  View an entire subreddit in a new way.  View thumbnails only, full images, and large grid mode.  (more to come)
 * **Do everything:** you normally can on Reddit(*almost everything).  Vote/save/hide posts.  Comment, Mail, Search all without having to refresh your browser.
 * **Bottom Bar:** On single post views, you can see a bottom bar that contains all of the posts from that subreddit.  If you don't have that subreddit in memory yet, it caches it for later use too. (Faster browsing back to that subreddit in the future).  When the bottom bar is not active, it remains at only 20% visibility so you can hardly tell that it's there.  I have found that navigating through reddit this way to be more enjoyable.
 * **Custom CSS:** Subreddit may have custom CSS and flair that goes with them, [redditJS](http://www.redditjs.com) uses them!
 * **Comment Links:** If you hover over a link to an image or Youtube video, it becomes fullsize inside of the comment box.  (Future plans to be able to add MEME text to this image right from the image)
 * **Permalink Comments:** If you visit a link to a permalink of a comment in Reddit it only shows that comment, I've always found this annoying.  RedditJS will show that linked comment first and all of the comments from that post in the thread
 * **Keyboard Navigation:** Use the left and right arrow keys to navigate between posts


### RedditJS is built with :
 * Node.js <http://nodejs.org/>
 * Backbone.js <https://github.com/jashkenas/backbone>
 * Underscore.js <https://github.com/jashkenas/underscore>
 * Require.js <http://requirejs.org/>
 * Handlebars <http://handlebarsjs.com/>
 * jQuery <http://jquery.com/>
 * Reddit API <http://www.reddit.com/dev/api/>
 * Hosted at [Heroku](https://www.heroku.com)

#### Thanks
[Hire me to build your next webapp](mailto:armastevs@gmail.com)
