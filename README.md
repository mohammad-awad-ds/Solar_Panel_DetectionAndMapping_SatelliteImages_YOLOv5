# Solar_Panel_Detection_Mapping_Satalite_YOLOv5 (This ReadME is a work in progress)
This is an end-to-end real world computer vision project for the detection and mapping of solar panels in the city of Amman. 

# Tools
Tools used in this project:
- Google Colab, python, pandas, NumPy, labelme, scikit-learn, YOLOv5, Folium, urllib.request, shutil and OS. 

# Project Scope
The project scope covers the following:
- Has a pipeline for scrapping tiles (satellite images as raw data) based on coordinates (ex: city of Amman) using an API.
- Preprocesses the tiles into suitable size and format while recording the latitude and longitude coordinates for each tile to be used in model training and solar panel location mapping.
- Manually labelling the PV solar panels appearing in the tiles.
- Trains a high precision YOLOv5 deep learning model for PV solar panel detection installed in comercial and residential environments.
- The solar panels detected by the model are then visually located on a map using the Folium python library based on the previously recorded coordinates.
- Statistical analysis is conducted for the solar panel distribution over east and west Amman.

# Some business use cases
The insights brought to light by this application can be used for:
- Targeted marketing for clients in neighborhouds based on the density (clusters) of solar panels show on the map.
- Offer solar panel maintainance companies the visibility over the location of solar panels in the city of Amman to better sell their services.
- Monitor weekly/monthly growth of solar panels across the city to gauge market demand by scheduling a rerun of this application (pipeline).


Note: The data used in this project is for demonstrative purpouses only, and is not intended for commercial use. The person using this code is solely responsible for gaining the permission and consent from the data owner/s for training and using the model.
