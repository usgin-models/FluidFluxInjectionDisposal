This repository contains document artifacts for an inforamtion exchange for fluid flux of injection or disposal from a well. The artifacts include an Excel Workbook that defines and documents the content model, and an XML schema that implements the model.

The Excel workbook documents fluid fluxes into or out of a well. A generic model is intended to allow for oil, gas, or water injection (negative flow). The focus of this observation type is on injection (any fluid flowed into well) or disposal. Because of the wide variety of possible flow measurements (commodities, aggregation type), the model adopts a thin approach, which may result in many records being returned for a single well. Thus most data about the well is linked through the HeaderURI instead of included inline to keep the redundant data volume down.


No services are currently deployed using this information exchange.