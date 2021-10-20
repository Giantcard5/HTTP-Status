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
    <b>1XX</b> Informational Response:
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

<h3 align="center">
    <b>2XX</b> Success:
</h3>

<p>This class of status codes <b>Indicates</b> the <b>Cction Requested</b> by the <b>Client</b> was <b>Received</b>, <b>Understood</b>, and <b>Cccepted</b>.</p>

<table>
    <tbody>
        <tr>
            <td><b>200</b> OK</td>
            <td>Standard response for <b>Successful HTTP Requests</b>. In a <b>GET Request</b>, the response will <b>Contain</b> an entity <b>Corresponding</b> to the <b>Requested Resource</b>. In a <b>POST Request</b>, the response will <b>Contain</b> an entity <b>Describing</b> or <b>Containing</b> the result of the <b>Action</b>.</td>
        </tr>
        <tr>
            <td><b>201</b> Created</td>
            <td>The request has been <b>Fulfilled</b>, <b>Resulting</b> in the creation of a <b>New Resource</b>.</td>
        </tr>
        <tr>
            <td><b>202</b> Accepted</td>
            <td>The request has been <b>Accepted</b> for <b>Processing</b>, but the <b>Processing</b> has <b>Not Been Completed</b>. The request <b>Might</b> or <b>Might</b> not be <b>Eventually Acted Upon</b>, and may be <b>Disallowed</b> when <b>Processing Occurs</b>.</td>
        </tr>
        <tr>
            <td><b>203</b> Non-Authoritative Information</td>
            <td>The <b>Server</b> is a <b>Transforming Proxy</b> that <b>Received</b> a <b>200</b> from its <b>Origin</b>, but is <b>Returning</b> a <b>Modified Version</b> of the origin's response.</td>
        </tr>
        <tr>
            <td><b>204</b> No Content</td>
            <td>The <b>Server Successfully Processed</b> the <b>Request</b>, and is <b>Not Returning</b> any <b>Content</b>.</td>
        </tr>
        <tr>
            <td><b>205</b> Reset Content</td>
            <td>The <b>Server Successfully Processed</b> the <b>Request</b>, asks that the <b>Requester Reset</b> its <b>Document View</b>, and is <b>Not Returning</b> any <b>Content</b>.</td>
        </tr>
        <tr>
            <td><b>206</b> Partial Content</td>
            <td>The <b>Server</b> is <b>Delivering Only</b> part of <b>The Resource Due</b> to a <b>Range Header Sent</b> by the <b>Client</b>. The <b>Range Header</b> is <b>Used</b> by <b>HTTP Clients</b> to <b>Enable Resuming</b> of <b>Interrupted Downloads</b>, or <b>Split a Download</b> into multiple simultaneous streams.</td>
        </tr>
        <tr>
            <td><b>207</b> Multi-Status</td>
            <td>The <b>Message</b>e body that <b>Follows</b> is by <b>Default an XML Message</b> and can <b>Contain a Number</b> of <b>Separate Response Codes</b>, <b>Depending</b> on <b>How Many Sub-Requests</b> were <b>Made</b>.</td>
        </tr>
        <tr>
            <td><b>226</b> IM Used</td>
            <td>The <b>Server</b> has <b>Fulfilled a Request</b> for the <b>Resource</b>, and the <b>Response</b> is a <b>Representation</b> of <b>The Result</b> of one or <b>More Instance-Manipulations</b> applied to the <b>Current Instance</b>.</td>
        </tr>
    </tbody>
</table>
