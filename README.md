# CitySafe_Project_Draft1
A website designed to help users identify safe and unsafe areas within a city in real-time. 
Using a combination of crime data and user reports, the website provides an interactive map highlighting high-risk zones and safe routes.
It features safety ratings and emergency assistance options, making it ideal for travellers, commuters, and residents who want to navigate urban areas securely. 
With its community-driven updates, City Safe empowers individuals to make informed decisions about their surroundings, enhancing personal safety and awareness.

## Technology Stack
Backend:
  Flask (Python web framework)
  pdfplumber (PDF data extraction)
  pandas (Data processing)

Geospatial :
  OpenStreetMap/Nominatim API (Geocoding)
  folium/Leaflet.js (Interactive maps)

Frontend :
  HTML/CSS/JavaScript
  DivIcon (Custom map markers)

Data :
  PDF crime reports
  Manual coordinate database
  JSON API endpoints

Infrastructure:
  File system integration
  RESTful architecture

## Installation

1. Clone this repository:
2. Install dependencies:
  Flask==2.0.1
  pdfplumber==0.7.0
  pandas==1.3.0
  folium==0.12.1
  requests==2.26.0
3. Run the application:
4. Open your browser and go to http://127.0.0.1:5000

## Future Scope & Impact 
Empowers urban safety – Provides real-time crime awareness using Machine Learning to identify Crime Hotspots.
IoT based City Planning – Enhances street lighting, patrolling, and Camera surveillance in unsafe areas.
Community-driven – Crowdsourced reports create a self-sustaining safety network.
Improves Public Safety Service Integration – Realtime alerts and direct links to Emergency Services, drastically reduce response times and save lives.
Boosts public confidence – Encourages safer mobility, economic activity, and tourism.

## Business Viability & Growth 💰
Smart city integration – Partner with state police and the National Crime Records Bureau for urban safety improvements.
Academic and Corporate security – Companies and institutions can protect employees and students, reducing liability risks.
Insurance & risk analysis – Crime heatmaps aid insurers in assessing policy risks.
Tourism & travel safety – Agencies can enhance visitor confidence and trust.
Revenue models – Freemium access, API licensing, ensure financial sustainability.

## Data Source
The application uses crime data from the Telangana State Crime Report. The PDF file is included in the directory.
The code right now is optimized with hard coded information of districts and commissionrates, to run the PDF extractor version, just add the path to the Telangana_CrimeRates.pdf
to pdf_path at line no. 209.
Other than that the code has been commented everywhere for your ease of understanding and acess.

## Thanks for checking out our project's draft #1!
For later editions we plan to add notification system, sumarized 3 year's worth of data, public report system as well.

## Team: Dhoomketu
Team Lead: Kushagr Joshi
7302480404
kushagrjoshi777@gmail.com
