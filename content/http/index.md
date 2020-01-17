<!--
title: Life in HTTP
description: Events in my life as HTTP status codes
website: http://zeke.sikelianos.com/http
keywords: [http, twitter, absurdism]
layout: false
publish_date: 2011-08-08
end: 2011-08-08
-->

<head>
  <meta http-equiv="Content-type" content="text/html; charset=utf-8">
  <title>http response codes</title>
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <style type="text/css" media="screen">

    body {
      font-family: "Anonymous Pro", "Menlo", "Consolas", "Bitstream Vera Sans Mono", "Courier New", monospace;
      font-size: 12px;
      padding: 20px;
    }

    body > p {
      margin: 80px 0 20px 0;
      padding: 0;
      color: black;
      color: #999;
    }

    body > p > a {
      margin: 0;
      padding: 0;
      background-color: red;
      color: white;
      text-decoration: none;
      padding: 3px 3px 3px 3px;
    }

    body > p > a > span {
      color: pink;
    }

    body > p > a:hover {
      background-color: black;
    }

    body > ul {
      display: block;
      float: none;
      clear: both;
      margin: 30px 0 0 0;
      padding: 0;
      list-style: none;
    }

    body > ul > li {
      margin: 0;
      padding: 0;
      display: block;
      float: left;
      border-top: 5px solid black;
      width: 220px;
      margin-right: 20px;
    }

    body > ul > li > ul {
      margin: 0;
      padding: 0;
      list-style: none;
    }

    body > ul > li > ul > li {
      font-size: 10px;
      padding: 2px 0 2px 0;
    }

    body > ul > li > ul > li:first-child {
      padding: 3px 0 10px 0;
    }

  </style>
</head>

<body>

  <p>

    <a href="http://twitter.com/zeke_in_http"><span>@</span>zeke_in_http</a>
    status code reference
  </p>

  <ul>
    <li>
      <ul>
        <li>Informational</li>
        <li>100 Continue</li>
        <li>101 Switching Protocols</li>
        <li>102 Processing</li>
      </ul>
    </li>

    <li>
      <ul>
        <li>Success
        <li>200 OK
        <li>201 Created
        <li>202 Accepted
        <li>203 Non-Authoritative Information
        <li>204 No Content
        <li>205 Reset Content
        <li>206 Partial Content
        <li>207 Multi-Status
        <li>226 IM Used</li>
      </ul>
    </li>

    <li>
      <ul>
        <li>Redirection
        <li>300 Multiple Choices
        <li>301 Moved Permanently
        <li>302 Moved Temporarily (HTTP 1.0)
        <li>302 Found (HTTP 1.1)
        <li>303 See Other (HTTP 1.1)
        <li>304 Not Modified
        <li>305 Use Proxy
        <li>306 (no longer used, but reserved)
        <li>307 Temporary Redirect</li>
      </ul>
    </li>

    <li>
      <ul>
        <li>Client Error
        <li>400 Bad Request
        <li>401 Unauthorized
        <li>402 Payment Required
        <li>403 Forbidden
        <li>404 Not Found
        <li>405 Method Not Allowed
        <li>406 Not Acceptable
        <li>407 Proxy Authentication Required
        <li>408 Request Timeout
        <li>409 Conflict
        <li>410 Gone
        <li>411 Length Required
        <li>412 Precondition Failed
        <li>413 Request Entity Too Large
        <li>414 Request-URI Too Long
        <li>415 Unsupported Media Type
        <li>416 Requested Range Not Satisfiable
        <li>417 Expectation Failed
        <li>422 Unprocessable Entity
        <li>423 Locked
        <li>424 Failed Dependency
        <li>426 Upgrade Required</li>
      </ul>
    </li>

    <li>
      <ul>
        <li>Server Error
        <li>500 Internal Server Error
        <li>501 Not Implemented
        <li>502 Bad Gateway
        <li>503 Service Unavailable
        <li>504 Gateway Timeout
        <li>505 HTTP Version Not Supported
        <li>507 Insufficient Storage
        <li>510 Not Extended</li>
      </ul>
    </li>
  </ul>
</body>
