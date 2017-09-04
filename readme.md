# Machine learning hackathon

In this machine learning hackathon we'll explore a dataset about cycle sharing, first part of the day
is going to be exploratory analysis, second part of the day we will do modelling and predictions.

In this hackathon we're using jupyter notebooks running in a docker container, so you'll need docker
installed on your laptop. The dataset is included in the repository and jupyter environment.


## Getting started

The docker/jupyter environment is fired up using a small shell script:

```
   $ ./start.sh

   ...

    Copy/paste this URL into your browser when you connect for the first time,
       to login with a token:
          http://localhost:8888/?token=575a53d5c6c8256093550b65c0f24777fe427986143e55d8

```

The script outputs some startup info and finally a link with token, with which you can access the
notebook environment. You should open that link (click or copy/paste) in your webbrowser.

![Notebook Environment](https://github.com/EikeDehling/ml-hackathon/raw/master/jupyter-home.png "Notebook Environment")

After opening the notebook environment, you'll see a folder list. Go into the "work" folder and
you'll see an example notebook and the dataset. Start by checking out the example notebook, then
start trying out your own data analysis ideas. (You can create a duplicate if you want)


## Dataset

The dataset in this hackathon is from a cycle sharing project in seattle. It includes information on
bicycle stations, trips and weather info. The data is provided as CSV files.

The stations data can be slightly ambiguous, so we'll list the fields and their explanation here:
- station_id: station id
- name: name of station
- lat: station geo latitude
- long: station geo longitude
- install_date: date station was placed in service
- install_dockcount: number of docks on the installation date
- modification_date: most recent date station was modified
- current_dockcount: number of docks on 8/31/2016
- decommission_date: date station was decommissioned
