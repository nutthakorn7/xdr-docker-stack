# xdr-docker-stack
# XDR MSSP Docker Stack (Full Version)

โครงสร้าง Docker Stack สำหรับ PoC หรือ Production ที่รวมเครื่องมือหลักสำหรับ SOC / MSSP พร้อมใช้งานได้ทันที

xdr-docker-stack/
├── docker-compose.yml                     # Stack หลัก
├── .env                                   # ตัวแปรลับ เช่น password, token
├── opensearch/                            # OpenSearch config
│   └── config/
│       └── opensearch.yml
├── dashboards/                            # OpenSearch Dashboards config
│   └── dashboards.yml
├── thehive/                               # TheHive config
│   ├── application.conf
│   └── docker-entrypoint.sh
├── cortex/                                # Cortex config
│   ├── application.conf
│   └── analyzers/
│       └── config.json
├── misp/                                  # MISP Threat Intel Platform
│   ├── Dockerfile
│   └── config.sh
├── vector/                                # Vector log pipeline
│   └── vector.toml
├── gpt/                                   # GPT Agent Assistant
│   ├── gpt-agent.py
│   └── requirements.txt
└── README.md                              # คู่มือการใช้งาน Stack
