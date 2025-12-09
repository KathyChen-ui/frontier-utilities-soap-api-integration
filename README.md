🧩 Frontier Utilities SOAP API Integration – XML Authentication & Product Retrieval
A Python script demonstrating XML-based SOAP API authentication and product data extraction.
This project connects to the Frontier Utilities SOAP Web API, authenticates using XML credentials, retrieves a SessionID, and then sends a second SOAP request to fetch product listings.

Working with SOAP APIs (older enterprise systems)
Crafting XML payloads
Handling SOAP envelopes
Parsing XML responses using BeautifulSoup
Managing authenticated sessions
Python automation for API-driven ETL workflows

🌟 Project Overview

Many enterprise systems still use legacy SOAP APIs rather than REST.
This project demonstrates how to:
Authenticate using an XML SOAP request
Parse the API’s SOAP response to extract a SessionID
Use the SessionID to request product information (e.g., energy plans)
Parse and print the API’s XML response
This is a common real-world scenario in utilities, telecom, healthcare, insurance, and government systems.

🚀 Key Features

✔ Sends SOAP-based XML requests using Python
✔ Authenticates via username/password to generate a SessionID
✔ Demonstrates session-based API workflows
✔ Fetches product/plan data from Frontier Utilities API
✔ Parses XML using BeautifulSoup (xml parser)
✔ Builds two-stage request flow: Authentication ➝ Data Retrieval
✔ Shows how to use custom headers + cookies\

🛠️ Tech Stack

Python 3
requests – for HTTP POST requests
BeautifulSoup (xml parser) – for XML parsing
SOAP Protocol
XML formatting & payload construction
