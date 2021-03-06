# Data Dump

Data dump for various information.

Information are stored as json files and can be obtained via **GET** request.

### Disclaimer

All data belongs to their rightful owner and will be removed upon request.

### Monash Data Collection

Host : https://jianloong.github.io/data/monash/

Version: V1

Simple API that allow consumers to view unit information.

| URI             | Description                    |
|:----------------|:-------------------------------|
| v1/units.json   | List of units                  |
| v1/FIT9131.json | Returns information of FIT9131 |

#### Example

````code
wget https://jianloong.github.io/data/monash/v1/units.json
````

````code
wget https://jianloong.github.io/data/monash/v1/FIT9131.json
````

### MARA Data Collection

Host : https://jianloong.github.io/data/mara/

This information is obtained from https://www.mara.gov.au

All information rightfully belongs to them. 

Version: V1

Simple API that allows consumer to view MARA agent information

| URI            | Description                        |
|:---------------|:-----------------------------------|
| v1/agents.json | List of agents                     |
| v1/{id}.json   | Returns information of specific Id |

#### Example

````code
wget https://jianloong.github.io/data/mara/v1/agents.json
````

````code
wget https://jianloong.github.io/data/mara/v1/0000048.json
````

