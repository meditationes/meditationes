# Meditationes

![Ruiterstandbeeld van Marcus Aurelius in de Capitolijnse Musea in Rome](images/marcus_aurelius.avif)

Marcus Aurelius werd bekend met zijn Meditationes (Ta eis heauton), persoonlijke notities waarin hij, als heerser van een wereldrijk, zijn gedachten ordende en zocht naar innerlijke rust, eenvoud en evenwicht. Geen leerboek, maar een intieme zoektocht naar wat echt van waarde is.
Hier sluit mijn eigen versie van Meditationes bij aan: een poging om mijn gedachten te spiegelen aan de wereld, in het besef dat mijn kennis beperkt en fragmentarisch is. Daarom laat ik ruimte voor twijfel en vragen, waarbij nieuwsgierigheid en leergierigheid mijn kompas vormen.

Francis

## Blogposts
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> - {{ post.date | date: "%d-%m-%Y" }}
    </li>
  {% endfor %}
</ul>
