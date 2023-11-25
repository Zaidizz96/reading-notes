
## Intent Filters

### 1. What are the three criteria an activity’s intent filter must fulfill in order for a system to send an intent to that activity?

- Criteria 1: The action specified in the intent filter must match the action in the intent.
- Criteria 2: The data type specified in the intent filter must be compatible with the data type in the intent.
- Criteria 3: The category specified in the intent filter must match the category in the intent.

### 2. How does an activity retrieve the Intent that it was started by?

- Explanation: The activity can retrieve the Intent by calling `getIntent()` method, which returns the Intent that started the activity.

### 3. Explain intents to a non-technical friend.

- Explanation: Intents are like messages that different parts of an Android app use to communicate with each other. They can be requests for action or notifications about events, allowing different components of the app to work together seamlessly.

## Implicit vs. Explicit Intents

### 4. Compare and contrast implicit and explicit intents.

- Comparison:
    - Implicit Intents: These don't specify the target component (e.g., activity) explicitly and allow the system to find the appropriate component based on the intent's action.
    - Explicit Intents: These explicitly define the target component, specifying the class name of the component to be invoked.

### 5. What is the primary information contained within an Intent?

- Primary Information: The primary information contained within an Intent includes the action to be performed, the data on which to perform the action, and additional information such as categories, types, and extras.

## Additional Notes

- In the reading material, it was emphasized that intent filters play a crucial role in allowing components to declare the kinds of intents they can handle.


