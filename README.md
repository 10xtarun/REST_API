# REST_API
This project explains working of REST API, concepts and how to build an API in Node.js
------------------------------------------------------
What and Why ?
Not every UI requires HTML pages.
eg.- Mobile Apps - Twitter -> backend includes Python,      Java, etc.
    - Single Page APP -> no page refresh
    - fetches the required data only
    - Service APIs (Google Maps)
    - Multiple Frontend (Decoupled)

Different Response:
REpresentational State Transfer (REST)
Transfer data instead of UI
------------------------------------------------------
REST API Big Picture
Data is transferred between 
    - App Backend API and Mobile App and SPA
    - Service API and Any App
------------------------------------------------------
Data Formats:
|- HTML -> Data + Structure -> UI -> Difficult to parse
|- Plain Text -> Data -> No UI -> difficult to parse
|- XML -> Data -> No UI -> Machine-readable but needs XML-parser (overhead)
|- JSON -> Data -> No UI -> Machine-readable and easily converted to JS
------------------------------------------------------
Routing:
|- using Methods and paths
|- Known as API Endpoints
------------------------------------------------------
REST Principles:
|1. Uniform Interface -> clear endpoints -> should be predictable 
|2. Stateless Interactions -> Server and client are separated -> every request handled separately

|1. Cacheable -> client can cache responses
|2. Layered System -> Server may forward requests to other APIs
------------------------------------------------------
