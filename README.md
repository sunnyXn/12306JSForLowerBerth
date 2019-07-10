# 12306JSForLowerBerth


用于123056网站上，选择下铺的js脚本，复制下面代码，添加到浏览器的书签栏，在选择上下铺界面点击标签使用。


javascript:(function(){var s=document.createElement('select');s.name='passenger_1_seat_detail_select';s.id='passenger_1_seat_detail_select';s.style='display:block';s.options[0]=new Option("随机","0");s.options[1]=new Option("上铺","3");s.options[2]=new Option("中铺","2");s.options[3]=new Option("下铺","1");s.onchange=function(){alert('1');setSeatDetail('1');};document.getElementById('seatType_1').after(s);})();


原html代码
<select name="passenger_1_seat_detail_select" style="display:block" id="passenger_1_seat_detail_select"onchange="setSeatDetail('1')"><option value="0">随机</option><option value="3">上铺</option><option value="2">中铺</option><option value="1">下铺</option></select>








