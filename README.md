<h2 align="center">
    📄 List of <b>HTTP</b> status codes.
</h2>

<p>This is a list of Hypertext Transfer Protocol <b>( HTTP )</b> response status codes.</p>

<p>The first digit of the status code specifies one of five standard classes of responses.</p>

<p>All HTTP response status codes are separated into five classes or categories. The first digit of the status code defines the class of response, while the last two digits do not have any classifying or categorization role. There are five classes defined by the standard:</p>

<table>
    <thead>
        <tr>
            <th>Status Codes</th>
            <th></th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td><b>1XX</b> Informational Response</td>
            <td>The request was <b>Received</b>, continuing process.</td>
        </tr>
        <tr>
            <td><b>2XX</b> Successful</td>
            <td>The request was successfully <b>Received</b>, <b>Understood</b>, and <b>Accepted</b>.</td>
        </tr>
        <tr>
            <td><b>3XX</b> Redirection</td>
            <td>Further action needs to be taken in order to complete the request.</td>
        </tr>
        <tr>
            <td><b>4XX</b> Client Error</td>
            <td>The request <b>Contains Bad Syntax</b> or <b>Cannot Be Fulfilled</b>.</td>
        </tr>
        <tr>
            <td><b>5XX</b> Server Error</td>
            <td>The server <b>Failed</b> to fulfil an apparently <b>Valid Request</b>.</td>
        </tr>
    </tbody>
</table>

<h3 align="center">
    <b>1XX</b> Informational Response
</h3>

<p>An informational response indicates that the request was <b>Received</b> and <b>Understood</b>. It alerts the client to <b>wait</b> for a <b>Final Response</b>.</p>

<table>
    <tbody>
        <tr>
            <td><b>100</b> Continue</td>
            <td>The server has <b>Received</b> the <b>Request Headers</b> and the <b>Client</b> should <b>Proceed</b> to send the request body ( <b>POST Request</b> for example ).</td>
        </tr>
        <tr>
            <td><b>101</b> Switching Protocols</td>
            <td>The requester has asked the server to <b>Switch Protocols</b> and the <b>Server</b> has <b>Agreed</b> to do so.</td>
        </tr>
        <tr>
            <td><b>102</b> Processing</td>
            <td>This code indicates that the <b>Server</b> has <b>Received</b> and is <b>Processing</b> the <b>Request</b>, but <b>No Response</b> is available yet.</td>
        </tr>
        <tr>
            <td><b>103</b> Early Hints</td>
            <td>Used to <b>Return</b> some <b>Response Headers</b> before final HTTP message.</td>
        </tr>
    </tbody>
</table>
