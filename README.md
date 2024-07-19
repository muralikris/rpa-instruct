# rpa-instruct
Design Robotic Process Automation (RPA) Agents for Desktops using Human Instruction and Computer Vision
![RPA Instructing RPA Agent](./assets/rpa_instruct.jfif)

# Why Robotic Process Automation (RPA)
RPA is preferred choice when API Access or System integrations/Connectors are not available to achieve automation needs.

- Realworld Examples of RPA: Website Scraping, Invoice processing, Outlook Calendar to Time Tracking Data Entry, Data Transfer: Download from Cloud Storage and Upload to Sharepoint
- RPA Software Providers: UiPath, Automation Anywhere, Microsoft Power Automate Desktop, rewst.io.

## Benefits of Computer Vision (CV) based RPA
1. Enhanced Flexibility and Adaptability
   - Allows RPA bots to interact with any visual interface. Eg: Virtual Desktop Infra (VDI)
   - Reduces dependence on legacy APIs or back-end integrations
   - Simplifies bot creation for visually-driven processes

2. Improved Accuracy and Reliability compared to traditional bots
   - Can handle dynamic UI elements and layout changes
   - Reduces errors caused by minor UI updates or inconsistencies

3. Expanded Automation Scope
   - Can work with scanned documents, images, and non-standard interfaces
   - Facilitates automation across multiple applications and platforms
   - Allows for more generalized automation solution

Speed and Capability Trade-off
   - While CV based solution may be slower compared to other options like Selenium, it offer intuitive/low-code experience for automation.
   - Ongoing improvements in CV algorithms and hardware acceleration will reduce the latency/performance gaps.
   - Use CV selectively for tasks where its benefits outweigh speed concerns

## References for Foundational Python Libraries which helped in realizing this work
1. Optical Character Recognition (OCR) Library- [docTR](https://github.com/mindee/doctr)
2. Segment Anything Model (SAM) Library- [SAM](https://github.com/facebookresearch/segment-anything)
3. Learning Robust Visual Features without Supervision- [DINOv2](https://github.com/facebookresearch/dinov2)

## Citation
If you use rpa-instruct in your work/research and found it useful, please leave me a star and/or use the following BibTeX entry.
@article{muralikp2024_rpainstruct,
  title={RPA-Instruct:Design Powerful Automation for desktops using computer vision},
  author={Pasupuleti, Murali Krishna},
  url={https://github.com/muralikris/rpa-instruct},
  journal={GitHub},
  year={2024}
}
