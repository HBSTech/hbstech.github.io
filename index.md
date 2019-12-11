# [Heartland Business Systems](https://www.hbs.net/solutions/data-application-solutions)

## Data and Application Services at HBS
### Proudly serving the Midwest

  - Business Productivity
  - Data Services & Business Intelligence
  - Custom Application and Web Solutions

### Our repositories
{% for repository in site.github.public_repositories %}
  {% if repository.name != "hbstech.github.io"%}
  * [{{ repository.name }}]({{ repository.html_url }})
  {% endif %}
{% endfor %}
