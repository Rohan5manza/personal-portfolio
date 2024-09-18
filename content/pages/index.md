---
type: PageLayout
title: Home
colors: colors-a
backgroundImage:
  type: BackgroundImage
  url: /images/bg1.jpg
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: no-repeat
  opacity: 75
sections:
  - elementId: ''
    colors: colors-f
    backgroundSize: full
    title: 'Hi,My name is Rohan marar. welcome to my portfolio website.'
    subtitle: >-
      This is my info—I’m sharing it all this with you to give you a glimpse
      into my life and my personality. you with many things that make me who I
      am. Continue to scroll down to see more details about me,and my personal
      and my professional life. I love to write, and this website gives me a
      chance to pin down my thoughts, my interests, and my ambitions, and all
      the things I've done till now, as well as my future plans.
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-36
          - pb-48
          - pl-4
          - pr-4
        alignItems: center
        justifyContent: center
        flexDirection: row-reverse
      title:
        textAlign: left
      subtitle:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
    type: HeroSection
    actions: []
  - colors: colors-a
    type: FeaturedProjectsSection
    elementId: ''
    actions:
      - type: Link
        label: See all works
        url: /projects
    showDate: false
    showDescription: true
    showFeaturedImage: true
    showReadMoreLink: true
    variant: variant-b
    projects:
      - content/pages/projects/project-two.md
      - content/pages/projects/my-book.md
      - content/pages/projects/my-newsletter.md
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-24
          - pb-24
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: left
      subtitle:
        textAlign: left
      actions:
        justifyContent: flex-end
    subtitle: 'Major things I''m building, or have completed...'
    title: My works
  - type: FeaturedPostsSection
    elementId: ''
    colors: colors-f
    variant: variant-d
    subtitle: >-
      An account of my personal and professional life, and other things I feel
      like writing about...
    showFeaturedImage: false
    actions:
      - type: Link
        label: See all posts
        url: /blog
    posts:
      - content/pages/blog/my-bodybuilding-journey.md
      - content/pages/blog/about-me.md
      - content/pages/blog/documentation.md
      - content/pages/blog/my-homelab-journey.md
    showDate: true
    showExcerpt: true
    showReadMoreLink: true
    styles:
      self:
        height: auto
        width: narrow
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-28
          - pb-48
          - pl-4
          - pr-4
        justifyContent: center
        borderRadius: none
        borderWidth: 0
        borderStyle: none
        borderColor: border-dark
      title:
        textAlign: left
      subtitle:
        textAlign: left
      actions:
        justifyContent: flex-end
    title: My blogs
  - type: TextSection
    colors: colors-f
    variant: variant-a
    title: My skills
    text: >+
      Technical skills:


      1.Proficient in AI/ML and deep learning.


      I have a strong interest in AI , and theory of computation.I am proficient
      in deep learning( ML, data science, python, pytorch, computer vision,
      LLMs, and other architectures, along with basic math required such as
      linear algebra, probability theory and calculus). I like to play around
      with deep neural networks and study the subject, both theoretically and
      via programming.Have experience of building real-world AI projects.


      2\. Home server management


      I possess basic knowledge and expertise of Proxmox homelab server
      management, virtualization, Linux, basic networking, and self-hosting
      applications. Exploring this field as a lifelong hobby.


      3\. Possess advanced knowledge of theoretical physics


      Modern physics(general relativity and quantum mechanics) sparked my
      lifelong love for science. Pursued this field passionately for 5 years


      4\. Other professional hobbies:


      I have a keen interest in entrepreneurship. I have knowledge of finance,
      economics, fundamental analysis of businesses, and value investing. Have
      experience of investing in stocks

    elementId: ''
    styles:
      self:
        height: auto
        width: narrow
        padding:
          - pt-28
          - pb-28
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: left
      subtitle:
        textAlign: left
      text:
        textAlign: left
  - type: LabelsSection
    title: Skills
    subtitle: List of my professional tool kit
    items:
      - type: Label
        label: Python
        url: ''
      - type: Label
        label: Java
        url: ''
      - type: Label
        label: C++
        url: ''
      - type: Label
        label: Pytorch
        url: ''
      - type: Label
        label: Proxmox
        url: ''
      - type: Label
        label: Docker
        url: ''
      - type: Label
        label: Linux
        url: ''
    colors: colors-f
    elementId: ''
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-36
          - pb-36
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: left
      subtitle:
        textAlign: left
  - type: LabelsSection
    title: My hobbies
    subtitle: 'Things I love to do '
    items:
      - type: Label
        label: Next.js
        url: ''
      - type: Label
        label: Netlify
        url: ''
      - type: Label
        label: Pancakes
        url: ''
      - type: Label
        label: C++
        url: ''
      - type: Label
        label: Swift
        url: ''
    colors: colors-f
    elementId: ''
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-36
          - pb-36
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: left
      subtitle:
        textAlign: left
  - type: ContactSection
    colors: colors-f
    backgroundSize: full
    title: "Got an interesting project that matches our interests? Would love to collab with you!...\U0001F4AC"
    form:
      type: FormBlock
      elementId: sign-up-form
      fields:
        - name: firstName
          label: First Name
          hideLabel: true
          placeholder: First Name
          isRequired: true
          width: 1/2
          type: TextFormControl
        - name: lastName
          label: Last Name
          hideLabel: true
          placeholder: Last Name
          isRequired: false
          width: 1/2
          type: TextFormControl
        - name: email
          label: Email
          hideLabel: true
          placeholder: Email
          isRequired: true
          width: 1/2
          type: EmailFormControl
        - name: address
          label: Address
          hideLabel: true
          placeholder: Address
          isRequired: true
          width: 1/2
          type: TextFormControl
        - name: updatesConsent
          label: Sign me up to recieve updates
          isRequired: false
          width: full
          type: CheckboxFormControl
      submitLabel: "Submit \U0001F680"
      styles:
        submitLabel:
          textAlign: center
    styles:
      self:
        height: auto
        width: narrow
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-24
          - pb-24
          - pr-4
          - pl-4
        alignItems: center
        justifyContent: center
        flexDirection: row
      title:
        textAlign: left
      text:
        textAlign: left
  - type: TestimonialsSection
    testimonials:
      - type: Testimonial
        quote: >
          I am always passionate to create and invent new stuff, and gain
          knowledge and expertise of things related to science and technology
          that interest me. I always approach a subject of my interest with
          curiosity and a first-principles basis.
        name: Rohan Marar
        title: Computer engineer
        image:
          type: ImageBlock
          url: /images/Screenshot 2024-06-23 172553.png
          altText: Rohan Marar
          caption: Caption of the image
          elementId: ''
        elementId: ''
        styles:
          name:
            fontWeight: 400
          title:
            fontWeight: 400
    colors: colors-a
    variant: variant-c
    elementId: ''
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-28
          - pb-28
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: left
      subtitle:
        textAlign: left
---
