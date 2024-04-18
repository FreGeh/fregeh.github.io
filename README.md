# European Hackathons

This page lists upcoming hackathons in Europe.

{% assign sorted_hackathons = site.data.hackathons | sort: 'date' %}
{% for hackathon in sorted_hackathons %}
## {{ hackathon.name }}

**Location:** {{ hackathon.location }}  
**Date:** {{ hackathon.date }}  
**Website:** {{ hackathon.website }}
<details>
<summary>More Info</summary>

- Description: {{ hackathon.description }}
- Topics: {{ hackathon.topics }}
- Prizes: {{ hackathon.prizes }}

</details>
---
{% endfor %}
