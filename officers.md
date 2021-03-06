---
layout: page
title: Officers
---

## CSGSA Executive Board 

### CSGSA Chair

{::options parse_block_html="true" /}
<div class="container">
<div class="row">
<div class="col-sm-4">
{::options parse_block_html="true" /}
{%assign person = site.data.officers.chair%}
{%if person.photo%}
![{{person.name}}]({{person.photo}}){:height="300px"}
{%endif%}
{{person.name}}

Contact: {{person.contact}}
</div>

<div class="col-sm-8">
The chair's responsibilities are to:

1. Manage all open projects 
2. Run meetings of the CSGSA 
3. Arrange meetings and develop agenda 
4. Represent graduate students to Department and University where appropriate 
5. Assign responsibilities to members as appropriate 
</div>
</div>
</div>

### CSGSA Vice Chair

{::options parse_block_html="true" /}
<div class="container">
<div class="row">
<div class="col-sm-4">
{::options parse_block_html="true" /}
{%assign person = site.data.officers.vice_chair%}
{%if person.photo%}
![{{person.name}}]({{person.photo}}){:height="300px"}
{%endif%}
{{person.name}}

Contact: {{person.contact}}
</div>

<div class="col-sm-8">
The vice chair's responsibilities are to:

1. Run CSGSA meetings in the chairs absence 
2. Manage and maintain membership records 
3. Manage regular email communication with members and student body 
4. Be responsible for minutes of meetings 
5. Assist the Chair where necessary 
</div>
</div>
</div>

### CSGSA Treasurer

{::options parse_block_html="true" /}
<div class="container">
<div class="row">
<div class="col-sm-4">
{::options parse_block_html="true" /}
{%assign person = site.data.officers.treasurer%}
{%if person.photo%}
![{{person.name}}]({{person.photo}}){:height="300px"}
{%endif%}
{{person.name}}

Contact: {{person.contact}}
</div>

<div class="col-sm-8">
The treasurer's responsibilities are to:

1. Handle any and all financial matters 
2. Apply for funding each year from multiple sources 
3. Submit reimbursement forms when needed 
4. Assist the Chair where necessary 
5. Report regularly on financial status of the organization
</div>
</div>
</div>

### CSGSA Anti-racism and Inclusion Chair

{::options parse_block_html="true" /}
<div class="container">
<div class="row">
<div class="col-sm-4">
{::options parse_block_html="true" /}
{%assign person = site.data.officers.anti_racism_inclusion_chair%}
{%if person.photo%}
![{{person.name}}]({{person.photo}}){:height="300px"}
{%endif%}
{{person.name}}

Contact: {{person.contact}}
</div>

<div class="col-sm-8">
The Anti-racism and Inclusion Chairs's responsibilities are to:

1. Facilitate student-led discussions on making CU Boulder CS more inclusive and proactively anti-racist (in continuity)
2. Hold CSGSA accountable for actions we plan to take on community inclusivity 
3. Serve as a peer reporter for microaggressions by monitoring the student reporting form
4. Work with the Associate Chair of Inclusive Excellence and our undergraduate leadership to ensure CSGSA efforts are in conjunction with the department efforts on antiracism
5. These tasks may be delegated to other members by the responsible executive.
</div>
</div>
</div>

## Department Graduate Committee Student Reps

{::options parse_block_html="true" /}
<div class="container">
<div class="row">
{%for person in site.data.officers.grad_comm%}
<div class="col-sm-4">
{%if person.photo%}
![{{person.name}}]({{person.photo}}){:height="300px"}
{%endif%}
{{person.name}} 

Contact: {{person.contact}}
</div>
{%endfor%}
</div>
</div>

The Graduate Committee is charged with a broad range of graduate student affairs, both for Masters and PhD students. This committee reviews all applications for admission to the Masters and Doctoral programs in Computer Science. All problems regarding any proposed changes to both the Master’s program and the Ph.D. program are handled by this Graduate Committee. It is also responsible for defining course content, considering new course offerings, and other issues for the graduate degree programs. There are three student representatives on the Graduate Committee, two PhD students and one Masters student.

## Department Executive Committee Student Representative

{::options parse_block_html="true" /}
<div class="container">
<div class="row">
<div class="col-sm-4">
{::options parse_block_html="true" /}
{%assign person = site.data.officers.exec_comm%}
{%if person.photo%}
![{{person.name}}]({{person.photo}}){:height="300px"}
{%endif%}
{{person.name}}

Contact: {{person.contact}}
</div>

<div class="col-sm-8">
The student member of this committee is considered to be the senior student representative. This committee usually meets once a week and is concerned with all Department issues: budget, space, promotions, etc. The Executive Committee also reviews applications from prospective new faculty members. The student representative sits on both the Executive Committee and the Search Committee with one full vote. This position provides an excellent opportunity to see how an academic Department is really run. Sometimes the representative is required to poll graduate student opinion and is usually in charge of taking prospective new faculty members out to lunch with a group of graduate students.
</div>
</div>
</div>

## GPSG Student Reps

{::options parse_block_html="true" /}
<div class="container">
<div class="row">
<div class="col-sm-4">
{::options parse_block_html="true" /}
{%assign person = site.data.officers.gpsg%}
{%if person.photo%}
![{{person.name}}]({{person.photo}}){:height="300px"}
{%endif%}
{{person.name}}

Contact: {{person.contact}}
</div>

<div class="col-sm-8">
[The Graduate and Professional Student Government](https://www.colorado.edu/gpsg/) is the primary advocacy group for graduate and professional students on the CU Boulder campus. They are committed to enhancing the graduate student experience by interacting with CU administration and the University of Colorado Student Government (CUSG) concerning issues such as financial aid, graduate stipends, healthcare, tuition and fees and graduate student well-being. Graduate students from each department and program are solicited to serve on the GPSG Assembly, ensuring diverse representation of the graduate student body. We have an official voting GPSG representative, but any student can attend GPSG meetings. Meetings are held weekly on Wednesdays, from 4 - 5 PM.
</div>
</div>
</div>

# Alumni

We're sad to see you go! Thanks for all your help.

{% for position in site.data.officers.alumni %}
{{position.title}}
  {% for person in position.people %}
  * {{ person.years }} &raquo; {{ person.name }}
  {% endfor %}
{% endfor %}

