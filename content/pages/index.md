---
type: PageLayout
title: Home
colors: colors-a
sections:
  - type: TextSection
    colors: colors-f
    variant: variant-b
    title: This site is to manage personal projects
    text: >+
      **About This Site**


      Welcome to the official site for RoRvzzz! This website serves as a hub for
      all information related to my projects, 


      ## What You’ll Find Here


      *   **Bot Information:** Details on how SpookyBot works and its features.


      *   **Terms & Privacy:** Our Terms of Service and Privacy Policy to help
      you understand how we operate and protect your data.


      *   **Contact Information:** Get in touch with us for support, inquiries,
      or feedback.





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
  - type: TextSection
    colors: colors-d
    variant: variant-a
    title: The Section Title
    subtitle: The section subtitle
    text: ''
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
      text:
        textAlign: left
  - type: ContactSection
    title: Contact Me
    text: |
      Have an inquiry?
    form:
      type: FormBlock
      title: Title of the form
      fields:
        - type: TextFormControl
          name: name
          label: Name
          hideLabel: true
          placeholder: Your name
          width: 1/2
          isRequired: 'true'
        - type: EmailFormControl
          name: email
          label: Name
          hideLabel: true
          placeholder: Your email
          width: 1/2
          isRequired: 'true'
        - type: TextareaFormControl
          name: message
          label: Tell me about your project
          hideLabel: true
          placeholder: Tell me about your project
          width: full
          isRequired: true
        - type: CheckboxFormControl
          name: updates
          label: Sign me up to receive updates
          width: full
          isRequired: 'false'
      submitLabel: Send Message
      elementId: contact-form
      styles:
        submitLabel:
          textAlign: left
    colors: colors-f
    backgroundSize: full
    elementId: ''
    styles:
      self:
        height: auto
        width: narrow
        padding:
          - pt-28
          - pb-36
          - pl-4
          - pr-4
        alignItems: center
        justifyContent: center
        flexDirection: row
      title:
        textAlign: center
      text:
        textAlign: center
backgroundImage:
  type: BackgroundImage
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: no-repeat
  opacity: 100
  url: /images/featured-Image2.jpg
---
