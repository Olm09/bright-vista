---
title: 'Home'
date: 2023-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: hero
    content:
      title: Reportage. News. Doku. 
      text: Fernsehen machen. Mit Profis. 
      primary_action:
        text: Jetzt anfragen 
        url: https://bewotv.de 
        icon: envelope
    #  secondary_action:
    #    text: Read the docs
    #    url: https://docs.hugoblox.com
    #  announcement:
    #    text: "Announcing the release of version 1."
    #    link:
    #      text: "Read more"
    #      url: "/blog/"
    design:
    #   spacing:
    #     padding: [0, 0, 0, 0]
    #     margin: [0, 0, 0, 0]
      # For full-screen, add `min-h-screen` below
      css_class: "dark"
      background:
        color: "navy"
        image:
          # Add your image background to `assets/media/`.
          filename: landing-bg.jpg
          filters:
            brightness: 0.5
          size: cover
          position: center
          parallax: false
  - block: features
    id: features
    content:
      title: Dienstleistungen 
      text: Fernsehen aus Leidenschaft 
      items:
        - name: TV Produktion 
          icon: tv 
          description: Wir denken, schreiben und erzählen deine Geschichte. Für jedes Format und jede Länge. 
        - name: EB Teams
          icon: video
          description: Viele Fernsehredaktionen schätzen die zuverlässige Arbeit unserer EB Teams sowohl handwerklich wie technisch bei unzähligen EB-Einsätzen und Auftragsproduktionen.
        - name: Postproduktion
          icon: scissors
          description: Nach dem Dreh ist vor dem Schnitt. In unserer Edit-Suite basteln wir bis alles passt.
  - block: cta-image-paragraph
    id: solutions
    content:
      items:
        - title: Schau dir unsere letzten Produktionen an! 
          text: Im Blog erfährst du, was wir aktuell so drehen. 
          # Upload image to `assets/media/` and reference the filename here
          image: cam.jpg
          button:
            text: Zum Blog 
            url: blog/
  - block: cta-card
    content:
      title: Fernsehen machen. Mit Profis. 
      text: Worauf wartest du noch?
      button:
        text: Jetzt anfragen
        url: https://bewotv.de
    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-primary-300"
        css_style: ""
---
