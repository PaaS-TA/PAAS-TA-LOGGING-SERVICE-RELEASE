# PAAS-TA-LOGGING-SERVICE-RELEASE

  PAAS-TA-LOGGING-SERVICE-RELEASE is based on Elasticsearch 5.x and Kibana 5.

### Create Logging Service Release

* Download the latest Logging Service Release

    ```sh
    $ git clone https://github.com/PaaS-TA/PAAS-TA-LOGGING-SERVICE-RELEASE.git
    ```
    
* Download the latest Logging Service Release
    ```sh
    $ cd PAAS-TA-LOGGING-SERVICE-RELEASE
    # <RELEASE TARBALL PATH> : release file path (e.g /home/ubuntu/workspace/paasta-logging-service-release.tgz)
    $ bosh create-release --force --tarball <RELEASE TARBALL PATH> --name paasta-logging-service-release --version 1.0
    ```  

### 참고 자료  
- https://bosh.io/docs  
- https://www.elastic.co/products/elasticsearch  
- https://www.elastic.co/products/logstash  
- https://www.elastic.co/products/kibana  