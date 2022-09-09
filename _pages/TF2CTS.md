---
title: (Console application) TF2 Chat to Speech
layout: default
permalink: /TF2CTS/
---
<h1 class="row justify-content-center"> [Console Application] TF2 Chat To Speech</h1>

<br>
<div class="row justify-content-center">
  <p>You can view TF2 Chat To Speech at the following link:</p>
</div>
<div class="row justify-content-around">
  <a href="https://github.com/Joey-Einerhand/TF2ChatToSpeech" class="btn btn-primary">GitHub link</a>
</div>

<br>

<div class = "row justify-content-center">
  <img src="/assets/Images/TF2CTS/UML.png" class="col-lg-10 rounded justify-content-center">
</div>

<br>
<p>
  TF2 Chat To Speech is a .NET framework application which reads the in-game text chat of a game called Team Fortress 2 and outputs it into the in-game voice chat. TF2CTS supports commands which users can write in-game in order for them to switch the speaker's voice and rate of speech.
</p>
<p>
  Some of the things I did:
</p>
<ul>
  <li>Designed the overall system couplings & data passthrough (Videogame -> Text file -> Program -> TTS -> audio device -> videogame) </li>
  <li>Implemented file reading whilst file is in-use</li>
  <li>Implemented text-filtering system</li>
  <li>Implemented text-command system (Chat messages could contain strings which edit the speed or voice of the text-to-speech bot)</li>
  <li> Implemented converting text to audio by using the NAudio framework and using text- and audiostreams</li>
</ul>

<p>The following tools and languages were used in this project:</p>
<ul>
  <li>C#</li>
  <li>.NET Framework</li>
  <li>NAudio Library</li>
</ul>