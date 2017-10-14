---
layout: page
title: Podcast
permalink: /podcast/
---

The CSSU is proud to announce their very own podcast: Room 2250!

This podcast will be for all UofT students discussing topics relating to UofT and Toronto with a lens of a computer science student.

The podcast will be hosted by CSSU treasurer Haider Nadeem and his co-host Christopher Mckerracher and will run every other weekend. We will be bringing on alumni, students and faculty for questions and their thoughts on the important subject matter like the best places to study, eat and make friends on campus and in Toronto.

We encourage all students, graduate or undergraduate, CS or non-CS, or anyone else who would listen in to tune in every other weekend!

Made possible by Vic Records.

You can listen and subscribe on your favourite platform:

[SoundCloud](https://soundcloud.com/room-2250) | 
[Google Play](https://play.google.com/music/m/Ilg4usk2dsp65rngd2dz4ehaax4?t=Room_2250) |
[iTunes](https://itunes.apple.com/ca/podcast/room-2250/id1278776873)

{% for track in site.data.podcast %}
  <iframe width="100%" height="166" scrolling="no" frameborder="no" src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/tracks/{{ track }}&amp;color=0d1117&amp;auto_play=false&amp;hide_related=false&amp;show_comments=true&amp;show_user=true&amp;show_reposts=false"></iframe>
{% endfor %}