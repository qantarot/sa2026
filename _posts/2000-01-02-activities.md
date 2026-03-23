---
title: "About"
bg: clrnew
color: about
fa-icon: info-circle
iconclr: '#428bca'
titleclr: '#428bca'
---

<center><img src="img/Stellenbosch_logo.png" style="height:300px;"></center>



<br>
<center><i class="fa fa-terminal fa-3x"></i></center>


<br>
<center><i class="fa-solid fa-palette fa-3x"></i></center>

<h3 style ="text-align: center;"> The theme for <span style="color:#63c4ca;">MRathon</span> will be low-field MRI.</h3> 


<hr>
 <h3>Speakers</h3>

 <p style ="text-align: center;  font-size:20px;"> Experts who specialize in implementing cutting-edge research into open-source projects will give tutorials and thought-provoking talks to inspire us! </p>

<div class="team" style="margin-top:10px;">
<div class="row" style="justify-content:center;">
{% for person in site.data.committee.speakers %}
<div class="col-sm-2">
<center>
<div class="team-player">
    <img src="{{ person.image }}" alt="Thumbnail Image" class="img-raised img-circle" style="width:100px;height:100px;border-radius: 50%;">
    <h5 class="title" style="color: black;">{{ person.name }}<br>
        <small class="text-muted" style="color: black;">{{ person.affiliation }}</small>
    </h5>
    <!-- <p style="color: darkgray;"> {{ person.affiliation }}</p> -->
</div>
</center>
</div>
  {% endfor %}

<div>
<div>
<hr>
<center>
 <h3>A sprint to push boundaries for collective creativity</h3>

 <p style ="text-align: center;  font-size:20px;">Participants who would like to work on a coding project are welcome to submit their project idea for making MRI research more accessible!</p>
</center>

