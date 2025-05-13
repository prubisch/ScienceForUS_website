---
# Leave the homepage title empty to use the site title
title:
type: landing

sections:
  - block: hero
    content:
      title: |
        Science for US
      image:
        filename: welcome.jpg
      text: |
        <br>
        
        Freie unabhängige Wissenschaft für alle. 
  
  - block: collection
    content:
      title: Thematik
      subtitle:
      text:
      count: 5
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: post
    design:
      view: card
      columns: '1'
  
  - block: markdown
    content:
      title: Code of Conduct
      subtitle: ''
      text: 'Wir laden zum gemeinsamen diskutieren ein, dabei ist uns wichtig das folgende Dinge immer eingehalten werden: 

* Alle Meinung sind willkommen und gewünscht: Austausch lebt von unterschiedlichen Meinungen ung lebhafter Diskussion. 

* Egal ob Student, WiMi oder Professor: wir sind alle gleichgestellt und jeder hat das selbe Recht sih mitzuteilen. 

* Der Austausch ist respektvoll und wohlwollend. Auch in hitzigen Diskussionen muss garantiert werden, dass wir mit respekt unserem gegenüber begegenen. '
    design:
      columns: '1'
      background:
      spacing:
        padding: ['0px', '0', '0px', '0']
      css_class: fullscreen

  - block: collection
    content:
      title: Nächste Meetings
      text: ""
      count: 5
      filters:
        folders:
          - event
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: post
    design:
      view: card
      columns: '1'

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the organisers →" %}}
    design:
      columns: '1'
---
