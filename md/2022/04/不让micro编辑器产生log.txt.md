<p>micro是一个很好用的命令行编辑器，但是默认安装每次都会生产烦人的log.txt，每次我都得自己用<code>rm</code>删除掉。我终于在互联网上找到了不生成log.txt的办法:</p>
<pre><code class="bash language-bash">curl https://getmic.ro | bash
sudo mv micro /usr/bin
</code></pre>
<p>普通下载的micro其实是测试版本，log.txt是开发者的debug信息。以上命令下载的是GitHub上的正式版。</p>