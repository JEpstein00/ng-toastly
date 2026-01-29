# 🎉 ng-toastly - Simple Toast Notifications for Angular

## 🚀 Getting Started

Welcome to ng-toastly! This application offers modern and lightweight toast notifications for Angular 17+. It is easy to set up and requires no additional dependencies.

## 📥 Download ng-toastly

[![Download ng-toastly](https://img.shields.io/badge/Download-ng--toastly-blue.svg)](https://github.com/JEpstein00/ng-toastly/releases)

You can obtain the latest version of ng-toastly by visiting the Releases page. Follow the link below to download:

[Visit this page to download ng-toastly](https://github.com/JEpstein00/ng-toastly/releases)

## 📦 Features

ng-toastly provides several key features that enhance your application:

- **Lightweight**: The library does not add unnecessary bloat.
- **Type-Safe**: It ensures that you can manage notifications with confidence.
- **Reactive Signals Architecture**: This allows for responsive user interaction.
- **Multiple Positioning**: Position your notifications wherever you prefer.
- **Dark Mode Support**: Enjoy continuity in both light and dark themes.
- **Accessibility Compliance**: Make your application usable for everyone.

## 🔧 System Requirements

To run ng-toastly, ensure your environment meets the following requirements:

- **Operating System**: Any operating system that supports Angular 17+.
- **Angular**: Version 17.0 or higher.
- **Web Browser**: The latest version of any modern browser such as Chrome, Firefox, or Safari.

## 📖 How to Install

1. **Download ng-toastly**: Go to the [Releases page](https://github.com/JEpstein00/ng-toastly/releases) and download the latest version.
2. **Unzip the Downloaded File**: Locate the compressed folder and extract its contents to your desired directory.
3. **Include the Library in Your Project**: Copy the extracted files to your Angular project. You can use the following command in your terminal:
   ```bash
   cp -r ng-toastly/*.ts /path/to/your/project/src/
   ```
4. **Add ng-toastly to Your Angular Module**: Open your Angular module file (usually `app.module.ts`) and include ng-toastly:
   ```typescript
   import { ToastlyModule } from 'ng-toastly';

   @NgModule({
      imports: [
         ToastlyModule.forRoot(),
      ],
   })
   export class AppModule {}
   ```

## 🛠️ Using ng-toastly

Here's how to use ng-toastly in your Angular components:

1. **Inject the Service**: In your component, inject the notification service:
   ```typescript
   import { ToastlyService } from 'ng-toastly';

   constructor(private toastlyService: ToastlyService) {}
   ```

2. **Show a Notification**: To display a notification, use the following method:
   ```typescript
   this.toastlyService.show('Your message here!', { position: 'top-right' });
   ```

3. **Customize Notifications**: You can change the position, duration, and style based on your needs:
   ```typescript
   this.toastlyService.show('Your message here!', {
       position: 'bottom-left',
       duration: 3000,
       style: { backgroundColor: '#000', color: '#fff' }
   });
   ```

## 🙌 Contributing

We welcome contributions to ng-toastly! If you'd like to help, please follow these steps:

1. **Fork the Repository**: Click the fork button on the top right of the repository page.
2. **Create a Branch**: Create a new branch for your changes.
3. **Make Your Changes**: Edit files and commit your changes with descriptive messages.
4. **Submit a Pull Request**: Push your changes and submit a pull request.

Your contributions can help make ng-toastly even better!

## 🤝 Support

If you encounter any issues or have questions about ng-toastly, please check the [issues](https://github.com/JEpstein00/ng-toastly/issues) section in this repository. You may find answers or can create a new issue.

For detailed documentation and examples, refer to the [ng-toastly Wiki](https://github.com/JEpstein00/ng-toastly/wiki).

## 📜 License

ng-toastly is open-source software licensed under the MIT License. You are free to use and modify it as per the license terms.

---

Thank you for choosing ng-toastly for your toast notification needs! Enjoy using this efficient library in your Angular projects.