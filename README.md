# Magento_Information


### Magento Information Gathering

This script is designed to quickly gather information about specific magento sites located on Linux devices. 


`wget https://raw.githubusercontent.com/LukeShirnia/magento_information/master/magento_info.py`

`sha1sum magento.py`

Output:

`0d3114b08f5423c2c7dbe3d309567f8c456823b1  magento_info.py`

<br />

```
Usage: magento_info.py [option]

Options:
  -h, --help    show this help message and exit
  -a, --apache  Check apache webserver for magento sites
  -n, --nginx   Check nginx webserver for magento sites
```


* Works on CentOS/RHEL
* Designed to work on Ubuntu/Debian...Not yet tested


<br />


### XML Parsing

If you would ONLY like to parse the local.xml file you can use the following script:
<br />
Replace "local.xml" in the command below with the full path to your file.


```
curl -s https://raw.githubusercontent.com/LukeShirnia/magento_information/master/Parsing_XML.py | python - local.xml
```

