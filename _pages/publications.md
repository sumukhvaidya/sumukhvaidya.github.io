---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

<!---{% if author.googlescholar %}--->

<!---{% endif %}--->
You can find my articles on <a href="https://scholar.google.com/citations?user=6DuGsdEAAAAJ&hl=en">Google Scholar</a>.

Also find me on  <a href="https://www.linkedin.com/in/sumukhvaidya">LinkedIn</a>.
<!---{% include base_path %}--->

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
