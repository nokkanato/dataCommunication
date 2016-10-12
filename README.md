# dataCommunication


import socket as skt
import os
import sys
from urlparse import urlparse

make argument Command line
use urlparse to get hostname, path, port

make class Downloader
    urlVerification() - use to add "http://" if it does not exist
    makeGet() - make GET request
    openConnection() - Connect Socket
    closeConnection() - close socket
    makeHeader() - extract the content length
    checkContent() - check whether content exist or not
    downloadWithContent() - download when http give back content
    downloadWithoutContent() - download when http doesnot give content-length
    checkPort() - checkPort whether is it default
    main() - check urlverification 
            check port 
            check content
            if exist go to downloadWithContent
            else go to downloadWithoutContent
 

    

    

    
        


    



   

    





