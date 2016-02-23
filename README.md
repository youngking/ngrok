[![Build
status](https://travis-ci.org/veonik/ngrok.svg)](https://travis-ci.org/veonik/ngrok)

# veonik's ngrok fork

## What is ngrok?
[ngrok](http://ngrok.com) is a reverse proxy that creates a secure tunnel from a public endpoint to a locally running web service.
ngrok captures and analyzes all traffic over the tunnel for later inspection and replay.

This is a fork of ngrok 1.0 and is intended for personal use.

## What can I do with ngrok?
- Expose any http service behind a NAT or firewall to the internet on a subdomain of ngrok.com
- Expose any tcp service behind a NAT or firewall to the internet on a random port of ngrok.com
- Inspect all http requests/responses that are transmitted over the tunnel
- Replay any request that was transmitted over the tunnel


## What is ngrok useful for?
- Temporarily sharing a website that is only running on your development machine
- Demoing an app at a hackathon without deploying
- Developing any services which consume webhooks (HTTP callbacks) by allowing you to replay those requests
- Debugging and understanding any web service by inspecting the HTTP traffic
- Running networked services on machines that are firewalled off from the internet

## Developing on ngrok
[ngrok developer's guide](docs/DEVELOPMENT.md)
