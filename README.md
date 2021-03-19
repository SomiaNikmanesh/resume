# resume

#' Create a resume in HTML
#'
#' This output format is based on Min-Zhong Lu's HTML/CSS in the Github repo
#' \url{https://github.com/SomiaNikmanesh/resume}. See
#' \url{https://pagedown.rbind.io/resume/} for an example.
#' @param ...,css,template,number_sections,fig_caption See
#'   \code{\link{html_paged}()}.
#' @return An R Markdown output format.
#' @export
html_resume = function(
  ..., css = 'resume', template = pkg_resource('html', 'resume.html'),
  number_sections = FALSE, fig_caption = FALSE
) {
  html_format(
    ..., css = css, template = template, theme = NULL, number_sections = number_sections,
    fig_caption = fig_caption, .pagedjs = TRUE,
    .dependencies = list(rmarkdown::html_dependency_font_awesome())
  )
}

<!DOCTYPE html>
<html xmlns="http://www.w3.org/1999/xhtml">
  <head>
    <meta charset="utf-8" />
    <meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
    <meta name="generator" content="pandoc" />
    <meta name="viewport" content="width=device-width, initial-scale=1">

    <meta name="author" content="SOMIA NIKMANESH" />
    <meta name="date" content="2021-03-08" />
    <title>Somia Nikmanesh’s resume</title>

    
        <link rel='stylesheet' href='https://d33wubrfki0l68.cloudfront.net/bundles/2e18486fa627d748580c3c26fcf2ff69bce17bb9.css'/>
    
    
    <script src='https://d33wubrfki0l68.cloudfront.net/js/81137880424bdad8c51b06a67b458ec2b9265923/jss-paged_files/paged/js/config.js'></script>
    <script src='https://d33wubrfki0l68.cloudfront.net/bundles/21c695a6c1604bba8b80dea520fddc3223d71594.js'></script>
    
    
  </head>
  <body>

<div id="aside" class="section level1">
<h1>Aside</h1>
<div id="contact" class="section level2">
<h2>Contact Info</h2>
<ul>
<li><i class="fa fa-envelope"></i> <a href="/cdn-cgi/l/email-protection#4b272221222a65323e0b243e3f2724242065282426" class="email"><span class="__cf_email__" data-cfemail="7e121714171f50070b3e110b0a12111115501d1113">somi.nik.nz@gmail.com</span></a></li>
<li><i class="fab fa-linkedin-in"></i>https://www.linkedin.com/in/somia-nikmanesh-60932180/</li>
<li><i class="fa fa-phone"></i> 022 4194645</li>
</ul>
</div>
<div id="skills" class="section level2">
<h2>Skills</h2>
<ul>
<li><p>Highly skilled in SQL, SPSS, R, SAS, Advanced Excel(VBA).</p></li>
<li><p>Experienced in statistical analysis, statistical learning models, and optimization methods.</p></li>
<li><p>Robust experience in data interpretation and reporting techniques.</p></li>
<li><p>Excellent communication skills both written and verbal.</p></li>
<li><p>Planning and organizational skills.</p></li>
<li><p>Great interpersonal skills.</p></li>
<li><p>High attention to detail and ability to deliver high quality outputs to deadlines.</p></li>
</ul>
</div>
<div id="disclaimer" class="section level2">
<h2>Disclaimer</h2>

</div>
</div>
<div id="main" class="section level1">
<h1>Main</h1>
<div id="title" class="section level2">
<h2>SOMAYEH (SOMIA) NIKMANESH</h2>
<div id="currently-searching-for-a-phd-student-position" class="section level3">
<h3></h3>
<p>Data Analyst / Marketing Scientist with PhD in Mathematical statistics and over 5 years of successful market research experience using predictive modelling,  data processing, and data mining algorithms to solve challenging business problems. Strong problem-solving and analytical skills. Advanced programming proficiency. Passionate about deep reinforcement learning.</p>
</div>
</div>


<div id="professional-experience" class="section level2" data-icon="suitcase">
<h2> Professional Experience</h2>
<div id="Marketing-Scientist" class="section level3">
<h3>Marketing Scientist</h3>
<p>Colmar Brunton (A Kantar company)</p>
<p>Auckland, New Zealand</p>
<p>2019 - 2021</p>
<div class="concise">
<ul>
<li>Spot trends and correlation between business actions and business performance on different customer segments.</li>
<li>Analysis of customer satisfaction survey.</li>
<li>Manage on-going and ad-hoc analysis or data requests from business stakeholders.</li>
<li>Work closely with the client service team to translate internal briefs into analytical projects.  </li>
<li>Provide qualitative and quantitative analysis and insight to inform business strategy, marketing and brand strategies.</li>
<li>Synthesising data and analysis into impactful, action- oriented reports for internal stakeholders.</li>
<li>Mine and analyze data from databases to drive optimization and improvement of marketing techniques and business strategies. </li>
</ul>
</div>
</div>
<div id="Data-Analyst" class="section level3">
<h3>Data Analyst</h3>
<p>Colmar Brunton (A Kantar company)</p>
<p>Auckland, New Zealand</p>
<p>2015 - 2021</p>
<div class="concise">
<ul>
<li>Writes data collection / data analysis scripts. </li>		
<li>Works on scripting of Links, Adhoc projects and tracker round changes. </li>
<li>Manage communication with client services team around the impact of changes to client deliverables.</li>
<li>Executes a final quality check/validation on client database deliverables to ensure client requirements have been executed as expected prior to delivery.</li>
<li>Use online based reporting tools to deliver information to clients.</li>
</ul>
</div>
</div>

