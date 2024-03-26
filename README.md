
# REST API to SOAP Service Transformation with WSO2 Integration Studio

## Project Description

This project aims to transform an existing REST API into a SOAP service using WSO2 Integration Studio. The objective is to enable integration with systems that only support the SOAP protocol. The "Petstore" REST API will be exposed via a REST endpoint and consumed by a system that only supports the SOAP protocol. WSO2 ESB will be used to create a service that transforms REST requests into SOAP messages and transfers them to a SOAP backend service to generate a WSDL Endpoint.

## Project Details

- **Languages/Technologies Used**: WSO2 Integration Studio, REST, SOAP
- **REST API Repository**: [Link to REST API](https://petstore.swagger.io/v2/swagger.json)

## How to Run

### Prerequisites
- [WSO2 Integration Studio](https://wso2.com/integration/integration-studio/)
- Internet access to download necessary dependencies and plugins

### Execution Instructions

1. Clone this repository to your local machine.
   ```bash
   git clone https://github.com/saiflayouni/useCase.git
   ```

2. Open WSO2 Integration Studio.

3. Import the project into WSO2 Integration Studio.
   - Go to `File` > `Import`.
   - Choose `Existing WSO2 Projects into workspace`.
   - Select the directory of the cloned project.
   - Click `Finish`.

4. Deploy the service in WSO2 Integration Studio.
   - Right-click on the project in the project explorer.
   - Choose `Run As` > `Run On Server`.
   - Follow the instructions to deploy the service.

5. Access the URL of the deployed service to test the functionalities.
   - By default, the URL might be `http://localhost:8280/<service_name>`.
   - Replace `<service_name>` with the name of the service you deployed.

