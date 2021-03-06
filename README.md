<h2 align='center'>
    📄 List of <b><a href='https://en.wikipedia.org/wiki/List_of_HTTP_status_codes'>HTTP</a></b> status codes.
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

<h3 align='center'>
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

<h3 align='center'>
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

<h3 align='center'>
    <b>3XX</b> Redirection:
</h3>

<p>This class of status code <b>Indicates</b> the client <b>Must</b> take <b>Additional Action</b> to complete the <b>Request</b>. Many of these status codes are <b>Used</b> in <b>URL Redirection</b>.</p>
<p>A user agent may carry out the <b>Additional Action</b> with no user interaction only if the method <b>Used</b> in the <b>Second Request</b> is <b>GET</b> or <b>HEAD</b>.</p>

<table>
    <tbody>
        <tr>
            <td><b>300</b> Multiple Choices</td>
            <td>Indicates <b>Multiple Options</b> for the <b>Resource</b> from which the client may <b>Choose</b>.</td>
        </tr>
        <tr>
            <td><b>301</b> Moved Permanently</td>
            <td>This and all future requests should be <b>Directed</b> to the <b>Given</b> a <b>Uniform Resource Identifier</b>.</td>
        </tr>
        <tr>
            <td><b>302</b> Found</td>
            <td>Tells the <b>Client</b> to <b>Look</b> at <b>Another URL</b>.</td>
        </tr>
        <tr>
            <td><b>303</b> See Other</td>
            <td>The response to the request can be <b>Found</b> under <b>Another Uniform Resource Identifier</b> using the <b>GET Method</b>. When <b>Received</b> in response to a <b>POST or PUT</b>, the client should <b>Presume</b> that the <b>Server</b> has <b>Received</b> the <b>Data</b> and should issue a <b>new GET Request</b> to the <b>Given</b> a <b>Uniform Resource Identifier</b>.</td>
        </tr>
        <tr>
            <td><b>304</b> Not Modified</td>
            <td>Indicates that the <b>Resource</b> has <b>Not Been Modified</b> since the <b>Version Specified</b> by the <b>Request Headers</b>.</td>
        </tr>
        <tr>
            <td><b>305</b> Use Proxy</td>
            <td>The requested <b>Resource</b> is <b>Available Only</b> through a <b>Proxy</b>, the <b>Address</b> for which is <b>Provided</b> in the <b>Response</b>.</td>
        </tr>
        <tr>
            <td><b>306</b> Switch Proxy</td>
            <td><b>No</b> longer <b>Used</b>.</td>
        </tr>
        <tr>
            <td><b>307</b> Temporary Redirect</td>
            <td>In this case, the <b>Request</b> should be <b>Repeated</b> with <b>Another Uniform Resource Identifier</b>; however, <b>Future Requests</b> should still <b>Use</b> the <b>Original Uniform Resource Identifier</b>.</td>
        </tr>
        <tr>
            <td><b>308</b> Permanent Redirect</td>
            <td>This and <b>All</b> future <b>Requests</b> should be d<b>Irected</b> to the given a <b>Another Uniform Resource Identifier</b>.</td>
        </tr>
    </tbody>
</table>

<h3 align='center'>
    <b>4XX</b> Client Error:
</h3>

<p>This class of <b>Status Code</b> is intended for <b>Situations</b> in which the <b>Error</b> seems to have been <b>Caused By The Client</b>. These <b>Status Codes</b> are applicable to any <b>Request Method</b>.</p>

