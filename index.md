---
title: hsh4you
id: index
---

## Du bist

<script> window.onload = function() { document.title = "hsh4you.de"; } </script>

<center>
<div class="flex-container" style="justify-content: space-around; max-width:400px">
  <div class="userselectioncontainer" onclick="updateImagesAndLists(this)">
    <img src="images/startpage/Jugendlicher.png">
    <img style="display:none" src="images/startpage/Jugendlicher_selected.png"><br>
    <span>Jugendlich</span>
  </div>
  <div class="userselectioncontainer" onclick="updateImagesAndLists(this)">
    <img src="images/startpage/Eltern.png">
    <img style="display:none" src="images/startpage/Eltern_selected.png"><br>
    <span>Mama/Papa</span>
  </div>
  <div class="userselectioncontainer" onclick="updateImagesAndLists(this)">
    <img src="images/startpage/Neu_in_Hsh.png">
    <img style="display:none" src="images/startpage/Neu_in_Hsh_selected.png"><br>
    <span>Neu in Hsh</span>
  </div>
  <div class="userselectioncontainer" onclick="updateImagesAndLists(this)">
    <img src="images/startpage/Senior.png">
    <img style="display:none" src="images/startpage/Senior_selected.png"><br>
    <span>Senior/in</span>
  </div>
</div>
</center>

## Du suchst
<div id="listVisible"></div>
<div class="displaynone" id="listDefault">
- <a class="calendar-link" href="calendar/calendar.html">Veranstaltungskalender</a>
- [Aktivitäten](Jugendklubs/top10_2.html)
- [Jugendklubs](Jugendklubs/Jugendklubs.html)
- [Wochenpläne](Jugendklubs/weeklyevents.html)
- [Freizeit](Freizeit/Freizeit.html)
- [Begegnungen](Begegnungen/Begegnungen.html)
- [Beratung](Beratung/Beratung.html)
- [Familienzentren](Familienzentren/Familienzentren.html)
- [Kitas](Kitas/Kitas.html)
- [Schulen](Schulen/Schulen.html)
- <a class="emergencycall-link" href="/Notrufnummern/Notrufnummern.html">Notrufnummern</a>
</div>
<div class="displaynone" id="listJugendlicher">
- <a class="calendar-link" href="calendar/calendar.html">Veranstaltungskalender</a>
- [Jugendklubs](Jugendklubs/Jugendklubs.html)
- [Wochenpläne](Jugendklubs/weeklyevents.html)
- [Aktivitäten](Jugendklubs/top10_2.html)
- [Freizeit](Freizeit/Freizeit.html)
- [Beratung](Beratung/Beratung_Jugendlicher.html)
- <a class="emergencycall-link" href="/Notrufnummern/Notrufnummern_Jugendlich.html">Notrufnummern</a>
</div>
<div class="displaynone" id="listEltern">
- <a class="calendar-link" href="calendar/calendar.html">Veranstaltungskalender</a>
- [Kitas](Kitas/Kitas.html)
- [Schulen](Schulen/Schulen.html)
- [Jugendklubs](Jugendklubs/Jugendklubs.html)
- [Beratung](Beratung/Beratung_Eltern.html)
- [Familienzentren](Familienzentren/Familienzentren.html)
- [Aktivitäten](Jugendklubs/top10_2.html)
- [Begegnungen](Begegnungen/Begegnungen.html)
- [Freizeit](Freizeit/Freizeit.html)
- <a class="emergencycall-link" href="/Notrufnummern/Notrufnummern_Eltern.html">Notrufnummern</a>
</div>
<div class="displaynone" id="listNeu_in_Hsh">
- <a class="calendar-link" href="calendar/calendar.html">Veranstaltungskalender</a>
- [Begegnungen](Begegnungen/Begegnungen.html)
- [Beratung](Beratung/Beratung_Eltern.html)
- [Kitas](Kitas/Kitas.html)
- [Schulen](Schulen/Schulen.html)
- [Familienzentren](Familienzentren/Familienzentren.html)
- [Familienbüro](Familienbuero.html)
- [Freizeit](Freizeit/Freizeit.html)
- [Aktivitäten](Jugendklubs/top10_2.html)
- <a class="emergencycall-link" href="/Notrufnummern/Notrufnummern.html">Notrufnummern</a>
</div>
<div class="displaynone" id="listSenior">
- <a class="calendar-link" href="calendar/calendar.html">Veranstaltungskalender</a>
- [Begegnungsstätten](Senioren/Begegnungsstaetten/Begegnungsstaetten.html)
- [Freizeit](Freizeit/Freizeit.html)
- [Ehrenamt](Senioren/Ehrenamt/Ehrenamt.html)
- <a class="emergencycall-link" href="/Notrufnummern/Notrufnummern.html">Notrufnummern</a>
</div>

<script type="text/javascript">
  // format lists after page has loaded
  document.addEventListener("DOMContentLoaded", function(event) {
    formatLists();
  });
</script>
