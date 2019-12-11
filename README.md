# dubboTest-V3.3.2
3.3.2dubbo接口测试
<!DOCTYPE html PUBLIC "-//W3C//DTD HTML 4.01 Transitional//EN">
<html>
<head>
<META http-equiv="Content-Type" content="text/html; charset=UTF-8">
<title>Load Test Results</title>
<style type="text/css">
				body {
					font:normal 68% verdana,arial,helvetica;
					color:#000000;
				}
				table tr td, table tr th {
					font-size: 68%;
				}
				table.details tr th{
				    color: #ffffff;
					font-weight: bold;
					text-align:center;
					background:#2674a6;
					white-space: nowrap;
				}
				table.details tr td{
					background:#eeeee0;
					white-space: nowrap;
				}
				h1 {
					margin: 0px 0px 5px; font: 165% verdana,arial,helvetica
				}
				h2 {
					margin-top: 1em; margin-bottom: 0.5em; font: bold 125% verdana,arial,helvetica
				}
				h3 {
					margin-bottom: 0.5em; font: bold 115% verdana,arial,helvetica
				}
				.Failure {
					font-weight:bold; color:red;
				}
				
	
				img
				{
				  border-width: 0px;
				}
				
				.expand_link
				{
				   position=absolute;
				   right: 0px;
				   width: 27px;
				   top: 1px;
				   height: 27px;
				}
				
				.page_details
				{
				   display: none;
				}
                                
                                .page_details_expanded
                                {
                                    display: block;
                                    display/* hide this definition from  IE5/6 */: table-row;
                                }


			</style>
<script language="JavaScript">
                           function expand(details_id)
			   {
			      
			      document.getElementById(details_id).className = "page_details_expanded";
			   }
			   
			   function collapse(details_id)
			   {
			      
			      document.getElementById(details_id).className = "page_details";
			   }
			   
			   function change(details_id)
			   {
			      if(document.getElementById(details_id+"_image").src.match("expand"))
			      {
			         document.getElementById(details_id+"_image").src = "collapse.png";
			         expand(details_id);
			      }
			      else
			      {
			         document.getElementById(details_id+"_image").src = "expand.png";
			         collapse(details_id);
			      } 
                           }
			</script>
