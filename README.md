# SBBTDelayUI

(In-browser) visualiser for train delay data from SBB. Lauzhack 2016 project by @tkw1536, @kuboschek and @Majorka1. 

## Requirements
* A MySQL server somewhere
* Python 3.5
* ```pip3 install -r requirements.txt```

## Usage
### Data Import
1. Download the data from the FTP server and put it into a folder somewhere. 
2. Start the script ```python3 import_data.py``` (and enter the right 
parameters). 
3. Wait for about 30 minutes. 
4. Done, you know have ~5 million items inside the database. 

### Start the webserver
1. Just run ```python3 run_server.py```. 
2. Go to [http://localhost:5000](http://localhost:5000/)


## License
licensed under MIT, see [license.md](license.md)