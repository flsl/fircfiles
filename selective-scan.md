注意我这个编译的whl不适合在RTX50系列显卡使用。<br>
编译环境：<br>
windows10 x64(用win11也行)<br>
vs2019（whl安装不需要安装这个）<br>
cmake==3.30.1（whl安装不需要安装这个）<br>
anaconda3+python3.10（必须要python3.10）<br>
cuda11.8.0+cudnn8.9.7(必须安装这个cuda和cudnn版本)<br>
RTX2070显卡（如果你是RTX50显卡则不能用该whl文件因为架构不一样）<br>
详细细节参考博文：https://blog.csdn.net/FL1623863129/article/details/151815993<br>
<table>
<thead><tr><th>版本名称</th><th>下载地址</th></tr></thead>
<tbody>
<tr><td>selective-scan-0.0.2-cp310-cp310-win-amd64.whl不含selective-scan-cuda-core</td><td><a href="https://mbd.pub/o/bread/YZWXmZtpaQ==">下载</a></td></tr>
<tr><td>selective-scan-0.0.2-cp310-cp310-win-amd64.whl包含selective-scan-cuda-core</td><td><a href="https://mbd.pub/o/bread/YZWXmZtpaA==">下载</a></td></tr>
</tbody>
</table>