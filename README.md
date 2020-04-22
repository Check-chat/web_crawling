<!DOCTYPE html PUBLIC "-//W3C//DTD HTML 4.01//EN" "http://www.w3.org/TR/html4/strict.dtd">
<html>
  <head>
      <meta http-equiv="Content-Type" content="text/html; charset=utf-8">
      <meta name="generator" content="PhpSpreadsheet, https://github.com/PHPOffice/PhpSpreadsheet">
      <meta name="author" content="user" />
      <style type="text/css">
      html { font-family:Calibri, Arial, Helvetica, sans-serif; font-size:11pt; background-color:white }
      a.comment-indicator:hover + div.comment { background:#ffd; position:absolute; display:block; border:1px solid black; padding:0.5em }
      a.comment-indicator { background:red; display:inline-block; border:1px solid black; width:0.5em; height:0.5em }
      div.comment { display:none }
      table { border-collapse:collapse; page-break-after:always }
      .gridlines td { border:1px dotted black }
      .gridlines th { border:1px dotted black }
      .b { text-align:center }
      .e { text-align:center }
      .f { text-align:right }
      .inlineStr { text-align:left }
      .n { text-align:right }
      .s { text-align:left }
      td.style0 { vertical-align:middle; border-bottom:none #000000; border-top:none #000000; border-left:none #000000; border-right:none #000000; color:#000000; font-family:'맑은 고딕'; font-size:11pt; background-color:white }
      th.style0 { vertical-align:middle; border-bottom:none #000000; border-top:none #000000; border-left:none #000000; border-right:none #000000; color:#000000; font-family:'맑은 고딕'; font-size:11pt; background-color:white }
      td.style1 { vertical-align:middle; text-align:center; border-bottom:none #000000; border-top:none #000000; border-left:none #000000; border-right:none #000000; color:#000000; font-family:'맑은 고딕'; font-size:11pt; background-color:white }
      th.style1 { vertical-align:middle; text-align:center; border-bottom:none #000000; border-top:none #000000; border-left:none #000000; border-right:none #000000; color:#000000; font-family:'맑은 고딕'; font-size:11pt; background-color:white }
      td.style2 { vertical-align:middle; text-align:center; border-bottom:1px solid #000000 !important; border-top:1px solid #000000 !important; border-left:1px solid #000000 !important; border-right:1px solid #000000 !important; color:#000000; font-family:'맑은 고딕'; font-size:11pt; background-color:#E2EEDA }
      th.style2 { vertical-align:middle; text-align:center; border-bottom:1px solid #000000 !important; border-top:1px solid #000000 !important; border-left:1px solid #000000 !important; border-right:1px solid #000000 !important; color:#000000; font-family:'맑은 고딕'; font-size:11pt; background-color:#E2EEDA }
      td.style3 { vertical-align:middle; text-align:center; border-bottom:none #000000; border-top:1px solid #000000 !important; border-left:1px solid #000000 !important; border-right:1px solid #000000 !important; color:#000000; font-family:'맑은 고딕'; font-size:11pt; background-color:white }
      th.style3 { vertical-align:middle; text-align:center; border-bottom:none #000000; border-top:1px solid #000000 !important; border-left:1px solid #000000 !important; border-right:1px solid #000000 !important; color:#000000; font-family:'맑은 고딕'; font-size:11pt; background-color:white }
      td.style4 { vertical-align:middle; text-align:center; border-bottom:none #000000; border-top:none #000000; border-left:1px solid #000000 !important; border-right:1px solid #000000 !important; color:#000000; font-family:'맑은 고딕'; font-size:11pt; background-color:white }
      th.style4 { vertical-align:middle; text-align:center; border-bottom:none #000000; border-top:none #000000; border-left:1px solid #000000 !important; border-right:1px solid #000000 !important; color:#000000; font-family:'맑은 고딕'; font-size:11pt; background-color:white }
      td.style5 { vertical-align:middle; text-align:center; border-bottom:1px solid #000000 !important; border-top:none #000000; border-left:1px solid #000000 !important; border-right:1px solid #000000 !important; color:#000000; font-family:'맑은 고딕'; font-size:11pt; background-color:white }
      th.style5 { vertical-align:middle; text-align:center; border-bottom:1px solid #000000 !important; border-top:none #000000; border-left:1px solid #000000 !important; border-right:1px solid #000000 !important; color:#000000; font-family:'맑은 고딕'; font-size:11pt; background-color:white }
      td.style6 { vertical-align:middle; text-align:center; border-bottom:none #000000; border-top:1px solid #000000 !important; border-left:1px solid #000000 !important; border-right:1px solid #000000 !important; color:#000000; font-family:'맑은 고딕'; font-size:11pt; background-color:white }
      th.style6 { vertical-align:middle; text-align:center; border-bottom:none #000000; border-top:1px solid #000000 !important; border-left:1px solid #000000 !important; border-right:1px solid #000000 !important; color:#000000; font-family:'맑은 고딕'; font-size:11pt; background-color:white }
      td.style7 { vertical-align:middle; text-align:center; border-bottom:1px solid #000000 !important; border-top:1px solid #000000 !important; border-left:1px solid #000000 !important; border-right:none #000000; color:#000000; font-family:'맑은 고딕'; font-size:11pt; background-color:#E2EEDA }
      th.style7 { vertical-align:middle; text-align:center; border-bottom:1px solid #000000 !important; border-top:1px solid #000000 !important; border-left:1px solid #000000 !important; border-right:none #000000; color:#000000; font-family:'맑은 고딕'; font-size:11pt; background-color:#E2EEDA }
      td.style8 { vertical-align:middle; text-align:center; border-bottom:1px solid #000000 !important; border-top:1px solid #000000 !important; border-left:none #000000; border-right:none #000000; color:#000000; font-family:'맑은 고딕'; font-size:11pt; background-color:#E2EEDA }
      th.style8 { vertical-align:middle; text-align:center; border-bottom:1px solid #000000 !important; border-top:1px solid #000000 !important; border-left:none #000000; border-right:none #000000; color:#000000; font-family:'맑은 고딕'; font-size:11pt; background-color:#E2EEDA }
      td.style9 { vertical-align:middle; text-align:center; border-bottom:1px solid #000000 !important; border-top:1px solid #000000 !important; border-left:none #000000; border-right:1px solid #000000 !important; color:#000000; font-family:'맑은 고딕'; font-size:11pt; background-color:#E2EEDA }
      th.style9 { vertical-align:middle; text-align:center; border-bottom:1px solid #000000 !important; border-top:1px solid #000000 !important; border-left:none #000000; border-right:1px solid #000000 !important; color:#000000; font-family:'맑은 고딕'; font-size:11pt; background-color:#E2EEDA }
      td.style10 { vertical-align:middle; text-align:center; border-bottom:1px solid #000000 !important; border-top:1px solid #000000 !important; border-left:1px solid #000000 !important; border-right:none #000000; color:#000000; font-family:'맑은 고딕'; font-size:11pt; background-color:white }
      th.style10 { vertical-align:middle; text-align:center; border-bottom:1px solid #000000 !important; border-top:1px solid #000000 !important; border-left:1px solid #000000 !important; border-right:none #000000; color:#000000; font-family:'맑은 고딕'; font-size:11pt; background-color:white }
      td.style11 { vertical-align:middle; text-align:center; border-bottom:1px solid #000000 !important; border-top:1px solid #000000 !important; border-left:none #000000; border-right:none #000000; color:#000000; font-family:'맑은 고딕'; font-size:11pt; background-color:white }
      th.style11 { vertical-align:middle; text-align:center; border-bottom:1px solid #000000 !important; border-top:1px solid #000000 !important; border-left:none #000000; border-right:none #000000; color:#000000; font-family:'맑은 고딕'; font-size:11pt; background-color:white }
      td.style12 { vertical-align:middle; text-align:center; border-bottom:1px solid #000000 !important; border-top:1px solid #000000 !important; border-left:none #000000; border-right:1px solid #000000 !important; color:#000000; font-family:'맑은 고딕'; font-size:11pt; background-color:white }
      th.style12 { vertical-align:middle; text-align:center; border-bottom:1px solid #000000 !important; border-top:1px solid #000000 !important; border-left:none #000000; border-right:1px solid #000000 !important; color:#000000; font-family:'맑은 고딕'; font-size:11pt; background-color:white }
      td.style13 { vertical-align:middle; text-align:center; border-bottom:1px solid #000000 !important; border-top:1px solid #000000 !important; border-left:1px solid #000000 !important; border-right:none #000000; color:#000000; font-family:'맑은 고딕'; font-size:11pt; background-color:white }
      th.style13 { vertical-align:middle; text-align:center; border-bottom:1px solid #000000 !important; border-top:1px solid #000000 !important; border-left:1px solid #000000 !important; border-right:none #000000; color:#000000; font-family:'맑은 고딕'; font-size:11pt; background-color:white }
      td.style14 { vertical-align:middle; text-align:center; border-bottom:1px solid #000000 !important; border-top:1px solid #000000 !important; border-left:none #000000; border-right:none #000000; color:#000000; font-family:'맑은 고딕'; font-size:11pt; background-color:white }
      th.style14 { vertical-align:middle; text-align:center; border-bottom:1px solid #000000 !important; border-top:1px solid #000000 !important; border-left:none #000000; border-right:none #000000; color:#000000; font-family:'맑은 고딕'; font-size:11pt; background-color:white }
      td.style15 { vertical-align:middle; text-align:center; border-bottom:1px solid #000000 !important; border-top:1px solid #000000 !important; border-left:none #000000; border-right:1px solid #000000 !important; color:#000000; font-family:'맑은 고딕'; font-size:11pt; background-color:white }
      th.style15 { vertical-align:middle; text-align:center; border-bottom:1px solid #000000 !important; border-top:1px solid #000000 !important; border-left:none #000000; border-right:1px solid #000000 !important; color:#000000; font-family:'맑은 고딕'; font-size:11pt; background-color:white }
      td.style16 { vertical-align:middle; text-align:left; padding-left:0px; border-bottom:none #000000; border-top:none #000000; border-left:none #000000; border-right:none #000000; color:#000000; font-family:'맑은 고딕'; font-size:11pt; background-color:white }
      th.style16 { vertical-align:middle; text-align:left; padding-left:0px; border-bottom:none #000000; border-top:none #000000; border-left:none #000000; border-right:none #000000; color:#000000; font-family:'맑은 고딕'; font-size:11pt; background-color:white }
      td.style17 { vertical-align:middle; text-align:center; border-bottom:none #000000; border-top:none #000000; border-left:1px solid #000000 !important; border-right:1px solid #000000 !important; color:#000000; font-family:'맑은 고딕'; font-size:11pt; background-color:white }
      th.style17 { vertical-align:middle; text-align:center; border-bottom:none #000000; border-top:none #000000; border-left:1px solid #000000 !important; border-right:1px solid #000000 !important; color:#000000; font-family:'맑은 고딕'; font-size:11pt; background-color:white }
      td.style18 { vertical-align:middle; text-align:center; border-bottom:1px solid #000000 !important; border-top:1px solid #000000 !important; border-left:1px solid #000000 !important; border-right:none #000000; color:#000000; font-family:'맑은 고딕'; font-size:11pt; background-color:white }
      th.style18 { vertical-align:middle; text-align:center; border-bottom:1px solid #000000 !important; border-top:1px solid #000000 !important; border-left:1px solid #000000 !important; border-right:none #000000; color:#000000; font-family:'맑은 고딕'; font-size:11pt; background-color:white }
      table.sheet0 col.col0 { width:52.86666606pt }
      table.sheet0 col.col1 { width:52.18888829pt }
      table.sheet0 col.col2 { width:42.69999951pt }
      table.sheet0 col.col3 { width:42.69999951pt }
      table.sheet0 col.col4 { width:42.69999951pt }
      table.sheet0 col.col5 { width:353.12221817pt }
      table.sheet0 tr { height:33.6pt }
      table.sheet0 tr.row0 { height:33.6pt }
      table.sheet0 tr.row1 { height:33.6pt }
      table.sheet0 tr.row2 { height:33.6pt }
      table.sheet0 tr.row3 { height:33.6pt }
      table.sheet0 tr.row4 { height:33.6pt }
      table.sheet0 tr.row5 { height:33.6pt }
      table.sheet0 tr.row6 { height:33.6pt }
      table.sheet0 tr.row7 { height:33.6pt }
      table.sheet0 tr.row8 { height:33.6pt }
      table.sheet0 tr.row9 { height:33.6pt }
      table.sheet0 tr.row10 { height:33.6pt }
      table.sheet0 tr.row11 { height:33.6pt }
      table.sheet0 tr.row12 { height:33.6pt }
      table.sheet0 tr.row13 { height:33.6pt }
      table.sheet0 tr.row14 { height:33.6pt }
      table.sheet0 tr.row15 { height:33.6pt }
      table.sheet0 tr.row16 { height:33.6pt }
      table.sheet0 tr.row17 { height:33.6pt }
      table.sheet0 tr.row18 { height:33.6pt }
      table.sheet0 tr.row19 { height:33.6pt }
    </style>
  </head>

  <body>
 # web_crawling
 Web crawling for medical data collection
<style>
@page { margin-left: 0.7in; margin-right: 0.7in; margin-top: 0.75in; margin-bottom: 0.75in; }
body { margin-left: 0.7in; margin-right: 0.7in; margin-top: 0.75in; margin-bottom: 0.75in; }
</style>
    <table border="0" cellpadding="0" cellspacing="0" id="sheet0" class="sheet0 gridlines">
        <col class="col0">
        <col class="col1">
        <col class="col2">
        <col class="col3">
        <col class="col4">
        <col class="col5">
        <tbody>
          <tr class="row0">
            <td class="column0 style2 s">주요기능</td>
            <td class="column1 style2 s">분류</td>
            <td class="column2 style7 s style9" colspan="4">참고사이트</td>
          </tr>
          <tr class="row1">
            <td class="column0 style6 s style5" rowspan="6">1. 자가진단</td>
            <td class="column1 style6 s style5" rowspan="2">공공기관</td>
            <td class="column2 style10 s style12" colspan="4">&lt;자가진단 서울대학교&gt;<br />
https://hallym.hallym.or.kr/hallymuniv_sub.asp?left_menu=left_health&amp;screen=ptm803</td>
          </tr>
          <tr class="row2">
            <td class="column2 style10 s style12" colspan="4">&lt;건강체크리스트&gt;<br />
https://hallym.hallym.or.kr/hallymuniv_sub.asp?left_menu=left_health&amp;screen=ptm803</td>
          </tr>
          <tr class="row3">
            <td class="column1 style6 s style5" rowspan="2">공공데이터</td>
            <td class="column2 style10 s style12" colspan="4">&lt;만성염증 테스트&gt;<br />
https://wantmore.tistory.com/11</td>
          </tr>
          <tr class="row4">
            <td class="column2 style10 s style12" colspan="4">&lt;건강백과&gt;<br />
https://terms.naver.com/list.nhn?cid=50871&amp;categoryId=50871#%7B%22htShapeData%22%3A%7B%22mark%22%3A%22all%22%2C%22shape%22%3A%22all%22%2C%22color%22%3A%22all%22%2C%22form%22%3A%22all%22%2C%22line%22%3A%22all%22%7D%2C%22sRangeType%22%3A%22a%22%2C%22nPage%22%3A1%7D</td>
          </tr>
          <tr class="row5">
            <td class="column1 style6 s style5" rowspan="2">타기업</td>
            <td class="column2 style10 s style12" colspan="4">&lt;Google play COPD자가진단 시스템2&gt;<br />
https://play.google.com/store/apps/details?id=kr.hntcoms.self_test_for_control_group</td>
          </tr>
          <tr class="row6">
            <td class="column2 style13 null style15" colspan="4"></td>
          </tr>
          <tr class="row7">
            <td class="column0 style3 s style5" rowspan="7">2.병원추천<br />
및<br />
진료비</td>
            <td class="column1 style6 s style5" rowspan="3">공공기관</td>
            <td class="column2 style10 s style12" colspan="4">&lt;건강보험심평원&gt;<br />
https://www.hira.or.kr/rg/dur/form.do?pgmid=HIRAA030029000000#</td>
          </tr>
          <tr class="row8">
            <td class="column2 style10 null style12" colspan="4"></td>
          </tr>
          <tr class="row9">
            <td class="column2 style10 s style12" colspan="4">&lt;한국보건산업진흥원 보건산업동향&gt;<br />
https://www.khidi.or.kr/board?pageNum=1&amp;rowCnt=10&amp;menuId=MENU01783&amp;maxIndex=00488242389998&amp;minIndex=00001777199998&amp;schType=0&amp;schText=&amp;categoryId=&amp;continent=&amp;country=&amp;upDown=0&amp;boardStyle=&amp;no1=331</td>
          </tr>
          <tr class="row10">
            <td class="column1 style6 s style5" rowspan="2">공공데이터</td>
            <td class="column2 style10 s style12" colspan="4">&lt;보건의료빅데이터시스템&gt;<br />
https://opendata.hira.or.kr/home.do</td>
          </tr>
          <tr class="row11">
            <td class="column2 style10 s style12" colspan="4">&lt;비급여 진료비&gt;<br />
https://guri.hyumc.com/guri/guidance/nonPaymentItem.do</td>
          </tr>
          <tr class="row12">
            <td class="column1 style6 s style5" rowspan="2">타기업</td>
            <td class="column2 style10 s style12" colspan="4">&lt;진료별로 클릭시 진료하는 병원들 뜸&gt;<br />
http://medinavi.co.kr/medical_course/1.html</td>
          </tr>
          <tr class="row13">
            <td class="column2 style18 s style15" colspan="4">&lt;약국 찾기&gt;<br />
https://www.e-gen.or.kr/egen/search_pharmacy.do?searchType=map</td>
          </tr>
          <tr class="row14">
            <td class="column0 style3 s style5" rowspan="6">3.의약품<br />
처방내역<br />
및 <br />
복용시<br />
주의사항</td>
            <td class="column1 style6 s style5" rowspan="2">공공기관</td>
            <td class="column2 style10 s style12" colspan="4">&lt;의약품안전처&gt;<br />
https://nedrug.mfds.go.kr/pbp/CCBCA01</td>
          </tr>
          <tr class="row15">
            <td class="column2 style13 null style15" colspan="4"></td>
          </tr>
          <tr class="row16">
            <td class="column1 style6 s style5" rowspan="2">공공데이터</td>
            <td class="column2 style10 s style12" colspan="4">&lt;질병&amp;약복용시 주의사항&gt;<br />
https://opendata.hira.or.kr/op/opc/selectOpenDataList.do?sno=0&amp;publDataTpCd=&amp;searchCnd=&amp;searchWrd=&amp;pageIndex=1</td>
          </tr>
          <tr class="row17">
            <td class="column2 style10 s style12" colspan="4">&lt;약국비용 계산기&gt;<br />
https://www.hira.or.kr/rf/medicine/calculator/form.do?pgmid=HIRAA030037000000</td>
          </tr>
          <tr class="row18">
            <td class="column1 style6 s style5" rowspan="2">타기업</td>
            <td class="column2 style10 s style12" colspan="4">&lt; 드러그인포&gt;<br />
https://www.druginfo.co.kr/board/board_read.aspx?boardId=1001&amp;articleId=37192&amp;articleNum=17405&amp;startNum=17362&amp;maxNum=17382&amp;requestPage=2&amp;fileId=&amp;reqDirectory1=0&amp;reqDirectory2=0&amp;reqReply=0&amp;reqInterest=0&amp;BestPeople=&amp;</td>
          </tr>
          <tr class="row19">
            <td class="column2 style13 null style15" colspan="4"></td>
          </tr>
        </tbody>
    </table>
  </body>
</html>

 
