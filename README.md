# Alfresco document fetcher command line

Alfresco document fetcher command line for python is compatibility with python3.5+

```bash
pip install requests ftfy
```

This __app__ help alfresco developper to export all folder structure

Usage:

```bash
python main.py [-h] -sn SERVICENAME [-hn HOSTNAME] [-rf root_folder] [-bsf BASE_STORAGE_FOLDER] [-u username] [-p PASSWORD] -o OUTPUT
```

## Arguments

```bash
-h, --help show this help message and exit
-sn SERVICENAME, --servicename SERVICENAME Service name
-hn HOSTNAME, --hostname HOSTNAME Alfresco host url or hostname
-rf ROOT_FOLDER, --root_folder ROOT_FOLDER Alfresco base folder
-bsf BASE_STORAGE_FOLDER, --base_storage_folder BASE_STORAGE_FOLDER
Storage path for local system
-u USERNAME, --username USERNAME Alfresco auth username
-p PASSWORD, --password PASSWORD Alfresco auth password
-o OUTPUT, --output OUTPUT Output file in csv
```

### Explain

__SERVICENAME__ : Is endpoint you want to crawl
__ROOT_FOLDER__ : Is base endpoint
