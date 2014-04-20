Ready to mock some sensors?
=======

Let's run dilbert.py

```bash
python dilbert.py
```

First thing it will ask for is the type of sensor you want to mock

```bash
What type of sensor would you like to mock?
1) iBeacon (Presence)
2) Temperature
3) Proximity
```

Define the interval in seconds in which Dilbert will generate data

```bash
How frequent (in seconds) do you want Dilbert to sense?: 5
```

Dilbert can output the data to different places. In this case we will select POST to an Endpoint. As it is the most common use case. 

```bash
Please select an output format
1) POST to an Endpoint
2) Print in console
3) Save locally into Json file
Choose your option:  1
```

Type the endpoint URL where you are going to receive the Json POST that the raspberry will send

```bash
Type endpoint URL where Dilbert should POST the data: http://myamazingapp.com/backend/getRaspberryData
```

At this point you should see Dilbert start generating Random data and sending it to the Cloud. 
Simulating Mobile Devices approaching to the iBeacon sensor in the RaspberryPi every 5 seconds. 

```bash
{
  "id": "326E8E9C-9259-5425-8CF6-AACA4E550D91",
  "first": "Alexandra",
  "last": "Pierce",
  "email": "ca@ol.io",
  "age": 19,
  "state": "AR",
  "gender": "Male",
  "timestamp": "2038-10-09T03:07:40.323Z"
}
Sending POST to http://myamazingapp.com/backend/getRaspberryData
```

### Enjoy!