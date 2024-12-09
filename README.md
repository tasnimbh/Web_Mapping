# Web Mapping Project 🌍  

Welcome to the Web Mapping! This guide will walk you through the process of creating and visualizing geospatial layers (couches) using GeoServer and ArcMap, integrating them into a web client using OpenLayers, and storing the resulting data in PostgreSQL.

---

## Prerequisites ✈  

Before you begin, ensure you have the following installed on your system:  
- **npm** and **Node.js** for running the server.  
- **GeoServer** for serving geospatial data.  
- **ArcMap** for visualizing and preparing the layers.  
- **PostgreSQL** for storing geospatial data.  

---

## Setting Up GeoServer Layers 🌐  

1. **Layer Creation**:  
   - Use **Geoserver** to create and prepare your geospatial layers . Ensure the data is correctly formatted and georeferenced.  
   - Publish the layers as **Web Map Service (WMS)** for easy integration with OpenLayers.  

3. **Test the WMS**:  
   - Verify the WMS endpoint by previewing your layers directly from the GeoServer interface.  

---

## Visualizing Layers with OpenLayers 🎯  

1. **Client Implementation**:  
   - Use **JavaScript, CSS, and HTML** with the **OpenLayers library** to fetch the layers from the GeoServer WMS.  
   - Customize the map interface to display your geospatial data interactively.  

2. **Integration Steps**:  
   - Link your WMS endpoints to the OpenLayers map object.  
---

## Storing Layers in PostgreSQL ⭐  

1. **PostgreSQL Configuration**:  
   - Ensure **PostgreSQL** is running and set up a database to store your geospatial data.  
   - The application will automatically handle table creation. Just provide your database credentials in the code.  

2. **Data Management**:  
   - Use **PostGIS** (PostgreSQL extension) to store and query spatial data efficiently.  

---

## Setting Up the Server 🌍  

1. Navigate to the `server` directory in the project folder.  
2. Run the following commands:  
   ```bash
   npm install
   node service.js

### Screenshots 📸
1. **OpenLayers Map with GeoServer Layers**
   ![OpenLayers Map](Images/openLayerMAP.PNG)

2. **Displaying Shapes Existing in the Database**
   ![Displaying Shapes from Database](Images/polygone.PNG)

3. **Displaying the local position**
   ![Global position](Images/Position.PNG)

