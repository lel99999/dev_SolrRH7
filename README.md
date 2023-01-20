# dev_SolrRH7
Solr Development and Deployment

#### Operational Instructions
- SSH into <solr_system>
- check if service is still running/port 8983 is being used
  ```
  $sudo netstat -tulnap | grep 8983
  ```
- cd into /opt/solr
- start solr
  ```
  $sudo java -jar start.jar &
  ```
