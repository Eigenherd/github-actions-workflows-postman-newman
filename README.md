![GitHub Logo](images/GitHub_Logo_h33.png)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;![Postman Logo](images/Postman-Logo-h33.png)
# GitHub Actions :: Workflows : Postman Newman

This project contains reusable GitHub Actions Pipeline Postman Newman workflows.

## Workflows
### Postman Newman Execution
Purpose: Setup Postman Newman execution

Input parameters:

<table>
  <tr>
    <th>#</th>
    <th>Name</th>
    <th>Datatype</th>
    <th>Description</th>
  </tr>
  <tr>
    <td>1</td>
    <td>environment</td>
    <td>string</td>
    <td>GitLab environment</td>
  </tr>    

  <tr>
    <td>2</td>
    <td>postmanCollectionId</td>
    <td>string</td>
    <td>Postman Collection Id</td>
  </tr>
  <tr>
    <td>3</td>
    <td>postmanEnvironmentId</td>
    <td>string</td>
    <td>Postman Environment Id</td>
  </tr>
  <tr>
    <td>4</td>
    <td>postmanTestingReportIterationCount</td>
    <td>string</td>
    <td>Postman Testing Report Iteration Count</td>
  </tr>
  <tr>
    <td>5</td>
    <td>postmanTestingReportHideRequestBodies</td>
    <td>string</td>
    <td>Postman Testing Report Hide Request Bodies</td>
  </tr>
  <tr>
    <td>6</td>
    <td>postmanTestingReportHideResponseBodies</td>
    <td>string</td>
    <td>Postman Testing Report Hide Response Bodies</td>
  </tr>
  <tr>
    <td>7</td>
    <td>postmanTestingReportSkipEnvironmentVars</td>
    <td>string</td>
    <td>Postman Testing Report Skip Environment Variables</td>
  </tr>
  <tr>
    <td>8</td>
    <td>postmanTestingReportSkipHeaders</td>
    <td>string</td>
    <td>Postman Testing Report Skip Headers</td>
  </tr>
  <tr>
    <td>9</td>
    <td>postmanTestingReportFilename</td>
    <td>string</td>
    <td>Postman Testing Report Filename</td>
  </tr>
  <tr>
    <td>10</td>
    <td>Customer Name</td>
    <td>string</td>
    <td>Customer Name</td>
  </tr>
</table>

Secrets:

<table>
  <tr>
    <th>#</th>
    <th>Name</th>
    <th>Description</th>
  </tr>
  <tr>
    <td>1</td>
    <td>GHCR_PAT</td>
    <td>GHCR Personal Access Token</td>
  </tr>
  <tr>
    <td>2</td>
    <td>POSTMAN_API_KEY</td>
    <td>Postman API Key</td>
  </tr>
  <tr>
    <td>3</td>
    <td>COMMAND_ADDITIONAL_PARAMETERS</td>
    <td>Postman Newman Command Additional Parameters</td>
  </tr>
</table>