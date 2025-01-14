---
title: Contact
type: landing
date: 2022-10-25

sections:
  - block: contact
    content:
      title: Contact
      subtitle:
      text: |-
        Dear visitors, you can contact me through messages, emails, or you can start a real-time chat by clicking the icon in the lower right corner.
      # Contact (add or remove contact options as necessary)
      email: pengwei.yang@sydney.edu.au
      phone: +61 450718075
      appointment_url: 'https://calendly.com'
      address: 
        street: Computer Science Building J12, the University of Sydney
        city: Sydney
        region: NSW
        postcode: '2006'
        country: Australia
        country_code: AU
      directions: SCSLab on Floor 4
      office_hours:
        - 'Saturday 10:00 to 13:00'
        - 'Sunday 09:00 to 10:00'
      contact_links:
        - icon: twitter
          icon_pack: fab
          name: DM Me
          link: 'https://twitter.com/Twitter'
        - icon: skype
          icon_pack: fab
          name: Skype Me
          link: 'skype:echo123?call'
        - icon: video
          icon_pack: fas
          name: Zoom Me
          link: 'https://zoom.com'
      
      coordinates:
          latitude: '-33.8882'
          longitude: '151.1941'

      # Automatically link email and phone or display as text?
      autolink: true
      
      # Email form provider
      form:
        provider: formspree
        formspree:
          id: xjvdjdjl
        netlify:
          # Enable CAPTCHA challenge to reduce spam?
          captcha: false
    design:
      columns: '1'
    
  - block: markdown
    content:
      title: ''
      subtitle: ''
      text: |-
        <script type='text/javascript' id='clustrmaps' src='//cdn.clustrmaps.com/map_v2.js?cl=ffffff&w=a&t=tt&d=IPz9CHURQbIcxY1LcH-h8QSuFwl3DVHDYvYkveXsHqc&co=2d78ad&cmo=3acc3a&cmn=ff5353&ct=ffffff'></script>
        <!-- Brevo Conversations {literal} -->
        <script>
            (function(d, w, c) {
                w.BrevoConversationsID = '64c2603da193dd6a6b6837a4';
                w[c] = w[c] || function() {
                    (w[c].q = w[c].q || []).push(arguments);
                };
                var s = d.createElement('script');
                s.async = true;
                s.src = 'https://conversations-widget.brevo.com/brevo-conversations.js';
                if (d.head) d.head.appendChild(s);
            })(document, window, 'BrevoConversations');
        </script>
        <!-- /Brevo Conversations {/literal} -->
    design:
      columns: '1'
---