<table>
    <tbody>
        <tr>
            <td><b>400</b> Bad Request</td>
            <td>The <b>Server Cannot</b> or will not <b>Process</b> the <b>Request</b> due to an apparent <b>Client Error</b>.</td>
        </tr>
        <tr>
            <td><b>401</b> Unauthorized</td>
            <td>Similar to <b>403 Error</b>, but specifically for use when <b>Authentication</b> is <b>Required</b> and has <b>Failed</b> or has <b>Not</b> yet been <b>Provided</b>. <b>User</b> does <b>Not Have Valid Authentication Credentials</b> for the <b>Target Resource</b>.</td>
        </tr>
        <tr>
            <td><b>402</b> Payment Required</td>
            <td>The original intention was that this code might be used as part of some form of digital cash or micropayment scheme.</td>
        </tr>
        <tr>
            <td><b>403</b> Forbidden</td>
            <td>The <b>Request</b> contained <b>Valid Data</b> and was <b>Understood</b> by the <b>Server</b>, but the <b>Server</b> is <b>Refusing Action</b>. This code is also typically <b>Used</b> if the <b>Request Provided Authentication</b> by answering the <b>WWW-Authenticate Header</b> field challenge.</td>
        </tr>
        <tr>
            <td><b>404</b> Not Found</td>
            <td>The <b>Requested Resource</b> could <b>Not Be Found</b> but may be <b>Available</b> in the <b>Future</b>.</td>
        </tr>
        <tr>
            <td><b>405</b> Method Not Allowed</td>
            <td>A <b>Request</b> method is <b>Not Supported</b> for the <b>Requested Resource</b>.</td>
        </tr>
        <tr>
            <td><b>406</b> Not Acceptable</td>
            <td>The <b>Requested</b> resource is capable of <b>Generating Only Content Not Acceptable According</b> to the <b>Accept Headers</b> sent in the <b>Request</b>.</td>
        </tr>
        <tr>
            <td><b>407</b> Proxy Authentication Required</td>
            <td>The <b>Client</b> must <b>First Authenticate</b> itself with the <b>Proxy</b>.</td>
        </tr>
        <tr>
            <td><b>408</b> Request Timeout</td>
            <td>The <b>Server</b> timed out <b>Waiting</b> for the <b>Request</b>.</td>
        </tr>
        <tr>
            <td><b>409</b> Conflict</td>
            <td>Indicates that the <b>Request</b> could <b>Not Be Processed</b> because of <b>Conflict</b> in the current <b>State</b> of the <b>Resource</b>.</td>
        </tr>
        <tr>
            <td><b>410</b> Gone</td>
            <td>Indicates that the <b>Resource Requested</b> is <b>No Longer Available</b> and will <b>Not Be Available Again</b>. This should be <b>Used</b> when a <b>Resource Has Been Intentionally Removed</b> and the <b>Resource</b> should be <b>Purged</b>.</td>
        </tr>
        <tr>
            <td><b>411</b> Length Required</td>
            <td>The <b>Request Did Not</b> specify the <b>Length</b> of its <b>Content</b>, which is <b>Required</b> by the <b>Requested Resource</b>.</td>
        </tr>
        <tr>
            <td><b>412</b> Precondition Failed</td>
            <td>The <b>Server Does Not</b> meet one of the <b>Preconditions</b> that the <b>Requester</b> put on the <b>Request Header Fields</b>.</td>
        </tr>
        <tr>
            <td><b>413</b> Payload Too Large</td>
            <td>The <b>Request</b> is <b>Larger</b> than the <b>Server</b> is <b>Willing</b> or <b>Able</b> to <b>Process</b>.</td>
        </tr>
        <tr>
            <td><b>414</b> URI Too Long</td>
            <td>The <b>URI Provided</b> was <b>Too Long</b> for the <b>Server To Process</b>. Often the <b>Result</b> of <b>Too Much Data</b> being encoded as a <b>Query-String</b> of a <b>GET Request</b>, in which case it should be <b>Converted</b> to a <b>POST Request</b>.</td>
        </tr>
        <tr>
            <td><b>415</b> Unsupported Media Type</td>
            <td>The <b>Request</b> entity <b>Has A Media Type</b> which the <b>Server</b> or <b>Resource</b> does <b>Not Support</b>.</td>
        </tr>
        <tr>
            <td><b>416</b> Range Not Satisfiable</td>
            <td>The client has <b>Asked</b> for a <b>Portion</b> of the <b>File</b>, but the <b>Server Cannot Supply</b> that <b>Portion</b>.</td>
        </tr>
        <tr>
            <td><b>417</b> Expectation Failed</td>
            <td>The <b>Server Cannot Meet</b> the <b>Requirements</b> of the <b>Expect Request-Header</b> field.</td>
        </tr>
        <tr>
            <td><b>421</b> </td>
            <td>The <b>Request</b> was <b>Directed</b> at a <b>Server</b> that is <b>Not Able</b> to <b>Produce</b> a <b>Response</b>.</td>
        </tr>
        <tr>
            <td><b>422</b> Unprocessable Entity</td>
            <td>The <b>Request</b> was <b>Well-Formed</b> but was unable to be <b>Followed Due</b> to <b>Semantic Errors</b>.</td>
        </tr>
        <tr>
            <td><b>423</b> Locked</td>
            <td>The <b>Resource</b> that is being <b>Accessed</b> is <b>Locked</b>.</td>
        </tr>
        <tr>
            <td><b>424</b> Failed Dependency</td>
            <td>The <b>Request Failed</b> because it <b>Depended</b> on <b>Another Request</b> and that <b>Request Failed</b>.</td>
        </tr>
        <tr>
            <td><b>425</b> Too Early</td>
            <td>Indicates that the <b>Server</b> is <b>Unwilling</b> to <b>Risk Processing</b> a <b>Request</b> that might be <b>Replayed</b>.</td>
        </tr>
        <tr>
            <td><b>426</b> Upgrade Required</td>
            <td>The <b>Client</b> should <b>Switch</b> to a <b>Different Protocol</b>.</td>
        </tr>
        <tr>
            <td><b>428</b> Precondition Required</td>
            <td>The origin <b>Server Requires</b> the <b>Request</b> to be <b>Conditional</b>.</td>
        </tr>
        <tr>
            <td><b>429</b> Too Many Requests</td>
            <td>The <b>User</b> has <b>Sent</b> too <b>Many Requests</b> in a <b>Given Amount</b> of time.</td>
        </tr>
        <tr>
            <td><b>431</b> Request Header Fields Too Large</td>
            <td>The <b>Server</b> is <b>Unwilling</b> to <b>Process</b> the <b>Request</b> because either an <b>Individual Header Field</b>, or <b>All</b> the <b>Header Fields Collectively</b>, are too <b>Large</b>.</td>
        </tr>
        <tr>
            <td><b>451</b> Unavailable For Legal Reasons</td>
            <td>A <b>Server Operator</b> has <b>Received</b> a legal <b>Demand</b> to <b>Deny Access</b> to a <b>Resource</b> or to a set of <b>Resources</b> that includes the <b>Requested Resource</b>.</td>
        </tr>
    </tbody>
