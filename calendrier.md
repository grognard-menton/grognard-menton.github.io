---
layout: default
title: Calendrier
permalink: /calendrier/
noindex: 1
---

<div id="activities">
  <div class="infobox">
    <h2>Cours</h2>
      <p>
There is no chin behind Chuck Norris' beard. There is only another fist Chuck Norris does not get frostbite. Chuck Norris bites frost, If you ask Chuck Norris what time it is, he always says, "Two seconds 'til." After you ask, "Two seconds 'til what?" he roundhouse kicks you in the face. Chuck Norris originally appeared in the "Street Fighter II" video game, but was removed by Beta Testers because every button caused him to do a roundhouse kick. When asked bout this "glitch," Norris replied, "That's no glitch." Chuck Norris doesn't wash his clothes, he disembowels them, Chuck Norris drives an ice cream truck covered in human skulls Chuck Norris doesn't wear a watch. HE decides what time it is. 
      </p>
  </div>
  <div class="infobox">
    <h2>Traduction</h2>
      <p>
Chuck Norris does not get frostbite. Chuck Norris bites frost, Chuck Norris uses pepper spray to spice up his steaks. Most people have 23 pairs of chromosomes. Chuck Norris has 72... and they're all poisonous. Outer space exists because it's afraid to be on the same planet with Chuck Norris, Chuck Norris doesn't churn butter. He roundhouse kicks the cows and the butter comes straight out. The leading causes of death in the United States are: 1. Heart Disease 2. Chuck Norris 3. Cancer Contrary to popular belief, America is not a democracy, it is a Chucktatorship, Outer space exists because it's afraid to be on the same planet with Chuck Norris. Most people have 23 pairs of chromosomes. Chuck Norris has 72... and they're all poisonous Guns don't kill people. Chuck Norris kills people Someone once videotaped Chuck Norris getting pissed off. It was called Walker: Texas Chain Saw Massacre Police label anyone attacking Chuck Norris as a Code 45-11... a suicide, 'The Downward Spiral' is about having a roundhouse kick by Chuck Norris When the Boogeyman goes to sleep every night, he checks his closet for Chuck Norris The Great Wall of China was originally created to keep Chuck Norris out. It failed miserably. 
      </p>
  </div>
  <div class="infobox">
    <h2>Conseil</h2>
      <p>
When Chuck Norris does a pushup, he isn't lifting himself up, he's pushing the Earth down. Chuck Norris doesn't read books. He stares them down until he gets the information he wants. CNN was originally created as the "Chuck Norris Network" to update Americans with on-the-spot ass kicking in real-time Contrary to popular belief, Chuck Norris, not the box jellyfish of northern Australia, is the most venomous creature on earth Contrary to popular belief, Chuck Norris, not the box jellyfish of northern Australia, is the most venomous creature on earth. When Chuck Norris sends in his taxes, he sends blank forms and includes only a picture of himself, crouched and ready to attack. Chuck Norris has not had to pay taxes, ever, It is very important for a grizzly bear to stay still when he sees Chuck Norris, Chuck Norris will attain statehood in 2009. His state flower will be the Magnolia. If you spell Chuck Norris in Scrabble, you win. Forever, The Great Wall of China was originally created to keep Chuck Norris out. It failed miserably Chuck Norris will attain statehood in 2009. His state flower will be the Magnolia Chuck Norris does not sleep. He waits. 
      </p>
  </div>
</div>

<div class="modal" id="modal-reservation">
  <div>
    <span class="close-modal" id="close-modal-reservation">&times;</span>
    <div id="reservation-infos">
    	<h2 id="reservation-title">Réservation :</h2>
	<p>
	  <table>
  	    <tbody>
    	      <tr>
                <td>
                  Début de la réservation :
                </td>
                <td>
                  <input id="reservation-startTime" type="datetime-local" name="reservation-startTime" value="" min="" max="" step="3600">
                </td>
              </tr>
              <tr>
                <td>
                  Fin de la réservation :
                </td> 
                <td>
                  <input id="reservation-endTime" type="datetime-local" name="reservation-endTime" value="" min="" max="" step="3600">
                </td>
              </tr>
              <tr>
                <td>
                  Type de la réservation : 
                </td>
                <td>
                  <select onchange="checkReservationType()" id="reservation-type" name="reservation-type">
                    <option value="cours">Cours</option>
    	            <option value="traduction">Traduction</option>
    	            <option value="conseil">Conseil</option>
                  </select>
                </td>
              </tr>
              <tr>
                <td>
                  Merci de remplir une adresse email valide, vous recevrez sur cette adresse toutes les informations concernant la réservation .
                </td>
                <td>
                  <input onchange="checkReservationEmail()" type="email" id="reservation-email" name="reservation-email" placeholder="votremail@gmail.com" id="email" />
                </td>
              </tr>
              <tr>
                <td colspan="2">
                  <button id="reservation-confirmation" disabled="disabled" type="submit"><span id="wait"></span></button>
                </td>
              </tr>
            </tbody>
          </table>
        </p>
      <div class="reservation-f" id="reservation-full">
        <p>Oups, vous avez choisi une plage horaire non disponible !</p>
      </div>
    </div>
  </div>
