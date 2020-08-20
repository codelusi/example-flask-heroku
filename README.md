# Langkah deploy Flask ke Heroku

<!-- wp:paragraph {"fontSize":"medium"} -->
<p class="has-medium-font-size">Langkah pada Heroku</p>
<!-- /wp:paragraph -->

<!-- wp:list {"ordered":true,"type":"1"} -->
<ol type="1"><li>Membuat akun <a href="https://heroku.com">Heroku</a> dan menambahkan project baru.</li></ol>
<!-- /wp:list -->

<!-- wp:image {"id":58,"sizeSlug":"large"} -->
<figure class="wp-block-image size-large"><img src="http://codelusi.com/wp-content/uploads/2020/08/image-1-1024x497.png" alt="" class="wp-image-58"/></figure>
<!-- /wp:image -->

<!-- wp:list {"ordered":true,"type":"1","start":2} -->
<ol type="1" start="2"><li>Mengisikan nama app, region dan klik create app.</li></ol>
<!-- /wp:list -->

<!-- wp:image {"id":62,"sizeSlug":"large"} -->
<figure class="wp-block-image size-large"><img src="http://codelusi.com/wp-content/uploads/2020/08/image-2-1024x491.png" alt="" class="wp-image-62"/></figure>
<!-- /wp:image -->

<!-- wp:list {"ordered":true,"type":"1","start":3} -->
<ol type="1" start="3"><li>Install Heroku CLI, dapat di download <a href="https://cli-assets.heroku.com/heroku-x64.exe" data-type="URL" data-id="https://cli-assets.heroku.com/heroku-x64.exe">disini</a></li><li>Login ke Heroku CLI dengan command pada cmd:  <code>heroku login</code></li><li>Membuat Git Repository baru.<br>melakukan inisialisasi repositori git di direktori baru atau yang sudah ada<br><code>cd /myproject</code><br><code>git init</code><br><code>heroku git:remote -a codelusi-flask-heroku</code></li><li>Deploy flask pada heroku.<br>commit code ke repository dan deploy ke heroku menggunakan Git.<br><code>git add .</code><br><code>git commit -am "initial commit"</code><br><code>git push heroku master</code></li></ol>
<!-- /wp:list -->
