# Android Fundamentals

## Intent in Android

An **Intent** in Android is like a message that different parts of your app or other apps use to communicate with each other. It's a way to request actions or pass data. Here are some examples of when you might use an Intent:

- **Starting Another Activity**: You can use an Intent to open a different screen or function within your app, like a settings screen or a user profile, when a user clicks a button.

- **External Actions with Implicit Intent**: Use an Intent to request actions from external components, such as sending an email, making a phone call, or opening a webpage. For instance, you can let the user choose their preferred email app to send feedback.

- **Inter-Component Communication with Explicit Intent**: Communicate between different components within your app, like passing data from one screen to another (e.g., user login information).

- **Broadcasting Events**: You can broadcast Intents to notify different parts of your app or even other apps about events or data. For example, to display a user message in your app.

- **Service Communication**: If your app has background services, you can use Intents to send requests and data to these services.

## Activity in Android

An **Activity** in Android is like a single screen or page in your app. It represents a specific task or interaction that the user can engage with. Activities are responsible for what you see on the screen, handling user interactions, and are linked together using Intents to create the user experience. They have lifecycles that help manage the state and behavior of your app as the user interacts with it. In your app, you can have multiple Activities, each responsible for a particular function.

Activities define your app's user interface and how users navigate through your app. For instance, your login screen is one Activity, and your home screen is another. Activities are essential building blocks in Android app development.

