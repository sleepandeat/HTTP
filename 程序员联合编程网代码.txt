<html><head>
<meta http-equiv="Content-Type" content="text/html; charset=gb2312">
<LINK href="/inc/html.css" type=text/css rel=stylesheet>
<LINK href="/style.css" type=text/css rel=stylesheet>
<title>Eigenface_f 降维,主要用来降低图像的维度，来提高 识别率 Graph Recognize 图形/文字  230万源代码下载- www.pudn.com</title>
<script language="JavaScript">
function checkinput()
{
	if (document.form1.keyword.value=="")
	 {
		alert("请输入想查询的内容！");
		document.form1.keyword.focus();
		return false;
	 }
	 return true;
}
function openwin(keyword, se_type)
{
if(se_type =='pudn')
  window.open('/search_db.asp?keyword=' + keyword, 'search');
else
  window.open('http://www.google.com/custom?domains=www.pudn.com&q=' + keyword +'&sitesearch=www.pudn.com&client=pub-8055710228382273&forid=1&ie=GB2312&oe=GB2312&safe=active&cof=GALT%3A%23008000%3BGL%3A1%3BDIV%3A%23336699%3BVLC%3A663399%3BAH%3Acenter%3BBGC%3AFFFFFF%3BLBGC%3A336699%3BALC%3A0000FF%3BLC%3A0000FF%3BT%3A000000%3BGFNT%3A0000FF%3BGIMP%3A0000FF%3BFORID%3A1&hl=zh-CN', 'search');
}
function favor_add(t, id, n)
{
  window.open('/favor_add.asp?e=' + id +'&t=' + t +'&n=' + n, '添加收藏');
}
function fcomment_q(id, grade)
{
  window.open('/fcomment_q.asp?id=' + id + '&grade=' + grade, '评论');
}
function SetIFrameHeight(iframe_id, add_y)
{
  var bobo=document.getElementById(iframe_id);
   if (bobo && !window.opera)
   {
    if (bobo.contentDocument && bobo.contentDocument.body.offsetHeight){
     bobo.height = bobo.contentDocument.body.offsetHeight+add_y;
    }else if(bobo.Document && bobo.Document.body.scrollHeight){
     bobo.height = bobo.Document.body.scrollHeight+add_y;
    }
   }
}
function addrow(tbobj,frm){
 var row = tbobj.insertRow(1);
 var col = row.insertCell(0);
 col.innerHTML = '请输入留言或评论：<input type=text name=content size=45> <input name=sbt type=submit value=提交>';
 frm.content.focus();
 return false;
}
var down_id=2682071;
var type_id=126;
var nav_info=" &gt; <a class=tblink href='/download1.html'>Downloads</a> &gt; <a class=tblink href='/sourcecode/download2.html'>源码/资料</a> &gt; <a class=tblink href='/sourcecode/graph/download32.html'>图形图象</a> &gt; <a href=/sourcecode/graph/Recognize/download126.html>Graph Recognize</a> &gt; <B>Eigenface_f</B>";
var user_email='';
var en_url="http://en.pudn.com/downloads661/sourcecode/graph/text_recognize/detail2682071_en.html";
</script>
</head>
<body style='overflow-x:hidden;'>
<div class="wrapper">
<script language="JavaScript" type="text/javascript" src="/inc/detail.js"></script>
   <div class="pagebody2">
    <div id="detail_fname">
      &nbsp;文件名称: <B>Eigenface_f</B><a href="/dl.asp?id=2682071" target="_blank" rel="nofollow" title="下载文件. 不支持迅雷等多线程工具"><IMG height=16 src=/images/d_download.gif
      width=21 border="0">下载</a>&nbsp; <a href=# onclick="javascript:favor_add('3', '2682071', 'Eigenface_f - 降维,主要用来降低图像的维度，来提高图像识别率');" rel="nofollow">收藏√</a>&nbsp; [<a href=# onclick="javascript:fcomment_q('2682071', '100');" rel="nofollow"><img src=/images/thumbs_up.gif border=0 align="middle" alt="投票：非常好"></a>
