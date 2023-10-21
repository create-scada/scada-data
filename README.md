Provides sample solar monitoring logs for Impact Allies' SCADA software, generated from solar-inverters running scada-client. The scada-client repository can be found [here](https://github.com/create-scada/scada-client). 

Format: {"_id":{"$oid":"6170d3c633da1eb412b85852"},"rtu_address":"madison-college.reedsburg","device_address":"controller1","point_data":{"pv_power":0.0,"temp":59.0,"skies":"LightRain"},"date":{"$date":"2021-10-21T02:43:18.676Z"}}

OID is the unique ID for the current reading. The rtu address is a structured name for the location. Device address is the individual controller at the site that is collecting the data. Point data provides the power reading, temperature in Fahrenheit, and a description of the weather. Date is the date of the current reading. 
