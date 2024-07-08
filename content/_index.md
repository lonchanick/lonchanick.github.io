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
        # filename: kalen-emsley-Bkci_8qcdvQ-unsplash.jpg
        filename: volcano.jpg
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
        <p>In this section you can check some implementations out of basic libraries like Entity Framework, ADO.NET and Dapper. Furthermore, you can check uses cases of MVC/API implementations, Unit testing, API consuming, Scraping, E-mail sender consuming among others basic library consuming.</p>
        <ul>
          <li><a href="https://github.com/lonchanick/CodeReviews.Console.CodingTracker">Coding Tracker</a></li>
          <li><a href="https://github.com/lonchanick/CodeReviews.Console.Drinks/tree/main/LONCHANICK.DrinksApp">Console Drinks</a></li>
          <li><a href="https://github.com/lonchanick/CodeReviews.Console.SportsResults/tree/main/Lonchanick.SportNotifier">Sports Data Scraper Service</a></li>
          <li><a href="https://github.com/lonchanick/CodeReviews.Console.ExcelReader/tree/main/ExcelReader.Lonchanick">Excel to Database Application</a></li>
        </ul>
      '

  - block: languages
    content:
      title: Languages
      username: admin
---
