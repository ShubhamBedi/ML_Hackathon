<img src="https://machinehack-be.s3.amazonaws.com/iiit_nr_taxi_trip_fare_prediction_challenge/IITR%20LARGE%20BANNER%20%281%29.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4OZIV247L3SL57HI%2F20221216%2Fap-south-1%2Fs3%2Faws4_request&X-Amz-Date=20221216T090307Z&X-Amz-Expires=172800&X-Amz-SignedHeaders=host&X-Amz-Signature=4857012cc45f623a755a0830752f9c6dcc60f55e5809cb7e517b08154bac438e" alt="Taxi Trip Fare Prediction" width="1200" height="200">

The beginner level hackathon was hosted on <a href  = "https://machinehack.com/home">Machine Hack</a></br>
<b>Event Duration: </b> 17 Nov 2022 to 17 Dec 2022 </br>
Link to the hackathon: <a href = "https://machinehack.com/hackathons/iiit_nr_taxi_trip_fare_prediction_challenge/overview"> Taxi Trip Fare Prediction Challenge</a>

<h3>Overview</h3>
This hackathon will try to address the challenges faced by taxi operators in quoting the right fare to customers before starting the trip. However, the details are shared with taxi drivers or operators related to the trip, they find it difficult to quote the right fare because of uncertainties and calculation complexities. The same issue is faced by passengers as well because of inaccurate or irrelevant fares quoted. To find a solution for this, this hackathon provides a historical dataset to participants that includes records of taxi trip details and fares of those trips. Using this dataset, the participants need to build machine learning models for predicting the trip fare based on the given other useful features of the trip.

Overall, it involves using a dataset, finding the best set of features from the dataset, building a machine learning model to predict trip fare based on other trip features and evaluating the predictions using mean squared error and finally submitting the predictions in the given template.

<h3>Data Description </h3>

<b>Trip_distance:</b> The elapsed trip distance in miles reported by the taximeter.</br>
<b>Rate_code:</b> The final rate code is in effect at the end of the trip. 1= Standard rate,2=JFK,3=Newark, 4=Nassau or Westchester, 5=Negotiated fare,6=Group ride.</br>
<b>Storeandfwd_flag:</b> This flag indicates whether the trip record was held in vehicle memory before sending it to the vendor and determines if the trip was stored in the server and forwarded to the vendor. Y= store and forward trip N= not a store and forward trip</br>
<b>Payment_type: </b> A numeric code signifying how the passenger paid for the trip. 1= Credit card,2= Cash, 3= No charge, 4= Dispute, 5= Unknown, 6= Voided trip</br>
<b>Fare_amount:</b> The time-and-distance fare calculated by the meter</br>
<b>Extra:</b> Miscellaneous extras and surcharges.</br>
<b>Mta_tax:</b> $0.50 MTA tax that is automatically triggered based on the metered rate in use.</br>
<b>Tip_amount:</b> Tip amount credited to the driver for credit card transactions.</br>
<b>Tolls_amount:</b> Total amount of all tolls paid in the trip.</br>
<b>Imp_surcharge: </b>$0.30 extra charges added automatically to all rides.</br>
<b>Total_amount:</b> The total amount charged to passengers. Does not include cash tips.</br>
<b>Pickuplocationid:</b> TLC Taxi Zone in which the taximeter was engaged.</br>
<b>Dropofflocationid: </b>TLC Taxi Zone in which the taximeter was disengaged.</br>
<b>Year:</b> The year in which the taxi trip was taken.</br>
<b>Month:</b> The month on which the taxi trip was taken.</br>
<b>Day:</b> The day on which the taxi trip was taken.</br>
<b>Day_of_week:</b> The day of the week on which the taxi trip was taken.</br>
<b>Hour_of_day:</b> Used to determine the hour of the day in 24 hours format.</br>
<b>Trip_duration:</b> The total duration of the trip in seconds.</br>
<b>calculated_total_amount:</b> The total amount the customer has to pay for the taxi.</br>

<h3>Evaluation</h3>
RMSE : Root Mean Squared Error </br>
<p>Can be calculated using : np.sqrt(mse(y_actual, y_predicted))</br></p>

