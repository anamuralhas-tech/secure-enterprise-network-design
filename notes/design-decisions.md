# Design Decisions

- A hierarchical star topology was selected for the headquarters in order to improve structure, scalability, and traffic organization.
- VLAN-based logical segmentation was adopted to separate departments and reduce broadcast domains.
- A deny-by-default model was chosen to restrict inter-VLAN communication to explicitly required flows only.
- Site-to-site VPN connectivity was selected as the most balanced WAN solution for security and cost control.
- WAN redundancy was included to reduce the operational impact of ISP failures.
- Cat6A was selected for endpoint cabling and fiber was selected for the internal backbone to support performance and lifecycle goals.
- PoE+ switching was chosen to support IP phones, access points, and CCTV devices while reducing power distribution complexity.
- A five-year lifecycle perspective was used to avoid under-dimensioning and to support investment realism.
