

## • API Setup
* Go to http://my.telegram.org  and log in.
* Click on API development tools and fill the required fields.
* put app name you want & select other in platform Example :
* copy "api_id" & "api_hash" after clicking create app ( will be used in setup.py )

## • How To Install and Use


* Install requierments

`$ python setup.py -i`

* setup configration file ( apiID, apiHASH )

`$ python setup.py -c`

* To Genrate User Data

`$ python scraper.py`

* ( members.csv is default if you changed name use it )

* To Add Users To Group
  
  `$ python add2group.py members.csv `

* Update Tool

`$ python setup.py -u`
