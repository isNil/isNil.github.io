---
layout: post
title: AFNetworking，MKNetworkKit，ASIHTTPRequest对比
tags: [iOS Three Library,转载]
---

AFNetworking、MKNetworkKit和ASIHTTPRequest对比


<table class="table table-bordered table-striped table-condensed">
<tr>
	<td>框架</td>
	<td>AFNetworking</td>
	<td>MKNetworkKit</td>
	<td>ASIHTTPRequest</td>
</tr>
<tr>
	<td>更新情况</td>
	<td>维护和使用者相对多</td>
	<td>维护和使用者相对少</td>
	<td>停止更新</td>
</tr>
<tr>
	<td>支持iOS和OSX</td>
	<td>是</td>
	<td>是</td>
	<td>是</td>
</tr>
<tr>
	<td>ARC</td>
	<td>是</td>
	<td>是</td>
	<td>否</td>
</tr>
<tr>
	<td>断点续传</td>
	<td>否，可通过AFDownloadRequestOperation</td>
	<td>是</td>
	<td>是</td>
</tr>
<tr>
	<td>同步异步请求</td>
	<td>只支持异步</td>
	<td>否</td>
	<td>是</td>
</tr>
<tr>
	<td>图片缓存到本地</td>
	<td>否，通过SDURLCache或AFCache</td>
	<td>否</td>
	<td>否</td>
</tr>
<tr>
	<td>图片缓存到内存</td>
	<td>是</td>
	<td>是</td>
	<td>否</td>
</tr>
<tr>
	<td>后台下载</td>
	<td>是</td>
	<td>是</td>
	<td>是</td>
</tr>
<tr>
	<td>下载进度</td>
	<td>否，可通过AFDownloadRequestOperation</td>
	<td>是</td>
	<td>是</td>
</tr>
<tr>
	<td>缓存离线请求</td>
	<td>否，通过SDURLCache或AFCache</td>
	<td>是</td>
	<td>否</td>
</tr>
<tr>
	<td>JSON、XML</td>
	<td>是</td>
	<td>是</td>
	<td>否</td>
</tr>
</table>

* 根据以上对比，AFNetworking虽然相比MKNetworkKit功能要弱一些，但是它的扩展性更强，而且维护者比较多，从长期来看要优于MKNetworkKit。
