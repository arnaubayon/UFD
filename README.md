This repository contains the electronic supplementary material that supports the paper:

Bayón, A., Valero, D. & Franca, M. (2023). "Urban Flood Drifters (UFD): identification, classification and characterization". Proceedings of the Royal Society of Edinburgh Section A: Mathematical, Physical and Engineering Sciences (submitted).


SUMMARY:

In this study, we define Urban Flood Drifters (UFDs) as loose objects present in the urban landscape that can become mobile under certain flow conditions, subsequently blocking drainage infrastructure and endangering both downstream and upstream communities. Based on post-flood photographic records from major inundations worldwide over the past quarter-century, we provide a comprehensive analysis of UFDs and their implications for flood hazards. We propose a classification of UFDs into different groups based on their origin. Additionally, we offer a detailed analysis of a representative sample of various types of urban objects that can become destabilized and turn into UFDs.


CONTENT:

- "prevalence.csv":, prevalence of urban flood drifters on a yes/no basis in the analyzed graphic material.

    ID:        photo/video identifier.<br>
    year:      year of event.<br>
    country:   country or countries affected by flood.<br>
    V1:        two-wheelers: Bikes, motorbikes and e-scooters.<br>
    V2:        cars: Cars and other light four-wheel vehicles designed to transport of passengers.<br>
    V3:        vans: Vans and other heavy four-wheel vehicles designed to transport materials and stock.<br>
    V4:        caravans & RVs : Vehicles designed to provide habitable space.<br>
    V5:        large heavy vehicles: Vehicles designed to transport many people or goods (buses, trucks, trains, boats, etc.).<br>
    F1:        urban fixtures: Facilities designed to provide a public service in streets (bins, waste containers, etc.).<br>
    F2:        household equipment: Facilities from private front gardens that can be dragged by floods (tanks, garden sheds, etc.).<br>
    DC:        construction: Material that can be dragged from construction sites or damaged buildings.<br>
    DM:        metal: Metal drifters, predominantly of constructive origin (sheets, pipes, etc.).<br>
    DP:        plastic: Plastics and textile objects of small dimensions and irregular shape.<br>
    DW:        wood: Natural wood (trunks, branches, etc.).<br>
    DO:        others: Other drifters of uncertain origin (food, tableware, leaves, sediment, etc.).<br>
    source:    original source where the graphic material was found.<br>

- "characteristics.csv": relevant physical properties of a series of potential urban flood drifting objects:

    ID:        Item identifier<br>
    name:      item name, brand and/or model<br>
    Lx:        crosswise length [m]<br>
    Ly:        streamwise length [m]<br>
    Lz:        total height [m]<br>
    m:         mass [kg]<br>
    V:         volume of bounding box (V = Lx·Ly·Lz) [m³]<br>
    ρ:         apparent density (ρ = m/V) [kg/m³]<br>
    source:    original source where theinformation was found<br>
    
