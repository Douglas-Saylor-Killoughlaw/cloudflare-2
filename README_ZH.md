[English](./README.md) | [简体中文](./README_ZH.md)

![Cloudflare](./document/image/cf-logo.jpg)
<div style="font-size: 11px;color: #6c757d!important;font-weight: 400;">注：Cloudflare®图形商标版权归 Cloudflare, Inc. 所有。.</div>
# Cloudflare
这个 Cloudflare Java 客户端支持 [Cloudflare 的 API v4](https://api.cloudflare.com/) ，允许您更快更轻松地访问Cloudflare的API的每一个特性！ 
要使用Maven或Gradle构建需要添加依赖项，请使用以下命令：

**Maven:**
```xml
<dependency>
  <groupId>net.renfei</groupId>
  <artifactId>cloudflare</artifactId>
  <version>0.0.1</version>
</dependency>
```

**Gradle:**
```
dependencies {
  compile 'net.renfei:cloudflare:0.0.1'
}
```

## Getting Started
Getting Started

## 支持的接口端点
- [ ] User
- [ ] User API Tokens
- [ ] Permission Groups
- [ ] User's Account Memberships
- [ ] Accounts
- [ ] Account Members
- [ ] Account Roles
- [ ] Account Subscriptions
- [ ] Organizations
- [ ] Organization Invites
- [ ] Organization Members
- [ ] Organization Roles
- [ ] User's Invites
- [ ] User's Organizations
- [ ] User Billing Profile
- [ ] User Billing History
- [ ] User Subscription
- [ ] Account Billing Profile
- [ ] Zone Rate Plan
- [ ] Zone Subscription
- [ ] Audit Logs
- [ ] Argo Smart Routing
- [ ] Argo Analytics for Zone
- [ ] Argo Analytics for Geolocation
- [x] Zone
- [ ] Zone Setting
- [ ] Zone Analytics
- [ ] Logs Received
- [ ] Logpush Jobs
- [ ] DNS Records for a Zone
- [ ] DNS Analytics
- [ ] DNSSEC
- [ ] DNS Firewall
- [ ] DNS Firewall Analytics
- [ ] Secondary DNS
- [ ] Secondary DNS (TSIG)
- [ ] Secondary DNS (Primary)
- [ ] Cloudflare IPs
- [ ] Custom Pages for a Zone
- [ ] Custom SSL for a Zone
- [ ] Custom Hostname for a Zone
- [ ] Custom Hostname Fallback Origin for a Zone
- [ ] Keyless SSL for a Zone
- [ ] Analyze Certificate
- [ ] Certificate Packs
- [ ] SSL Verification
- [ ] Universal SSL Settings for a Zone
- [ ] Origin CA
- [ ] Zone-Level Authenticated Origin Pulls
- [ ] Per-hostname Authenticated Origin Pull
- [ ] Stream Videos
- [ ] Stream Signing Keys
- [ ] Stream Subtitles/Captions
- [ ] Stream Webhook
- [ ] Stream Watermark Profile
- [ ] Worker Script
- [ ] Worker Routes
- [ ] Workers KV Namespace
- [ ] Workers KV Request Analytics
- [ ] Workers KV Stored Data Analytics
- [ ] Worker Script (Deprecated)
- [ ] Worker Binding (Deprecated)
- [ ] Worker Filters (Deprecated)
- [ ] Worker Cron Trigger
- [ ] Spectrum Applications
- [ ] Spectrum Analytics (Summary)
- [ ] Spectrum Analytics (By Time)
- [ ] Spectrum Aggregate Analytics
- [ ] Page Rules for a Zone
- [ ] Available Page Rules for a Zone
- [ ] Rate Limits for a Zone
- [ ] User-level Firewall Access Rule
- [ ] Account-level Firewall access rule
- [ ] Organization-level Firewall Access Rule
- [ ] Firewall Access Rule for a Zone
- [ ] WAF Rule Packages
- [ ] WAF Rule Groups
- [ ] WAF Rules
- [ ] Waf Overrides
- [ ] User-Agent Blocking Rules
- [ ] Zone Lockdown
- [ ] Firewall rules
- [ ] Filters
- [ ] Rules Lists
- [ ] Rules for Rulesets
- [ ] Account rulesets
- [ ] Zone rulesets
- [ ] Load Balancer Monitors
- [ ] Load Balancer Pools
- [ ] Load Balancer Healthcheck Events
- [ ] Load Balancer Regions
- [ ] Account Load Balancer Monitors
- [ ] Account Load Balancer Pools
- [ ] Account Load Balancer Search
- [ ] Load Balancers
- [ ] IP Address Management Prefixes
- [ ] IP Address Management Dynamic Advertisement
- [ ] IP Address Management Prefix Delegation
- [ ] Railgun
- [ ] Railgun Connections for a Zone
- [ ] Account Railguns
- [ ] Railgun Connections
- [ ] Organization Railgun
- [ ] Custom Pages (Account)
- [ ] Access Organizations
- [ ] Access Identity Providers
- [ ] Access Groups
- [ ] Access Service Tokens
- [ ] Access Short-Lived Certificates
- [ ] Access Mutual TLS Authentication
- [ ] Access Applications
- [ ] Access Policy
- [ ] Access Requests
- [ ] Zone-Level Access Organizations
- [ ] Zone-Level Access Identity Providers
- [ ] Zone-Level Access Groups
- [ ] Zone-Level Access Service Tokens
- [ ] Zone-Level Access Short-Lived Certificates
- [ ] Zone-Level Access Mutual TLS Authentication
- [ ] Zone-Level Access Applications
- [ ] Zone-Level Access Policy
- [ ] Health Checks
- [ ] Diagnostics
- [ ] Waiting Room
- [ ] Registrar Domains
- [ ] Argo Tunnel