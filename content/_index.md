---
title: 'Home'
date: 2023-10-24
type: landing

design:
  spacing: "6rem"

sections:
  - block: hero
    content:
      title: Building the Future of Digital Cities
      text: At Matrixity Games, we’re creating a digital city where strategy meets innovation. Welcome to Matrixity.
      primary_action:
        text: Explore Our World
        url: "/game/"
        icon: rocket-launch
      secondary_action:
        text: Learn About Us
        url: "/about/"
      announcement:
        text: "Dive into the Future of City Gaming"
        link:
          text: "Discover more"
          url: "/about/"
    design:
      spacing:
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
      css_class: "dark"
      background:
        color: "navy"
        image:
          filename: bg-triangles.svg
          filters:
            brightness: 0.6
  - block: stats
    content:
      items:
        - statistic: "50K+"
          description: |
            Players building  
            their digital cities
        - statistic: "100+"
          description: |
            Digital structures  
            to construct
        - statistic: "500+"
          description: |
            Strategy elements  
            for city management
    design:
      css_class: "bg-gray-100 dark:bg-gray-900"
      spacing:
        padding: ["1rem", 0, "1rem", 0]
  - block: features
    id: features
    content:
      title: Why Matrixity?
      text: Dream big, build bigger 🏙️
      items:
        - name: Immersive City Building
          icon: city
          description: Dive into a fully digital city experience where every building and decision counts.
        - name: Real-Time Strategy
          icon: clock
          description: Manage your city in real-time with evolving challenges and opportunities.
        - name: Seamless Accessibility
          icon: key
          description: Build and expand your city anytime, anywhere.
        - name: Community-Driven Development
          icon: users
          description: Join a community of city planners and shape the city of the future together.
        - name: Cutting-Edge Visualization
          icon: eye
          description: Experience a digital city with stunning graphics and smooth interactions.
        - name: Endless Customization
          icon: puzzle-piece
          description: Tailor your city with unique structures and layouts to make it truly yours.
  - block: cta-image-paragraph
    id: about
    content:
      items:
        - title: Creating a Digitalized City
          text: Matrixity Games brings you a city that lives and breathes in the digital space.
          feature_icon: globe
          features:
            - "Strategic urban planning made digital"
            - "Focus on sustainability and growth"
            - "Inspired by real-world city dynamics"
          image: build-website.png
          button:
            text: Learn More
            url: /about/
        - title: Join the Matrixity Community
          text: Connect with other city builders and bring your ideas to life.
          feature_icon: handshake
          features:
            - "Collaborate with other players"
            - "Share and get feedback on your city designs"
            - "Stay updated on game developments"
          image: coffee.jpg
          button:
            text: Join Community
            url: https://discord.gg/matrixity
    design:
      css_class: "bg-gray-100 dark:bg-gray-900"
  - block: testimonials
    content:
      title: ""
      text: ""
      items:
        - name: "Jordan Lee"
          role: "City Planner at Matrixity Games"
          image: "testimonial-1.jpg"
          text: "Building my dream city with Matrixity has been an incredible experience. The digital city concept is something truly unique!"
    design:
      spacing:
        padding: ["6rem", 0, 0, 0]
  - block: cta-card
    content:
      title: Start Building Your Digital City
      text: Ready to create your city in the Matrixity universe?
      button:
        text: Get Started
        url: /game/
    design:
      card:
        css_class: "bg-primary-700"
        css_style: ""
---
