# Meditationes

![Ruiterstandbeeld van Marcus Aurelius in de Capitolijnse Musea in Rome](images/marcus_aurelius.avif)

Marcus Aurelius werd bekend met zijn Meditationes (Ta eis heauton), persoonlijke notities waarin hij, als heerser van een wereldrijk, zijn gedachten ordende en zocht naar innerlijke rust, eenvoud en evenwicht. Vaak wordt de lezing verkeerd opgevat als een leerboek van de stoa. Dat was het eigenlijk nooit. Het was voor Marcus Aurelius een intieme zoektocht naar wat echt van waarde is.

Hier sluit mijn eigen versie van Meditationes bij aan: een poging om mijn gedachten te spiegelen aan de wereld, in het besef dat mijn kennis beperkt en fragmentarisch is (en zal blijven). Daarom laat ik ruimte voor twijfel en vragen, waarbij nieuwsgierigheid en leergierigheid mijn kompas vormen. In een ideale wereld lees je dit en ben je het met me (on)eens en nemen we samen even de tijd om hierover te ping-pongen...

Francis

## Gedachtengangen
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      <br>
      <small>{{ post.date | date: "%d-%m-%Y" }}</small>
    </li>
  {% endfor %}
</ul>
