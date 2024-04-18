# European Hackathons

This page lists upcoming hackathons in Europe.

{% for hackathon in site.data.hackathons %}
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
