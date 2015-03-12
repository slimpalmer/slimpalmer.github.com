---
layout: page
title: Slim Palmer
tagline: Author/Writer (and a bit eccentric)
---
{% include JB/setup %}

Former photo-journalist, fine artist, juggler, fire breather, theatre
professional and graphic designer Slim Palmer’s novels have been well received
by public and critics alike.
Albert The Third  - fantasy short stories - was shortlisted for the 2007 Blooker Prize.
His Rob Crowther theatre novels are read by many who tread the boards - and many who don’t.
His further Steve Aziz novels are currently being written and 'The Others' is widely available
He lives in the UK in an anomaly of Northumberland.

{% if site.posts.size > 0 %}
## Posts

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

{% endif %}
