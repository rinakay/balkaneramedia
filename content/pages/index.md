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
    title: 'We''re not just a media company, we empower independence '
    subtitle: >-
      Ignite your music and content with Balkan Era Media's revolutionary
      technology driven platform. Set your creativity free and expand your reach
      across the globe with Balkan Era Media!
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
  - type: MediaGallerySection
    title: Gallery
    subtitle: This is the subtitle
    images:
      - type: ImageBlock
        url: /images/logo1.svg
        altText: logo one
        caption: Caption of the image
        elementId: ''
      - type: ImageBlock
        url: /images/logo2.svg
        altText: logo two
        caption: Caption of the image
        elementId: ''
      - type: ImageBlock
        url: /images/logo3.svg
        altText: logo three
        caption: Caption of the image
        elementId: ''
      - type: ImageBlock
        url: /images/logo4.svg
        altText: logo four
        caption: Caption of the image
        elementId: ''
      - type: ImageBlock
        url: /images/logo5.svg
        altText: logo five
        caption: Caption of the image
        elementId: ''
    colors: colors-a
    spacing: 16
    columns: 5
    aspectRatio: '16:9'
    showCaption: true
    enableHover: false
    elementId: ''
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-12
          - pb-12
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: center
      subtitle:
        textAlign: center
  - type: ContactSection
    colors: colors-f
    backgroundSize: full
    title: Contact Us
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
        - name: updatesConsent
          label: Sign me up to recieve updates
          isRequired: false
          width: full
          type: CheckboxFormControl
      submitLabel: Submit
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
---
