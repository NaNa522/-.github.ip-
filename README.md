# h1 消費カロリー計算

### h3 痩せ創価と一緒に消費カロリー計算せよう～＞＜


###### h6 ではでは：

 h8 次の中から出発点選んでみましょう
 
 
電車運賃
<SCRIPT language = "JavaScript">
<!--

//データ抽出
function calcFare(){
 kugiri = 5;
 departure = document.f.from.selectedIndex;
 arrival   = document.f.to.selectedIndex;
 document.f.resultwin.value = "";
 document.f.resultwin.value += "運賃は”
   + Fare[departure].substring(arrival*kugiri,arrival*kugiri + kugiri) 
   + "";
}

//料金データ
Fare = new Array();
Fare[0] = "   - 990";
Fare[1] = " 990   -";

//-->
</SCRIPT>

<FORM name = "f">
<TABLE><TR><TD>
どこから<BR>
<SELECT name = "from">
<OPTION>東京
<OPTION>上野
</SELECT></TD><TD>
どこへ<BR>
<SELECT name = "to">
<OPTION>東京
<OPTION>上野

</SELECT></TD></TR>
</TABLE><BR>
<INPUT type = "button" value = " 運賃を検索 "
 onClick = "calcFare()"><BR><BR>
<INPUT type = "text" name = "resultwin" size = 10>
</FORM>

