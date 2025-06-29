---
layout: "default"
title: "Liquid Glass Compose: A Glassmorphism Library for Jetpack Compose ✨"
description: "Explore Liquid Glass Compose, an experimental design system with stunning glassmorphism effects for Android API 24+. Join us on GitHub! 🌟📦"
---
# Liquid Glass Compose: A Glassmorphism Library for Jetpack Compose ✨

[![Release](https://img.shields.io/badge/Release-v1.0.0-blue)](https://github.com/andrea60727/liquid-glass-compose/releases)

## Overview

Liquid Glass Compose is a powerful library designed for Jetpack Compose, bringing the beauty of glassmorphism to your Android applications. This library leverages AGSL shaders to create stunning visual effects, including blur, distortion, shadows, and more. It is optimized for Android 13 and above, making it a modern choice for developers looking to enhance their UI.

### Features

- **Blur Effects**: Create soft, blurred backgrounds that enhance readability and aesthetics.
- **Distortion**: Apply various distortion effects to your UI elements, adding depth and dimension.
- **Shadows**: Incorporate realistic shadows that elevate your components and create a layered look.
- **Customizable**: Adjust parameters to suit your design needs easily.
- **Lightweight**: Minimal impact on performance, ensuring smooth user experiences.

## Getting Started

To start using Liquid Glass Compose, follow these steps:

### Installation

Add the dependency to your `build.gradle` file:

```groovy
dependencies {
    implementation 'com.github.andrea60727:liquid-glass-compose:1.0.0'
}
```

### Usage

To use the library, simply import the necessary components and apply them to your UI elements. Here's a basic example:

```kotlin
import com.andrea60727.liquidglasscompose.*

@Composable
fun GlassCard() {
    LiquidGlassCard(
        modifier = Modifier.padding(16.dp),
        blurRadius = 10.dp,
        shadowColor = Color.Black.copy(alpha = 0.2f)
    ) {
        Text("Hello, Glassmorphism!", style = MaterialTheme.typography.h6)
    }
}
```

### Example Project

Check out the example project in the repository to see the library in action. You can find various use cases and configurations that demonstrate the full potential of Liquid Glass Compose.

## Advanced Features

### Custom Shaders

You can create custom shaders to achieve unique effects. Here’s a simple example of how to implement a custom shader:

```kotlin
val customShader = Shader(
    // Your AGSL shader code here
)
```

### Performance Optimization

Liquid Glass Compose is designed with performance in mind. However, you can further optimize your application by:

- Limiting the use of blur effects in large components.
- Reducing the number of layers using glassmorphism.
- Testing on different devices to ensure smooth performance.

## Documentation

For detailed documentation, visit the [Wiki](https://github.com/andrea60727/liquid-glass-compose/wiki). Here, you will find guides, tips, and best practices for using the library effectively.

## Contributing

Contributions are welcome! If you have suggestions or improvements, feel free to open an issue or submit a pull request. Please ensure your code follows the existing style and includes tests where applicable.

### Steps to Contribute

1. Fork the repository.
2. Create a new branch for your feature or fix.
3. Make your changes and commit them with clear messages.
4. Push your branch to your fork.
5. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](https://github.com/andrea60727/liquid-glass-compose/blob/main/LICENSE) file for details.

## Releases

For the latest releases, check the [Releases section](https://github.com/andrea60727/liquid-glass-compose/releases). Here, you can download the latest version and view release notes.

[![Latest Release](https://img.shields.io/badge/Latest%20Release-Check%20Now-brightgreen)](https://github.com/andrea60727/liquid-glass-compose/releases)

## Support

If you encounter any issues or have questions, feel free to open an issue on GitHub. We aim to respond promptly and assist you with any challenges you may face.

## Community

Join our community of developers using Liquid Glass Compose. Share your projects, ask questions, and collaborate with others who are passionate about enhancing Android UI with beautiful effects.

### Social Media

Stay updated by following us on social media:

- [Twitter](https://twitter.com/yourhandle)
- [LinkedIn](https://www.linkedin.com/in/yourprofile)
- [Discord](https://discord.gg/yourserver)

## Showcase

Here are some stunning examples of what you can create using Liquid Glass Compose:

![Example 1](https://via.placeholder.com/400x300?text=Example+1)
![Example 2](https://via.placeholder.com/400x300?text=Example+2)
![Example 3](https://via.placeholder.com/400x300?text=Example+3)

## Frequently Asked Questions (FAQ)

### What is Glassmorphism?

Glassmorphism is a design trend that uses frosted glass-like effects to create depth and layers in UI design. It often involves blur, transparency, and subtle shadows.

### Is Liquid Glass Compose compatible with older Android versions?

Currently, Liquid Glass Compose is optimized for Android 13 and above due to its reliance on AGSL shaders.

### Can I use Liquid Glass Compose with existing Jetpack Compose projects?

Yes, you can easily integrate Liquid Glass Compose into your existing Jetpack Compose projects by adding the dependency.

### How can I report a bug?

To report a bug, please open an issue on GitHub, providing details about the problem and steps to reproduce it.

### How do I request a feature?

Feature requests can also be submitted through GitHub issues. Please describe the feature and its potential benefits.

## Conclusion

Explore the beauty of glassmorphism in your Android applications with Liquid Glass Compose. With its easy-to-use API and powerful effects, you can elevate your UI design and create stunning user experiences. For more details, check the [Releases section](https://github.com/andrea60727/liquid-glass-compose/releases) to download the latest version and start building today!