</head>
<body>
<h1>Load Test Results</h1>
<table width="100%">
<tr>
<td align="left">Date report: 2019/12/11 14:17</td><td align="right">Designed for use with <a href="http://jmeter.apache.org/">JMeter</a> and <a href="http://ant.apache.org">Ant</a>.</td>
</tr>
</table>
<hr size="1">
<h2>Summary</h2>
<table width="95%" cellspacing="2" cellpadding="5" border="0" class="details" align="center">
<tr valign="top">
<th># Samples</th><th>Failures</th><th>Success Rate</th><th>Average Time</th><th>Min Time</th><th>Max Time</th>
</tr>
<tr valign="top" class="">
<td align="center">42</td><td align="center">0</td><td align="center">100.00%</td><td align="center">1503 ms</td><td align="center">6 ms</td><td align="center">11240 ms</td>
</tr>
</table>
<hr align="center" width="95%" size="1">
<h2>Pages</h2>
<table width="95%" cellspacing="2" cellpadding="5" border="0" class="details" align="center">
<tr valign="top">
<th>URL</th><th># Samples</th><th>Failures</th><th>Success Rate</th><th>Average Time</th><th>Min Time</th><th>Max Time</th><th></th>
</tr>
<tr valign="top" class="">
<td>getDocUserListByMobile获取用户基本信息</td><td align="center">1</td><td align="center">0</td><td align="right">100.00%</td><td align="right">10949 ms</td><td align="right">10949 ms</td><td align="right">10949 ms</td><td align="center"><a href="javascript:change('page_details_1')"><img alt="expand/collapse" src="expand.png" id="page_details_1_image"></a></td>
</tr>
<tr class="page_details" id="page_details_1">
<td bgcolor="#FF0000" colspan="8">
<div align="center">
<b>Details for Page "getDocUserListByMobile获取用户基本信息"</b>
<table width="95%" cellspacing="1" cellpadding="1" border="0" bgcolor="#2674A6" bordercolor="#000000">
<tr>
<th>Thread</th><th>Iteration</th><th>Time (milliseconds)</th><th>Bytes</th><th>Success</th>
</tr>
<tr>
<td>用户 3-1</td><td align="center">1</td><td align="right">10949</td><td align="right">382</td><td align="center">true</td>
</tr>
</table>
</div>
</td>
</tr>
<tr valign="top" class="">
<td>queryAreaById地区编号获取地区详情</td><td align="center">1</td><td align="center">0</td><td align="right">100.00%</td><td align="right">10945 ms</td><td align="right">10945 ms</td><td align="right">10945 ms</td><td align="center"><a href="javascript:change('page_details_2')"><img alt="expand/collapse" src="expand.png" id="page_details_2_image"></a></td>
</tr>
<tr class="page_details" id="page_details_2">
<td bgcolor="#FF0000" colspan="8">
<div align="center">
<b>Details for Page "queryAreaById地区编号获取地区详情"</b>
<table width="95%" cellspacing="1" cellpadding="1" border="0" bgcolor="#2674A6" bordercolor="#000000">
<tr>
<th>Thread</th><th>Iteration</th><th>Time (milliseconds)</th><th>Bytes</th><th>Success</th>
</tr>
<tr>
<td>地区 4-1</td><td align="center">1</td><td align="right">10945</td><td align="right">219</td><td align="center">true</td>
</tr>
</table>
</div>
</td>
</tr>
<tr valign="top" class="">
<td>根据id、secret获取app信息getAppInfo-正向测试</td><td align="center">1</td><td align="center">0</td><td align="right">100.00%</td><td align="right">10949 ms</td><td align="right">10949 ms</td><td align="right">10949 ms</td><td align="center"><a href="javascript:change('page_details_3')"><img alt="expand/collapse" src="expand.png" id="page_details_3_image"></a></td>
</tr>
<tr class="page_details" id="page_details_3">
<td bgcolor="#FF0000" colspan="8">
<div align="center">
<b>Details for Page "根据id、secret获取app信息getAppInfo-正向测试"</b>
<table width="95%" cellspacing="1" cellpadding="1" border="0" bgcolor="#2674A6" bordercolor="#000000">
<tr>
<th>Thread</th><th>Iteration</th><th>Time (milliseconds)</th><th>Bytes</th><th>Success</th>
</tr>
<tr>
<td>org机构名录 2-1</td><td align="center">1</td><td align="right">10949</td><td align="right">331</td><td align="center">true</td>
</tr>
</table>
</div>
</td>
</tr>
<tr valign="top" class="">
<td>getAppInfo获取app信息-正向测试</td><td align="center">1</td><td align="center">0</td><td align="right">100.00%</td><td align="right">10949 ms</td><td align="right">10949 ms</td><td align="right">10949 ms</td><td align="center"><a href="javascript:change('page_details_4')"><img alt="expand/collapse" src="expand.png" id="page_details_4_image"></a></td>
</tr>
<tr class="page_details" id="page_details_4">
<td bgcolor="#FF0000" colspan="8">
<div align="center">
<b>Details for Page "getAppInfo获取app信息-正向测试"</b>
<table width="95%" cellspacing="1" cellpadding="1" border="0" bgcolor="#2674A6" bordercolor="#000000">
<tr>
<th>Thread</th><th>Iteration</th><th>Time (milliseconds)</th><th>Bytes</th><th>Success</th>
</tr>
<tr>
<td>app 5-1</td><td align="center">1</td><td align="right">10949</td><td align="right">331</td><td align="center">true</td>
</tr>
</table>
</div>
</td>
</tr>
<tr valign="top" class="">
<td>getDocUserListByMobile获取用户基本信息-手机号必填项校验</td><td align="center">1</td><td align="center">0</td><td align="right">100.00%</td><td align="right">7 ms</td><td align="right">7 ms</td><td align="right">7 ms</td><td align="center"><a href="javascript:change('page_details_5')"><img alt="expand/collapse" src="expand.png" id="page_details_5_image"></a></td>
</tr>
<tr class="page_details" id="page_details_5">
<td bgcolor="#FF0000" colspan="8">
<div align="center">
<b>Details for Page "getDocUserListByMobile获取用户基本信息-手机号必填项校验"</b>
<table width="95%" cellspacing="1" cellpadding="1" border="0" bgcolor="#2674A6" bordercolor="#000000">
<tr>
<th>Thread</th><th>Iteration</th><th>Time (milliseconds)</th><th>Bytes</th><th>Success</th>
</tr>
<tr>
<td>用户 3-1</td><td align="center">1</td><td align="right">7</td><td align="right">4</td><td align="center">true</td>
</tr>
</table>
</div>
</td>
</tr>
<tr valign="top" class="">
<td>getDocUserListByMobile获取用户基本信息-手机号不存在</td><td align="center">1</td><td align="center">0</td><td align="right">100.00%</td><td align="right">7 ms</td><td align="right">7 ms</td><td align="right">7 ms</td><td align="center"><a href="javascript:change('page_details_6')"><img alt="expand/collapse" src="expand.png" id="page_details_6_image"></a></td>
</tr>
<tr class="page_details" id="page_details_6">
<td bgcolor="#FF0000" colspan="8">
<div align="center">
<b>Details for Page "getDocUserListByMobile获取用户基本信息-手机号不存在"</b>
<table width="95%" cellspacing="1" cellpadding="1" border="0" bgcolor="#2674A6" bordercolor="#000000">
<tr>
<th>Thread</th><th>Iteration</th><th>Time (milliseconds)</th><th>Bytes</th><th>Success</th>
</tr>
<tr>
<td>用户 3-1</td><td align="center">1</td><td align="right">7</td><td align="right">4</td><td align="center">true</td>
</tr>
</table>
</div>
</td>
</tr>
<tr valign="top" class="">
<td>getUserOpenInfo获取用户子系统信息-正响测试</td><td align="center">1</td><td align="center">0</td><td align="right">100.00%</td><td align="right">11 ms</td><td align="right">11 ms</td><td align="right">11 ms</td><td align="center"><a href="javascript:change('page_details_7')"><img alt="expand/collapse" src="expand.png" id="page_details_7_image"></a></td>
</tr>
<tr class="page_details" id="page_details_7">
<td bgcolor="#FF0000" colspan="8">
<div align="center">
<b>Details for Page "getUserOpenInfo获取用户子系统信息-正响测试"</b>
<table width="95%" cellspacing="1" cellpadding="1" border="0" bgcolor="#2674A6" bordercolor="#000000">
<tr>
<th>Thread</th><th>Iteration</th><th>Time (milliseconds)</th><th>Bytes</th><th>Success</th>
</tr>
<tr>
<td>用户 3-1</td><td align="center">1</td><td align="right">11</td><td align="right">191</td><td align="center">true</td>
</tr>
</table>
</div>
</td>
</tr>
<tr valign="top" class="">
<td>queryAreaById地区编号获取地区详情-areaId必填项校验--缺少提示</td><td align="center">1</td><td align="center">0</td><td align="right">100.00%</td><td align="right">24 ms</td><td align="right">24 ms</td><td align="right">24 ms</td><td align="center"><a href="javascript:change('page_details_8')"><img alt="expand/collapse" src="expand.png" id="page_details_8_image"></a></td>
</tr>
<tr class="page_details" id="page_details_8">
<td bgcolor="#FF0000" colspan="8">
<div align="center">
<b>Details for Page "queryAreaById地区编号获取地区详情-areaId必填项校验--缺少提示"</b>
<table width="95%" cellspacing="1" cellpadding="1" border="0" bgcolor="#2674A6" bordercolor="#000000">
<tr>
<th>Thread</th><th>Iteration</th><th>Time (milliseconds)</th><th>Bytes</th><th>Success</th>
</tr>
<tr>
<td>地区 4-1</td><td align="center">1</td><td align="right">24</td><td align="right">6358</td><td align="center">true</td>
</tr>
</table>
</div>
</td>
</tr>
<tr valign="top" class="">
<td>getAppInfo获取app信息-子系统appId必传项校验</td><td align="center">1</td><td align="center">0</td><td align="right">100.00%</td><td align="right">28 ms</td><td align="right">28 ms</td><td align="right">28 ms</td><td align="center"><a href="javascript:change('page_details_9')"><img alt="expand/collapse" src="expand.png" id="page_details_9_image"></a></td>
</tr>
<tr class="page_details" id="page_details_9">
<td bgcolor="#FF0000" colspan="8">
<div align="center">
<b>Details for Page "getAppInfo获取app信息-子系统appId必传项校验"</b>
<table width="95%" cellspacing="1" cellpadding="1" border="0" bgcolor="#2674A6" bordercolor="#000000">
<tr>
<th>Thread</th><th>Iteration</th><th>Time (milliseconds)</th><th>Bytes</th><th>Success</th>
</tr>
<tr>
<td>app 5-1</td><td align="center">1</td><td align="right">28</td><td align="right">17725</td><td align="center">true</td>
</tr>
</table>
</div>
</td>
</tr>
<tr valign="top" class="">
<td>根据id、secret获取app信息getAppInfo-子系统秘钥必传项验证</td><td align="center">1</td><td align="center">0</td><td align="right">100.00%</td><td align="right">28 ms</td><td align="right">28 ms</td><td align="right">28 ms</td><td align="center"><a href="javascript:change('page_details_10')"><img alt="expand/collapse" src="expand.png" id="page_details_10_image"></a></td>
</tr>
<tr class="page_details" id="page_details_10">
<td bgcolor="#FF0000" colspan="8">
<div align="center">
<b>Details for Page "根据id、secret获取app信息getAppInfo-子系统秘钥必传项验证"</b>
<table width="95%" cellspacing="1" cellpadding="1" border="0" bgcolor="#2674A6" bordercolor="#000000">
<tr>
<th>Thread</th><th>Iteration</th><th>Time (milliseconds)</th><th>Bytes</th><th>Success</th>
</tr>
<tr>
<td>org机构名录 2-1</td><td align="center">1</td><td align="right">28</td><td align="right">17743</td><td align="center">true</td>
</tr>
</table>
</div>
</td>
</tr>
<tr valign="top" class="">
<td>getUserOpenInfo获取用户子系统信息-子系统编号必填项校验---缺少提示</td><td align="center">1</td><td align="center">0</td><td align="right">100.00%</td><td align="right">13 ms</td><td align="right">13 ms</td><td align="right">13 ms</td><td align="center"><a href="javascript:change('page_details_11')"><img alt="expand/collapse" src="expand.png" id="page_details_11_image"></a></td>
</tr>
<tr class="page_details" id="page_details_11">
<td bgcolor="#FF0000" colspan="8">
<div align="center">
<b>Details for Page "getUserOpenInfo获取用户子系统信息-子系统编号必填项校验---缺少提示"</b>
<table width="95%" cellspacing="1" cellpadding="1" border="0" bgcolor="#2674A6" bordercolor="#000000">
<tr>
<th>Thread</th><th>Iteration</th><th>Time (milliseconds)</th><th>Bytes</th><th>Success</th>
</tr>
<tr>
<td>用户 3-1</td><td align="center">1</td><td align="right">13</td><td align="right">7119</td><td align="center">true</td>
</tr>
</table>
</div>
</td>
</tr>
<tr valign="top" class="">
<td>areaCode2Name通过地区id转化为地区名称-省市区街道</td><td align="center">1</td><td align="center">0</td><td align="right">100.00%</td><td align="right">19 ms</td><td align="right">19 ms</td><td align="right">19 ms</td><td align="center"><a href="javascript:change('page_details_12')"><img alt="expand/collapse" src="expand.png" id="page_details_12_image"></a></td>
</tr>
<tr class="page_details" id="page_details_12">
<td bgcolor="#FF0000" colspan="8">
<div align="center">
<b>Details for Page "areaCode2Name通过地区id转化为地区名称-省市区街道"</b>
<table width="95%" cellspacing="1" cellpadding="1" border="0" bgcolor="#2674A6" bordercolor="#000000">
<tr>
<th>Thread</th><th>Iteration</th><th>Time (milliseconds)</th><th>Bytes</th><th>Success</th>
</tr>
<tr>
<td>地区 4-1</td><td align="center">1</td><td align="right">19</td><td align="right">44</td><td align="center">true</td>
</tr>
</table>
</div>
</td>
</tr>
<tr valign="top" class="">
<td>areaCode2Name通过地区id转化为地区名称-省市区</td><td align="center">1</td><td align="center">0</td><td align="right">100.00%</td><td align="right">9 ms</td><td align="right">9 ms</td><td align="right">9 ms</td><td align="center"><a href="javascript:change('page_details_13')"><img alt="expand/collapse" src="expand.png" id="page_details_13_image"></a></td>
</tr>
<tr class="page_details" id="page_details_13">
<td bgcolor="#FF0000" colspan="8">
<div align="center">
<b>Details for Page "areaCode2Name通过地区id转化为地区名称-省市区"</b>
<table width="95%" cellspacing="1" cellpadding="1" border="0" bgcolor="#2674A6" bordercolor="#000000">
<tr>
<th>Thread</th><th>Iteration</th><th>Time (milliseconds)</th><th>Bytes</th><th>Success</th>
</tr>
<tr>
<td>地区 4-1</td><td align="center">1</td><td align="right">9</td><td align="right">29</td><td align="center">true</td>
</tr>
</table>
</div>
</td>
</tr>
<tr valign="top" class="">
<td>getAppInfo获取app信息-子系统appId错误</td><td align="center">1</td><td align="center">0</td><td align="right">100.00%</td><td align="right">29 ms</td><td align="right">29 ms</td><td align="right">29 ms</td><td align="center"><a href="javascript:change('page_details_14')"><img alt="expand/collapse" src="expand.png" id="page_details_14_image"></a></td>
</tr>
<tr class="page_details" id="page_details_14">
<td bgcolor="#FF0000" colspan="8">
<div align="center">
<b>Details for Page "getAppInfo获取app信息-子系统appId错误"</b>
<table width="95%" cellspacing="1" cellpadding="1" border="0" bgcolor="#2674A6" bordercolor="#000000">
<tr>
<th>Thread</th><th>Iteration</th><th>Time (milliseconds)</th><th>Bytes</th><th>Success</th>
</tr>
<tr>
<td>app 5-1</td><td align="center">1</td><td align="right">29</td><td align="right">17725</td><td align="center">true</td>
</tr>
</table>
</div>
</td>
</tr>
<tr valign="top" class="">
<td>根据id、secret获取app信息getAppInfo-子系统secret错误</td><td align="center">1</td><td align="center">0</td><td align="right">100.00%</td><td align="right">31 ms</td><td align="right">31 ms</td><td align="right">31 ms</td><td align="center"><a href="javascript:change('page_details_15')"><img alt="expand/collapse" src="expand.png" id="page_details_15_image"></a></td>
</tr>
<tr class="page_details" id="page_details_15">
<td bgcolor="#FF0000" colspan="8">
<div align="center">
<b>Details for Page "根据id、secret获取app信息getAppInfo-子系统secret错误"</b>
<table width="95%" cellspacing="1" cellpadding="1" border="0" bgcolor="#2674A6" bordercolor="#000000">
<tr>
<th>Thread</th><th>Iteration</th><th>Time (milliseconds)</th><th>Bytes</th><th>Success</th>
</tr>
<tr>
<td>org机构名录 2-1</td><td align="center">1</td><td align="right">31</td><td align="right">17743</td><td align="center">true</td>
</tr>
</table>
</div>
</td>
</tr>
<tr valign="top" class="">
<td>getUserOpenInfo获取用户子系统信息-子系统密钥必填项校验</td><td align="center">1</td><td align="center">0</td><td align="right">100.00%</td><td align="right">27 ms</td><td align="right">27 ms</td><td align="right">27 ms</td><td align="center"><a href="javascript:change('page_details_16')"><img alt="expand/collapse" src="expand.png" id="page_details_16_image"></a></td>
</tr>
<tr class="page_details" id="page_details_16">
<td bgcolor="#FF0000" colspan="8">
<div align="center">
<b>Details for Page "getUserOpenInfo获取用户子系统信息-子系统密钥必填项校验"</b>
<table width="95%" cellspacing="1" cellpadding="1" border="0" bgcolor="#2674A6" bordercolor="#000000">
<tr>
<th>Thread</th><th>Iteration</th><th>Time (milliseconds)</th><th>Bytes</th><th>Success</th>
</tr>
<tr>
<td>用户 3-1</td><td align="center">1</td><td align="right">27</td><td align="right">19738</td><td align="center">true</td>
</tr>
</table>
</div>
</td>
</tr>
<tr valign="top" class="">
<td>areaCode2Name通过地区id转化为地区名称-省市</td><td align="center">1</td><td align="center">0</td><td align="right">100.00%</td><td align="right">7 ms</td><td align="right">7 ms</td><td align="right">7 ms</td><td align="center"><a href="javascript:change('page_details_17')"><img alt="expand/collapse" src="expand.png" id="page_details_17_image"></a></td>
</tr>
<tr class="page_details" id="page_details_17">
<td bgcolor="#FF0000" colspan="8">
<div align="center">
<b>Details for Page "areaCode2Name通过地区id转化为地区名称-省市"</b>
<table width="95%" cellspacing="1" cellpadding="1" border="0" bgcolor="#2674A6" bordercolor="#000000">
<tr>
<th>Thread</th><th>Iteration</th><th>Time (milliseconds)</th><th>Bytes</th><th>Success</th>
</tr>
<tr>
<td>地区 4-1</td><td align="center">1</td><td align="right">7</td><td align="right">20</td><td align="center">true</td>
</tr>
</table>
</div>
</td>
</tr>
<tr valign="top" class="">
<td>getUserOpenInfo获取用户子系统信息-userId用户编号必填项校验----缺少提示</td><td align="center">1</td><td align="center">0</td><td align="right">100.00%</td><td align="right">6 ms</td><td align="right">6 ms</td><td align="right">6 ms</td><td align="center"><a href="javascript:change('page_details_18')"><img alt="expand/collapse" src="expand.png" id="page_details_18_image"></a></td>
</tr>
<tr class="page_details" id="page_details_18">
<td bgcolor="#FF0000" colspan="8">
<div align="center">
<b>Details for Page "getUserOpenInfo获取用户子系统信息-userId用户编号必填项校验----缺少提示"</b>
<table width="95%" cellspacing="1" cellpadding="1" border="0" bgcolor="#2674A6" bordercolor="#000000">
<tr>
<th>Thread</th><th>Iteration</th><th>Time (milliseconds)</th><th>Bytes</th><th>Success</th>
</tr>
<tr>
<td>用户 3-1</td><td align="center">1</td><td align="right">6</td><td align="right">182</td><td align="center">true</td>
</tr>
</table>
</div>
</td>
</tr>
<tr valign="top" class="">
<td>areaCode2Name通过地区id转化为地区名称-省</td><td align="center">1</td><td align="center">0</td><td align="right">100.00%</td><td align="right">10 ms</td><td align="right">10 ms</td><td align="right">10 ms</td><td align="center"><a href="javascript:change('page_details_19')"><img alt="expand/collapse" src="expand.png" id="page_details_19_image"></a></td>
</tr>
<tr class="page_details" id="page_details_19">
<td bgcolor="#FF0000" colspan="8">
<div align="center">
<b>Details for Page "areaCode2Name通过地区id转化为地区名称-省"</b>
<table width="95%" cellspacing="1" cellpadding="1" border="0" bgcolor="#2674A6" bordercolor="#000000">
<tr>
<th>Thread</th><th>Iteration</th><th>Time (milliseconds)</th><th>Bytes</th><th>Success</th>
</tr>
<tr>
<td>地区 4-1</td><td align="center">1</td><td align="right">10</td><td align="right">11</td><td align="center">true</td>
</tr>
</table>
</div>
</td>
</tr>
<tr valign="top" class="">
<td>areaCode2Name通过地区id转化为地区名称-areaCodeString必填项校验--缺少提示</td><td align="center">1</td><td align="center">0</td><td align="right">100.00%</td><td align="right">9 ms</td><td align="right">9 ms</td><td align="right">9 ms</td><td align="center"><a href="javascript:change('page_details_20')"><img alt="expand/collapse" src="expand.png" id="page_details_20_image"></a></td>
</tr>
<tr class="page_details" id="page_details_20">
<td bgcolor="#FF0000" colspan="8">
<div align="center">
<b>Details for Page "areaCode2Name通过地区id转化为地区名称-areaCodeString必填项校验--缺少提示"</b>
<table width="95%" cellspacing="1" cellpadding="1" border="0" bgcolor="#2674A6" bordercolor="#000000">
<tr>
<th>Thread</th><th>Iteration</th><th>Time (milliseconds)</th><th>Bytes</th><th>Success</th>
</tr>
<tr>
<td>地区 4-1</td><td align="center">1</td><td align="right">9</td><td align="right">6938</td><td align="center">true</td>
</tr>
</table>
</div>
</td>
</tr>
<tr valign="top" class="">
<td>queryAreaListByParentId地区编号获取地区详情</td><td align="center">1</td><td align="center">0</td><td align="right">100.00%</td><td align="right">51 ms</td><td align="right">51 ms</td><td align="right">51 ms</td><td align="center"><a href="javascript:change('page_details_21')"><img alt="expand/collapse" src="expand.png" id="page_details_21_image"></a></td>
</tr>
<tr class="page_details" id="page_details_21">
<td bgcolor="#FF0000" colspan="8">
<div align="center">
<b>Details for Page "queryAreaListByParentId地区编号获取地区详情"</b>
<table width="95%" cellspacing="1" cellpadding="1" border="0" bgcolor="#2674A6" bordercolor="#000000">
<tr>
<th>Thread</th><th>Iteration</th><th>Time (milliseconds)</th><th>Bytes</th><th>Success</th>
</tr>
<tr>
<td>地区 4-1</td><td align="center">1</td><td align="right">51</td><td align="right">232</td><td align="center">true</td>
</tr>
</table>
</div>
</td>
</tr>
<tr valign="top" class="">
<td>queryAreaListByParentId地区编号获取地区详情-parentId必填项校验--缺少提示</td><td align="center">1</td><td align="center">0</td><td align="right">100.00%</td><td align="right">41 ms</td><td align="right">41 ms</td><td align="right">41 ms</td><td align="center"><a href="javascript:change('page_details_22')"><img alt="expand/collapse" src="expand.png" id="page_details_22_image"></a></td>
</tr>
<tr class="page_details" id="page_details_22">
<td bgcolor="#FF0000" colspan="8">
<div align="center">
<b>Details for Page "queryAreaListByParentId地区编号获取地区详情-parentId必填项校验--缺少提示"</b>
<table width="95%" cellspacing="1" cellpadding="1" border="0" bgcolor="#2674A6" bordercolor="#000000">
<tr>
<th>Thread</th><th>Iteration</th><th>Time (milliseconds)</th><th>Bytes</th><th>Success</th>
</tr>
<tr>
<td>地区 4-1</td><td align="center">1</td><td align="right">41</td><td align="right">2</td><td align="center">true</td>
</tr>
</table>
</div>
</td>
</tr>
<tr valign="top" class="">
<td>queryAreaByDeptId获取省市区3级下的街道列表</td><td align="center">1</td><td align="center">0</td><td align="right">100.00%</td><td align="right">43 ms</td><td align="right">43 ms</td><td align="right">43 ms</td><td align="center"><a href="javascript:change('page_details_23')"><img alt="expand/collapse" src="expand.png" id="page_details_23_image"></a></td>
</tr>
<tr class="page_details" id="page_details_23">
<td bgcolor="#FF0000" colspan="8">
<div align="center">
<b>Details for Page "queryAreaByDeptId获取省市区3级下的街道列表"</b>
<table width="95%" cellspacing="1" cellpadding="1" border="0" bgcolor="#2674A6" bordercolor="#000000">
<tr>
<th>Thread</th><th>Iteration</th><th>Time (milliseconds)</th><th>Bytes</th><th>Success</th>
</tr>
<tr>
<td>地区 4-1</td><td align="center">1</td><td align="right">43</td><td align="right">2432</td><td align="center">true</td>
</tr>
</table>
</div>
</td>
</tr>
<tr valign="top" class="">
<td>queryAreaByDeptId获取省市区3级下的街道列表-deptId必传项校验---缺少提示</td><td align="center">1</td><td align="center">0</td><td align="right">100.00%</td><td align="right">43 ms</td><td align="right">43 ms</td><td align="right">43 ms</td><td align="center"><a href="javascript:change('page_details_24')"><img alt="expand/collapse" src="expand.png" id="page_details_24_image"></a></td>
</tr>
<tr class="page_details" id="page_details_24">
<td bgcolor="#FF0000" colspan="8">
<div align="center">
<b>Details for Page "queryAreaByDeptId获取省市区3级下的街道列表-deptId必传项校验---缺少提示"</b>
<table width="95%" cellspacing="1" cellpadding="1" border="0" bgcolor="#2674A6" bordercolor="#000000">
<tr>
<th>Thread</th><th>Iteration</th><th>Time (milliseconds)</th><th>Bytes</th><th>Success</th>
</tr>
<tr>
<td>地区 4-1</td><td align="center">1</td><td align="right">43</td><td align="right">2</td><td align="center">true</td>
</tr>
</table>
</div>
</td>
</tr>
<tr valign="top" class="">
<td>queryCenterList获取全部筛查中心列表</td><td align="center">1</td><td align="center">0</td><td align="right">100.00%</td><td align="right">11240 ms</td><td align="right">11240 ms</td><td align="right">11240 ms</td><td align="center"><a href="javascript:change('page_details_25')"><img alt="expand/collapse" src="expand.png" id="page_details_25_image"></a></td>
</tr>
<tr class="page_details" id="page_details_25">
<td bgcolor="#FF0000" colspan="8">
<div align="center">
<b>Details for Page "queryCenterList获取全部筛查中心列表"</b>
<table width="95%" cellspacing="1" cellpadding="1" border="0" bgcolor="#2674A6" bordercolor="#000000">
<tr>
<th>Thread</th><th>Iteration</th><th>Time (milliseconds)</th><th>Bytes</th><th>Success</th>
</tr>
<tr>
<td>筛查中心 6-1</td><td align="center">1</td><td align="right">11240</td><td align="right">31161</td><td align="center">true</td>
</tr>
</table>
</div>
</td>
</tr>
<tr valign="top" class="">
<td>queryCenterList获取子系统下的筛查中心列表</td><td align="center">1</td><td align="center">0</td><td align="right">100.00%</td><td align="right">16 ms</td><td align="right">16 ms</td><td align="right">16 ms</td><td align="center"><a href="javascript:change('page_details_26')"><img alt="expand/collapse" src="expand.png" id="page_details_26_image"></a></td>
</tr>
<tr class="page_details" id="page_details_26">
<td bgcolor="#FF0000" colspan="8">
<div align="center">
<b>Details for Page "queryCenterList获取子系统下的筛查中心列表"</b>
<table width="95%" cellspacing="1" cellpadding="1" border="0" bgcolor="#2674A6" bordercolor="#000000">
<tr>
<th>Thread</th><th>Iteration</th><th>Time (milliseconds)</th><th>Bytes</th><th>Success</th>
</tr>
<tr>
<td>筛查中心 6-1</td><td align="center">1</td><td align="right">16</td><td align="right">1619</td><td align="center">true</td>
</tr>
</table>
</div>
</td>
</tr>
<tr valign="top" class="">
<td>queryCenterList获取子系统下的筛查中心列表--bug移除筛查中心后列表中仍查出来</td><td align="center">1</td><td align="center">0</td><td align="right">100.00%</td><td align="right">15 ms</td><td align="right">15 ms</td><td align="right">15 ms</td><td align="center"><a href="javascript:change('page_details_27')"><img alt="expand/collapse" src="expand.png" id="page_details_27_image"></a></td>
</tr>
<tr class="page_details" id="page_details_27">
<td bgcolor="#FF0000" colspan="8">
<div align="center">
<b>Details for Page "queryCenterList获取子系统下的筛查中心列表--bug移除筛查中心后列表中仍查出来"</b>
<table width="95%" cellspacing="1" cellpadding="1" border="0" bgcolor="#2674A6" bordercolor="#000000">
<tr>
<th>Thread</th><th>Iteration</th><th>Time (milliseconds)</th><th>Bytes</th><th>Success</th>
</tr>
<tr>
<td>筛查中心 6-1</td><td align="center">1</td><td align="right">15</td><td align="right">1619</td><td align="center">true</td>
</tr>
</table>
</div>
</td>
</tr>
<tr valign="top" class="">
<td>queryAreaListByParentId地区父级的id获取省下面的市级列表</td><td align="center">1</td><td align="center">0</td><td align="right">100.00%</td><td align="right">43 ms</td><td align="right">43 ms</td><td align="right">43 ms</td><td align="center"><a href="javascript:change('page_details_28')"><img alt="expand/collapse" src="expand.png" id="page_details_28_image"></a></td>
</tr>
<tr class="page_details" id="page_details_28">
<td bgcolor="#FF0000" colspan="8">
<div align="center">
<b>Details for Page "queryAreaListByParentId地区父级的id获取省下面的市级列表"</b>
<table width="95%" cellspacing="1" cellpadding="1" border="0" bgcolor="#2674A6" bordercolor="#000000">
<tr>
<th>Thread</th><th>Iteration</th><th>Time (milliseconds)</th><th>Bytes</th><th>Success</th>
</tr>
<tr>
<td>地区 4-1</td><td align="center">1</td><td align="right">43</td><td align="right">3710</td><td align="center">true</td>
</tr>
</table>
</div>
</td>
</tr>
<tr valign="top" class="">
<td>selectCenterByDeptCode科室编号获取筛查中心列表-正向测试</td><td align="center">1</td><td align="center">0</td><td align="right">100.00%</td><td align="right">9 ms</td><td align="right">9 ms</td><td align="right">9 ms</td><td align="center"><a href="javascript:change('page_details_29')"><img alt="expand/collapse" src="expand.png" id="page_details_29_image"></a></td>
</tr>
<tr class="page_details" id="page_details_29">
<td bgcolor="#FF0000" colspan="8">
<div align="center">
<b>Details for Page "selectCenterByDeptCode科室编号获取筛查中心列表-正向测试"</b>
<table width="95%" cellspacing="1" cellpadding="1" border="0" bgcolor="#2674A6" bordercolor="#000000">
<tr>
<th>Thread</th><th>Iteration</th><th>Time (milliseconds)</th><th>Bytes</th><th>Success</th>
</tr>
<tr>
<td>筛查中心 6-1</td><td align="center">1</td><td align="right">9</td><td align="right">418</td><td align="center">true</td>
</tr>
</table>
</div>
</td>
</tr>
<tr valign="top" class="">
<td>queryAreaListByParentId地区父级的id获取市下面的区级列表</td><td align="center">1</td><td align="center">0</td><td align="right">100.00%</td><td align="right">41 ms</td><td align="right">41 ms</td><td align="right">41 ms</td><td align="center"><a href="javascript:change('page_details_30')"><img alt="expand/collapse" src="expand.png" id="page_details_30_image"></a></td>
</tr>
<tr class="page_details" id="page_details_30">
<td bgcolor="#FF0000" colspan="8">
<div align="center">
<b>Details for Page "queryAreaListByParentId地区父级的id获取市下面的区级列表"</b>
<table width="95%" cellspacing="1" cellpadding="1" border="0" bgcolor="#2674A6" bordercolor="#000000">
<tr>
<th>Thread</th><th>Iteration</th><th>Time (milliseconds)</th><th>Bytes</th><th>Success</th>
</tr>
<tr>
<td>地区 4-1</td><td align="center">1</td><td align="right">41</td><td align="right">1849</td><td align="center">true</td>
</tr>
</table>
</div>
</td>
</tr>
<tr valign="top" class="">
<td>queryAreaListByParentId地区父级的id获取区下面的街道列表</td><td align="center">1</td><td align="center">0</td><td align="right">100.00%</td><td align="right">47 ms</td><td align="right">47 ms</td><td align="right">47 ms</td><td align="center"><a href="javascript:change('page_details_31')"><img alt="expand/collapse" src="expand.png" id="page_details_31_image"></a></td>
</tr>
<tr class="page_details" id="page_details_31">
<td bgcolor="#FF0000" colspan="8">
<div align="center">
<b>Details for Page "queryAreaListByParentId地区父级的id获取区下面的街道列表"</b>
<table width="95%" cellspacing="1" cellpadding="1" border="0" bgcolor="#2674A6" bordercolor="#000000">
<tr>
<th>Thread</th><th>Iteration</th><th>Time (milliseconds)</th><th>Bytes</th><th>Success</th>
</tr>
<tr>
<td>地区 4-1</td><td align="center">1</td><td align="right">47</td><td align="right">3082</td><td align="center">true</td>
</tr>
</table>
</div>
</td>
</tr>
<tr valign="top" class="">
<td>queryAreaListByParentId地区父级的id获取街道下面的列表</td><td align="center">1</td><td align="center">0</td><td align="right">100.00%</td><td align="right">43 ms</td><td align="right">43 ms</td><td align="right">43 ms</td><td align="center"><a href="javascript:change('page_details_32')"><img alt="expand/collapse" src="expand.png" id="page_details_32_image"></a></td>
</tr>
<tr class="page_details" id="page_details_32">
<td bgcolor="#FF0000" colspan="8">
<div align="center">
<b>Details for Page "queryAreaListByParentId地区父级的id获取街道下面的列表"</b>
<table width="95%" cellspacing="1" cellpadding="1" border="0" bgcolor="#2674A6" bordercolor="#000000">
<tr>
<th>Thread</th><th>Iteration</th><th>Time (milliseconds)</th><th>Bytes</th><th>Success</th>
</tr>
<tr>
<td>地区 4-1</td><td align="center">1</td><td align="right">43</td><td align="right">2</td><td align="center">true</td>
</tr>
</table>
</div>
</td>
</tr>
<tr valign="top" class="">
<td>getHospitalByDeptCode获取医院信息-正向测试</td><td align="center">1</td><td align="center">0</td><td align="right">100.00%</td><td align="right">603 ms</td><td align="right">603 ms</td><td align="right">603 ms</td><td align="center"><a href="javascript:change('page_details_33')"><img alt="expand/collapse" src="expand.png" id="page_details_33_image"></a></td>
</tr>
<tr class="page_details" id="page_details_33">
<td bgcolor="#FF0000" colspan="8">
<div align="center">
<b>Details for Page "getHospitalByDeptCode获取医院信息-正向测试"</b>
<table width="95%" cellspacing="1" cellpadding="1" border="0" bgcolor="#2674A6" bordercolor="#000000">
<tr>
<th>Thread</th><th>Iteration</th><th>Time (milliseconds)</th><th>Bytes</th><th>Success</th>
</tr>
<tr>
<td>org机构名录 2-1</td><td align="center">1</td><td align="right">603</td><td align="right">794</td><td align="center">true</td>
</tr>
</table>
</div>
</td>
</tr>
<tr valign="top" class="">
<td>getHospitalByDeptCode获取医院信息-code非必填项校验</td><td align="center">1</td><td align="center">0</td><td align="right">100.00%</td><td align="right">7 ms</td><td align="right">7 ms</td><td align="right">7 ms</td><td align="center"><a href="javascript:change('page_details_34')"><img alt="expand/collapse" src="expand.png" id="page_details_34_image"></a></td>
</tr>
<tr class="page_details" id="page_details_34">
<td bgcolor="#FF0000" colspan="8">
<div align="center">
<b>Details for Page "getHospitalByDeptCode获取医院信息-code非必填项校验"</b>
<table width="95%" cellspacing="1" cellpadding="1" border="0" bgcolor="#2674A6" bordercolor="#000000">
<tr>
<th>Thread</th><th>Iteration</th><th>Time (milliseconds)</th><th>Bytes</th><th>Success</th>
</tr>
<tr>
<td>org机构名录 2-1</td><td align="center">1</td><td align="right">7</td><td align="right">4</td><td align="center">true</td>
</tr>
</table>
</div>
</td>
</tr>
<tr valign="top" class="">
<td>getHosDeptByCode获取部门医院信息-正向测试</td><td align="center">1</td><td align="center">0</td><td align="right">100.00%</td><td align="right">8 ms</td><td align="right">8 ms</td><td align="right">8 ms</td><td align="center"><a href="javascript:change('page_details_35')"><img alt="expand/collapse" src="expand.png" id="page_details_35_image"></a></td>
</tr>
<tr class="page_details" id="page_details_35">
<td bgcolor="#FF0000" colspan="8">
<div align="center">
<b>Details for Page "getHosDeptByCode获取部门医院信息-正向测试"</b>
<table width="95%" cellspacing="1" cellpadding="1" border="0" bgcolor="#2674A6" bordercolor="#000000">
<tr>
<th>Thread</th><th>Iteration</th><th>Time (milliseconds)</th><th>Bytes</th><th>Success</th>
</tr>
<tr>
<td>org机构名录 2-1</td><td align="center">1</td><td align="right">8</td><td align="right">794</td><td align="center">true</td>
</tr>
</table>
</div>
</td>
</tr>
<tr valign="top" class="">
<td>queryDistrictByProvince获取省级下面的列表</td><td align="center">1</td><td align="center">0</td><td align="right">100.00%</td><td align="right">653 ms</td><td align="right">653 ms</td><td align="right">653 ms</td><td align="center"><a href="javascript:change('page_details_36')"><img alt="expand/collapse" src="expand.png" id="page_details_36_image"></a></td>
</tr>
<tr class="page_details" id="page_details_36">
<td bgcolor="#FF0000" colspan="8">
<div align="center">
<b>Details for Page "queryDistrictByProvince获取省级下面的列表"</b>
<table width="95%" cellspacing="1" cellpadding="1" border="0" bgcolor="#2674A6" bordercolor="#000000">
<tr>
<th>Thread</th><th>Iteration</th><th>Time (milliseconds)</th><th>Bytes</th><th>Success</th>
</tr>
<tr>
<td>地区 4-1</td><td align="center">1</td><td align="right">653</td><td align="right">1009</td><td align="center">true</td>
</tr>
</table>
</div>
</td>
</tr>
<tr valign="top" class="">
<td>queryDistrictByProvince获取省级下面的列表-provinceId省级id必填项验证---缺少提示</td><td align="center">1</td><td align="center">0</td><td align="right">100.00%</td><td align="right">57 ms</td><td align="right">57 ms</td><td align="right">57 ms</td><td align="center"><a href="javascript:change('page_details_37')"><img alt="expand/collapse" src="expand.png" id="page_details_37_image"></a></td>
</tr>
<tr class="page_details" id="page_details_37">
<td bgcolor="#FF0000" colspan="8">
<div align="center">
<b>Details for Page "queryDistrictByProvince获取省级下面的列表-provinceId省级id必填项验证---缺少提示"</b>
<table width="95%" cellspacing="1" cellpadding="1" border="0" bgcolor="#2674A6" bordercolor="#000000">
<tr>
<th>Thread</th><th>Iteration</th><th>Time (milliseconds)</th><th>Bytes</th><th>Success</th>
</tr>
<tr>
<td>地区 4-1</td><td align="center">1</td><td align="right">57</td><td align="right">2</td><td align="center">true</td>
</tr>
</table>
</div>
</td>
</tr>
<tr valign="top" class="">
<td>selectDeptAll获取部门列表-正向测试</td><td align="center">1</td><td align="center">0</td><td align="right">100.00%</td><td align="right">1377 ms</td><td align="right">1377 ms</td><td align="right">1377 ms</td><td align="center"><a href="javascript:change('page_details_38')"><img alt="expand/collapse" src="expand.png" id="page_details_38_image"></a></td>
</tr>
<tr class="page_details" id="page_details_38">
<td bgcolor="#FF0000" colspan="8">
<div align="center">
<b>Details for Page "selectDeptAll获取部门列表-正向测试"</b>
<table width="95%" cellspacing="1" cellpadding="1" border="0" bgcolor="#2674A6" bordercolor="#000000">
<tr>
<th>Thread</th><th>Iteration</th><th>Time (milliseconds)</th><th>Bytes</th><th>Success</th>
</tr>
<tr>
<td>org机构名录 2-1</td><td align="center">1</td><td align="right">1377</td><td align="right">4376382</td><td align="center">true</td>
</tr>
</table>
</div>
</td>
</tr>
<tr valign="top" class="">
<td>IBasicOrgService获取科室列表-正向测试</td><td align="center">1</td><td align="center">0</td><td align="right">100.00%</td><td align="right">981 ms</td><td align="right">981 ms</td><td align="right">981 ms</td><td align="center"><a href="javascript:change('page_details_39')"><img alt="expand/collapse" src="expand.png" id="page_details_39_image"></a></td>
</tr>
<tr class="page_details" id="page_details_39">
<td bgcolor="#FF0000" colspan="8">
<div align="center">
<b>Details for Page "IBasicOrgService获取科室列表-正向测试"</b>
<table width="95%" cellspacing="1" cellpadding="1" border="0" bgcolor="#2674A6" bordercolor="#000000">
<tr>
<th>Thread</th><th>Iteration</th><th>Time (milliseconds)</th><th>Bytes</th><th>Success</th>
</tr>
<tr>
<td>org机构名录 2-1</td><td align="center">1</td><td align="right">981</td><td align="right">4376382</td><td align="center">true</td>
</tr>
</table>
</div>
</td>
</tr>
<tr valign="top" class="">
<td>queryDeptByCenter获取部门列表-正向测试</td><td align="center">1</td><td align="center">0</td><td align="right">100.00%</td><td align="right">8 ms</td><td align="right">8 ms</td><td align="right">8 ms</td><td align="center"><a href="javascript:change('page_details_40')"><img alt="expand/collapse" src="expand.png" id="page_details_40_image"></a></td>
</tr>
<tr class="page_details" id="page_details_40">
<td bgcolor="#FF0000" colspan="8">
<div align="center">
<b>Details for Page "queryDeptByCenter获取部门列表-正向测试"</b>
<table width="95%" cellspacing="1" cellpadding="1" border="0" bgcolor="#2674A6" bordercolor="#000000">
<tr>
<th>Thread</th><th>Iteration</th><th>Time (milliseconds)</th><th>Bytes</th><th>Success</th>
</tr>
<tr>
<td>org机构名录 2-1</td><td align="center">1</td><td align="right">8</td><td align="right">2</td><td align="center">true</td>
</tr>
</table>
</div>
</td>
</tr>
<tr valign="top" class="">
<td>queryDeptByCenter获取医生科室信息-正向测试</td><td align="center">1</td><td align="center">0</td><td align="right">100.00%</td><td align="right">8 ms</td><td align="right">8 ms</td><td align="right">8 ms</td><td align="center"><a href="javascript:change('page_details_41')"><img alt="expand/collapse" src="expand.png" id="page_details_41_image"></a></td>
</tr>
<tr class="page_details" id="page_details_41">
<td bgcolor="#FF0000" colspan="8">
<div align="center">
<b>Details for Page "queryDeptByCenter获取医生科室信息-正向测试"</b>
<table width="95%" cellspacing="1" cellpadding="1" border="0" bgcolor="#2674A6" bordercolor="#000000">
<tr>
<th>Thread</th><th>Iteration</th><th>Time (milliseconds)</th><th>Bytes</th><th>Success</th>
</tr>
<tr>
<td>org机构名录 2-1</td><td align="center">1</td><td align="right">8</td><td align="right">238</td><td align="center">true</td>
</tr>
</table>
</div>
</td>
</tr>
<tr valign="top" class="">
<td>deptInfoMap获取科室医院信息-正向测试</td><td align="center">1</td><td align="center">0</td><td align="right">100.00%</td><td align="right">3724 ms</td><td align="right">3724 ms</td><td align="right">3724 ms</td><td align="center"><a href="javascript:change('page_details_42')"><img alt="expand/collapse" src="expand.png" id="page_details_42_image"></a></td>
</tr>
<tr class="page_details" id="page_details_42">
<td bgcolor="#FF0000" colspan="8">
<div align="center">
<b>Details for Page "deptInfoMap获取科室医院信息-正向测试"</b>
<table width="95%" cellspacing="1" cellpadding="1" border="0" bgcolor="#2674A6" bordercolor="#000000">
<tr>
<th>Thread</th><th>Iteration</th><th>Time (milliseconds)</th><th>Bytes</th><th>Success</th>
</tr>
<tr>
<td>org机构名录 2-1</td><td align="center">1</td><td align="right">3724</td><td align="right">3110758</td><td align="center">true</td>
</tr>
</table>
</div>
</td>
</tr>
</table>
<hr align="center" width="95%" size="1">
</body>
</html>

