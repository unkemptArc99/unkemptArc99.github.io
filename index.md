---
layout: default
---

<div style="display: flex; justify-content: space-between; align-items: center;">
  <h1>Your Name</h1>
  <img src="https://via.placeholder.com/150" alt="Profile Picture" style="border-radius: 50%; width: 150px; height: 150px;">
</div>

---

## Bio

This is a placeholder for your bio. You can write a few paragraphs about yourself here. Talk about your passions, your skills, and what you do. Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

## Social Media

*   [LinkedIn](https://www.linkedin.com/in/yourprofile)
*   [GitHub](https://github.com/yourusername)
*   [Twitter](https://twitter.com/yourusername)

## Projects

{% for project in site.projects %}
### [{{ project.title }}]({{ project.url }})
{{ project.description }}
{% endfor %}

---

## Contact

You can reach me at [your.email@example.com](mailto:your.email@example.com).

[Download My Resume](link/to/your/resume.pdf)