<div id="Research-Analyst" class="section level3">
<h3>Research Analyst</h3>
<p>UM Institute of Research Management and Monitoring (Malaysia’s leading research university with a high international ranking in the world in research area)</p>
<p>Kuala Lumpur, Malaysia</p>
<p>2012 - 2014</p>
<div class="concise">
<ul>
<li>Working as a part of the team on a project on “Outlier Detection in Time Series model”.</li>
<li>Create, manipulate, and merge large and complex data sets.</li>
<li>Interpret results, identify potential problems and their solutions.</li>
<li>Summarize and communicate results of analyses to the supervisor.</li>
</ul>
</div>
</div>
</div>
<div id="teaching-experience" class="section level2" data-icon="chalkboard-teacher">
<h2> Teaching Experience</h2>
<div id="introduction-to-r-language-for-beginners." class="section level3">
<h3>Lecturer</h3>
<p>Bostonweb College</p>
<p>Kuala Lumpur, Malaysia</p>
<p>2009 - 2012</p>
<p>Limkokwing College</p>
<ul>
<li> Writing lecture material and handouts as well as presenting information in lectures </li>
<li> Writing examination papers and marking examination papers for students</li>
</ul>
</div>
</div>



<div id="education" class="section level2" data-icon="graduation-cap" data-concise="true">
<h2> Education</h2>
<div id="Kuala Lumpur-University Malaya" class="section level3">
<h3>University Malaya</h3>
<p>PhD in Mathematical Statistics</p>
<p>Kuala Lumpur, Malaysia</p>
<p>2014</p>
<p>Thesis: Mixed Poisson Distribution with applications on insurance claim data</p>
<p> Key Achievements: </p>
<p>
<ul> 
<li>Fellowship Scheme award</li>
<li>Developed existing models for claim data</li> 
<li>Published papers in journals and presented at International Conferences</li>
</ul>
</p>
</div>
<div id="Tehran-Tarbiat Moallem University" class="section level3">
<h3>Tarbiat Moallem University</h3>
<p>M.Sc. in Mathematical Statistics</p>
<p>Tehran, Iran</p>
<p>2006</p>
<p>Thesis:Estimation of Ruin Probability Classical in The Presence of Heavy Tails</p>
</div>

<div id="Tehran-Azad Tehran University" class="section level3">
<h3>Azad Tehran University</h3>
<p>B.Sc. in Applied Mathematics</p>
<p>Tehran, Iran</p>
<p>2004</p>
</div>
</div>





<script data-cfasync="false" src="/cdn-cgi/scripts/5c5dd728/cloudflare-static/email-decode.min.js"></script><script>
(function() {
  var i, s, j, el, els;
  var create_el = function(type, className, content, isHTML) {
    var el = document.createElement(type);
    if (className) el.className = className;
    if (content) {
      if (isHTML) {el.innerHTML = content;} else {el.innerText = content;}
    }
    return el;
  }

  // replace h2 title with h1
  var title = document.getElementById('title').querySelector('h2');
  title.parentNode.replaceChild(create_el('h1', false, title.innerHTML, true), title);

  // add the class .aside to #aside
  el = document.getElementById('aside');
  if (el) el.className += ' aside';

  // tweak class names of sections, and add icons
  els = document.getElementById('main').querySelectorAll('.level2');
  for (i = 0; i < els.length; i++) {
    el = els[i];
    if (i === 0 && el.id === 'title') continue;
    el.className += ' main-block';
    if (el.dataset['concise']) el.className += ' concise';
    // if there is no icon, add an icon:
    if (el.firstElementChild.firstChild && el.firstElementChild.firstChild.nodeName !== 'I') {
      s = el.dataset['icon'] || 'bookmark';
      el.firstElementChild.insertBefore(create_el('i', 'fa fa-' + s), el.firstElementChild.firstChild);
    }
  }

  // tweak class names of blocks in sections
  els = document.getElementById('main').querySelectorAll('.level3');
  for (i = 0; i < els.length; i++) {
    el = els[i];
    if (el.parentNode.id === 'title') continue;
    el.className += ' blocks';
    el.innerHTML = '<div class="date"></div>' + '<div class="decorator"></div>' +
      '<div class="details"><header></header><div></div></div>' + el.innerHTML;
    var ps = el.querySelectorAll('p');
    // move the date paragraph to the date div
    if (ps.length >= 3) {
      s = ps[2].innerText;
      s = s === 'N/A' ? [] : s.split(' - ');
      el.removeChild(ps[2]);
      for (j = 0; j < s.length && j < 2; j++) {
        el.children[0].appendChild(create_el('span', false, s[j]))
      }
    }
    // move title, description, location to the details div
    (function(h) {
      h.appendChild(el.children[3]);
      var p = el.children[3];  // description
      if (p.innerText !== 'N/A') {
        h.appendChild(create_el('span', 'place', p.innerHTML, true));
      }
      el.removeChild(p);
      p = el.children[3];  // location
      if (p.innerText !== 'N/A') {
        s = create_el('span', 'location', p.innerHTML, true);
        s.innerHTML = '<i class="fa fa-map-marker-alt"></i> ' + s.innerHTML;
        h.appendChild(s);
      }
      el.removeChild(p);
    })(el.children[2].firstElementChild);
    // move the rest of content in a block into the last div of the details div
    s = el.children[2];
    while (j = s.nextSibling) {
      if (j.className === 'aside') { s = j; continue; }
      el.children[2].lastElementChild.append(j);
    }
  }
})();
</script>


  </body>
 </html> 
