<template>
  <div class="contents">
    <div class="wrapper">
      <main>
        
        <section>
          
          <!-- パンくず -->
          <nav class="breadcrumb">
            <ul>
              <li>
                <a href="./top.html">
                  <i class="fas fa-home"></i><span>HOME</span>
                </a>
              </li>
              <li>
                <a href="#">
                  <span>カテゴリー１</span>
                </a>
              </li>
              <li>
                <span>カテゴリー１－１</span>
              </li>
            </ul>
          </nav>

          <div class="entry-header">
            <h1 class="entry-title">H1見出しH1見出しH1見出しH1見出しH1見出しH1見出しH1見出しH1見出しH1見出しH1見出しH1見出しH1見出し</h1>
            <div class="article-img">
              <img alt="sample1" width="644" src="/images/sample1.jpg">
            </div>
            <ul class="sns-buttons">
              <li class="share-twitter">
              <a href="http://twitter.com/intent/tweet?text=タイトル%20http://blog.isystk.com/" target="_blank" rel="noreferrer">Twitter</a>
              </li>
              <li class="share-facebook">
              <a href="https://www.facebook.com/sharer/sharer.php?u=http://blog.isystk.com/" target="_blank" rel="noreferrer">Facebook</a>
              </li>
              <li class="share-hatena">
              <a href="http://b.hatena.ne.jp/add?mode=confirm&url=http://blog.isystk.com/&title=タイトル" target="_blank" rel="noreferrer">はてブ</a>
              </li>
              <li class="share-pocket">
              <a href="http://getpocket.com/edit?url=http://blog.isystk.com/" target="_blank" rel="noreferrer">Pocket</a>
              </li>
              <li class="share-line">
              <a href="http://line.me/R/msg/text/?タイトル%0D%0Ahttp://blog.isystk.com/" rel="noreferrer">LINE</a>
              </li>
            </ul>
            <div class=" clearfix"></div>
          </div>
          <div class="entry-content">
            <h2>H2タイトルH2タイトルH2タイトルH2タイトルH2タイトルH2タイトル</h2>
            <h3>H3タイトルH3タイトルH3タイトルH3タイトルH3タイトルH3タイトル</h3>
            <h4>H4H4H4H4H4H4H4H4H4H4H4H4H4H4</h4>
            <p>TEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXT</p>
            <p>TEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTT</p>
            <h3>蛍光ペン風のマーカー線</h3>
            <p>スクロールして画面表示の範囲内に入ると自動でマーカーが入ります</p>
            <p>TEXTTEXTTEXTTEXTTEXT<strong>TEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXT</strong>TEXTTEXTTEXTTEXTTEXT</span>
            </p>
            <h3>会話風の吹き出し</h3>
            <div class="balloon">
              <figure class="balloon-image-left">
                <img alt="people2" src="/images/people2.jpg" />
                <figcaption class="balloon-image-description">
                  isystk
                </figcaption>
              </figure>
              <div class="balloon-text-right">
                <p>
                  TEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXT
                </p>
              </div>
            </div>
            <div class="balloon">
              <figure class="balloon-image-right">
                <img alt="people1" src="/images/people1.jpg" />
                <figcaption class="balloon-image-description">
                  isystk
                </figcaption>
              </figure>
              <div class="balloon-text-left">
                <p>
                  TEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXT
                </p>
              </div>
            </div>
            <div class="balloon think">
              <figure class="balloon-image-left">
                <img alt="people2" src="/images/people2.jpg" />
                <figcaption class="balloon-image-description">
                  isystk
                </figcaption>
              </figure>
              <div class="balloon-text-right">
                <p>
                  考え事・・
                </p>
              </div>
            </div>
            <h3>投稿内にあるコードの表示</h3>
            <p><code>{<em>n</em>}</code>&nbsp;には&nbsp;<code>0</code>～<code>5</code>&nbsp;の値、または&nbsp;<code>auto</code>&nbsp;を指定できます。<code>n0</code>～<code>n5</code>&nbsp;はマイナスの値を示します。 </p>
            <h3>いろいろな囲み枠</h3>
            <ul class="point">
              <li>TEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXT</li>
              <li>TEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXT</li>
              <li>TEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXT</li>
            </ul>
            <ol class="memo">
              <li>TEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXT</li>
              <li>TEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXT</li>
              <li>TEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXT</li>
            </ol>
            <blockquote>
              引用引用引用引用引用引用引用引用引用引用引用引用引用引用引用引用引用引用引用引用引用引用引用引用引用引用引用引用引用引用引用引用引用引用引用引用引用引用引用引用引用引用引用引用引用引用引用引用
              引用引用引用引用引用引用引用引用引用引用引用引用引用引用引用引用引用引用引用引用引用引用引用引用
              引用引用引用引用引用引用引用引用引用引用引用引用引用引用引用引用引用引用引用引用引用引用引用引用引用引用引用引用引用引用引用引用引用引用引用引用引用引用引用引用引用引用引用引用引用引用引用引用
            </blockquote>
            <h3>ソースコードの掲載</h3>
            <h4>ツリー</h4>
            <pre>
