<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN"
"http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
<html xmlns="http://www.w3.org/1999/xhtml">
<head>
<meta http-equiv="refresh" content="0; URL='https://gulcalikli.github.io'" />
<meta http-equiv="Content-Type" content="text/html; charset=UTF-8" />
<title>Gul Calikli's Home Page</title>
<script type="text/javascript">
function goToAnchor(anchor_name)
	{
    window.location.hash=anchor_name;
	window.scrollBy(0,-235);
	}
function expandAnnoucements()
	{
	var ann = document.getElementById('announcements');
	ann.className='expanded_ann';
	var gls = document.getElementById('glass_panel');
	gls.className='glass_active';
	document.body.className="no_scroll";	
	}
function shrinkAnnoucements()
	{
	var ann = document.getElementById('announcements');
	ann.className='normal_ann';
	var ann_list = document.getElementById('ann_list');
	ann_list.scrollTop = 0;		
	var gls = document.getElementById('glass_panel');
	gls.className='glass_deactive';	
	document.body.className="";
	}
</script>
<style type="text/css">
body, #header_back, .msel, .msel2 { background-color: #FCFCFF; }
h1, h2, .msel, .msel2 { border-radius: 15px;	}
h1, h2, h3, .msel, .msel2, #title  { font-family: Tahoma, Geneva, sans-serif; }
h1, h2 { font-size: 16px; }
h1, h2, h3, .msel, .msel2, #name, .bold { font-weight: bold; }
h1 { padding: 5px 15px; color: #F6F6F7; }
h1, .msel:hover { background-color: #202020; }
.msel2:hover { background-color: #202060; border-color: #202060; }
h3 { margin-left: 40px; font-style: italic; }
#content, #info, #menu { position: relative; }
h3, li, .msel, .msel2 { font-size: 14px; color: #202020; }
hr { border-width: thin 0 0 0; border-style: dashed none none none; border-color: #A0A0A0; margin-bottom: 280px}
#announcements hr { margin: 0 0 5px 0; padding: 0;}
ul { font-family: 'Palatino Linotype', 'Book Antiqua', Palatino, serif;  }
#title, #bbl { font-size: 15px; }
.msel:hover, .msel2:hover { color: #F6F6F7;  }
.sp { margin-bottom: 5px; }
.bbl { list-style-type: circle; }	
.ind { margin-left: 35px; }
.no_scroll { overflow: hidden;}
#info { display: inline-block; width: 510px; }
#info a, #more a, li a {color:#202080;}
#content { width: 940px;  margin: 240px 10px 20px 10px; }
#menu { width:550px; height:30px; }
#name { font-family: Arial, Helvetica, sans-serif; font-size: 26px;}
#title { font-style: italic; color: #303030; }
body { position: absolute; left: 50%; margin-top: 0px; margin-left:-480px; width:960px; padding: 0px; }
h2 { color: #202020; background-color: #E0E0E0;	margin-left: 35px; padding: 0px 10px; }
#header { background-color: #F6F6F7; z-index: 10; border: thin dashed #D0D0D0;margin-top: 10px;	padding: 10px; text-align: left;}
#header_back { margin-top: 0px; padding: 20px 10px 10px 10px; z-index: 9; }
#header, #header_back { position: fixed; display: block; width: 940px; height: 200px; }
#avatar { float: right;right: 10px; top: 10px; width: 350px; height:200px; }
#contact { display: block; margin-left: 20px; margin-top: 10px; font-family: Verdana, Geneva, sans-serif; 	font-size: 13px; }
.msel, .msel2 { display: inline-block; padding: 0px 0px; margin-top: 20px; margin-left: 0px; width: 100px; border: thin solid #202020; text-align: center; text-decoration: none; }
#interests {width: 940px; height: auto; display: inline-block; vertical-align: text-top;}
.normal_ann {width: 940px; max-height: 245px; display: inline-block; padding-bottom: 18px; vertical-align: text-top; font-size: 12px; overflow: hidden; }
.normal_ann #ann_list {max-height:175px; overflow: hidden; margin-top: -5px; }
.normal_ann #more { background: #222222; height: 16px; width: 915px; margin: 0 0 0 5px; padding: 0 0 6px 10px; border-width: 1px 2px 2px 1px; border-style: solid; border-color: #444444; border-radius: 0 0 5px 5px; z-index: 5; }
.normal_ann #more a { font-size: 16px; font-style: oblique; font-weight: 600; color: #fcfcfc; }
.normal_ann #more:hover { background: #fcfcfc; }
.normal_ann #more:hover a { color: #202080; }
.normal_ann h1 a { display: none; }
.normal_ann #spacer { display: none; }
.expanded_ann h1 a { float: right; width: 90px; border: 2px solid #FCFCFC; border-radius: 10px; margin: -2px 0 0 0; color: #fcfcfc; font-family: "Helvetica","Verdana","Arial","sans-serif"; text-align: center; font-size: 15px; text-decoration: none; padding: 3px 0 0 0; }
.expanded_ann h1 a:hover { border-color: #FCFCFC; background-color: #FCFCFC; color: #222222; }
.expanded_ann {position: fixed; right: 50%; width: 915px; height: 100%; margin-right:  -475px; display: inline-block; vertical-align: text-top; font-size: 11px; background-color: #ffffff; z-index: 20; padding: 15px; border: 2px solid #222222; border-radius: 5px; }
.expanded_ann #ann_list { height: 100%; margin-top: -10px; padding-top: 10px; overflow: scroll; }
.expanded_ann #more, .expanded_ann #more a { display: none; }
.expanded_ann #spacer { height: 300px; width: 100%; }
.list_item { position: relative; display: block; padding: 0;  margin: 0 5px; }
.list_item div p img { float: left; display: inline-block; padding: 0; vertical-align: text-top; }
.list_item div p { display: inline-block; min-height: 30px; border: thin solid #999999; font-family: "Palatino Linotype", "Book Antiqua", Palatino, serif; text-align: justify; }
.list_item div p a { color:#202080; }
.list_item div span { display: block; border: thin solid #333333; border-radius: 4px 4px 0 0; background: #444444; color: #FCFCF0; font-family: "Helvetica","Verdana","Arial","sans-serif"; text-align: center; }
.normal_ann div .list_item div p img { height: 24px; width: 24px; margin: 1px 6px 0 2px;}
.normal_ann div .list_item div p { width: 920px; margin: 0 0 2px 0; padding: 3px;  font-size: 12px; }
.normal_ann div .list_item div span { width: 58px; height: 12px; margin: 0 350px 0 0; border-radius: 4px 4px 0 0; padding: 2px 3px 0 3px; font-size: 11px;}
.expanded_ann div .list_item div p img { height: 45px; width: 45px; margin: 0 10px 0 0;}
.expanded_ann div .list_item div p { width: 865px; margin: 0 0 10px 0; padding: 10px; font-size: 14px; }
.expanded_ann div .list_item div span { width: 80px; height: 13px; margin: 0 770px 0 0; border-radius: 5px 5px 0 0; padding: 3px 15px 3px 15px; font-size: 14px;}
#glass_panel { position: fixed; background: #202020; opacity: 0.5; z-index: 12; }
.glass_active { background: #202020;top: 0; left: 0; width: 100%; height: 100%; }
.glass_deactive {background: none; top: -10000em; left: -10000em; width: 1px; height: 1px; }
</style>
<style type="text/css" media="print">
#header_back  { left: -1000em; top: -1000em; }
#header { position: relative; border: none; background: none; }
#menu, li a { display: none; }
#content { margin-top: 0; }
#info { position: relative; left: 0; top: 0; }
body { width: 900px; margin: 0; left: 0; }
a, #info a, li a { text-decoration: none; color: #000000; }
h1, h2 { background: none; border: none; color: #000000; }
hr { display: none; }
#interests { height: auto; }
#announcements { display: none; }
</style>
</head>
<body>
<div id="header" align="center">
<div id="info">
<span id="name">Handan Gul CALIKLI</span><br/>
<span id="title"> Post Doctoral Research Fellow 
@ The Open University</a>, <br/>  Department of Computing, Faculty of Maths, Computing and Technology, <br/>
Walton Hall, Milton Keynes MK7 6AA, United Kingdom </span><br/>
<span id="contact">E-mail: gul.calikli<img src="images/em.png" alt="" />open.ac.uk<br/>
Office: 2nd Floor, Jennie Lee Building<br/></span>
</div>
<img id="avatar" src="images/gul.png" alt="" />
<div id="menu">
<a class="msel" href="javascript:void(0);"
onclick="javascript:goToAnchor('interests');">
<span>Interests</span></a>
<a class="msel" href="javascript:void(0);"
onclick="javascript:goToAnchor('publications');">
<span>Publications</span></a>
<a class="msel" href="javascript:void(0);"
onclick="javascript:goToAnchor('education');">
<span>Education</span></a>
<a class="msel" href="javascript:void(0);"
onclick="javascript:goToAnchor('teaching');">
<span>Teaching</span></a>
<a class="msel2" href="download/Handan_Gul_CALIKLI_CV.pdf">
<span>Resume</span></a>
</div>
</div>
<div id="header_back"></div>
<div class="content" id="content">

<div id="announcements" class="normal_ann">
<h1>ANOUNCEMENTS<a href="javaScript:shrinkAnnoucements();">CLOSE</a></h1>
<div id="ann_list">
<?php 
if (file_exists('config/ann.txt')){
	$lines=file('config/ann.txt');
	include 'config/_listitems.php'; // List items
} 
?>
<div id="spacer">&nbsp;</div>
</div>
<p id="more" onclick="javascript:expandAnnoucements();">
<a href="javascript:expandAnnoucements();">more...</a>
</p>
</div>

<a name="interests"></a>
<div id="interests">
<h1>RESEARCH INTERESTS</h1>
<ul><li class="bbl">Empirical software engineering</li>
<li class="bbl">Human aspects in software engineering</li>
<li class="bbl">Mining Software Repositories</li>
<li class="bbl">Recommendation Systems for Software Engineering</li>
<li class="bbl">Software engineering for Privacy-aware Adaptive Systems</li></ul>
</div>

<a name="publications"></a>
<h1>PUBLICATIONS</h1>
<h2>Journals</h2>
<ul class="ind">
<li class="sp">G. Calikli and A. Bener, &ldquo;<a href="download/calikli_bener_SQJ_2015.pdf">Empirical Analysis of Factors Affecting Confirmation Bias Levels of Software Engineers</a>&ldquo;, (23)4:695-722, Software Quality Journal, 2015 (electronic access published on 2014)</li></ul>
<ul class="ind">
<li class="sp">G. Calikli and A. Bener, &ldquo;<a href="download/calikli_bener_SQJ2013.pdf">Influence of Confirmation Biases of Developers on Software Quality: An Empirical Study</a>&ldquo;, (21)2:377-416, Software Quality Journal, 2013 (electronic access published on 2012)</li></ul>




<h2>Invited Talks</h2>
<ul class="ind"><li>Microsoft Research Redmond, "Confirmation Bias as a Human Aspect in Software Engineering", January 16, 2013, Redmond, WA, USA. <a href="download/MSR_Talk_calikli_bener.pdf">Download slides</a> and <a href="http://research.microsoft.com/apps/video/default.aspx?id=180163"> Watch video</a> </li> </ul>
<ul class="ind"><li>York University, Lassonde Building (Dept. of Computer Science and Engineering Building), "Confirmation Bias in Software Engineering: Task Assignment and Handling Missing Data", March 26, 2013, Toronto, ON, Canada. <a href="download/York_Talk_calikli.pdf">Download slides</a> </li></ul>
<ul class="ind"><li>Gebze Institute of Technology, Department of Computer Engineering, "Modeling Human Aspects in Software Engineering", October 3, 2013, Cayirova, Kocaeli, Turkey.  </li></ul>
<ul class="ind"><li>Bournemouth University, Department of Computing and Informatics, "Elicitation of Privacy Requirements by Using Personas", February 23, 2014, Poole, Dorset, UK.  </li></ul>


<h2>Book Chapters</h2>
<ul class="ind">
<li class="sp">A. Bener, A. Tosun-Misirli, B. Caglayan, E. Kocaguneli and G. Calikli, &ldquo;"Lessons Learned from Software Analytics in Practice"&ldquo;, in "The Art and Science of Analyzing Software Data", Tim Menzies, Christian Bird and Thomas Zimmerman (Eds.), Morgan Kaufman Publishers, 2015.</li></ul>
<ul class="ind">
<li class="sp">A. Tosun-Misirli, A. Bener, B. Caglayan, G. Calikli and B. Turhan, &ldquo;"Part II. Evaluation: Field Studies"&ldquo;, in "Recommendation Systems in Software Engineering", Martin P. Robillard, Walid Maalej, Robert W. Walker and Thomas Zimmerman (Eds.), Springer, 2014.</li></ul>


<h2>Conferences</h2>
<ul class="ind">

<li class="sp"> G. Calikli, M. Law, A. K. Bandara, A. Russo, L. Dickens, B. A. Price, A. Stuart, M. Levine and B. Nuseibeh &ldquo;Privacy Dynamics: Learning Privacy Norms for Social Software &rdquo;,  11th International Symposium on Adaptive and Self-Managing Systems (SEAMS 2016), Austin, Texas, USA, May 16-17, 2016 (accepted). 
</li>

<li class="sp"> G. Calikli, M. S. Andersen, B. A. Price, A. K. Bandara and B. Nuseibeh &ldquo;Personal Informatics for Non-Geeks: Lessons Learned from Ordinary People &rdquo;,  Ubicomp Adjunct 2014, Seattle, Washington, USA, September 13-17, 2014. 
</li>

<li class="sp"> G. Calikli, A. Bener, T. Aytac and O. Bozcan &ldquo;<a href="download/calikli_et_al_ESEM2013.pdf">Towards a Metric Suite Proposal to Quantify Confirmation Biases of Developers</a> &rdquo;,  International Symposium on Empirical Software Engineering and Measurement (ESEM 2013), Industry Track (ESEM 2013), Baltimore, Maryland, USA, October 10-11, 2013. <b><font color="red">BEST PAPER AWARD (Best Industry Experience Paper)</font></b>
</li>

<li class="sp"> G. Calikli and A. Bener &ldquo;Analyzing the Effects of Confirmation Bias on Software Development Team
Performance: A Field Study during a Hackathon &rdquo;, 39th Euromicro Conference on Software Engineering and Advanced Applications, Work In Progress Track (SEAA 2013), Santander, Spain, September 4-6, 2013.
</li>

<li class="sp"> G. Calikli and A. Bener &ldquo;An Algorithmic Approach to Missing Data Problem in Modeling Human Aspects in Software Development &rdquo;, the 9th International Conference on Predictive Models in Software Engineering (PROMISE 2013), Baltimore, Maryland, USA, October, 2013.
</li>

<li class="sp"> B. Caglayan, G. Calikli, A. Bener, A. Tosun-Misirli, B. Turhan and T. Aytac &ldquo;Evaluating Dione: A Decision Support Tool for Software Development
&rdquo;, 2nd Workshop on User evaluations for Software Engineering Researchers (USER: ICSE 2013 Workshop) (non-archival paper), San Francisco, USA, May, 2013.
</li>

<li class="sp">G. Calikli and A. Bener, &ldquo;The Impact of Confirmation Bias on the Release-based Defect Prediction of Developer
Groups&rdquo;, 25th International Conference on Software Engineering and Knowledge Engineering (SEKE 2013),  Boston, USA, June, 2013.
</li><li class="sp">G. Calikli, B. Caglayan, A. Tosun Misirli and A. Bener, &ldquo;Modeling Human Aspects to Enhance Software Quality Management&rdquo;, 2012 International Conference on Information Systems (ICIS 2012),  Orlando Florida, USA, December, 2012.
</li><li class="sp"> B. Caglayan, A. Tosun Misirli, G. Calikli, T. Aytac, A. Bener and B. Turhan, &ldquo;Dione: An Integrated Measurement and Defect Prediction Solution&rdquo;, 20th International Symposium on Foundations of Software Engineering, Cary, North Carolina, USA, September, 2012.
</li><li class="sp">G. Calikli, and A. Bener, &ldquo;Empirical Analyses of the Factors Affecting Confirmation Bias and the Effects of Confirmation Bias on Software Developer/ Tester Performance&rdquo;, Promise 2010, Tmisoara, Romania, September, 12-13, 2010.
</li><li class="sp">G. Calikli, and A. Bener, &ldquo;Preliminary Analysis of the Effects of Confirmation Bias on Software Defect Density&rdquo;, ESEM 2010, Bozen, Italy, September, 16-17, 2010.
</li><li class="sp">G. Calikli, B. Arslan and A. Bener, &ldquo;Confirmation Bias in Software Development and Testing: An Analysis of the Effects of Company Size, Experience and Reasoning Skills&rdquo;, 22nd Annual Psychology of Programming Interest Group Workshop, 19-21 September 2010.
</li><li class="sp">G. Calikli, A. Bener, and B. Arslan, &ldquo;An Analysis of the Effects of Company Culture, Education and Experience on Confirmation Bias Levels of Software Developers and Testers&rdquo;, ICSE 2010, May 2-8, Cape Town.
</li><li class="sp">G. Calikli, A. Tosun, A. Bener, and M. Celik, &ldquo;The Effect of Granularity Level on Software Defect Prediction", Proceedings of the 24th International Symposium on Computer and Information Sciences (ISCIS 2009), pp. 531-536.
</li><li class="sp">O. Korcak, G. Calikli, I. Kaya and F. Alagöz, &ldquo;Performance Evaluation of Adaptive and Static Routing Algorithms and Contention Resolution Techniques in LEO Satellite Constellations&rdquo;, IEEE Recent Advances in Space Technologies RAST2005, June 2005, Istanbul, Turkey.
</li><li class="sp">G. Calikli and M. U. Caglayan, &ldquo;A Formal Policy Specification Language for an 802.11 WLAN with Enhanced Security Network”, Lecture Notes in Computer Science, Vol.3733, Proc. of the 20th International Symposium on Computer and Information Sciences, pp.183-192, Springer-Verlag, 2005.
</li></ul>


<h2>MS Thesis</h2>
<ul class="ind"><li>Gul Calikli, &ldquo;A Policy Specification Language for an 802.11WLAN with Enhanced Security Network&rdquo;, Department of Computer Engineering, Bogazici University, Istanbul, Turkey, 2004.</li></ul>
<h2>PhD Thesis</h2>
<ul class="ind"><li>Gul Calikli, &ldquo;Improving Performance of Defect Predictors Using Confirmation Bias Metrics&rdquo;, Department of Computer Engineering, Bogazici University, Istanbul, Turkey, 2012.</li></ul>

<a name="education"></a>
<h1>EDUCATION</h1>
<ul class="ind"><li><span class="bold">2005-2012</span>&nbsp;&nbsp;&nbsp;PhD,  Department of Computer Engineering, Bogazici University
</li><li><span class="bold">2002-2005</span>&nbsp;&nbsp;&nbsp;MS, Department of Computer Engineering, Bogazici University
</li><li><span class="bold">1996-2000</span>&nbsp;&nbsp;&nbsp;BS, Department of Mechanical Engineering, Bogazici University
</li></ul>
<h3>Summer Schools</h3>
<ul class="ind"><li><span class="bold">2006</span>&nbsp;&nbsp;&nbsp;Marktoberdorf Summer School on Software System Reliability and Security, August 1-13, Marktoberdorf, Munchen, Germany.</li></ul>

<a name="teaching"></a>
<h1>TEACHING EXPERIENCE</h1>

<h2> Teaching at Ryerson University (Fall 2012) </h2>

<h3> UNDERGRADUATE COURSE (Instructor)</h3>
<ul class="ind"><li><span class="bold">CITM 102:</span>&nbsp;&nbsp;&nbsp;Business Information Systems 1
</li> </ul>

<h3> GRADUATE COURSE (Teaching Assistant) </h3>
<ul class="ind"><li><span class="bold">MT 8103:</span>&nbsp;&nbsp;&nbsp;Research Methods 1
</li> </ul>

<h2>Assisted Courses at Bogazici University</h2>

<h3>UNDERGRADUATE COURSES</h3>
<ul class="ind"><li><span class="bold">CMPE 150:</span>&nbsp;&nbsp;&nbsp;Introduction to Computing (C)
</li><li><span class="bold">CMPE 150:</span>&nbsp;&nbsp;&nbsp;Introduction to Computing (Java)
</li><li><span class="bold">CMPE 160:</span>&nbsp;&nbsp;&nbsp;Introduction to Object Oriented Computing
</li><li><span class="bold">CMPE 300:</span>&nbsp;&nbsp;&nbsp;Analysis of Algorithms
</li><li><span class="bold">CMPE 322:</span>&nbsp;&nbsp;&nbsp;Operating Systems
</li><li><span class="bold">CMPE 344:</span>&nbsp;&nbsp;&nbsp;Computer Organization
</li><li><span class="bold">CMPE 352:</span>&nbsp;&nbsp;&nbsp;Fundamentals of Software Engineering
</li><li><span class="bold">CMPE 450:</span>&nbsp;&nbsp;&nbsp;Software Engineering
</li><li><span class="bold">CMPE 451:</span>&nbsp;&nbsp;&nbsp;Project Development in Software Engineering
</li><li><span class="bold">CMPE 475:</span>&nbsp;&nbsp;&nbsp;Computer Netwroks
</li><li><span class="bold">CMPE 476:</span>&nbsp;&nbsp;&nbsp;Distributed Systems</li></ul>

<h3>GRADUATE courses</h3>
<ul class="ind"><li><span class="bold">CMPE 550:</span>&nbsp;&nbsp;&nbsp;Advanced Topics in Software Engineering
</li><li><span class="bold">CMPE 58M:</span>&nbsp;&nbsp;&nbsp;Software Engineering Economics and Risk Management
</li><li><span class="bold">CMPE 589:</span>&nbsp;&nbsp;&nbsp;Software Quality Modeling</li></ul>
<br/><br/><hr/><br/>
</div>
<div id="glass_panel" class="glass_deactive" onclick="javaScript:shrinkAnnoucements();"></div>
</body>
</html>
