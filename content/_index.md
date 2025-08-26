---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  spacing: "6rem"

sections:
  # 1) BIO / Interests / Education (already pulls from content/authors/admin/)
  - block: resume-biography-3
    content:
      username: admin
      text: ""
    design:
      css_class: dark
      avatar:
        size: medium
        shape: circle
      background:
        color: black
        image:
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false

  # 2) RECENT NEWS (static bullet list)
  - block: markdown
    id: recent-news
    content:
      title: "Recent News"
      text: |-
        - **August 2025** — Congratulations to Reza on our IEEE ICDM 2025 paper.
        - **August 2025** — Congratulations to Santosh on our ACM CIKM 2025 paper.
        - **August 2025** — Congratulations to Peiyu and Pouya on our two IEEE DSAA 2025 papers.
        - **July 2025** — We received the NSF CAIG grant [Award #2530946](https://www.nsf.gov/awardsearch/showAward?AWD_ID=2530946) !  
        - **December 2024** — Congratulations to Reza on our SIAM SDM 2025 paper.
        - **December 2024** — Congratulations to Onur, Peiyu, Reza, and Pouya on four IEEE Big Data 2024 papers.
        - **December 2024** — Congratulations to Khaznah, Pouya, and Omar on three ICPR 2024 papers.
        - **October 2024** — Congratulations to Santosh on our IEEE DSAA 2024 paper.
        - **May 2024** — Congratulations to Cory and Santosh on our AAAI ICWSM 2024 paper.
        - **December 2023** — Congratulations to Omar, Peiyu, Cory, and Santosh on three IEEE Big Data 2023 papers.
        - **February 2023** — I received the NSF SHINE grant [Award #2301397](https://www.nsf.gov/awardsearch/showAward?AWD_ID=2301397) !
        - **December 2022** — Congratulations to Omar and Peiyu on two IEEE Big Data 2022 papers.
        - **October 2022** — Congratulations to Soukaina on our ACM CIKM 2022 paper.
        - **August 2022** — I started my Assistant Professor position at CS USU.
        - **May 2022** — Congratulations to Cory on our AAAI ICWSM 2022 paper.
        - **January 2022** — I received the NSF CRII award [Award #2305781](https://www.nsf.gov/awardsearch/showAward?AWD_ID=2305781) !
        - **August 2020** — I started my Assistant Professor position at CS NMSU.
    design:
      columns: "1"
      

  # 3) FEATURED PUBLICATIONS (keep)
  - block: collection
    id: papers
    content:
      title: Featured Publications
      filters:
        folders: ["publication"]
        featured_only: true
    design:
      view: article-grid
      columns: 2

  # 4) RECENT PUBLICATIONS (move to end)
  - block: collection
    content:
      title: Recent Publications
      text: ""
      filters:
        folders: ["publication"]
        exclude_featured: false
    design:
      view: citation
---
