# FustionDashboardWebsite

I built this Strategic Fusion Dashboard to solve the core problem of fragmented intelligence data. The main idea was to bring OSINT, HUMINT, and IMINT together on one single interactive map so analysts don’t have to keep switching between different tools.
I used Leaflet.js for the map because it’s lightweight and perfect for adding interactive markers. Each marker represents a different type of intelligence – blue for OSINT, green for HUMINT, and red for IMINT. When you hover over any marker, a clean pop-up instantly shows the details and image (for IMINT). This “hover-and-view” feature gives immediate visual confirmation without leaving the main screen.
For data ingestion, I added simple buttons to simulate loading from MongoDB/S3, CSV/JSON, and drag-and-drop image upload. In a real version, these would connect directly to the actual databases and storage.
The whole dashboard is designed to give a real “common operating picture” in one place, exactly as mentioned in the problem statement.
