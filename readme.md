# Machine learning hackathon

Pronto cycle share dataset: 
- https://www.kaggle.com/pronto/cycle-share-dataset

## Data

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
