---


---

<h1 id="第三届阿里云安全算法挑战赛-答辩">第三届阿里云安全算法挑战赛 答辩</h1>
<h2 id="季军-safety-first-第6名">季军 Safety First (第6名)</h2>
<h3 id="特征工程">特征工程</h3>
<ul>
<li>序列长度</li>
<li>进程数(tid_cnt)</li>
<li>每个 api 在调用序列里的的index 以及 index_ratio 的 describe 310<em>4</em>2 - api/</li>
<li>每个 api 调用间隔</li>
</ul>
<h3 id="ngram">ngram</h3>
<ul>
<li>原始序列， 做 1-gram 到5-gram</li>
<li>合连续重复调用， 再做 1-gram 到 3-gram</li>
</ul>
<p>但 LightGBM 的 feature importance 剔除后， 剩下约 2000 个特征</p>

