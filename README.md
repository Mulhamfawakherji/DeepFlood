# High Resolution Land Cover Classification Model

## Overview
Land cover describes the surface of the Earth and is essential for various applications, including urban planning, resource management, change detection, agriculture, and more. Land-cover classification, however, is a complex process that traditional methods struggle to address effectively.

Deep learning models excel at learning complex semantics and can significantly improve land-cover classification accuracy, automating tedious manual processes and saving time and effort.

This repository provides resources for the **High Resolution Land Cover Classification - USA** model, designed to classify land cover using deep learning techniques.

---

## Key Features

- **Input**: Raster, mosaic dataset, or image service.
- **Output**: A classified raster with the same classes as the Chesapeake Bay Land Cover 7-class dataset (2013/2014). Class descriptions are available on the [Chesapeake Conservancy website](https://www.chesapeakeconservancy.org).
- **Compute Requirements**: GPU with a minimum CUDA compute capability of 6.0 is recommended for optimal performance.
- **Applicable Geographies**: Best results are observed in the United States, particularly the Chesapeake Bay region.
- **Architecture**: Utilizes the UNet model architecture, implemented in the ArcGIS API for Python.
- **Accuracy Metrics**: The model achieves an accuracy of **87.86%**.

---

## Dataset Challenges
While there are public datasets for land cover, their spatial and temporal coverage may not always meet specific user needs. Creating custom datasets is resource-intensive and requires expertise. This model addresses these challenges by streamlining land-cover classification through deep learning.

---

## License Requirements
To use this model, the following licenses are required:

- **ArcGIS Desktop**: ArcGIS Image Analyst extension for ArcGIS Pro.
- **ArcGIS Enterprise**: ArcGIS Image Server with raster analytics configured.
- **ArcGIS Online**: ArcGIS Pro or Professional Plus user type.

---

## Access and Download
The pretrained model can be accessed in the following ways:

1. **From ArcGIS Living Atlas of the World**:
   - Sign in with your ArcGIS Online credentials.
   - Search for **High Resolution Land Cover Classification - USA**.
   - Open the item page and click the **Download** button.

2. **From ArcGIS Pro**:
   - Use the **.dlpk** file directly in your projects.

3. **From ArcGIS Enterprise**:
   - Upload the model for enterprise-wide use.

### Fine-Tuning
If necessary, fine-tune the pretrained model to meet your specific requirements.

---

## Contributing
We welcome contributions to enhance the functionality or extend the applicability of the model. Please open an issue or submit a pull request.

---

## License
This project follows the licensing terms as defined by Esri. Refer to the documentation for specific terms and conditions.

For more details, visit [ArcGIS Living Atlas of the World](https://livingatlas.arcgis.com).
