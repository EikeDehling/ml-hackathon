# Machine learning hackathon

In this machine learning hackathon we'll explore a dataset about cycle sharing, first part of the day
is going to be exploratory analysis, second part of the day we will do modelling and predictions.

In this hackathon we're using jupyter notebooks running in a docker container, so you'll need docker
installed on your laptop. The dataset is included in the repository and jupyter environment.


## Getting started

The docker/jupyter environment is fired up using a small shell script:

```
 $ ./start.sh
```

The script outputs some startup info and finally a link with token, with which you can access the
notebook environment. You should open that link (click or copy/paste) in your webbrowser.

After opening the notebook environment, you'll see a folder list. Go into the "work" folder and
you'll see an example notebook and the dataset. Start by checking out the example notebook, then
start trying out your own data analysis ideas. (You can create a duplicate if you want)


## Dataset

Pronto cycle share dataset: 
- https://www.kaggle.com/pronto/cycle-share-dataset

```
    Station dataset
        station_id: station ID number
        name: name of station
        lat: station latitude
        long: station longitude
        install_date: date that station was placed in service
        install_dockcount: number of docks at each station on the installation date
        modification_date: date that station was modified, resulting in a change in location or dock count
        current_dockcount: number of docks at each station on 8/31/2016
        decommission_date: date that station was placed out of service
    Trip dataset
        trip_id: numeric ID of bike trip taken
        starttime: day and time trip started, in PST
        stoptime: day and time trip ended, in PST
        bikeid: ID attached to each bike
        tripduration: time of trip in seconds
        from_station_name: name of station where trip originated
        to_station_name: name of station where trip terminated
        from_station_id: ID of station where trip originated
        to_station_id: ID of station where trip terminated
        usertype: "Short-Term Pass Holder" is a rider who purchased a 24-Hour or 3-Day Pass; "Member" is a rider who purchased a Monthly or an Annual Membership
        gender: gender of rider
        birthyear: birth year of rider
    Weather dataset contains daily weather information in the service area
```
