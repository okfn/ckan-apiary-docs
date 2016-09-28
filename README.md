# CKAN APIARY Docs
Home of documentation


The `ckan.apib` file gets used by the Fabre tool to generate the Fiware-flawored API Docs:

    docker run -it --rm -v /home/adria/dev/pyenvs/fiware/src/:/apib -v /home/adria/dev/pyenvs/fiware/src/tools.Fabre/html:/html fiware/fabre -i /apib/ckan-2.6.apib -o /html/ckan-2.6
