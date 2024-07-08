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
  - colors: colors-f
    type: FeaturedProjectsSection
    elementId: ''
    actions:
      - type: Link
        label: See all dates
        url: 'https://mobilerabiesvaccination.my.canva.site/'
        showIcon: true
    showDate: false
    showDescription: true
    showFeaturedImage: true
    showReadMoreLink: true
    variant: variant-b
    projects: []
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
    subtitle: Mobile Rabies Vaccination
    title: 'Tohono O,odham Nation Mobile Rabies Vaccination'
  - type: FeaturedPostsSection
    elementId: ''
    colors: colors-f
    variant: variant-d
    subtitle: Featured Posts
    showFeaturedImage: false
    actions:
      - type: Link
        label: See all posts
        url: 'https://mobilerabiesvaccination.my.canva.site/'
    posts:
      - content/pages/blog/post-six.md
      - content/pages/blog/post-four.md
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
  - type: MediaGallerySection
    title: Gallery
    subtitle: This is the subtitle
    images:
      - type: ImageBlock
        url: /images/gallery-1.jpg
        altText: Image one
        caption: Image one caption
        elementId: ''
      - type: ImageBlock
        url: /images/gallery-2.jpg
        altText: Image two
        caption: Image two caption
        elementId: ''
      - type: ImageBlock
        url: /images/gallery-3.jpg
        altText: Image three
        caption: Image three caption
        elementId: ''
      - type: ImageBlock
        url: /images/gallery-4.jpg
        altText: Image four
        caption: Image four caption
        elementId: ''
    colors: colors-c
    spacing: 16
    columns: 2
    aspectRatio: '1:1'
    showCaption: false
    enableHover: false
    elementId: ''
    styles:
      self:
        height: auto
        width: narrow
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
    title: "Got a question? Ask...\U0001F4AC"
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
        quote: "##### JayDiamond Taliman, DrPH,\_MPH\n\n##### Director of Environmental Health\n\n##### Tohono O’odham Nation Health Care\n\n##### (520) 307-8073\n\n##### <JayDiamond.Taliman@tonation-nsn.gov>\n\n"
        name: ''
        title: ''
        image:
          type: ImageBlock
          url: /images/TONHC_Seal 2023.jpg
          altText: ''
          caption: ''
          elementId: ''
        elementId: ''
        styles:
          name:
            fontWeight: 400
          title:
            fontWeight: 400
      - type: Testimonial
        quote: "##### Elvis Tanyi-Arrey,\_MPH,\_REHS/RS.\n\n##### Environmental Health Officer\n\n##### Tohono O’odham Nation Health Care\n\n##### Office 520 383 7200 Ext. 5354\n\n##### Cell\_\_\_\_520 334 9402\n\n##### <elvis.tanyi-arrey@tonation-nsn.gov>\n\n"
        name: ''
        title: ''
        image:
          type: ImageBlock
          url: /images/TONHC Seal B&W.jpg
          altText: ''
          caption: ''
          elementId: ''
        elementId: ''
        styles:
          name:
            fontWeight: 400
          title:
            fontWeight: 400
    colors: colors-a
    variant: variant-a
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
        textAlign: center
      subtitle:
        textAlign: center
---