</table>

<h3 align='center'>
    <b>5XX</b> Server Error:
</h3>

<p>The <b>Stats Code</b> indicate cases in which the <b>Server</b> is aware that it has <b>Encountered</b> an <b>Error</b> or is otherwise <b>Incapable Of Performing</b> the <b>Request</b>. These response codes are <b>Applicable</b> to <b>Any Request Method</b>.</p>

<table>
    <tbody>
        <tr>
            <td><b>500</b> Internal Server Error</td>
            <td>A <b>Generic Error Message</b>, given when an <b>Unexpected Condition</b> was <b>Encountered</b> and no more <b>Specific Message</b> is <b>Suitable</b>.</td>
        </tr>
        <tr>
            <td><b>501</b> Not Implemented</td>
            <td>The <b>Server</b> either does <b>Not Recognize</b> the <b>Request Method</b>, or it lacks the ability to <b>Fulfil</b> the <b>Request</b>.</td>
        </tr>
        <tr>
            <td><b>502</b> Bad Gateway</td>
            <td>The <b>Server</b> was acting as a <b>Gateway</b> or <b>Proxy</b> and <b>Received</b> an <b>Invalid Response</b> from the <b>Upstream Server</b>.</td>
        </tr>
        <tr>
            <td><b>503</b> Service Unavailable</td>
            <td>The <b>Server Cannot Handle</b> the <b>Request</b>.</td>
        </tr>
        <tr>
            <td><b>504</b> Gateway Timeout</td>
            <td>The <b>Server</b> was acting as a <b>Gateway</b> or <b>Proxy</b> and <b>Did Not Receive</b> a timely <b>Response</b> from the <b>Upstream Server</b>.</td>
        </tr>
        <tr>
            <td><b>505</b>  HTTP Version Not Supported</td>
            <td>The <b>Server</b> does <b>Not Support</b> the <b>HTTP Protocol Version</b> used in the <b>Request</b>.</td>
        </tr>
        <tr>
            <td><b>506</b> Variant Also Negotiates</td>
            <td><b>Transparent</b> content <b>Negotiation</b> for the <b>Request Results</b> in a <b>Circular Reference</b>.</td>
        </tr>
        <tr>
            <td><b>507</b> Insufficient Storage</td>
            <td>The <b>Server</b> is unable to <b>Store</b> the <b>Representation</b> needed to <b>Complete</b> the <b>Request</b>.</td>
        </tr>
        <tr>
            <td><b>508</b> Loop Detected</td>
            <td>The <b>Server</b> detected an <b>Infinite Loop</b> while <b>Processing</b> the <b>Request</b>.</td>
        </tr>
        <tr>
            <td><b>510</b> Not Extended</td>
            <td>Further <b>Extensions</b> to the <b>Request</b> are <b>Required</b> for the <b>Server</b> to <b>Fulfil</b> it.</td>
        </tr>
        <tr>
            <td><b>511</b> Network Authentication Required</td>
            <td>The <b>Client</b> needs to <b>Authenticate</b> to gain <b>Network Access</b>. Intended for use by <b>Intercepting Proxies</b> used to <b>Control Access</b> to the <b>Network</b>.</td>
        </tr>
    </tbody>
</table>