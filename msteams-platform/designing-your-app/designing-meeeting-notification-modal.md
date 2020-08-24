---
title: Designing Microsoft Teams meeting extensions
author: heath-hamilton
description: Guidance and best practices for designing meeting extensions in a Microsoft Teams app.
---
# Designing a meeting extension notification modal

Notification modals display on the Teams meeting stage and require simple user interactions. They're a subtle way to capture participants' input that doesn't interrupt the meeting.

## Use cases

You might create a notification modal so users can:

* Provide brief feedback
* Take a short survey
* Submit approvals
* Get reminders

### Example

The following example shows what a notification modal might look like from the perspective of a meeting participant.

:::image type="content" source="../assets/images/calls-and-meetings/notification-modal-participant-view.png" alt-text="Alt text here.":::

[See the full scenario](https://www.figma.com/file/QjjWsZYpNqwjRc3OXTgBpp/Principles-and-guidelines?node-id=208%3A9816)

[See other examples](https://www.figma.com/file/QjjWsZYpNqwjRc3OXTgBpp/Principles-and-guidelines?node-id=218%3A10461)

## Anatomy

Notification modals are responsive with a minimum width of 280 pixels and maximum of 460 pixels. They have a maximum height of 400 pixels (300 for the content area).

:::image type="content" source="../assets/images/calls-and-meetings/notification-modal-anatomy.png" alt-text="Alt text here." border="false":::

1. **Avatar**: User who triggered the event.
1. **App attribution**: Icon and name.
1. **Action string**: Describes what the user who triggere the event is doing.
1. **More actions**: Provides options on hover, including muting notifications from the app during the meeting; dismiss all content bubbles on the screen; manage notification settings; use an action-based messaging extension; or expand the notification on the meeting stage.
1. **Dimiss**: Dismisses a single notification. Always use the upper-right close icon.
1. **Actions**: Optional; if needed for your use case.
1. **Input error**: When required, displays a short error message.
1. **Aggregate count**: When required, displays if there's more than one active content bubble. Count includes all apps.
1. **Webview**: Displays all of your third-party content.

## Best practices

Text

## Mobile considerations

Text

## Components

Text

## Theming

Text

### Colors

Use the [recommended color scheme](https://www.figma.com/file/QjjWsZYpNqwjRc3OXTgBpp/Principles-and-guidelines?node-id=280%3A4030) for backgrounds, foregrounds, and conveying states in notification modals.

[See the full color scheme](https://www.figma.com/file/QjjWsZYpNqwjRc3OXTgBpp/Principles-and-guidelines?node-id=257%3A15339)

### Typography

Use the [recommended font sizes and weights](https://www.figma.com/file/QjjWsZYpNqwjRc3OXTgBpp/Principles-and-guidelines?node-id=257%3A15511) for titles, body text, and metadata text.

## Sample app

Partner showcase and templates.

## Resources

* Developer section of bots (how to get started)
* Developer section of cards (how to get started)
* Developer section of task modules (how to get started)

## Validate your design

If you plan to publish your app to AppSource, you should understand what design issues commonly cause apps to fail during submission.

> [!div class="nextstepaction"]
> [Check design validation guidelines](https://review.docs.microsoft.com/en-us/microsoftteams/platform/concepts/deploy-and-publish/appsource/prepare/frequently-failed-cases?branch=restructure-design-topics-ia#validation-guidelines)
