
![MAppMundiAPI Banner](https://github.com/iCamilo/MAppCountriesTestAPI/assets/8431922/644504b5-9411-4434-8149-25bad5b2687d)


# MAppMundiTestAPI

A test API for the endpoints required by [MAppMundi](https://github.com/iCamilo?tab=repositories#:~:text=Star-,CountriesApp,-Private) Mobile Application. 
I use this repository mainly for end to end testing, with controlled responses. 

For the API server I am using [My JSON Server](https://my-json-server.typicode.com/)

## Endpoints

<details>
<summary>GET all</summary>

```json
GET https://my-json-server.typicode.com/iCamilo/MAppMundiTestAPI/all
200 Response

[
 {
   "name": {
      "common": "United Kingdom",
      "official": "United Kingdom of Great Britain and Northern Ireland"
   },
   "capital": [
      "London"
   ],
   "flags": {
      "png": "https://flagcdn.com/w320/gb.png",
      "svg": "https://flagcdn.com/gb.svg",
      "alt": "The flag of the United Kingdom — the Union Jack — has a blue field.  ..."
    }
 },
{
   "name": {
      "common": "South Africa",
      "official": "Republic of South Africa"
   },
   "capital": [
       "Pretoria",
       "Bloemfontein",
       "Cape Town"
   ],
   "flags": {
      "png": "https://flagcdn.com/w320/za.png",
      "svg": "https://flagcdn.com/w320/za.svg",
      "alt": "The flag of South Africa is composed of two equal horizontal bands ... "
    }
 },
{
   "name": {
      "common": "Bouvet Island",
      "official": "Bouvet Island"
   },
   "flags": {
      "png": "https://flagcdn.com/w320/bv.png",
      "svg": "https://flagcdn.com/w320/bv.svg",      
    }
 }
]

```

  
<details>
