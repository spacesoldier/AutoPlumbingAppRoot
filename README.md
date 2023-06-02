# AutoPlumbingAppRoot

This is the root repository of the project that was developed on the hackathon. The main purpose was to prototype the application which helps engineer with tracing the plumbing pipes inside the apartment bathroom

# Components

This project consists of several components which placed in their own repositories:
## landing page
Just a simple landing page with feedback form, used as a default entry point to the platform
https://github.com/spacesoldier/AutoPlumbingAppLanding

Biult with Webflow and a bit of handwritten JS script

## platform interface frontend
This is the frontend application which implements UI of the auto plumbing application
https://github.com/spacesoldier/AutoPlumbingAppFront

## an API implementation
Provides API to frontend and implements some logic around receiving and storing the data and interfacing with microservices
https://github.com/spacesoldier/AutoPlumbingAppProtoApi

## dxf parsing service
This microservice parses DXF files into JSON structure so the backend is comfortable to use it
https://github.com/spacesoldier/AutoPlumbingAppDxfParseSrv

## application backend
This is the main part of the application which implements API to iterate over the bathroom plan elements and trace the plumbing pipes
https://github.com/spacesoldier/AutoPlumbingAppBack
