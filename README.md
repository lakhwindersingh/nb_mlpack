# nb_quantlib
MLpack container with Jupyter and Python bindings for rapid prototying.

Docker compose expects location at line 15 in docker-compose.yml, currently pointing towards </data/code/projects/notebook>, which will be mapped to /home/jupyter/notebook. Replace this prior to running following commands.

Run following command to build the quantlib from the source with python bindings.

        docker-compose build

Run following command to bring up quantlib on local port 8282

        docker-compose up
        
Point your browser to https://0.0.0.0:8282 or https://127.0.0.1:8282 to run quantlib python samples        


                                                              Courtesy - Infectolabs@ Neutron Binary LLC
