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
      <div class="container mt-5">
        <div class="row row-cols-1 row-cols-md-2 g-4">
            <div class="col">
                <div class="card">
                    <div class="card-body">
                        <h5 class="card-title"><i class="fas fa-project-diagram me-2"></i><a href="/projects/project1">Project 1</a></h5>
                        <p class="card-text">Description of Project 1.</p>
                    </div>
                </div>
            </div>
            <div class="col">
                <div class="card">
                    <div class="card-body">
                        <h5 class="card-title"><i class="fas fa-project-diagram me-2"></i><a href="/projects/project2">Project 2</a></h5>
                        <p class="card-text">Description of Project 2.</p>
                    </div>
                </div>
            </div>
            <div class="col">
                <div class="card">
                    <div class="card-body">
                        <h5 class="card-title"><i class="fas fa-project-diagram me-2"></i><a href="/projects/project3">Project 3</a></h5>
                        <p class="card-text">Description of Project 3.</p>
                    </div>
                </div>
            </div>
            <div class="col">
                <div class="card">
                    <div class="card-body">
                        <h5 class="card-title"><i class="fas fa-project-diagram me-2"></i><a href="/projects/project4">Project 4</a></h5>
                        <p class="card-text">Description of Project 4.</p>
                    </div>
                </div>
            </div>
            <div class="col">
                <div class="card">
                    <div class="card-body">
                        <h5 class="card-title"><i class="fas fa-project-diagram me-2"></i><a href="/projects/project5">Project 5</a></h5>
                        <p class="card-text">Description of Project 5.</p>
                    </div>
                </div>
            </div>
        </div>
      </div>
      '

  - block: languages
    content:
      title: Languages
      username: admin
 
---
