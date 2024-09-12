---
title: Enabling Open Telemetry in .NET Intelligent (AI) Applications
description: Exploring large/ small language models options in Azure
date:
    created: 2024-09-01
    updated: 2024-09-01
authors:
    -  Logan Talbot
categories:
    - .NET
    - Semantic Kernel
draft: true
readtime: 5
tags:
    - Open Telemetry
    - .NET
    - Observability
    - Logging
    - Semantic Kernel
---

# Enabling Open Telemetry in .NET Intelligent (AI) Applications

Observability is a key aspect of modern software development. It allows developers to understand how their applications are behaving in production, and to identify and fix issues quickly. OpenTelemetry is an open-source observability framework that provides a set of APIs, libraries, agents, and instrumentation to collect, process, and export telemetry data (metrics, logs, and traces) from your applications.

In this article, we will explore:

- Benefits of observability in Intelligent Applications
- How to enable OpenTelemetry in .NET applications, specifically in the context of intelligent applications.
- How enabling OpenTelemetry when using Semantic Kernel SDK can help you gain insights into your intelligent applications.
<!-- more -->

## Benefits of Observability in Intelligent Applications

Intelligent applications can be complex and difficult to debug. Observability is essential for understanding how these applications are behaving in production, and for identifying and fixing issues quickly. It is important to have visibility of the performance, availability, and reliability of your intelligent applications including your non ai features. Observability can help you:

- Bug identification and resolution: Observability can help you identify and fix bugs quickly by providing insights into the behavior of your intelligent applications. You can use metrics, logs, and traces to understand how your applications are behaving in production, and to identify and fix issues quickly.
- Performance optimization: Observability can help you optimize the performance of your intelligent applications by providing insights into the performance bottlenecks and hotspots in your code. You can use metrics, logs, and traces to identify the slowest parts of your code and optimize them for better performance.
- Reliability and availability: Observability can help you ensure the reliability and availability of your intelligent applications by providing insights into the health of your applications. You can use metrics to monitor the availability of your applications and to identify and fix issues before they impact your users.
- Data-driven decision making: Observability can help you make data-driven decisions about your intelligent applications by providing insights into the behavior of your applications. Applying this to observing your AI models can help you understand how they are performing in production and make data-driven decisions about how to improve them.



## References

- [Open Telemetry](https://opentelemetry.io/)
- [Open Telemetry .NET](https://opentelemetry.io/docs/languages/net/)
- [.NET observability with OpenTelemetry](https://learn.microsoft.com/en-us/dotnet/core/diagnostics/observability-with-otel)
- [Github Semantic Kernel Telemetry Documentation](https://github.com/microsoft/semantic-kernel/blob/main/dotnet/docs/TELEMETRY.md)
- [Azure Monitor](https://docs.microsoft.com/en-us/azure/azure-monitor/)
- [Blob: Unlock the Power of Telemetry in Semantic Kernel SDK](https://devblogs.microsoft.com/semantic-kernel/unlock-the-power-of-telemetry-in-semantic-kernel-sdk/)
- [YouTube: Practical OpenTelemetry in .NET 8 - Martin Thwaites - NDC London 2024](https://www.youtube.com/watch?v=WzZI_IT6gYo)
- [Enable Azure Monitor OpenTelemetry for .NET, Node.js, Python, and Java applications](https://learn.microsoft.com/en-us/azure/azure-monitor/app/opentelemetry-enable?tabs=aspnetcore)
- [Quickstart: Using Azure OpenTelemetry Exporter to export SDK telemetry data to Application Insights](https://learn.microsoft.com/en-us/azure/communication-services/quickstarts/telemetry-application-insights?pivots=programming-language-csharp)