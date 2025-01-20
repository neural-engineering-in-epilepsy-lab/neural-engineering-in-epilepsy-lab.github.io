---
title: Research
date: 2022-10-24

type: landing

sections:
  - block: slider
    content:
      slides:
      - title: 👋 Welcome to the group
        content: Take a look at what we're working on...
        align: center
        background:
          image:
            filename: coders.jpg
            filters:
              brightness: 0.7
          position: right
          color: '#666'
      - title: Temporal and spatial properties of High Frequency Oscillations
        content: We are investigating the differences between pathological and non-pathological high-frequency oscillations (HFOs), as well as the distinction between signals with HFOs and those without. Pathological HFOs are associated with epileptic hyperexcitability, while non-pathological HFOs are linked to normal brain functions like memory consolidation. Understanding these differences is critical for identifying epileptogenic tissue, improving epilepsy diagnostics, and distinguishing seizure-related activity from normal neural processes.
        align: left
        background:
          image:
            filename: hfo_background.jpg
            filters:
              brightness: 0.7
          position: right
          color: '#000'
      - title: Dynamical modeling and analysis to characterize seizure dynamics
        content: In a collaboration with Viktor Jirsa and Christophe Bernard (Marseille, France), we developed a dynamical model of seizure activity, based upon the bifurcations and state variables necessary to produce focal seizures. We found that the most common bifurcations were a saddle node at seizure onset, and a homoclinic bifurcation at offset. These bifurcations led to several predictions about canonical seizure dynamics, several of which we were able to validate in multiple species such as rats, mice, zebrafish, and humans. Using this framework, we are now categorizing human seizure dynamics on a larger scale, with the hopes of improving our understanding of the time course of seizures. We also use the model to assess perturbation responses and coupling dynamics, as well as to generate simulated seizures that are used to train classifiers for seizure detection and prediction.
        font_size: xs
        align: right
        background:
          image:
            filename: dynampype+baclr.jpg
            filters:
              brightness: 0.5
          position: center
          color: '#333'
        link:
          icon: graduation-cap
          icon_pack: fas
          text: Join Us
          url: ../contact/
    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: ''
      is_fullscreen: true
      # Automatically transition through slides?
      loop: false
      # Duration of transition between slides (in ms)
      interval: 2000
---