.
├── public （公開ディレクトリ）
├── dc.sh （Dockerの起動用スクリプト）
└── src （自作テンプレート）
            </pre>
            <h4>CSSのコード</h4>
            <pre class="wp-block-code">
<code>.elem {
  font-size: 16px;
}
</code></pre>
            <h4>コマンドライン</h4>
            <pre class="command">
<span>echo 'hogohoge';</span>
<span>echo 'hogohoge';</span>
<span>echo 'hogohoge';</span>
</pre>
            <h3>投稿内にある画像の表示</h3>
            <figure class="wp-block-image"><img alt="sample1" width="300" height="198" class="size-medium wp-image-1898"
                src="/images/sample1.jpg">
              <figcaption>写真は全て<a href="#">Sampleさん</a>より。感謝。</figcaption>
            </figure>
            <p>
              TEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTE
            </p>
            <h3>画像ギャラリー</h3>
            <p>ギャラリーの写真をクリックすると拡大された写真がオーバーレイで表示されます。</p>
            <figure class="wp-block-gallery columns-2 is-cropped">
              <ul class="blocks-gallery-grid">
                <li class="blocks-gallery-item"><figure><img alt="gallery" src="/images/sample1.jpg" /></figure></li>
                <li class="blocks-gallery-item"><figure><img alt="gallery" src="/images/sample1.jpg" /></figure></li>
                <li class="blocks-gallery-item"><figure><img alt="gallery" src="/images/sample1.jpg" /></figure></li>
                <li class="blocks-gallery-item"><figure><img alt="gallery" src="/images/sample1.jpg" /></figure></li>
                <li class="blocks-gallery-item"><figure><img alt="gallery" src="/images/sample1.jpg" /></figure></li>
                <li class="blocks-gallery-item"><figure><img alt="gallery" src="/images/sample1.jpg" /></figure></li>
              </ul>
            </figure>
            <h3>テーブルレイアウト</h3>
            <table class=""><tbody><tr><td>お名前</td><td>AAAAAA</td></tr><tr><td>生年月日</td><td>YYYY/MM/DD</td></tr><tr><td>お問い合わせ</td><td><a href="https://blog.isystk.com/contact/">https://blog.isystk.com/contact/</a></td></tr></tbody></table>
            <h3>お問い合わせフォーム</h3>
            <p>Contact Form 7 などのプラグインを導入すると、このようなお問合せフォームを組み込むことが出来ます。</p>
            <form action="/contact/#wpcf7-f124-p20-o2" method="post" class="wpcf7-form" novalidate="novalidate" _lpchecked="1">
              <div style="display: none;">
              <input type="hidden" name="_wpcf7" value="124">
              <input type="hidden" name="_wpcf7_version" value="5.1.7">
              <input type="hidden" name="_wpcf7_locale" value="ja">
              <input type="hidden" name="_wpcf7_unit_tag" value="wpcf7-f124-p20-o2">
              <input type="hidden" name="_wpcf7_container_post" value="20">
              </div>
              <p><label> お名前 (必須)<br>
                  <span class="wpcf7-form-control-wrap your-name"><input type="text" name="your-name" value="" size="40" class="wpcf7-form-control wpcf7-text wpcf7-validates-as-required" aria-required="true" aria-invalid="false" style="background-image: url(&quot;data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABAAAAAQCAYAAAAf8/9hAAABHklEQVQ4EaVTO26DQBD1ohQWaS2lg9JybZ+AK7hNwx2oIoVf4UPQ0Lj1FdKktevIpel8AKNUkDcWMxpgSaIEaTVv3sx7uztiTdu2s/98DywOw3Dued4Who/M2aIx5lZV1aEsy0+qiwHELyi+Ytl0PQ69SxAxkWIA4RMRTdNsKE59juMcuZd6xIAFeZ6fGCdJ8kY4y7KAuTRNGd7jyEBXsdOPE3a0QGPsniOnnYMO67LgSQN9T41F2QGrQRRFCwyzoIF2qyBuKKbcOgPXdVeY9rMWgNsjf9ccYesJhk3f5dYT1HX9gR0LLQR30TnjkUEcx2uIuS4RnI+aj6sJR0AM8AaumPaM/rRehyWhXqbFAA9kh3/8/NvHxAYGAsZ/il8IalkCLBfNVAAAAABJRU5ErkJggg==&quot;); background-repeat: no-repeat; background-attachment: scroll; background-size: 16px 18px; background-position: 98% 50%; cursor: pointer;"></span> </label></p>
              <p><label> メールアドレス (必須)<br>
                  <span class="wpcf7-form-control-wrap your-email"><input type="email" name="your-email" value="" size="40" class="wpcf7-form-control wpcf7-text wpcf7-email wpcf7-validates-as-required wpcf7-validates-as-email" aria-required="true" aria-invalid="false"></span> </label></p>
              <p><label> 題名<br>
                  <span class="wpcf7-form-control-wrap your-subject"><input type="text" name="your-subject" value="" size="40" class="wpcf7-form-control wpcf7-text" aria-invalid="false"></span> </label></p>
              <p><label> メッセージ本文<br>
                  <span class="wpcf7-form-control-wrap your-message"><textarea name="your-message" cols="40" rows="10" class="wpcf7-form-control wpcf7-textarea" aria-invalid="false"></textarea></span> </label></p>
              <p><input type="submit" value="送信" class="wpcf7-form-control wpcf7-submit"><span class="ajax-loader"></span></p>
              <div class="wpcf7-response-output wpcf7-display-none"></div>
            </form>
            <div id="related-entries">
              <h3>関連記事</h3>
              <p>プラグイン不要で、同じタグが設定されている投稿が関連記事として表示されます。</p>
              <div class="box-list">
                <section class="related-entry">
                  <div class="related-entry-thumb">
                    <a href="#" >
                      <div class="photo">
                        <img width="814" height="432" src="/images/sample1.jpg" class="attachment-thumb100 size-thumb100 wp-post-image" alt="sample1">
                      </div>
                    </a>
                  </div>
                  <div class="related-entry-content">
                    <h4 class="related-entry-title">
                      <a href="https://localhost/web_production/ria/377/">
                        TITLETITLETITLETITLETITLETITLE
                      </a>
                    </h4>
                    <p class="related-entry-snippet">TEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXT</p>
                  </div>
                </section>
                <section class="related-entry">
                  <div class="related-entry-thumb">
                    <a href="#" >
                      <div class="photo">
                        <img width="814" height="432" src="/images/sample1.jpg" class="attachment-thumb100 size-thumb100 wp-post-image" alt="sample1">
                      </div>
                    </a>
                  </div>
                  <div class="related-entry-content">
                    <h4 class="related-entry-title">
                      <a href="https://localhost/web_production/ria/377/">
                        TITLETITLETITLETITLETITLETITLE
                      </a>
                    </h4>
                    <p class="related-entry-snippet">TEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXT</p>
                  </div>
                </section>
                <section class="related-entry">
                  <div class="related-entry-thumb">
                    <a href="#" >
                      <div class="photo">
                        <img width="814" height="432" src="/images/sample1.jpg" class="attachment-thumb100 size-thumb100 wp-post-image" alt="sample1">
                      </div>
                    </a>
                  </div>
                  <div class="related-entry-content">
                    <h4 class="related-entry-title">
                      <a href="https://localhost/web_production/ria/377/">
                        TITLETITLETITLETITLETITLETITLE
                      </a>
                    </h4>
                    <p class="related-entry-snippet">TEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXT</p>
                  </div>
                </section>
                <section class="related-entry">
                  <div class="related-entry-thumb">
                    <a href="#" >
                      <div class="photo">
                        <img width="814" height="432" src="/images/sample1.jpg" class="attachment-thumb100 size-thumb100 wp-post-image" alt="sample1">
                      </div>
                    </a>
                  </div>
                  <div class="related-entry-content">
                    <h4 class="related-entry-title">
                      <a href="https://localhost/web_production/ria/377/">
                        TITLETITLETITLETITLETITLETITLE
                      </a>
                    </h4>
                    <p class="related-entry-snippet">TEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXTTEXT</p>
                  </div>
                </section>
              </div>
              <br style="clear:both;">
            </div>

          </div>
          <div class="clearfix"></div>
          <div class="sns-buttons">
            <ul class="sns-button">
              <li><div class="fb-like" data-href="https://developers.facebook.com/docs/plugins/" data-width="" data-layout="button" data-action="like" data-size="small" data-share="true"></div></li>
              <li><a href="https://twitter.com/share" class="twitter-share-button">Tweet</a></li>
            </ul>
          </div>
          <div class="clearfix"></div>
          <div class="entry-meta">
            <i class="far fa-clock"></i>
            <time datetime="2020-03-02">2020年3月2日</time>
            <span> / </span>
            <span class="cat-data">
              <a href="#" rel="category tag">カテゴリー</a>
            </span>
            <span> / </span>
            <span class="post_comments_link">
              コメント数(0)
            </span>
          </div>
          <div class="entry-tags">
            <div class="section-tag">
              <ul><li>タグ： </li><li><a href="https://blog.isystk.com/tag/docker/" rel="tag">Docker</a></li><li><a href="https://blog.isystk.com/tag/java/" rel="tag">Java</a></li></ul>          </div>
          </div>
          
          <ul class="sns-buttons">
            <li class="share-twitter">
            <a href="http://twitter.com/intent/tweet?text=タイトル%20http://blog.isystk.com/" target="_blank" rel="noreferrer">Twitter</a>
            </li>
            <li class="share-facebook">
            <a href="https://www.facebook.com/sharer/sharer.php?u=http://blog.isystk.com/" target="_blank" rel="noreferrer">Facebook</a>
            </li>
            <li class="share-hatena">
            <a href="http://b.hatena.ne.jp/add?mode=confirm&url=http://blog.isystk.com/&title=タイトル" target="_blank" rel="noreferrer">はてブ</a>
            </li>
            <li class="share-pocket">
            <a href="http://getpocket.com/edit?url=http://blog.isystk.com/" target="_blank" rel="noreferrer">Pocket</a>
            </li>
            <li class="share-line">
            <a href="http://line.me/R/msg/text/?タイトル%0D%0Ahttp://blog.isystk.com/" target="_blank" rel="noreferrer">LINE</a>
            </li>
          </ul>
          <div class=" clearfix"></div>

          <div class="entry-comments">
            <div id="comment_area">
              <h3 id="comments">コメント</h3>
              <ol class="commets-list">
                  <li id="comment-3" class="comment byuser comment-author-iseyoshitaka bypostauthor even thread-even depth-1 parent">
                    <section id="div-comment-3" class="comment-body">
                      <footer class="comment-meta">
                        <div class="comment-author vcard">
                          <img alt="avatar" src="https://secure.gravatar.com/avatar/399bd217e4e44b521ed166ecd83085e4?s=48&amp;d=mm&amp;r=g" srcset="https://secure.gravatar.com/avatar/399bd217e4e44b521ed166ecd83085e4?s=96&amp;d=mm&amp;r=g 2x" class="avatar avatar-48 photo" height="48" width="48">						<b class="fn"><a href="https://blog.isystk.com/" rel="external nofollow ugc" class="url">iseyoshitaka</a></b> <span class="says">より:</span>		
                        </div><!-- .comment-author -->
              
                        <div class="comment-metadata">
                          <a href="https://localhost/web_production/wordpress/51/#comment-3">
                            <time datetime="2020-02-07T18:53:21+09:00">
                              2020年2月7日 6:53 PM							</time>
                          </a>
                        </div><!-- .comment-metadata -->
                      </footer><!-- .comment-meta -->
              
                      <div class="comment-content">
                        <p>hogehoge</p>
                      </div><!-- .comment-content -->
              
                      <div class="reply"><a rel="nofollow" class="comment-reply-link" href="https://localhost/web_production/wordpress/51/?replytocom=3#respond" data-commentid="3" data-postid="51" data-belowelement="div-comment-3" data-respondelement="respond" aria-label="iseyoshitaka に返信">返信</a></div>
            			  </section><!-- .comment-body -->
                  <ul class="children">
                  <li id="comment-4" class="comment odd alt depth-2 parent">
                    <section id="div-comment-4" class="comment-body">
                      <footer class="comment-meta">
                        <div class="comment-author vcard">
                          <img alt="avatar" src="https://secure.gravatar.com/avatar/d17e119c60ca8389c52cf7434d63ad93?s=48&amp;d=mm&amp;r=g" srcset="https://secure.gravatar.com/avatar/d17e119c60ca8389c52cf7434d63ad93?s=96&amp;d=mm&amp;r=g 2x" class="avatar avatar-48 photo" height="48" width="48">						<b class="fn">test</b> <span class="says">より:</span>					</div><!-- .comment-author -->
              
                        <div class="comment-metadata">
                          <a href="https://localhost/web_production/wordpress/51/#comment-4">
                            <time datetime="2020-04-27T17:55:44+09:00">
                              2020年4月27日 5:55 PM							</time>
                          </a>
                                    </div><!-- .comment-metadata -->
              
                                  <em class="comment-awaiting-moderation">あなたのコメントは管理者の承認待ちです。これはプレビューで、コメントは承認後に表示されます。</em>
                                </footer><!-- .comment-meta -->
              
                      <div class="comment-content">
                        <p>aaaa</p>
                      </div><!-- .comment-content -->
              
                      <div class="reply"><a rel="nofollow" class="comment-reply-link" href="https://localhost/web_production/wordpress/51/?replytocom=4#respond" data-commentid="4" data-postid="51" data-belowelement="div-comment-4" data-respondelement="respond" aria-label="test に返信">返信</a></div>			</section><!-- .comment-body -->
                  <ul class="children">
                  <li id="comment-6" class="comment even depth-3">
                    <section id="div-comment-6" class="comment-body">
                      <footer class="comment-meta">
                        <div class="comment-author vcard">
                          <img alt="avatar" src="https://secure.gravatar.com/avatar/d17e119c60ca8389c52cf7434d63ad93?s=48&amp;d=mm&amp;r=g" srcset="https://secure.gravatar.com/avatar/d17e119c60ca8389c52cf7434d63ad93?s=96&amp;d=mm&amp;r=g 2x" class="avatar avatar-48 photo" height="48" width="48">						<b class="fn">isystk</b> <span class="says">より:</span>					</div><!-- .comment-author -->
              
                        <div class="comment-metadata">
                          <a href="https://localhost/web_production/wordpress/51/#comment-6">
                            <time datetime="2020-04-27T17:56:48+09:00">
                              2020年4月27日 5:56 PM							</time>
                          </a>
                                    </div><!-- .comment-metadata -->
              
                                  <em class="comment-awaiting-moderation">あなたのコメントは管理者の承認待ちです。これはプレビューで、コメントは承認後に表示されます。</em>
                                </footer><!-- .comment-meta -->
              
                      <div class="comment-content">
                        <p>hoge</p>
                      </div><!-- .comment-content -->
              
                      <div class="reply"><a rel="nofollow" class="comment-reply-link" href="https://localhost/web_production/wordpress/51/?replytocom=6#respond" data-commentid="6" data-postid="51" data-belowelement="div-comment-6" data-respondelement="respond" aria-label="isystk に返信">返信</a></div>			</section><!-- .comment-body -->
                  </li><!-- #comment-## -->
              </ul><!-- .children -->
              </li><!-- #comment-## -->
              </ul><!-- .children -->
              </li><!-- #comment-## -->
                  <li id="comment-5" class="comment odd alt thread-odd thread-alt depth-1">
                    <section id="div-comment-5" class="comment-body">
                      <footer class="comment-meta">
                        <div class="comment-author vcard">
                          <img alt="avatar" src="https://secure.gravatar.com/avatar/d17e119c60ca8389c52cf7434d63ad93?s=48&amp;d=mm&amp;r=g" srcset="https://secure.gravatar.com/avatar/d17e119c60ca8389c52cf7434d63ad93?s=96&amp;d=mm&amp;r=g 2x" class="avatar avatar-48 photo" height="48" width="48">						<b class="fn">test</b> <span class="says">より:</span>					</div><!-- .comment-author -->
              
                        <div class="comment-metadata">
                          <a href="https://localhost/web_production/wordpress/51/#comment-5">
                            <time datetime="2020-04-27T17:56:11+09:00">
                              2020年4月27日 5:56 PM							</time>
                          </a>
                                    </div><!-- .comment-metadata -->
              
                                  <em class="comment-awaiting-moderation">あなたのコメントは管理者の承認待ちです。これはプレビューで、コメントは承認後に表示されます。</em>
                                </footer><!-- .comment-meta -->
              
                      <div class="comment-content">
                        <p>bbb</p>
                      </div><!-- .comment-content -->
              
                      <div class="reply"><a rel="nofollow" class="comment-reply-link" href="https://localhost/web_production/wordpress/51/?replytocom=5#respond" data-commentid="5" data-postid="51" data-belowelement="div-comment-5" data-respondelement="respond" aria-label="test に返信">返信</a></div>			</section><!-- .comment-body -->
                  </li><!-- #comment-## -->
              </ol>
                <div id="respond" class="comment-respond">
                  <h3 id="reply-title" class="comment-reply-title">コメントを残す <small><a rel="nofollow" id="cancel-comment-reply-link" href="/web_production/wordpress/51/#respond" style="display:none;">コメントをキャンセル</a></small></h3><form action="https://localhost/wp-comments-post.php" method="post" id="commentform" class="comment-form" novalidate="" _lpchecked="1"><p class="commentNotesBefore">入力エリアすべてが必須項目です。メールアドレスが公開されることはありません。</p><label>コメント<span class="require">*</span></label><p class="comment-form-comment"><textarea id="comment" name="comment" cols="50" rows="6" aria-required="true" placeholder="COMMENT"></textarea></p><p class="commentNotesAfter">内容をご確認の上、送信してください。</p><label>お名前<span class="require">*</span></label><p class="comment-form-author"><input id="author" name="author" type="text" value="" size="30" placeholder="your name"></p>
              <label>メールアドレス<span class="require">*</span></label><p class="comment-form-email"><input id="email" name="email" type="text" value="" size="30" placeholder="your email"></p>
              
              <p class="comment-form-cookies-consent"><input id="wp-comment-cookies-consent" name="wp-comment-cookies-consent" type="checkbox" value="yes"> <label for="wp-comment-cookies-consent">次回のコメントで使用するためブラウザーに自分の名前、メールアドレス、サイトを保存する。</label></p>
              <p class="form-submit"><input name="submit" type="submit" id="submit" class="submit" value="送信する"> <input type="hidden" name="comment_post_ID" value="51" id="comment_post_ID">
              <input type="hidden" name="comment_parent" id="comment_parent" value="0">
              </p></form>	</div><!-- #respond -->
            </div>
          </div>
        </section>

      </main>
      
      <!-- サイドメニュー -->
      <aside class="side-left" >
        <div id="sticky">
          <div id="sticky-navigator"></div>
        </div>
      </aside>

    </div>
  </div>
  
</template>

<script lang="ts">
import { Component, Vue } from "vue-property-decorator";
import ContentHeader from "@/components/ContentHeader.vue";

@Component({
  components: {
    ContentHeader
  }
})
export default class extends Vue {}
</script>