</div>

<div class="modal" id="modal-reservation-not">
  <div>
    <span class="close-modal" id="close-modal-reservation-not">&times;</span>
    <div id="not-reservation">
    	<h2 id="reservation-title">Oops :</h2>
	<p>
	  <table>
  	    <tbody>
    	      <tr>
                <td colspan="2">
                  Vous avez sélectionné une plage horaire non disponible ou déjà réservée . Veuillez réessayer . 
                </td>
                <td colspan="2">
                  Les réservations se font au minimum 3 heures avant afin de pouvoir m'organiser concernant la demande . Merci de votre compréhension .
                </td>
              </tr>
            </tbody>
          </table>
        </p>
    </div>
  </div>
</div>

<div id="payment-successful" class="infobox end-of-flow-success">
	Merci pour votre réservation ! Vous allez recevoir un email de confirmation.
</div>

<div id="cancel-successful" class="infobox end-of-flow-success">
	Réservation annulée avec succès !
</div>

<div id="refund-successful" class="infobox end-of-flow-success">
	Réservation remboursée avec succès ! Le remboursement se fera sur la carte bleue qui a servi au paiement sous 5 à 10 jours. Vous allez recevoir un email de confirmation.
</div>

<div id="postpone-successful" class="infobox end-of-flow-success">
	Réservation reportée avec succès ! Vous allez reçevoir un email de confirmation. 
</div>

<div id="postpone-mode" class="infobox">
	Pour finaliser votre report de réservation, veuillez sélectionner la nouvelle réservation qu'il vous convient. 
</div>

<div id="reservation">
  <div>
    <h2>Mes prochaines disponibilités</h2>
    <p>Cliquez sur un créneau disponible afin de réserver.</p>
    <div id="calendar"></div>
  </div>
</div>

<script src="https://cdn.jsdelivr.net/npm/moment@2.29.4/moment.js" integrity="sha256-wz8JpOEjDzB1vo0qlAgRCNUvYtPDC5ojiUH+gHkCZ8Y=" crossorigin="anonymous"></script>
<script src="https://cdn.jsdelivr.net/npm/fullcalendar@5.11.3/main.min.js" integrity="sha256-7PzqE1MyWa/IV5vZumk1CVO6OQbaJE4ns7vmxuUP/7g=" crossorigin="anonymous"></script>
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/fullcalendar@5.11.3/main.min.css" integrity="sha256-5veQuRbWaECuYxwap/IOE/DAwNxgm4ikX7nrgsqYp88=" crossorigin="anonymous">

