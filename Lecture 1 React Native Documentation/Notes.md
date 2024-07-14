# Expo in React Native

## Introduction
Expo is a framework and a platform for universal React applications. It is a set of tools and services built around React Native and native platforms that help you develop, build, deploy, and quickly iterate on iOS, Android, and web apps from the same JavaScript/TypeScript codebase.


# Getting Started with Expo

## Prerequisites
- Ensure you have [Node.js](https://nodejs.org/) installed on your machine.

## Installation

### Create a New Expo App
To create a new Expo app, run the following command in your terminal:

```bash
npx create-expo-app@latest
```

## Key Features of Expo

1. **Development Tools:**
   - **Expo CLI:** A command-line tool that streamlines the process of developing and building React Native apps.
   - **Expo Go:** A mobile app available on the App Store and Google Play that allows you to preview your app on your physical device without needing to build a native binary.

2. **Managed Workflow:**
   - Expo provides a managed workflow where it takes care of many configuration steps for you, allowing you to focus on writing JavaScript/TypeScript code.
   - It includes a rich set of APIs and modules for things like camera access, location services, push notifications, and more.

3. **Bare Workflow:**
   - For more control and flexibility, Expo also supports a bare workflow that lets you use Expo tools with custom native code.

4. **Over-the-Air Updates:**
   - With Expo, you can push updates to your app without going through the app store review process, allowing for quicker iterations and bug fixes.

5. **Build Services:**
   - Expo offers build services that can create standalone APK (Android) and IPA (iOS) files for your app, making the deployment process straightforward.