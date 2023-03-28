This repository contains the electronic supplementary material that supports the paper:

Bayón, A., Valero, D. & Franca, M. (2023). "Urban Flood Drifters (UFD): identification, classification and characterization". Proceedings of the Royal Society of Edinburgh Section A: Mathematical, Physical and Engineering Sciences (submitted).


SUMMARY:

In this study, we define Urban Flood Drifters (UFDs) as loose objects present in the urban landscape that can become mobile under certain flow conditions, subsequently blocking drainage infrastructure and endangering both downstream and upstream communities. Based on post-flood photographic records from major inundations worldwide over the past quarter-century, we provide a comprehensive analysis of UFDs and their implications for flood hazards. We propose a classification of UFDs into different groups based on their origin. Additionally, we offer a detailed analysis of a representative sample of various types of urban objects that can become destabilized and turn into UFDs.


CONTENT:

- "prevalence.csv":, prevalence of urban flood drifters on a yes/no basis in the analyzed graphic material.

    ID:        photo/video identifier<br>
    year:      year of event<br>
    country:   country or countries affected by flood
    V1:        two-wheelers: Bikes, motorbikes and e-scooters.
    V2:        cars: Cars and other light four-wheel vehicles designed to transport of passengers.
    V3:        vans: Vans and other heavy four-wheel vehicles designed to transport materials and stock.
    V4:        caravans & RVs : Vehicles designed to provide habitable space.
    V5:        large heavy vehicles: Vehicles designed to transport many people or goods (buses, trucks, trains, boats, etc.).
    F1:        urban fixtures: Facilities designed to provide a public service in streets (bins, waste containers, etc.).
    F2:        household equipment: Facilities from private front gardens that can be dragged by floods (tanks, garden sheds, etc.).
    DC:        construction: Material that can be dragged from construction sites or damaged buildings.
    DM:        metal: Metal drifters, predominantly of constructive origin (sheets, pipes, etc.).
    DP:        plastic: Plastics and textile objects of small dimensions and irregular shape.
    DW:        wood: Natural wood (trunks, branches, etc.).
    DO:        others: Other drifters of uncertain origin (food, tableware, leaves, sediment, etc.).
    source:    original source where the graphic material was found

- "characteristics.csv": relevant physical properties of a series of potential urban flood drifting objects:

    ID:        Item identifier
    name:      item name, brand and/or model
    Lx:        crosswise length [m]
    Ly:        streamwise length [m]
    Lz:        total height [m]
    m:         mass [kg]
    V:         volume of bounding box (V = Lx·Ly·Lz) [m³]
    ρ:         apparent density (ρ = m/V) [kg/m³]
    source:    original source where theinformation was found
    
