---
title: "Jingwen Lab - Team"
layout: gridlay
excerpt: "Jingwen Lab: Team members"
sitemap: false
permalink: /team/
---

<br/>
Jump to [Master students](#master), [Bachelor students](#bachelor), [Lab visitors](#lab-visitors), [Alumni](#alumni).

### Principle Investigator  
![]({{ site.url }}{{ site.baseurl }}/images/profile.jpg){: style="width: 130px; float: left; margin: 30px 30px 50px 15px;"}
<br/>
#### Jingwen Yan, Ph.D
*Associate Professor* <br/> 
*Program director, Bioinformatics* <br/> 
📧 [jingyan@iu.edu](mailto:jingyan@iu.edu)<br/>   

Dr. Jingwen Yan is an Associate Professor of Bioinformatics in the Department of Biomedical Engineering and Informatics at Indiana University Indianapolis (IUI). Her research interests include bioinformatics, machine learning, brain imaging genomics and systems biology, and the applications in Alzheimer’s and other complex diseases. 

### PhD Students
{% assign number_printed = 0 %}
{% for member in site.data.phd %}

{% assign even_odd = number_printed | modulo: 2 %}

<div class="row">

<div class="col-sm-12 clearfix">
  <div class="col-sm-2">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="100%" style="float: left" />
  </div>
  <div class="col-sm-10">
  <h4>{{ member.name }}</h4>
  <i> {{member.info}} </i> <br/>
  📧 [{{member.email}}](mailto:{{member.email}}) <br/>
  
  <ul style="overflow: hidden">

  {% if member.number_educ == 1 %}
  <li> {{ member.education1 }} </li>
  {% endif %}

  {% if member.number_educ == 2 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  {% endif %}

  {% if member.number_educ == 3 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  {% endif %}

  {% if member.number_educ == 4 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  {% endif %}

  {% if member.number_educ == 5 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  <li> {{ member.education5 }} </li>
  {% endif %}
  </ul>
    
  Research interest:{{member.research_interest}}
  </div>
</div>

{% assign number_printed = number_printed | plus: 1 %}

</div>

{% endfor %}


### Master Students<a name="master"></a>
{% for member in site.data.master %}

<div class="row">

<div class="col-sm-12 clearfix">
  <div class="col-sm-2">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="100%" style="float: left" />
  </div>
  <div class="col-sm-10">
  <h4>{{ member.name }}</h4>
  <i> {{member.info}} </i> <br/>
  📧 [{{member.email}}](mailto:{{member.email}}) <br/>
  
  <ul style="overflow: hidden">

  {% if member.number_educ == 1 %}
  <li> {{ member.education1 }} </li>
  {% endif %}

  {% if member.number_educ == 2 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  {% endif %}

  {% if member.number_educ == 3 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  {% endif %}

  {% if member.number_educ == 4 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  {% endif %}

  {% if member.number_educ == 5 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  <li> {{ member.education5 }} </li>
  {% endif %}
  </ul>
    
  Research interest:{{member.research_interest}}
  </div>
</div>

</div>

{% endfor %}

<!-- ## Bachelor Students<a name="bachelor"></a>

## Lab Visitors<a name="lab-visitors"></a> -->


### Alumni<a name="alumni"></a>

<!--<div class="row">
<div class="col-sm-12 clearfix"> -->
<table>
<colgroup>
  <col width="15%" />
  <col width="10%" />
  <col width="10%" />
</colgroup>
<tbody>
  {% for member in site.data.alumni %}
  <tr>
    <td>{{ member.name }}@{{ member.employment }}</td>
    <td>{{ member.degree }}</td>
    <td>{{ member.period }}</td>
  </tr>
  {% endfor %}
</tbody>
</table>  
<!--</div>
</div> -->
<br/><br/><br/>
