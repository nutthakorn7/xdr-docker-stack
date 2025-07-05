# xdr-docker-stack
# XDR MSSP Docker Stack (Full Version)

xdr-docker-prod/
├── node1-opensearch/
│   └── docker-compose.yml
├── node2-ui-vector/
│   └── docker-compose.yml
├── node3-thehive-cortex/
│   └── docker-compose.yml
├── node4-misp-llm/
│   └── docker-compose.yml
├── node5-nginx-certbot/
│   ├── docker-compose.yml
│   └── init-letsencrypt.sh
├── shared/
│   ├── .env
│   ├── vector/
│   │   └── vector.toml
│   ├── opensearch/
│   │   └── config/
│   ├── dashboards/
│   │   └── config/
│   ├── thehive/
│   └── cortex/
├── README.md
