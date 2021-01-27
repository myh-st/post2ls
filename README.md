post2ls
=========

ansible uri module for post JSON data format to Logstash

Requirements
------------

JSON file
Logstash biding input (http)

Role Variables
--------------
    elk_ip: "IP"
    es_port: "ES_PORT"
    ls_port: "LS_PORT"
    es_user: "USERNAME"
    es_pass: "PASSWORD"
    csv2json: "JSON_FILE"


Example Playbook
----------------


    ---
    - hosts: localhost
     roles:
      - post2ls

License
-------

BSD

Author Information
------------------

My name is MYH. I'm Developer.
