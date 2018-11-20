
# Politics Tech Challenge


# Backend
WEB API deploy on Heroku:
https://pure-mountain-71887.herokuapp.com/
(/politicians) 
    -Get: List of politicians
    -Post: Send or get Out of Jail
  -     >  params: {
            politicianid :id,
            jail:bool
        }
(/support)
  - Post:  Generate Some Data
  -     > params : amount int
## Implementation

### Installation

1 - Clone de project
```
git clone github.com/PedroPascoal6/politician-lj
```

2 - Please make sure you have a .env. 

3 - Install dependencies
```
pip3 install requirements.txt
```

4 - Run
```
python3 app.py
python3 -m unittest (Unit Tests)
```

5 - At this point, website should be running on http://127.0.0.1:5000/


# Front-End
Front-End Deploy on Heroku: 
https://tranquil-hamlet-22768.herokuapp.com
