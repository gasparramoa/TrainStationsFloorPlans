# Train Station🚉 Floor Plans Database

This repository is an open-access database of train station floor plans intended to be used for various purposes, including converting them into audio-tactile representations for people with visual impairments (BVI). Currently, the repository includes floor plans in PNG and PDF formats for train stations in Germany's Baden-Wuttermberg and Bavaria districts and from the states of Bremen and Nordhein Westfalen. The database consists of 2831 files. However, we aim to expand the collection to include floor plans from other European train stations in the future.


![Nuremberg Railway station floor plan](NurembergHbf.png) Nuremberg Main Railway train station. (Collected from the [BEG](https://www.bayern-fahrplan.de/de/zusaetzliche-informationen/stationsdatenbank) database). 

## <span style="font-size:larger;">**Background**</span>
This project aims to provide a valuable resource for individuals with visual impairments by making train station floor plans accessible through audio-tactile representations. By converting the floor plans into SVG format, we can create tactile representations that can be interpreted through touch and sound, allowing individuals with BVI to navigate train stations independently and safely.

## <span style="font-size:larger;">**Dataset Structure**</span>
The dataset is organized as follows:

```markdown
root/
├── Germany/
│   ├── Baden-wuttermberg/
│   │   ├── station1/
│   │   │   ├── station1.png
│   │   │   ├── station1.pdf
│   │   │   └── ...
│   │   ├── station2/
│   │   │   ├── station2.png
│   │   │   ├── station2.pdf
│   │   │   └── ...
│   │   └── ...
│   ├── Bavaria/
│   │   ├── station1/
│   │   │   ├── station1.png
│   │   │   ├── station1.pdf
│   │   │   └── ...
│   │   ├── station2/
│   │   │   ├── station2.png
│   │   │   ├── station2.pdf
│   │   │   └── ...
│   │   └── ...
│   └── ...
└── ...
```



Each train station has its own directory containing both PNG and PDF versions of the floor plans. Additional European 🌍 train stations will be added to the corresponding country and district directories in the future.

To access additional train station floor plans, you can also visit our [Google Drive folder](https://drive.google.com/drive/folders/1mb3frqlO70MktOJYpr-8I_btsUQ_3VbI) containing the files.

## Contribution Guidelines
Contributions to this project are welcome! If you have floor plans for train stations in other European regions, please follow these steps to contribute:

1. Fork the repository and create a new branch for your contributions.
2. Create a directory structure similar to the existing format for the corresponding country and district.
3. Add the floor plans in both PNG and PDF formats to the appropriate directory.
4. Create a pull request with a clear description of the changes made.

     
## Citation :page_with_curl:
If you use this dataset, please cite:
```
location = {Corfu, Greece},
series = {PETRA '23}
}
