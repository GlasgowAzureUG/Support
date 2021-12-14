name: Speaker
about: 'Use this to indicate if you would like to speak at a Glasgow Azure User Group
  meetup. '
title: "[SPEAKER] <your-name>"
labels: [speaker]
body:
  - type: input
    id: link  
    attributes:
      label: Session Title
      placeholder: The title of your session
    validations:
      required: true
  - type: input
    id: link
      label: Session Description
      placeholder: Some details on your session
    validations:
      required: true
  - type: input
    id: link
      label: Session Length
      placeholder: The length of your session in time
    validations:
      required: true
  - type: markdown
    attributes:
      value: |
        Be sure to follow our Twitter account to keep up to date with everything that is going on.  [Follow us on Twitter](https://www.twitter.com/glasgowazureug)
  



