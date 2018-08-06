# jquery.media.js
#一款在线展示pdf文档的插件
#兼容ie，chrome，firefox，对移动端、pc端都友好
#使用
<a style="color: #007AFF;" href="javascript:;" onclick="clickpdf('judgement')">《人身保险伤残评定标准》</a>
#js部分
function clickpdf(msg){
  location.href= '../pdfshow/web/viewer.html?file='+msg+'.pdf'
//window.open('../pdfshow/web/viewer.html?file='+msg+'.pdf')
}