<script>
  const minReservationDay = moment().format('YYYY-MM-DD');
  const maxReservationDay = moment().add(30,'days').format('YYYY-MM-DD'); 
  const minReservationTime = '08:00';
  const maxReservationTime = '21:00';
  const durationSlot = '01:00';
  const minReservationDayTime = moment().format('YYYY-MM-DDT08:00');
  const maxReservationDayTime = moment().format('YYYY-MM-DDT21:00');
  const modalReservation = document.getElementById("modal-reservation");  
  const modalReservationNot = document.getElementById("modal-reservation-not");  

  closeModalReservation = () => { 
    modalReservation.style.display = "none"; 
  }
  document.getElementById("close-modal-reservation").addEventListener("click", closeModalReservation)
  window.addEventListener("click", (event) => {
    event.target == modalReservation && closeModalReservation()
  })
  
  closeModalReservationNot = () => { 
    modalReservationNot.style.display = "none";
  }
  document.getElementById("close-modal-reservation-not").addEventListener("click", closeModalReservationNot)
  window.addEventListener("click", (event) => {
    event.target == modalReservationNot && closeModalReservationNot()
  })

  document.addEventListener('DOMContentLoaded', function() {
    document.getElementById("reservation-endTime").min = moment().format('YYYY-MM-DDTHH:mm');
    var calendarEl = document.getElementById('calendar');
    var calendar = new FullCalendar.Calendar(calendarEl, {
      initialView: 'timeGridWeek',
      titleFormat: { day: 'numeric', month: 'short' },
      locale: 'fr',
      weekends: false,
      allDaySlot: false,
      slotDuration: durationSlot,
      slotMinTime: minReservationTime,
      slotMaxTime: maxReservationTime,
      firstDay: 1,
      validRange: {
        start: minReservationDay,
        end: maxReservationDay
      },
      businessHours: {
        startTime: minReservationTime,
        endTime: maxReservationTime,
        daysOfWeeks: [1,2,3,4,5]
      },
      buttonText: {
        today: "Aujourd'hui" 
      },
      height: "auto",
      selectable: true,
      longPressDelay:10,
      selectConstraint: {
        startTime: '08:00',
        endTime: '21:00' 
      },
      select: function(info) {
	if (checkSlotValable(info.start) === true){
	  console.log('Selected');
          modalReservation.style.display = "flex";
          populateModal(info.start, info.end);
        } else if (checkSlotValable(info.start) === false){
	  modalReservationNot.style.display ="flex";
        }
      }
    });
    calendar.render();
  });
</script>

<script defer type="text/javascript">
  function datetimeToFrenchDatetimeAndDuration(start, end) {
    const durationMs = end - start
    const durationHour = parseInt(durationMs/(3600*1000))
    const durationMinute = String(parseInt(durationMs/(60*1000))%60).padStart(2, '0')
    const durationHuman = (durationHour > 0) ? durationHour + "h" + durationMinute : durationMinute + " min"
    const monthNames = ["janvier", "février", "mars", "avril", "mai", "juin", "juillet", "août", "septembre", "octobre", "novembre", "décembre"]
    const dayNames = ["lundi", "mardi", "mercredi", "jeudi", "vendredi", "samedi", "dimanche"]
    const startHuman = `${dayNames[start.getDay() - 1]} ${start.getDate()} ${monthNames[start.getMonth()]} à ${start.getHours()}h${String(start.getMinutes()).padStart(2, '0')}`
    return {durationHuman, startHuman}
  }
  function animateWaitElement(waitEl, button) {
    const oldButtonText = button.innerText
    button.disabled = true
    const dotsSetInterval = setInterval(() => {
      if (waitEl.innerHTML.length > 3 ) 
        waitEl.innerHTML = ""
      else 
        waitEl.innerHTML += "."
    }, 250)
    return () => {
      clearInterval(dotsSetInterval)
      waitEl.innerHTML = ""
      button.innerText = oldButtonText
      button.disabled = false
    }
  }
  function getMaxSlot(startTimeReservation){
    startSlot = startTimeReservation
    endSlot = moment().format('YYYY-MM-DDT20:00')
    maxSlot = endSlot.diff(startSlot, 'hours');
    return maxSlot;
  } 
  function getMaxTimeReservation(){
    return moment().format('YYYY-MM-DDT20:00')
  }
  function getMinTimeReservation(){
    return moment().format('YYYY-MM-DDTHH:mm')
  }
  function checkSlotValable(startTimeReservation){
    r = moment(startTimeReservation);
    c = moment();
    diff = r.diff(c, 'hours');
    console.log(diff);
    if (diff < 2){
      return false;
    } else {
      return true;
    }
  }
  function populateModal(startSelectedSlot, endSelectedSlot){
    document.getElementById("reservation-startTime").min = moment(startSelectedSlot).format('YYYY-MM-DDTHH:mm');
    document.getElementById("reservation-startTime").value = moment(startSelectedSlot).format('YYYY-MM-DDTHH:mm');
    document.getElementById("reservation-startTime").max = moment(maxReservationDayTime).subtract(1,'hours').format('YYYY-MM-DDTHH:mm');
    document.getElementById("reservation-endTime").min = moment(startSelectedSlot).add(1, 'hours').format('YYYY-MM-DDTHH:mm');
    document.getElementById("reservation-endTime").value = moment(endSelectedSlot).format('YYYY-MM-DDTHH:mm');
    document.getElementById("reservation-endTime").max = moment(maxReservationDayTime).format('YYYY-MM-DDTHH:mm');
    return;
  }
  function checkReservationType(){
    console.log("Check Reservation Type");
  }
  function checkReservationEmail(){
    console.log("Check Reservation Email");
  }

    
</script>
