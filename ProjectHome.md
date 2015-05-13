<blockquote>Main change of each version：<br>
<blockquote><ol>
<blockquote><li> Get PCM data from mic. </li>
<li> Encode with speex.</li>
<li> Package in flv format.</li>
<li> Publish audio to server.</li>
<li> Record both local and server side.</li>
<li> Play server side file with rtmp protocol on android.</li>
</blockquote></ol>
</blockquote>
<blockquote>主要包括下面几次迭代过程:<br>
<ol>
<blockquote><li> 使用android中的AudioRecord类，获取原始PCM数据. </li>
<li> 将PCM数据用speex编码.</li>
<li> 将编码后的数据打包录制成flv文件.</li>
<li> 使用android-rtmp-client库将编码，打包后的数据直接发布到流媒体服务器.</li>
<li> 本地与服务器端录音同时进行.</li>
<li> 在手机上通过rtmp协议回放服务器端录好的文件.</li>
</blockquote></ol>
</blockquote>