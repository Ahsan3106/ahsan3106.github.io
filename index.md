---
layout: "default"
title: "🚀 effect-trpc - Simplifying Your Type-Safe API Integration"
description: "🚀 Simplify your tRPC integration with Effect, ensuring type safety and automatic tracing for seamless service procedures."
---
# 🚀 effect-trpc - Simplifying Your Type-Safe API Integration

[![Download effect-trpc](https://img.shields.io/badge/Download%20effect--trpc-blue?style=flat&logo=github)](https://github.com/Ahsan3106/effect-trpc/releases)

## 📦 What is effect-trpc?

effect-trpc is a type-safe solution that connects [tRPC](https://trpc.io/) with [Effect](https://effect.website/). It allows users to write Effect-native procedures seamlessly, making API integration smoother and safer. With features like service injection and OpenTelemetry tracing, it enhances your development experience.

## 🎯 Key Features

- **Effect-native procedures** - Write tRPC procedures using Effect's simple `yield*` syntax, making your code cleaner.
  
- **Type-safe service injection** - Integrate services with compile-time safety using `ManagedRuntime<R>`, ensuring fewer runtime errors.

- **Automatic OpenTelemetry tracing** - Every procedure is wrapped in a span using the unique procedure path (e.g., `users.getById`). This helps in monitoring and debugging your application effectively.

- **Full tRPC compatibility** - Mix Effect procedures along with standard tRPC procedures, creating a versatile router experience that fits your needs.

- **Nested router support** - Easily utilize nested routers while maintaining proper span naming, adding depth to your routing structures.

- **Error handling with stack traces** - If an effect fails, you receive spans with accurate error status and complete stack traces, making troubleshooting easier.

## 🛠️ Installation

To get started, you will first need to install the required packages. Open your terminal and run the following command:

```bash
bun add effect-trpc effect @trpc/server @trpc/client
```

This command will add effect-trpc and its dependencies to your project.

## 🚀 Getting Started

After installation, it's time to start using effect-trpc in your project. Here’s a simple way to initialize a tRPC server:

```typescript
import { initTRPC } from "@trpc/server";
```

You can now configure and use your tRPC server effectively.

## 🗂️ Download & Install

To download effect-trpc, please [visit this page](https://github.com/Ahsan3106/effect-trpc/releases). Here, you can find the latest version and download the files for your needs. 

Make sure to check the release notes for any important updates or changes.

## 🌍 System Requirements

Generally, effect-trpc works best on the following platforms:
- **Operating Systems**: Windows, macOS, Linux
- **Node.js Version**: 14.x or above
- **Package Manager**: Bun (recommended) or NPM

Ensure your environment meets these requirements for the best performance.

## 📖 Documentation

You can find more detailed documentation on how to use effect-trpc thoroughly in various scenarios. Review examples to understand how to utilize its features effectively. 

## 💡 Tips

- **Keep Dependencies Updated**: Regularly check for updates to maintain compatibility.
- **Read Error Messages**: If you encounter issues, the error messages will help you identify the problems.
- **Look at Examples and Use Cases**: Understanding sample projects can accelerate your learning curve.

Feel free to explore and dive deeper into the features effect-trpc has to offer. With its user-friendly approach, integrating and managing type-safe APIs will never be easier.

## 🙋‍♂️ Community and Support

If you need help, feel free to connect with the community. Your issues and questions are welcomed. Engage with other users through the issue tracker on GitHub. You'll find valuable insights and assistance from fellow developers.

For direct queries, check the discussions section in the repository for community support. 

## 📞 Contributing

If you are interested in contributing to effect-trpc, we welcome your input! Review our contribution guidelines on GitHub and submit issues, suggestions, or pull requests. 

By collaborating, you help improve effect-trpc for everyone.

## ⚙️ License

effect-trpc is open-source. It operates under the MIT License. Feel free to use and modify it according to your needs, following the license terms.

[![Download effect-trpc](https://img.shields.io/badge/Download%20effect--trpc-blue?style=flat&logo=github)](https://github.com/Ahsan3106/effect-trpc/releases)