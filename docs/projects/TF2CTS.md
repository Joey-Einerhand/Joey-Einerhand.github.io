---
title: TF2 Chat Text to Speech
subtitle: In-game chat to speech converter with commands and filtering
project_type: "(.NET Console App)"
is_old_project: false
page_type: "project_for_frontpage"
banner_image: "/assets/images/tf2chattospeech/TF2CTSLogo.png"
display_priority: "3"
hide:
  - navigation
  - toc
---
<h1 class="text-center">[Console Application] TF2 Chat To Speech</h1>

<div class = "row justify-content-center">
  <img src="/assets/images/tf2chattospeech/UML.png" class="col-lg-10 rounded justify-content-center">
</div>

<br>

<div class="row justify-content-center">
  <p>You can view TF2 Chat To Speech on <a href="https://github.com/Joey-Einerhand/TF2ChatToSpeech" class="btn btn-primary">GitHub</a></p>
</div>

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