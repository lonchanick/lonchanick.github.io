---
title: 'Home'
date: 2023-10-24
type: landing

design:
  # Default section spacing
  spacing: "5rem"

# Note: `username` refers to the user's folder name in `content/authors/`

# Page sections
sections:
  - block: biography
    content:
      username: admin
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download Resume
        url: uploads/resume.pdf
    design:
      banner:
        # Upload your cover image to the `assets/media/` folder and reference it here
        filename: kalen-emsley-Bkci_8qcdvQ-unsplash.jpg
        # filename: malecon.jpg
      biography:
        # Customize the style of your biography text
        style: 'text-align: justify; font-size: 0.8em;'

  - block: experience
    content:
      username: admin
    design:
      # Hugo date format
      date_format: 'January 2006'
      # Education or Experience section first?
      is_education_first: false

  - block: skills
    content:
      title: Skills & Hobbies
      username: admin

  - block: markdown
    id: section-1
    content:
      title: Small Projects (repositories)
      subtitle: List of projects
      text: '
        <p>In this section you can check some implementations out of basic libraries and like Entity Framework, ADO.NET and Dapper. Furthermore, you can check uses cases of MVC/API implementations, Unit testing, API consuming, Scraping, E-mail sender consuming among others basic library consuming.</p>
        <ul>
          <li><a href="https://github.com/lonchanick/CodeReviews.Console.CodingTracker">CodingTracker</a></li>
          <li><a href="/projects/project2">Project 2</a></li>
          <li><a href="/projects/project3">Project 3</a></li>
          <li><a href="/projects/project4">Project 4</a></li>
          <li><a href="/projects/project5">Project 5</a></li>
        </ul>
      '

  - block: languages
    content:
      title: Languages
      username: admin
 
---
