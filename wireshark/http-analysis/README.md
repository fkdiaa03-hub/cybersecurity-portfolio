# HTTP Traffic Analysis with Wireshark

## Objective

Practice analyzing HTTP traffic in Wireshark and identifying important information from requests and responses.

## Tools

- Wireshark
- An authorized practice PCAP or lab capture

## Concepts

### HTTP Request

An HTTP request is sent by a client to a server to request a resource or perform an action.

```text
Client  ---- HTTP Request ----> Server
```

### HTTP Response

The server sends an HTTP response back to the client.

```text
Client  <--- HTTP Response ---- Server
```

### Client and Server

The client initiates the request. The server receives it and sends a response.

## Information to Identify

- Source IP address
- Destination IP address
- Source port
- Destination port
- HTTP method
- Requested resource
- HTTP response status, when present

## HTTP and HTTPS

HTTP traffic is not encrypted by HTTP itself, so its application-layer content may be readable in a packet capture. HTTPS protects HTTP communication using TLS encryption, although some connection metadata may still be visible.

## Key Takeaways

- IP addresses identify network endpoints.
- Ports help identify the communication endpoints used by applications.
- The client initiates the request and the server responds.
- Wireshark can display packet and protocol details.

## Practice Notes

Add your own lab observations and screenshots after removing private, sensitive, or identifying information. Use only traffic you are authorized to inspect.