&nbsp;<a href=# onclick="javascript:fcomment_q('2682071', '100');" title="投票：非常好" rel="nofollow">5</a> &nbsp;<a href=# onclick="javascript:fcomment_q('2682071', '85');" title="投票：还不错" rel="nofollow">4</a> &nbsp;<a href=# onclick="javascript:fcomment_q('2682071', '75');" title="投票：一般，勉强可用" rel="nofollow">3</a> &nbsp;<a href=# onclick="javascript:fcomment_q('2682071', '50');" title="投票：很一般" rel="nofollow">2</a> &nbsp;<a href=# onclick="javascript:fcomment_q('2682071', '3');" title="投票：太差了" rel="nofollow">1</a>&nbsp;<a href=# onclick="javascript:fcomment_q('2682071', '3');" rel="nofollow"><img src=/images/thumbs_down.gif border=0 align="middle" alt="投票：太差了"></a>]    </div>
    <div id="detail_info">
      <div id="detail_gg">
<script language="JavaScript">
show_ad("ad_detail_b");
</script>
      </div>
      <div id="detail_list">
        <div class="detail_listnamevalue">
        &nbsp;&nbsp;所属分类: <a href="/sourcecode/graph/Recognize/download126.html"><B>Graph Recognize</B></a>
        </div>
        <div class="detail_listnamevalue">
        &nbsp;&nbsp;开发工具: <B>matlab</B>
        </div>
        <div class="detail_listnamevalue">
        &nbsp;&nbsp;文件大小: 1 KB
        </div>
        <div class="detail_listnamevalue">
        &nbsp;&nbsp;上传时间: 2014-12-27
        </div>
        <div class="detail_listnamevalue">
        &nbsp;&nbsp;下载次数: 0
        </div>
        <div class="detail_listnamevalue">
        &nbsp;&nbsp;提 供 者: <a href=http://s.pudn.com/upload_log.asp?e=3643828 target=_blank>宋天成</a>
        </div>
      </div>
    </div>
    <div class="detail_line">
&nbsp;详细说明：<B>降维,主要用来降低图像的维度，来提高图像识别率-reduce the  dim</B><div id="clogin"></div>
    </div>
    <div class="detail_line">
      <B>文件列表</B>(点击判断是否您需要的文件，如果是垃圾请在下面评价投诉): <BR>
&nbsp;&nbsp;Eigenface_f.m<BR>    </div>
    <div id="detail_line">
<TABLE id=tb1 style="TABLE-LAYOUT: fixed; WORD-BREAK: break-all" cellSpacing=0 cellPadding=0 width="100%" border=0>
<TBODY>
<TR bgcolor=#F1F1F1>
<TD height=30>
请<font color=red>评价</font>：<a href=# onclick="javascript:fcomment_q('2682071', '100');" rel="nofollow">推荐↑</a>
&nbsp;<a href=# onclick="javascript:fcomment_q('2682071', '75');" rel="nofollow">一般</a>&nbsp;<a href=# onclick="javascript:fcomment_q('2682071', '5');" rel="nofollow">有密码</a>&nbsp;<a href=# onclick="javascript:fcomment_q('2682071', '40');" rel="nofollow">和说明不符</a>&nbsp;<a href=# onclick="javascript:fcomment_q('2682071', '10');" rel="nofollow">不是源码或资料</a>&nbsp;<a href=# onclick="javascript:fcomment_q('2682071', '20');" rel="nofollow">文件不全</a>
&nbsp;<a href=# onclick="javascript:fcomment_q('2682071', '0');" rel="nofollow">不能解压</a>&nbsp;<a href=# onclick="javascript:fcomment_q('2682071', '3');" rel="nofollow">纯粹是垃圾</a>
&nbsp;<a href=# onclick="javascript:addrow(tb1, addform);return false;" rel="nofollow">留言</a>
</TD>
</TR>
<FORM action=/fcomment_q.asp method=get name=addform target=_blank>
<input type=hidden name=id value=2682071>
<TR>
</FORM>
<TD>
</TD>
</tr>
<tr height=10><td></td></tr>
</tbody>
</table>
    </div>
<form name=frm_search2 action=/search_db.asp method=get>
    <div class="detail_line">
