Features:
Pest and Disease Management:

1. Predict probability of disease
Factors considered:  Crop, Humidity, Temperature, Date (Month/Season), Region(State and district),  
Soil moisture and rainfall. Here we have used a pre-trained regression model available on 
http://www.imdagrimet.gov.in/node/399 for every crop and it’s corresponding diseases.

2. Suggest pesticide according to the disease. Data for this was obtained from 
http://pest2.bengalsols.com and http://raitamitra.kar.nic.in/pps/listMF.htm 
for the states of Maharashtra and Karnataka.

3. Display vendor along with quantity, directions to use, and other vendor details like vendor district, 
and vendor state. The vendor list generated is mapped to the farmer model, to filter out only those vendors
which are constrained within the district boundaries.

Advantages: 
1. Predicting beforehand will reduce the total loss if failure occurs.
2. Suggesting pesticides to use for that particular disease for farmers who are unaware.
3. Display vendors who sell those specific pesticides so that farmers know where to go.


Factors considered for better UX and ease of use for farmers:
1.  Multilingual site. Supports all regional languages.
2. SMS API Integration for Farmers, which ensures ease of use of technology by them.


Technology Used:
1.  Optimizing a pre-trained model using machine learning, based on a weather API, along with the factors listed above.
2.  Running Python scripts in Laravel.
3.  Laravel as a back-end framework.
4.  HTML, CSS, Bootstrap, JS, jQuery, Ajax.
5. Weather Forecast API (Darkscan).
6.  Email.js
7. SMS API: Message91
8. Web Scrapping for Vendor Details of Pesticide.


Datasets:
1.  Vedas : Soil Moisture dataset.
2. http://farmer.gov.in : Pesticide Dealers.
3. http://www.imdagrimet.gov.in : Pesticide Disease.
4. http://agmarknet.gov.in/ : Current Mandi MSP.


https://sammy1997blog.wordpress.com/
This link contains the project description wrt datasets, tech stack used, features as well as screenshots.