&nbsp;输入关键字，在本站230万海量源码库中尽情搜索：<INPUT maxLength=50 size=20 name=keyword value="">
<input  type=submit value="搜 索" name=_search2>&nbsp;<a href=/search_help.htm target=_blank>帮助</a>
    </div>
</form>
    <div class="detail_line">
&nbsp;<script language="JavaScript">
show_ad('ad_detail_c');
</script>
<BR>
    </div>
  </div>
<div id="rightSideBar">
<div class="dirList">
<TABLE cellSpacing=0 cellPadding=1 width=175 border=0 bgcolor=#F9F9F9>
<TBODY>
<TR bgColor=#D0D0D0><TD colSpan=2 height=1></TD></TR>
<TR bgcolor=#F0F0F0><TD height=22 colspan=2><div class=malign><img src=http://www.pudn.com/images/folderopen.gif> Graph Recognize</div></TD></TR>
<TR bgColor=#D0D0D0><TD colSpan=2 height=1></TD></TR>
<TR bgColor=#D0D0D0><TD colSpan=2 height=1></TD></TR>
<TR bgcolor=#F0F0F0><TD height=22 colspan=2><div class=malign><img src=http://www.pudn.com/images/folderopen.gif> 相关类别</div></TD></TR>
<TR bgColor=#D0D0D0><TD colSpan=2 height=1></TD></TR>
</table>
</div>
<div class="sidebar">
<p>
·<A href="/downloads563/sourcecode/graph/texture_mapping/detail2319851.html" target=_blank>用于块搜索模式的运动识别，包括所</A><BR>
·<A href="/downloads563/doc/detail2320230.html" target=_blank>一种关于车牌的最新提取算法，鲁棒</A><BR>
·<A href="/downloads565/sourcecode/others/detail2325528.html" target=_blank>马可波罗次世代验证码系统，自动识</A><BR>
·<A href="/downloads565/sourcecode/graph/text_recognize/detail2326143.html" target=_blank>是用于解决基于HMM的人脸识别算法中</A><BR>
·<A href="/downloads565/sourcecode/others/detail2326312.html" target=_blank>中控X628指纹机的各种二次开发demo</A><BR>
·<A href="/downloads567/sourcecode/windows/csharp/detail2332493.html" target=_blank>手写识别（HandWriting Recognition</A><BR>
·<A href="/downloads567/sourcecode/math/detail2334110.html" target=_blank>一个人脸检测的matlab代码，自带数</A><BR>
·<A href="/downloads568/sourcecode/graph/text_recognize/detail2335042.html" target=_blank>flann 快速近邻搜索 win64已编译好</A><BR>
·<A href="/downloads566/sourcecode/windows/other/detail2330299.html" target=_blank>vb手写识别，非常好用，识别快速，</A><BR>
·<A href="/downloads567/sourcecode/labview/detail2332673.html" target=_blank>自动识别系统图标，用于获取系统图</A><BR>
·<A href="/downloads566/sourcecode/windows/control/combobox/detail2330306.html" target=_blank>二维码识别程序，可直接在VB中使用</A><BR>
·<A href="/downloads565/sourcecode/graph/text_recognize/detail2327540.html" target=_blank>简单的图形识别，OCR开发包，能实现</A><BR>
·<A href="/downloads565/sourcecode/graph/text_recognize/detail2327795.html" target=_blank>本段程序实现简单验证码的分割，提</A><BR>
·<A href="/downloads565/sourcecode/delphi_control/detail2327877.html" target=_blank>该程序是关于中控集团的指纹检测器</A><BR>
·<A href="/downloads565/sourcecode/math/detail2327881.html" target=_blank>改程序是用C++ Builder编的指纹检测</A><BR>
·<A href="/downloads566/sourcecode/graph/detail2328056.html" target=_blank>人脸检测与识别训练图像，人脸图像</A><BR>
·<A href="/downloads566/sourcecode/math/detail2328873.html" target=_blank>鉴别一个移动物体,可以实现锁定目标</A><BR>
·<A href="/downloads566/sourcecode/windows/system/detail2328886.html" target=_blank>opencv 中的camshift实例，可以识别</A><BR>
·<A href="/downloads566/sourcecode/java/detail2330865.html" target=_blank>ocr图片文字识别技术,对图片中的文</A><BR>
·<A href="/downloads566/sourcecode/windows/other/detail2329532.html" target=_blank>统计文本单词，当然只是现实单间的</A><BR>
·<A href="/downloads62/sourcecode/graph/text_recognize/detail218502.html" target=_blank>支持向量机(SVM)实现的分类算法源码</A><BR>
·<A href="/downloads32/sourcecode/math/detail103739.html" target=_blank>人工智能OCR文字识别源程序,VB编写</A><BR>
·<A href="/downloads54/sourcecode/graph/text_recognize/detail187354.html" target=_blank>《Visual C++_MATLAB图像处理与识别</A><BR>
·<A href="/downloads69/sourcecode/graph/text_recognize/detail248412.html" target=_blank>这是利用VC++6.0开发的汽车车牌识别</A><BR>
·<A href="/downloads9/sourcecode/graph/text_recognize/detail34491.html" target=_blank>汽车牌照的自动定位和识别程序源代</A><BR>
·<A href="/downloads114/doc/detail476079.html" target=_blank>用matlab做车牌识别的研究生论文。</A><BR>
·<A href="/downloads183/sourcecode/graph/texture_mapping/detail856272.html" target=_blank>基于Opencv的人脸识别程序，人脸定</A><BR>
·<A href="/downloads62/sourcecode/graph/text_recognize/detail215515.html" target=_blank>该程序包含四种人脸识别优秀算法，P</A><BR>
·<A href="/downloads66/sourcecode/graph/texture_mapping/detail237251.html" target=_blank>小弟毕业设计:基于神经网络的车牌识</A><BR>
·<A href="/downloads111/sourcecode/graph/text_recognize/detail463248.html" target=_blank>用matlab做的车牌识别的完整源代码,</A><BR>
·<A href="/downloads28/sourcecode/windows/bitmap/detail88577.html" target=_blank>车牌定位识别程序，算法为先对车牌</A><BR>
·<A href="/downloads114/sourcecode/graph/text_recognize/detail477593.html" target=_blank>基于"pca+lda+粗糙集+模糊神经网络"</A><BR>
·<A href="/downloads33/sourcecode/graph/text_recognize/detail106896.html" target=_blank>一个简单、快速的图片识别代码，只</A><BR>
·<A href="/downloads22/sourcecode/windows/bitmap/detail72754.html" target=_blank>对图像分割及运动检测</A><BR>
·<A href="/downloads34/sourcecode/graph/text_recognize/detail108948.html" target=_blank>opencv是c语言编写的图像和视频处理</A><BR>
·<A href="/downloads115/sourcecode/graph/text_recognize/detail483538.html" target=_blank>用Vc++实现的人脸识别Demo程序。Ada</A><BR>
·<A href="/downloads32/sourcecode/graph/text_recognize/detail103640.html" target=_blank>目前该手写体识别系统主要分为 预处</A><BR>
·<A href="/downloads107/sourcecode/graph/text_recognize/detail440017.html" target=_blank>由于这段时间一直在学习ADABOOST，</A><BR>
·<A href="/downloads47/sourcecode/math/detail160089.html" target=_blank>指纹识别代码，经多次验证可靠，VC</A><BR>
·<A href="/downloads97/sourcecode/math/detail399168.html" target=_blank>非常优秀的文字识别程序，基于bp神</A><BR>
</TBODY></TABLE>
</p>
</div></div>
<div class="footer" align="center">
<a href=mailto:pudn@qq.com>联系站长</a> · <a href=/comment.asp?type_id=1010 target=_blank rel="nofollow">版权投诉</a> · <a href=/comment.asp?type_id=1010 target=_blank rel="nofollow">网站修改建议</a><br>
</span>  &copy; 2004-2010 <a href=http://www.pudn.com><font color=red>pudn.com</font></a> 湘ICP备07000446<br>
<script src="http://s117.cnzz.com/stat.php?id=1236358&web_id=1236358&show=pic" language="JavaScript" charset="gb2312"></script>
<script src="http://www.pudn.com/inc/tail.js" language="JavaScript"></script>
</body>
</html>
